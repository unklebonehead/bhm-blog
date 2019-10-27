---
layout: post
published: true
title: "Yunohst Post Intall"
date: 2019-07-27
author: "Unkle Bonehead"
categories: [ tshv ]
featureImage: "img/bhm3.png"
tags:
  - Self Hosting
  - Tutorial
---
<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts" src="https://peertube.social/videos/embed/b7348a52-76db-4b7d-aba2-9dcbeb84ca7b" frameborder="0" allowfullscreen></iframe>

The step called "post-installation" is actually the initial configuration of YunoHost. It has to be done just after the installation of the system itself.
You can do it from through ssh, directly on the server or through a web browser. The browser is what I did because it is the easiest for people like me. Who dont know what they are doing.

#### Post-Installation

The step called "post-installation" is actually the initial configuration of YunoHost. It has to be done just after the installation of the system itself.
From the web interface

##### You can perform the post-installation with the web interface by entering in your browser :

the local IP address of your server if it is on your local network (e.g. at home !). The address typically looks like 192.168.x.y (see 'Find your IP' on the page about SSH)
the public IP address of your server if your server is not on your local network. Typically, if you own a VPS, your VPS provider should have given you the IP of the server.

During the first visit, you will very likely encounter a security warning related to the certificate used by the server. For now, your server uses a self-signed certificate. You will later be able to add a certificate automatically recognized by web browsers as described in the certificate documentation. For now, you should add a security exception to accept the current certificate.

##### From the command line

You can also perform the postinstallation with the command directly on the server or through ssh.

	 yunohost tools postinstall 
	 

##### Informations asked

**Main domain**

This is the first domain name linked to your YunoHost server, but also the one which will be used by your server's users to access the authentication portal. It will thus be visible by everyone, choose it wisely.

 If you do not have a domain name, or if you want to use the YunoHost's DynDNS service, choose a sub-domain of .nohost.me, .noho.st or .ynh.fr (e.g. homersimpson.nohost.me). Provided that it's not already taken, the domain will be configured automatically and you won't need any further configuration step.

 If you do know what DNS is, you probably want to configure your own domain name here. In this case, please refer to the DNS page page for more informations.

 If you don't own a domain name and don't want a .nohost.me, .noho.st or .ynh.fr, you can use a local domain. The idea is to configure your router to redirect a local domain name to your server. For example you could create the yunohost.local domain redirecting to your server in your router, and now every device on the network will be redirected to your server when accessing yunohost.local. More information on how to setup a local domain can be found here.

**Administration password**

This password will be used to access to your server's administration interface. You would also use it to connect via SSH or SFTP. In general terms, this is your system's key, **choose it carefully.**


- If you're self-hosting at home and without a VPN, you need to make sure to correctly [forward ports on your router/Internet](https://yunohost.org/#/isp_box_config) forward ports on your router/Internet box ;
-  If you're using your own domain name (i.e. not a .nohost.me / .noho.st), you need to configure it according to the [recommended DNS configuration](https://yunohost.org/#/dns_config) recommended DNS configuration ;
-  If you cannot configure your domain name yet (because you didn't register it yet, or because this is a test domain), see last paragraph [here](https://yunohost.org/#/dns_local_network) here for a workaround ;
- Don't be too afraid of the certificate warning, you'll probably be able to [install a Let's Encrypt certificate](https://yunohost.org/#/certificate) install a Let's Encrypt certificate :).
- Have a look at the[ available apps](https://yunohost.org/#/apps)  available apps !
