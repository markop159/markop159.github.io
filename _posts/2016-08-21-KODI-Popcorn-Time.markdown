---
layout: post
title:  "KODI Popcorn Time"
date:   2016-08-21
categories: kodi
image: KODI-Popcorn-Time.jpg
---
<img alt="{{page.title}}" title="{{page.title}}" itemprop="thumbnailUrl" src="/img/{{page.image}}" style="max-width:100%;">

When Popcorn Time released I was really impressed by its simplicity. You just open an app on your computer and watch all movies with the simple mouse click. Additionally it is powered by torrent P2P technology. What basically means that you watch what others are sharing on torrent sites, and when you are watching you are sharing this content to other people as well so they can watch it too.

### Why KODI addon?

Since I am using a Raspberry PI 2 with OSMC as a media center I like to watch everything on it. So I started to search for some similar addon for KODI. Then I found on Github Popcorn Time port for KODI. It was developed by Diblo. I started to follow his work but then when Popcorn Time was shutdown he stopped development and tried to find someone who would be willing to continue his work.

I was thinking about signing up but at that time I had a lot of things going on in my life so I simply couldn't.

In July 2016 I finished my school and checked again progress on Diblo's work. I found out that it was where he left it, so I decided to fork his work and start playing with his code. This was my first time writing something for KODI and first time programming in python.

### My First steps

First things I started google-ing all around about developing addons for KODI, about python, xml...
Then first repaired movies section with changing provider. Tested it for couple of days on Windows and Raspberry PI. I noticed that not all movies are working, so I also repaired this issue. Then I created a Repository for future updates and released the first version.

### My First update

In spite of working on bigger update I released first minor update couple of weeks later because of the timeout issue on Linux devices, and replaced provider due to issue with "action: seed" not working on current version.

### My First Big update

Today I released new update and this is a big one. This update adds the capability to watch TV Shows and for bonus it also delivers Anime section. I also introduced new API provider with Popcorn Time API version 2.1.0 that introduced a lot of changes. In this update there are a lot of Issues with Settings GUI so I advice to use settings only for enable-ing debugging in case of submitting Issues.

### Is it free?

Yes all my projects on Github come for free and anybody can check it to learn something new or use my work for your projects. In case of using this no your projects please add Credits and link to my [Developer Github Page](https://markop159.github.io). If you really liked it and want to buy me a beer you can always use a donate button on bottom of my page.
