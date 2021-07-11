---
layout: post
comments: true
published: true
title:  "Why we can offer digital audio guides in offline mode without any app"
description: "Museums often have a bad network coverage and cannot stream our digital audio guides. That's why we developed an offline mode that doesn't require downloading any app!"
slug: "digital-audio-guides-tours-offline"
date:   2018-06-14
image: /images/posts/audioguide-nexo-nubart2.jpg
tags: [audio tour, offline]
langpath-es: /2018/01/03/audioruta-nubart-offline/
langpath-de: /2018/06/14/digitale-audioguides-offline-ohne-netzabdeckung/
---

Sometimes a problem is an opportunity in disguise. This is what we experienced long time ago when producing the audio tour to visit the natural monuments of El Maestrazgo (Teruel, Spain) for Nexo Turismo y Cultura. It was the origin of our offline digital audio guides for smartphones that work without wifi and without data coverage. Here's the story. 

<!--more-->

## We not only create audio guides, but also audio tours

Our card-shaped audio guides are not only valuable for museums. They can also be adapted for guided tours of larger areas, such as cities or natural spaces and be offered at alternative points of sale, such as tourist information offices. Noelia Porrúa noticed this when she settled in the wonderful region of Maestrazgo in Teruel (Spain) and decided to found her company [Nexo Turismo y Cultura.](https://www.nexoturismocultura.com/){:target="_blank"}

Noelia contacted us because, in addition to the guided tours she is preparing for hikers, she also wanted to offer something to hikers who want to discover the natural sights at their own pace, without the company of a guide, and in their language. 

She also wanted to boost the local economy by selling our cards in local stores. The spectacular beauty of the natural landscapes of El Maestrazgo is becoming increasingly known. "There are many websites that provide information -Noelia tells us- but you have to browse through each one of them. I wanted visitors to have all the information on their mobile phone. But also that  shops in the area could sell this information in a tangible format, like your cards”. 

## The problem of natural sites without data coverage

Noelia prepared a great script that we proofread and translated into English and French. We prepared the voice-over in these two languages and in Spanish and revised the maps to adapt them to the content of the audio tour. We also designed the card using Noelia's photos. 
![Nubart Audio tour through the natural monuments of El Maestrazgo - Nexo Turismo y Cultura]({{site.baseurl}}/images/posts/audioguide-nexo-nubart2.jpg){: .center-image }

Everything was going great until we asked her about the tweets.


Our audio guides have a "tweet about this item" option that allows users to promote the exhibition or the tour from their own social network. "It may not be a good idea to include this option on your route," we told Noelia, "because although our content is adapted to consume a minimum of data and to load very quickly, the Twitter app works slowly when the coverage is not good”. "In that case -she replied- we'd better take it off, since in El Maestrazgo there is no coverage at all.”

Ouch... 

No coverage *at all*? 

At Nubart we were worried. Our cards worked in *streaming*, so that wifi or data coverage, however bad, was necessary. The content was already produced, the audio tour uploaded and the cards printed, but without data or wifi they were useless. 

But Noelia was right: there are still several areas without any data coverage in the EU. El Maestrazgo was one of them. 

We faced a serious problem. We had all spent a lot of time and enthusiasm on this project. And now, we could either give the money back to our client using the cards to craft a decorative mosaic in the office, or we had to look for a technical solution. 

We chose the second option. 

## The problem of downloading content offline without installing an app

We had to find a way to allow the complete download of the audio route content in a place with coverage, to be able to access it later offline, from the mobile phone. In theory, only native mobile apps allow that. But at Nubart we don't develop apps, since we don’t believe in them. We had to find a way to access our digital content quickly and offline directly from the browser, without having to go through the inconvenient process of searching for an app on the store, downloading it, installing it, opening it and giving permissions. We also didn't want to consume the user's mobile phone memory, as apps do once they are installed. 

The "preload" attribute in html was not a viable solution, since virtually none of the mobile browsers follow that attribute. 

Probably 99% of software companies would tell you that, without an app, this problem has no solution.

## How do our audioguides or audio tours work in offline mode

Our co-founder and CTO Simon Effing managed to find a way. Using some last-generation Javascript, Simon could ensure that the complete content of the audio tour is always downloaded from any browser and provisionally stored in the temporary memory of the mobile phone (also known as 'random access memory'). The information contained in the RAM does not consume memory, since it disappears when closing the browser page or when turning off the device. However, this does not mean that it will be lost forever: users can always recover it by using the unique code of their Nubart card again. All this is done swiftly, without downloading any app.

In this improvised video recording of the audio guide we produced for the German open air museum Steinzeitpark Dithmarschen you can see the whole process in real time:

<iframe src="https://player.vimeo.com/video/292135804" width="640" height="360" frameborder="0" allowfullscreen></iframe>{: .center-image }

As you can see, the process to access our offline audio tours is as easy for Nubart users as is accessing a Nubart audio guide in conventional streaming. They just have to wait a little longer for the contents to load.

Once we had the Noelia problem solved, it was clear to us that other clients could also benefit from the offline mode, like museums that have Wi-Fi in the reception area, but a bad data coverage in the exhibition halls. It also solved a problem for non-EU tourists who do not want to pay *roaming* while using the audio guide, as they can use a free wifi spot to download the content.

Meanwhile, we have expanded this development and now we also offer a hybrid solution, switching only the audio tracks assigned to areas of poor connectivity to offline mode. This improves loading speed and usability, as well as our data report.

Our offline mode also works well with our geolocation feature.

***

#### <font color="blue">At Nubart we produce innovative audioguide cards</font>


![Nubart's Audioguide als Kärtchen]({{site.baseurl}}/images/posts/proceso-nubart.png){: .center-image }
<form action="../../../../../">
    <input type="submit" value="Request a sample here" />
</form>