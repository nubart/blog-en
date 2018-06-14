---
author_name: Rosa Sala
author_bio: Rosa is Nubart's CEO and co-founder
author_location: Berlin / Barcelona
layout: post
comments: true
published: true
title:  "Why we can offer digital audio guides in offline mode without any app"
description: "Museums often have a bad network coverage and cannot stream our digital audio guides. That's why we developed an offline mode that doesn't require downloading any app!"
slug: "digital-audio-guides-tours-offline"
date:   2018-06-14
banner_image: audioguide-nexo-nubart2.jpg
tags: [audio tour, offline]
---

Sometimes a problem ends up being a great opportunity. This is what we had the opportunity to see with the audio tour through the natural monuments of the Maestrazgo (Teruel) that we produced for Nexo Turismo y Cultura and that was the origin of our first offline digital audio guide for smartphones that works without wifi and without coverage. Here's the story. 

<!--more-->

## Not only audio guides, we also do audio tours

Our card-shaped audio guides are not only useful for museums. They can also be offered at alternative points of sale, such as tourist information offices, and can be adapted for guided tours of larger areas, such as cities or natural spaces. Noelia Porrúa recognized this when she settled in the wonderful region of Maestrazgo in Teruel (Spain) and decided to found her company [Nexo Turismo y Cultura.](https://www.nexoturismocultura.com/){:target="_blank"}

Noelia contacted us because, in addition to the guided tours she is preparing for hikers, she also wanted to offer something to lone rangers who want to know the territory on their own, without the company of a guide, and to do so in their own language. 

She also wanted to boost the local economy by selling our cards in local stores. The spectacular beauty of the natural landscapes of El Maestrazgo is becoming more and more well known. "There are many websites that provide information -Noelia tells us- but you have to visit them all one by one. I wanted visitors to have all the information on their mobile phone. But also that the shops in the area can offer this information in a tangible format that can be sold, like your cards”. 

## The problem of natural sites without data coverage

We had been wanting to produce a tourist route in Nubart for a long time, so we were very excited about the project. Noelia prepared a great script that we proofread and translated into English and French. We prepared the voice-over in these two languages and in Spanish and reworked the maps to adapt them to the content of the audio tour. We also designed the card using Noelia's photos. 
[Nubart Audio tour through the natural monuments of El Maestrazgo - Nexo Turismo y Cultura]({{site.baseurl}}/images/posts/audioguide-nexo-nubart.jpg){: .center-image }

Everything was going great until we asked her about the tweets.


Our audio guides have a "tweet about this piece" option that allows the user to promote the exhibition or the tour from their own social network. "It may not be a good idea to put this button on your route," we told Noelia, "because although our content is adapted to consume a minimum of data and to load very quickly, the Twitter app works slowly when the coverage is not very good”. "In that case -she replied- we'd better take it off. There is no coverage at all in El Maestrazgo.”

Ouch... 

There is no coverage *at all* in El Maestrazgo? 

In Nubart we were astonished. Our cards worked in *streaming*, so that wifi or data coverage, however bad, was necessary. The content was produced, the audio tour settled and the cards printed. Only that without data or wifi they were useless. There had been a terrible misunderstanding.
We checked it out and Noelia was right: in the 21st century and in the middle of the EU there are still areas without data coverage. El Maestrazgo was one of them. 
We had a serious problem. We had all spent a lot of time and enthusiasm on this project. And now, we could either give the money back to our client and use the cards to craft a decorative mosaic in the office, or we had to look for a technical solution. 
We chose the second option. 

## The problem of offline downloading of content without installing an app

We had to find a way to allow the complete download of the content of the audio route in a place with coverage, so that everything could be accessed later from the mobile phone, but in offline mode. In theory, only native mobile apps allow that. But at Nubart we don't do apps, since we don’t believe in them. We had to find a way to access our digital content quickly and offline directly from the browser, without having to go through the cumbersome process of searching for an app on the store, downloading it, installing it, opening it and giving permissions. We also didn't want to consume the memory of the user's mobile phone, as apps do once they are installed. 
If you are a bit *teckie*, you may know "preload" attribute in html. Theoretically, you can use it to download audio files automatically when loading the page. But the reality is that each browser decides whether or not it wants to follow that attribute, and virtually none of the mobile browsers follow it. As Nubart audio guides and audio tours are specially designed for use from a smartphone, the *preload* label was not a viable solution. 
In short: 99% of software companies would tell you that, without an app, this problem has no solution.
## How our audioguides or audio tours work in offline mode

Luckily, at Nubart we have a secret weapon called Simon Effing, our co-founder and CTO. Using intelligent, next-generation Javascript, Simon found a way to ensure that the complete content of the audio tour is always downloaded from any browser and provisionally stored in the temporary memory of the mobile phone (also known as 'random access memory' or 'RAM memory'). As we wanted, the information contained in the RAM does not consume memory, since it disappears when closing the browser page or when turning off the device. However, this does not mean that it will be lost forever: users can always recover it by using again the unique code of their Nubart card. And all this immediately and easily, without downloading any app.
In this video you can see the whole process in real time:
<iframe src="https://player.vimeo.com/video/250765199" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>{: .center-image }
As you can see, the process to access our offline audio tours is as easy for Nubart users as that of a Nubart audio guide in conventional streaming. They just have to wait a little longer for the contents to load.
Once we had the Noelia problem solved, we saw that the offline mode could also benefit other clients, such as the many museums that have Wi-Fi in the reception area, but a bad data coverage in the exhibition halls. It also solved a problem for non-EU tourists who do not want to pay *roaming* while using the audio guide, as they can download the content using a spot with free wifi.
In the meantime, we have expanded this development further and now we also offer a hybrid solution, switching in offline mode only the audio tracks assigned to areas of poor connectivity. This improves loading speed and usability, as well as our data report.

#### In Nubart we produce innovative and affordable audio guides.

<form action="../../../../../">
    <input type="submit" value="Visit our website" />
</form>