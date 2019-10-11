---
title: Ep11 News and Updates
author: Unkle Bonehead
date: 2019-10-09
published: false
categories:
  - TSHP
tags: 
  - Self Hosting
featureImage: "img/bhm2.png"
---
<audio controls?>
	<source src="https://.mp3">
    </audio>
[Download untracked Mp3 here]()

I'm back! Now with a redneck, tricked out Frankenputer latop. But its powered by KDENeon and backedup by Yunohost. It's episode 11 and I got some news, opinions and updates for you right here, right now on The Self Hosted Podcast.
### Housekeeping
My laptop broke. Thats why I've been silent. But I was able to jerry rig it enough that its usable. I'll post pics or you can go see them on Mastodon.
I'm using KDENeon and I am loving how easy it is on the ram. It really quick and light. Plus I'm on a newer kernel instead of using a low latency 4.xx on Ubuntu Studio. I may just keep this and be rid of US forever. But I do want to try Manjaro really bad. I used Arch once before but I borked it and decided it was not for me. But I hear nothing but good reviews for Manjaro for the last couple of years now. Plus its what Unfa uses. And if its good enough for Unfa to create the beautiful music he does with it why wouldn't it be good for a podcaster?
Some quick stats about you from Anchor. As you know these are only tracked if you are using an app on your mobile or listening to it on Anchors website. If you manually download from the show notes I have no idea who you are or where you are from. 
As of this recording 603 plays. And there is estimated to be at least 50 of you that listen to me every time I put out an episode. Thank you and I hope you are getting something out of this.
59% of you use Android while only 17% of you use iphone. 24% of you are listed as other so I am guessing that is on the web.
I also know that 51% of you are in the US with UK, Germany, Australia and Canda rounding out the top 10. In total this podcast is being listened to in 26 countries around the world.
I sincerly thank you and hope that I am inspireing you to get into hosting your own data and taking back control.
#### Yunohost App highlight
**[FreshRss](https://www.freshrss.org/)** A free, self hostable aggregator
I have fallen in love with it.
Its clean and easy to read and use.
Looks and works good enough on mobile that you dont really need an app. 
Has two different api's. Greader and Fever
### News
#### How to avoid being banned by fail2ban forever!
So a user by the name of "Mad" over at the Yunohost forums has posted a pretty awesome tip. To be honest I havent tried it out yet but I plan to as soon as I get my laptop situation straightened out. It's a two part solution if I am understanding this. 
1. Always allow ssh from another fixed ip address. What this is ssh into a vps and then through that vps you ssh into your Yunohost. So on your Yunohost you need to set fail2ban to always allow a connection from the other vps. Pretty simple and quite interesting concept.
2. But when your not in that specific vps and you need to access your Yunohost. So he has posted a script that uses dyndns so you can do the same thing from home. I'll put it in the shownotes.

Aleks noted in the thread that in Yunohost version 3.7 they are increasing the max retry to 10 on fail2ban to help aleviate the problem of there being only 5 attempts allowed currently.
#### Links
##### Linux
[Microsoft Edge for Linux](https://www.omgubuntu.co.uk/2019/09/microsoft-edge-linux-survey?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+d0od+%28OMG%21+Ubuntu%21%29)
[Ubuntu 19.10 beta+Flavors](https://www.omgubuntu.co.uk/2019/09/ubuntu-19-10-beta-download?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+d0od+%28OMG%21+Ubuntu%21%29)

##### Oops they f@&#ed up again!
[Dropbox paper leaks emails](https://reclaimthenet.org/dropbox-paper-shows-email-address/)
### Opinion
On episode [226 of Linux For the Rest of Us](http://podnutz.com/lftrou226/) Door to Door Geek got into a rant that had me cheering! What set him off was Richrd M Stallman and how some people were shocked and others werent. And Door is right. We all knew that RMS was looney and we just kind of gave him a pass because he is the percieved father of open source. But then Door lit into some of these podcasters that I've been griping about on Mastodon recently. But for me its not just Linux podcasters. It's a vast majority of them. It seems like since podcastings boom has really hit hard that they all seem to get a big head and think that they are a respected member of the media. They got sponsors! They are hhhhhuuuuuuuggge! This is turning me off to some of the better produced and better sounding audio podcasts out there and I dont like it. I want to support the underdog, the little guy. But they all want to be and act like they are these top rated celebrities. I heard one talking about how great it was to have been asked for an autograph at a conference. I've signed autographs. Hell, I autgraphed boobs with a sharpie before. I've had people asked to take pictures with me. Now none of this was from podcasting but being in the band, It was fun. It's really interesting to see the look on your wifes face after a show in front a packed casino to have a bunch of people rush all of you asking for autographs and pics. She was like "I'm married to a rockstar". 