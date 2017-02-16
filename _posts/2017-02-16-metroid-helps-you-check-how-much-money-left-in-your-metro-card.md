---
layout: post
published: false
title: Metroid helps you check how much money left in your metro card
---
Have you ever wondered what was the use of you NFC chip? Here's one : check your public transportation card's balance. 

At the moment, the supported cards are as follow :
* Bilhete Único - São Paulo, Brazil (requires encryption keys, not compatible with all devices, must be selected as fallback reader)
* Clipper - San Francisco, CA, USA
* EZ-Link - Singapore (Not compatible with all devices)
* Go card (Translink) - Brisbane and South East Queensland, Australia (requires encryption keys, not compatible with all devices, not all stations known)
* Manly Fast Ferry - Sydney, NSW, Australia (requires encryption keys, not compatible with all devices)
* Matkakortti, HSL - Finland
* Myki - Melbourne (and surrounds), VIC, Australia (Only the card number can be read)
* MyWay - Australian Capital Territory, Australia (preview, requires encryption keys, not compatible with all devices, must be selected as fallback reader)
* NETS FlashPay - Singapore
* Octopus - Hong Kong
* Opal - Sydney (and surrounds), NSW, Australia
* ORCA - Seattle, WA, USA
* OV-chipkaart - Netherlands (Requires encryption keys, not compatible with all devices)
* Shenzhen Tong - Shenzhen, Guangdong Province, China
* Suica, ICOCA, PASMO, Edy - Japan
* Transit Access Pass - Los Angeles, CA, USA (Requires encryption keys, not compatible with all devices)

As I live between Hong Kong and Shenzhen, I will focus on these two. Let's have a look on how to check my Octopus card (Hong Kong) balance :

![first.png]({{site.baseurl}}/img/first.png)

First, download the app called Metroid (from [Play store](https://play.google.com/store/apps/details?id=au.id.micolous.farebot) or [F-droid](https://f-droid.org/), it is open-source and the code is on [Github](https://github.com/micolous/metrodroid)) :

Second, after you launched the app, you will be prompted to activate NFC, 

![reqding.png]({{site.baseurl}}/img/reqding.png)

Third, just put your card at the back of your phone and let's start reading! 

![balance.png]({{site.baseurl}}/img/balance.png)

Here we go I still have 40 HKD on my Octopus 🐙! 

When I try the same thing with my 深圳通  (Shenzhen Tong), I get an error :

![error.png]({{site.baseurl}}/img/error.png)


It may be because the shenzhen's card support is still in beta or because my phone is not a NXP NFC chipset (About screen says: `Mifare Classic: Supported`). 

Anyway, if your phone and city transportation card are fully supported it is a useful app to have. It happened to me a few times that I give away these cards to my friends before they go visit a city but I always have to warn them that "I don't know how much money is in it!". 
