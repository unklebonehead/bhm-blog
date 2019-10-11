---
title: Ep7 Securering Your Yunohost Server
author: Unkle Bonehead
date: 2019-08-18
categories:
  - TSHP
tags: 
  - Self Hosting
---
### Ep7 Security

<audio controls>
    <source src="https://archive.org/download/tshpep7security/TSHP-Ep-7-Security.mp3">
    </audio>
[Download Mp3](https://archive.org/download/tshpep7security/TSHP-Ep-7-Security.mp3) 

### Housekeeping
I just recorded episode 4 of The Self Hosted Vidcast. I uninstalled Wordpress and showed how to install a static html site on Yunohost.
Bonehead Media is back to being a simple static html site. It's only got 2 pages that I built in Bootstrap Studio. I'll flesh it out more in the future. 
I would like to turn it into a theme for Pelican or Hugo and post the shownotes to the front page. But that will require more effort on an ongoing basis for me. Plus I already have my stuff posted to the [Fediverse](https://fediverse.blog/@/UnkleBonehead). The reason behind that is three fold.
1. It has the coolness factor that you can subscribe through Mastodon (and the rest of the Fediverse) or the RSS feed.
2. Just in case something catestrophic happens to my home server you will still be able to get updates. 
3. It will drasticaly reduce the traffic to my home server. 

I'm looking for a better Markdown editor for Ubuntu. I'm currently using Remarkable and it works good but I would like to try something new. 
Does anybody have any suggestions? I definatly need something with a preview since I am using it write shownotes.
I'm testing out recording a bit differetn today.
I'm using [Zrythm](https://www.zrythm.org/en/) to record todays episode. It's written by a small dude I'm following on Mastodon named [AlexTee](https://www.alextee.org/) 
### Security
YunoHost has been developed to provide the best security without too much complication. Every protocol used in YunoHost are encrypted, only password's hashs are stored and by default each user is able to access to his personal directory only.
If you need advice, do not hesitate to [ask for help!](https://yunohost.org/#/help) 
#### 2 things are very important to remember.
1. Installing additional apps can significantly increase the number of potential security flaws. Do not hesitate to get information about security flaws before installing an app, and try to install only apps which will suit your needs.
2. The fact that YunoHost is a well-spread software increases the chances of an attack. If a flaw is discovered, it could potentially affect all the YunoHost instances at once. Keep your system up-to-date to remain safe.

#### There are 5 various way to harden your Yunohost.
1. Change SSH authentication to use a key instead of a password 
By default, the SSH authentication uses the administration password. Deactivating this kind of authentication and replacing it by a key mechanism is advised.
2. Modify SSH port number
To prevent SSH connection attempts by robots that scan the Internet for any servers with SSH accessible, you can change the SSH port.
3. Change the user that is authorized to use SSH 
To avoid multiple forced login attempts to admin by robots, change the authorized user who can connect.
(In the case of a key authentication, a brute force attack has no chance of succeeding. This step is not really useful in this case. )
4. Change the cipher compatatibility configuration.
I have not done this because I want anybody to be able to see the site.
The default TLS configuration for services tend to offer a good compatibility to support old devices. You can tune this policy for specific services like SSH and NGINX. By default, the NGINX configuration follows the intermediate compatibility recommendation from Mozilla. You can choose to switch to the 'modern' configuration which uses more recent security recommendations, but decreases the compatibility, which may be an issue for your users and visitors using older devices. More details about the compatibility can be found on this page.

Changing the compatibility level is not definitive and can be reverted if it doesn't feet your environment.
5. Disable the Yunohost API
This is your admin panel.
YunoHost administration is accessible through an HTTP API, served on the 6787 port by default (only on localhost). It can be used to administrate a lot of things on your server, so malicious actors can also use it to damage your server. The best thing to do, if you know how to use the command-line interface, is to deactivate the yunohost-api service.
[Yunohost Security](https://yunohost.org/#/security) 

I suggest that you take the time and do some addiional reading
of [Josh Rollins Basic SSH Security](https://joshrollinswrites.com/help-desk-head-desk/basic-ssh-security/) post. I literally read it 3 times and each time I read it something else clicked in my brain that I hadnt noticed the previous time. For instance, I didnt know that you could change the login grace time or that you should start around port 8000 if you change the port number. 
While your there you should check out the rest of his blog as well.
