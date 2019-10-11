---
title: Ep8 Commit2Quit
author: Unkle Bonehead
date: 2019-08-25
categories:
  - TSHP
tags: 
  - Self Hosting
---
### Ep8 Commit2Quit

<audio controls>
    <source src="https://reel2bits.boneheadmedia.com/uploads/sounds/unklebonehead/b1a0e4567d53ce8dc7a86283da3e7cd2eed5016b3ec43863b7835e4204c4c8db.mp3">
    </audio>
[Download Here](https://reel2bits.boneheadmedia.com/uploads/sounds/unklebonehead/b1a0e4567d53ce8dc7a86283da3e7cd2eed5016b3ec43863b7835e4204c4c8db.mp3)

## Housekeeping
It seems that this podcasts goal has already been achieved. It has inspired 2 people to start self hosting. I got a couple of notifications on Mastodon that one is researching on how to self host on bsd and the other actually installed Yunohost! Thats frickin AWESOME! 
CONGRATS TO BOTH OF YOU! And I sincerely hope it works out for each your situations. Especially the one doing it on bsd. I want to know how you end up doing it!
Keep in mind If you aint root, you dont own it.
Own your shit!
### Additional Security points from a Yunohost Dev
Alek, one of the main dev/contributor on Yunohost's core and project managment team sent me some additional points to remember about security. The emphasis is mine.
>- **One of the key point of security is to limit the attack surface**. Don't install apps just for fun or give access to the user "because it's convenient and might be useful later"
>- Don't get too crazy about using the top-notch security ciphers with 4096bit keys or whatever. It doesn't matter. Usually the weak link of the security is elsewhere - either human or technical.
>- Last but not least, there is no such thing as "being secure".** Security is a process, and is always a tradeoff with usability**. 
>
>For ex, in the context of Yunohost, we have fail2ban configured to ban after 5 failed auth attempt. We see that it triggers a lot of false positive (legitimate users trying to login and getting banned for misc reasons). 
>
>**But point is, even if you get to some perfect "technical" security, the human part of security is not to be neglected **

#### Main Topic 1 Intro
I've been hearing and seeing people both in podcasts and on Mastodon griping about PeerTube. 
1. It doesnt have the viewers that Youtube has.
2. I dont get any revenue.
3. The videos take forever to stream
4. It doesnt have the discovery/search ability that Youtube has.
5. I cant stream live
Ok, I get your points but...and there is always a but right?
You are comparing apple to oranges and you are not grasping the full concept of federation! Just look at the theory. The idea of federated websites is that everyone hosts their own instance. In the case of PeerTube the tech behind the videos works through P2P which is bit torrent. The more seeders you have the faster the download. So if you have more instances that are following each other the faster the videos are for the entire network. That will make the discovery/search better as well. The whole streaming live is coming from what I understand. It's on their roadmap.
Now as far as having the viewers. I heard on a recent podcast the comment **"on my peertube video I had 6 views and the same video on youtube had 8000+"**. I hear bull shit like this everytime somone compares PeerTube and Youtube. You can not compare the two. They are totally different. Youtube is a fully funded company backed by the largest advertising agency/search engine multi billion dollar company in the world. The very same company that started paying people to create content to be on their site.
PeerTube is not backed by a company other than Framasoft which isn't paying anybody to create content for it. It is intended to be a bunch of individual servers that connect to each other in order to spread the load of streaming high quaility videos across a network. 
Now in the before mentioned comment he solved his own problem within his own statement. Did you catch it? The same video on Youtube had nearly an 8000% better view rate than the one on PeerTube. Is that because PeerTube isn't the automatic giant out of the box that Youtube is now? I imagine that might have something to do with it. I mean remember how long it took Youtube to get to size it is today. Think about how many millions of dollars went into getting it there. It was the first so yeah it is obviously be bigger with more viewers. I wonder how much money was spent on developing PeerTube? Probably not anywhere near what was spen on Youtube. Now the other part of the problem with that comment is "same video". **If you want viewers to go to a different platform you need to give them a compelling reason. Give them exclusive content! DONT POST THE SAME SHIT ON BOTH SITES!** 
As far as the whole "I'm not getting paid for my content". Thats up to you as the creator to do. Framasoft and PeerTube are not advertising agencies and they dont have any shareholders to beholden to.
Honestly, I'm getting sick of people who say they are all for privacy, fight the man, rage against the machine and never stop to think just how to take the action to do it. Nor do they make the effort to do it.
Thats why I will not post any videos to Youtube anymore. If you find any of my Vidcast on Youtube let me know because I didnt put it there. I do currently still have an account on there but that will be leaving soon as well.
#### Commit 2 Quit
I know that this is'nt something new. Framasoft and other people have already launched a similar campaign a year or so ago. So I admit that I am riding the coat tails of some big peeps. But since I've joined the Fediverse and really embraced it and the whole "control your data" movement I've noticed that there are an awful lot of, I dont know what you call them, bot accounts? It looks like its a bot that is just reposting crap from Twitter accounts on Mastodon. Somebody is prolly just being lazy and wrote a script that will copy/paste something to Mastodon. But I ask why? Why stay on Twitter and bitch about Twitter? Why stay of Facebook and bitch about Facebook? Seriously, you talk about hypocrites! There are 3 main things that really burns my ass and pisses me off the most.
1. Hypocrites 
2. Stupidity
3. Lying
Now let me explain why. 

**Hypocrites** - Now I understand if you have a Twitter/Facebook yada yada and are using it to try to educate people about the Fediverse and to talk them into switching over. Thats not being a hypocrite. Thats being productive. But to keep it and post on it more than than on Mastodon? Nah, I'm not buying it.

**** In full disclosure I am using Anchor.fm to distribute the audio files for this podcast. Anchor.fm does use Amazon to host those media files. So if you are subscribed in an app on your phone that automatically downloads the audio file that is where it comes from and those are tracked by Anchor. They only tell me how many downloads and what app is used. But I do put a link in the show notes to download those files directly from my personal server. In the future I may change and move those to Archive.org. But for the time being they will remain coming from my server. Those downloads are not tracked and I dont really care how many downloads I get from either place.***

**Stupidity** - Now I'm not talking being ignorant here. I know that some people dont "get things" as fast or fully. Hell I'm one of them. Rather I am talking about the basic common sense things that all humans understand. For example, somebody creates a Gab instance and tries to connect it to the rest of the Fediverse, it gets blocked, then they do it again with a different name, it gets blocked, etc, etc. You would think they would eventually stop. Thats another thing, Gab. Nuff said.
Another example, you touch something hot, get burned. Then touch it again. Isn't that stupid?

**Lying** - This one I really shouldnt have to go over but lets just say that it is what everone does at one point or another. Mostly by politicians and large tech companies. 

But eventually we will all reach a mass critical point where we will have to make the switch fully and completely move our stuff. People in general, incuding your friends and family will either follow you or they wont. If they want to make contact with you they will. If they dont then you will have to make the decision for yourself. Are you going to stay and remain being a product with no privacy or are you going to commit to being who you are and be in control of who you are. Which brings me to (a brilliant segway?) 

**The Problem**
These companies are much like an addiction. They've been successful at creating social media and free productivity/communicataion apps that appeal to human emotion. Whether it triggers a response in your brain to release dopamine, that hormone that gets released when you smoke a cigerette or take a drug. I dont know I'm not a doctor or a scientist. But either way people are obviously addicted to these comapanies and products. 
Everybody flips out over the newest iphone, or the first thing they check in the morning is Facebook and Twitter and the last thing they do before they go to bed is check Facebook or Twitter. It's obviously an addiction. And it needs to stop. **You** need to stop using these companies and their products. Because they have made you the product. 
Now I do understand that I will never ever be 100% free from these companies nor will you. They control and own entirely too much of the internet to actually do it all. But we can certainly minimize them in our lives. You may also have to deal with these companies in your job. But that is diffent than what I am talking about. I'm a talking about doing this for your personal life. Just because you have to deal with them in your work life doesnt mean you have to deal with them in your personal life. Dont give up your personal freedom and privacy. Your job is not your life, it's what pays the bills. Hopefully it's something you enjoy doing but keep in mind, unless you are your own boss the boss doesnt control you 24 hrs a day. ie I'm a truck driver and I love it. But my employer isn't what pays the bills. My Commercial Drivers Liscense is what pays the bills and it doesnt matter who signs the paycheck or where it came from. As long as I protect that CDL my income is golden.

I am asking you to do it, **Commit 2 quit**. Now I'm not asking you to do it forever. But just give it a try. Do it with baby steps. First 30 days then 60 then 90. If you can make it through 90 days can you try it for a year? Treat it lika an addiction. 
Here is my personal progress so far.

**Twitter** - 5 of 6 accounts are gone. Last one I cant get rid of because I dont remember the log in and cant find it.

**Instagram** - Both accounts are gone

**Apple** - I dont use their products so I'm good there.

**Microsoft**  - I think I have an account but I dont remember if I did anything with it. I used to have a couple of Skype accounts but havent used them in so long I dont remember what they were, lol.

**Amazon** - I did have an affiliate account with them at one time but havent used it so I dont even know if its active. My wife has a Prime account so I can just hers, lol.

**Google** - I have 1 personal account left to get rid of. The only thing holding me back on this is that I have a couple of medical accounts and Netflix connected to gmail that I need to switch over before I can delete it. I'm guessing that the Youtube will go with it.
I also have a work account that I have to keep. The only way I can get rid of it is to quit my company. But this company treats me very good and pays me too much for me to go somewhere else so I think Im just gonna stay here until I retire, lol.

**Facebook** - As soon as I break it to the boys in the band that I'm not getting back into the band. I just dont have time to be on the road 6 days a week, then be home for 34 hrs to play family time and squeeze in being a rock star. Then its bye bye Facebook!
I've always hated Facebook from the day I started the accounts. I quit once then went back for the band. Almost deleted it but I'm still there because of it. Havent posted to Facebook proper since before last Christmas but I do use Messenger daily to talk with friends. 
