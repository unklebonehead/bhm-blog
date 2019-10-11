---
title: "Ep12 Hubzilla and More News"
author: Unkle Bonehead
date: 2019-10-11T04:44:13-04:00
draft: true
categories:
  - TSHP
tags:
  - hubzilla
  - yunohost
featureImage: "img/bhm2.png"
---
<audio controls?>
	<source src="https://.mp3">
    </audio>
[Download untracked Mp3 here]()

#### Preroll
Quick bit of news and then we install and play wiht Hubzilla. Right here on episode 12 of The Self Hosted Podcast!

#### Housekeeping
Yunohost has been upgraded to 3.6.5.2 along with Yunohost Admin panel. It is now at 3.6.5.
Nextcloud-ynh has also been updated to 15.0.11.
I ran into an issue just after upgrading. I was getting an "api not responding" error and ended up logging out and doing something else for about 10 minutes. When I logged back in everything was working so it seems to have fixed itself and all is right in the world of the bonehead.

#### Hubzilla
[Yunohost package](https://github.com/YunoHost-Apps/hubzilla_ynh/blob/master/README.md)

[Hubzilla main page](https://zotlabs.org/page/hubzilla/hubzilla-project)

[Hubzilla code on Framagit](https://framagit.org/hubzilla/core)

[Hubzilla addons on Framagit](https://framagit.org/hubzilla/addons)

Hubzilla is a social networking platform built with control of your privacy at center stage. Your online communications can be as public as you wish or as private as you require. Private conversations, private photos, private videos. Your media isn't hidden behind an obscure URL which can be guessed, it is protected by state-of-the-art cross-domain authentication. What this all means for youis **less drama**.

It does require a dedicated domain so if you are using a domain from Yunohost you wont be able to install it. If you have your own domain such as boneheadmedia.com you can intstall it in a subdomain such as hub.boneheadmedia.com.
It also requires that you have an ssl cert.