+++
title = "Gwion, a musical programming language"
date = "2022-05-24T10:13:50+05:30"
author = "Aarav Navani"
authorTwitter = "AaravNavani" #do not include @
cover = ""
tags = ["gwion", "music"]
keywords = ["gwion", "music", "musical programming", "programming languages"]
description = ""
showFullContent = false
readingTime = true
hideComments = false
+++

Gwion is a strongly timed, musical programming language designed with ease of use and the ability to be extendable in mind. It's simple syntax and module system lends itself to a fun music-making experience.

I had the pleasure of being able to talk with Jérémie Astor, creator of Gwion, and learn about the process of Gwion and where he wants it to go. The interview follows.

Aarav: Alright, let us start with your introduction then, tell us a little about yourself and Gwion

Jérémie: I'm a musician, started getting pro gigs when I was 16yo, at the time mainly a jazz guitarist. In my 20s I started also getting contracts for direction and composition, and it stayed about that way until now. I do love a very wide range of musics, including classical contemporary music and for this part of my work I wanted a tool that helped devise new scales and rythms at one point I found chuck, which I loved, that's actually what got me into programming. I had the chance to make a few gigs with it including very funny stuff using kinect to make music realtime that would react to the audience but after sometime I somehow became too fluent in chuck that is I would start writing piece that would eat all the resources of my computer very quick then I told myself: let's write something like chuck but in C because I genuinely thought C would automagically solve my problems. So at the start Gwion was aiming to be a faster Chuck with a few things I missed in it like function pointers and generics.

Aarav: Thats quite interesting, now having used Chuck and working on Gwion, do you think music and programming pair well together?

Jérémie: Well I don't think it really pairs well with like playing guitar around the campfire but a fair amount of my job is making nice structures for pieces and there's a large overlap between that and software architecture, also being able to analyze music in realtime can really help growing as an interpret especially when you deal with uncommon scales/rythms.

Aarav: I see, now does this mean that musical or music-oriented programming languages can help lower the entry barriers for making music?

Jérémie: it sure can help for production but you will still need to learn basic human music skills, like breathing and singing (breathing right is pretty fundamental to get rythm right and helps a lot with having a clear state of mind) but indeed with all the devices we have in this century, a music language can help producing anywhere anytime including with a very low skill level.

Aarav: Gotcha, that is pretty neat, now I am a big fan of electronic music especially house music, could something like Gwion or Chuck assist me in producing more electronic music, or are they oriented towards particular genres of music?

Jérémie: no they are pretty low level in the musical sense so it allows the user to make any music they want, that's really something I loved in chuck and I wanted to keep that in gwion tbf I only gave langs like sonicpi a quick look since they are much more biased towards occidental music theory, that said, they are a very good fit if that's what you wanna do.

Aarav: Sounds good! Now earlier you mentioned that there was stuff you missed in Chuck, is there anything else that you miss in Chuck that you added to Gwion?

Jérémie: Turns out the gwion type system is much more expressive. I also added a preprocessor, since it's a thing I really like in C, also there are recent additions that are especially interesting/useful in my opinion like music locales that allows the user to define the name and frequency of the notes they want to use, also virtual time, that allows to have a strongly timed process running as fast as possible while you still have the strong real time aspect.

Aarav: Seems like you've really shaped Gwion to be the language you've always wanted it to be, has Gwion seen any real usage outside of testing?

Jérémie: I used it in a few shows mainly children shows, it's also used by the company supporting the lang.

Aarav: Oh wow, that is amazing! How do you plan on growing Gwion, as in how do you wish to get the word out about Gwion and get more people to use it?

Jérémie: Well if I use it more in my on job I could advertise it more, but atm I'm making more acoustic music. Also if the company has some success it could help, but clearly the main pain point for that atm is that I'm fairly not confident when writing docs and docs probably play a huge part in user adoption, that said I had never planned for this project to have any success but if it can help people making music I'm happy helping it grow. Gwion was basically just a tool for my job.

Aarav: Pretty cool! Now before we close off, do you have any tips or advice for people trying to build out their languages?

Jérémie: Stick to it that would be my main advice while it's nice to try a lot of langs/framework/tools the main thing that will help a project reach some completion is dedication in my experience. Oh I have a second advice, don't expect your lang to be perfect, be it the 10th times, it's tradeoff all along the way.

Aarav: Sound advice, well I thank you for your time and wish you good luck on your further adventures!

Jérémie: thanks, talk soon, and good luck for your projects.
