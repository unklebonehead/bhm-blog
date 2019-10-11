---
layout: post
published: true
title: Ep2 Choosing Yunohost and The Fediverse
author: Unkle Bonehead
date: 2019-08-02
categories: [ TSHP ]
tags: 
  - Self Hosting
URL: "/posts/ep2-choosing-yunohost/"
image: "tshp-300.jpg"
---  

### Ep2 Choosing Yunohost and The Fediverse

<audio controls>
    <source src="https://reel2bits.boneheadmedia.com/uploads/sounds/unklebonehead/01df3fc7bd8dc55d19b650cda09cfaa0cf58265ded1f8c3a528490382d43e94b.mp3">
            </audio>
    
[Download Episode](https://reel2bits.boneheadmedia.com/uploads/sounds/unklebonehead/01df3fc7bd8dc55d19b650cda09cfaa0cf58265ded1f8c3a528490382d43e94b.mp3) 
 #### What it is
If you've ever messed with Linux you have undoubtedly experienced the dreaded (but fun) thing called "distro hopping". Where you constantly download and install tons of different distros and use them to see what they are like and how well they run. Hell you may be running 3-4 of them on a pc at any given time. Wait, what? You dont know what a distro is? Well then... 
**Distro aka Distribution** - An operating system that is comprised of a collection of software packaged around the Linux kernel. There are many. Quite possibly thousands of distros out there. But there are some big ones that have been around for a long time that you may have heard of. Debian, Slack, Red Hat, Arch, Gentoo, etc. There are even some you may even be using currently and you dont even know it. Android is essentially a distro. The widely popluar Chromebooks and Chromeboxes run on ChromeOS which is derived from Gentoo. So now that you know what a distro is lets continue. 
[Yunohost](https://yunohost.org) is a Linux distro that you can install on a vps remotely or an old desktop or laptop that is just laying around the house. It has very low system requirements so it can even be installed on something as small as a RasperryPi. Put simply it turns your old computer or a vps into your very own server just for you. It gives you an admin panel to run install/remove apps, check on network and hardware usage, download backups, etc. You dont even really have to get into a terminal if you dont want to. 
#### Easy set up 
If you choose during installation to use a sub domain of one their domains the dns is all set up for you and you dont have to do any configuring. But beware there are limitations. The big one is that if you want to install an app that requires its own domain you will have to add a domain to your Yunohost to do it. **But dont let that stop you!** Its extremely easy and I will be showing you how to do that and many other things over the course of this podcast. It sets you up with your own email and chat (XMPP) servers and just that alone is worth its weight in gold in my book. 
The next thing you will want to do is to go crazy with installing apps and building websites but you need to practice some self moderation. Even though Yunohost gives you the ability to install and run over 100 apps chances are you wont be able to. You have to think about the limitiations of the machine you are running as well as the connection of your isp at home. Chances are you arent going to be able to use your new email server because most isp's in the states block port 25 unless you pay extra for it. Some may even block ports 443 and 22. Which are essential to controling your server from outside the network. But dont worry, where there is a will there is a way. Now let me just reassure you that not being able to use the email of the Yunohost server isnt a show stopper. You can still install many, many apps and use the server on the local network. You can set it up to use as a media server so you dont have 1000's of dvd's and cd's lying around. Have your own Nextcloud and work on documents on your network just like using Google drive and docs. Now me personally I've played with Yunohost for nearly two months at this point. Im running this website, hosting this podcast including the files you download to listen to. Along with a Nextcloud, email, chat, a Peertube, Pixelfed and Writefreely instances. It's time for me to give it some more serious thought on what I want to accomplish. 
#### My plan 
I'm going to blow away the Pixelfed instance. I'm the only one on it and it hasnt implemented the full ActivityPub stuff yet. So it's pretty much useless to me. Plus I'm really not into the "instagram" style of posting. I do like to just scroll through but dont really like to post. I prefer Mastodon or something along the lines of microblogging. I'm trying to get Funkwhale installed but I dont know whats causing the problem there. It is still fairly early for Funkwhale but they have plans on implementing podcasting in it. When it does I plan on moving this podcast exclusively to Funkwhale. I'm going to keep PeerTube going because I really enjoy it. I really like posting to my "Quick Clips" chanell. Just short 1 minute clips that I started using Instagram for before I quit posting over there. I gotta keep my Nextcloud and email those are pretty much esstential for me. Plus since I am apparently still "in the band" and they are going to be recording soon I use Nextcloud for us to share files for recording, mixing and mastering. Next episode I'll go over how easy it is to install Yunohost and get it up and running in minutes. I'll make a video to accomany it and post it to PeerTube. It will be installing it in a virtual machine but it is still the same process. So now as promised from the last episode let do some explaining of the Fediverse. 
#### Definitions of the Fediverse:
*These are as I understand them* First we need to cover a few basics. 
**The Fediverse** - Basically federated social networks that run on open source software on servers all over the world. 
**Instance** - The individual server 
**Follow** - When one instance follows another instance. It's users can see and interact with each other as if they are on the same instance. Additionally a "follow" from the pov of a user is that if I write a blog you can follow that user throughout the Fediverse no matter what platform you are on. ie Mastodon, Pleroma, Diaspora, GNUsocial, WriteFreely, etc 
**ActivtityPub** - Is the protocol that makes this all happen. The best way I can describe it is imagine a giant trailer park where each trailer is its own house, with its own rules, but the whole park is connected to look like one giant house. Now each house (instance) doesnt have to be connected (follow) the others and can choose which ones it wants to be connected (follow) to. If they are all connected it would be absolutley awesome but people are individuals and nobody really thinks alike. Everybody has an opinion and they can vary wildly on the extreme. Now do you see my excitement? You can follow someone once and you dont have to follow them on 48 different sites. You just go where you like to go and they are there. Thats what gets me excited. But this whole tech is young and has some kinks to work out yet. But it has plenty of room to grow. And, here is the major selling points for me. 
**NO ADS** 
**Open Source** 
**No tracking**
**FREE as in Freedom!** 
