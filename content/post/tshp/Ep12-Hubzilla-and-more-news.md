---
title: "Ep12 Hubzilla and More News"
author: Unkle Bonehead
date: 2019-10-11T04:44:13-04:00
draft: false
categories:
  - TSHP
tags:
  - hubzilla
  - yunohost
featureImage: "img/bhm2.png"
---
<audio controls>
	<source src="https://archive.org/download/tshp-ep12/tshp-ep12.mp3">
    </audio>

[Download untracked Mp3 here](https://archive.org/download/tshp-ep12/tshp-ep12.mp3)

***There is a video that I recorded for this to show Hubzilla. I will post it tomarrow in it's own post.***

#### Preroll
Quick bit of news and then we play with Hubzilla. Right here on episode 12 of The Self Hosted Podcast!

#### Housekeeping
Yunohost has been upgraded to 3.6.5.2 along with Yunohost Admin panel. It is now at 3.6.5.
Nextcloud-ynh has also been updated to 15.0.11.
I ran into an issue just after upgrading. I was getting an "api not responding" error and ended up logging out and doing something else for about 10 minutes. When I logged back in everything was working so it seems to have fixed itself and all is right in the world of the bonehead. It turns out that this is normal. Some apps will need to restart nginx which during this time the admin panel cannot access it. So just be patient and it will fix itself.

**Yunohost is looking for help in translations.**
If you can help by doing some translations please go [here.](https://translate.yunohost.org/)
I got an email from one of the devs and they say that they need the most help with 
>When running YunoHost in any locale, (even English) it still remains the case that the stringbase is lacking, or flat out erroneous.

Dont know if I should let this cat out of the bag yet but I'm going to. Yunohost is going to start a blog for news and updates. You can help with this if you like by folowing the repo on [github](https://github.com/YunoHost/news).

**Critcial Know Error**
If you subscribe to the feed in the upper right corner of the site https://boneheadmedia.com/index.xml in Nextcloud News you will get an error. I can not reproduce this on a desktop or mobile app but I know what the problem is. That file is generated by hugo and it prints out lacking a closeing tag. I will try to solve this issue but since the site is generated by netlify and github using hugo everytime I fix it on github it regenerates the screwed up file and I go in a vicious circle.


#### Hubzilla
[Yunohost package](https://github.com/YunoHost-Apps/hubzilla_ynh/blob/master/README.md)

[Hubzilla main page](https://zotlabs.org/page/hubzilla/hubzilla-project)

[Hubzilla code on Framagit](https://framagit.org/hubzilla/core)

[Hubzilla addons on Framagit](https://framagit.org/hubzilla/addons)

Hubzilla is a social networking platform built with control of your privacy at center stage. Your online communications can be as public as you wish or as private as you require. Private conversations, private photos, private videos. Your media isn't hidden behind an obscure URL which can be guessed, it is protected by state-of-the-art cross-domain authentication. What this all means for youis **less drama**.

It does require a dedicated domain so if you are using a domain from Yunohost you wont be able to install it. If you have your own domain such as boneheadmedia.com you can intstall it in a subdomain such as hub.boneheadmedia.com.
It also requires that you have an ssl cert.

