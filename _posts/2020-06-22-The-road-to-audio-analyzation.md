---
layout: post
title:  "How Analyze Audio"
date:   2020-06-22 15:25:00 +0100
tags: School Update
color: rgb(255,90,90)
cover: '../assets/Images/uwuBotWebots.png'
subtitle: 'Dance your way to victory'
---
Hello again,

last time I was talking about two tasks I had to do.
1. Make the Music Spectrum Analyzer for the project.
2. Draw/Make a good-looking poster.

This time we are going to talk about the music spectrum analyzer.
About the journey how it was made it and how we got there in the end.

There won't be as many pictures this time as last post.

I'll try to add some videos of the results at the end of this post.
If that doesn't work out there will be a link to where you can watch them.

Now on to the topic at hand.
The sound analyzer step of this project is two fold.
1. Create dance moves.
2. Load/listen to audio and break it down in a spectrum of hertz ranges.

While I was making the program to break down the audio and analyze it, another teammate was making the "sweet" dance moves.  
First I had to find a viable library to load audio into a buffer so i could break it down.  
The first library I arrived at was [Lieff/MiniMp3](https://github.com/lieff/minimp3).  
while this worked in loading an mp3 successfully it had a tendency to not build the buffer I needed to use.  
So the search continued to find another library.  
To spare you the details of how many libraries we had tried we'll just skip to the final library used.  
The last library we tried was [Bass.net](http://bass.radio42.com/).  
While testing this library came to the conclusion that we needed write a small external analyzer outside to the robots control script.

To make it easy on the eyes a small debug GUI was made aswell.  
This is how it looked like when it was finished.
![Debug GUI](/assets/Images/DebugGUI.PNG)

While I couldn't make videos, get to work in this post due to time constraints
here the link to a teamate [stack](https://stack.anotherfoxguy.com/s/Ue65kEaJEv3QsH2?dir=Wedstrijd&node-id=0) with the videos.  
Dancing on a chosen song [Rasputin](https://stack.anotherfoxguy.com/public-share/Ue65kEaJEv3QsH2/download?download-path=%2FWedstrijd%2FDancing+on+the+moon%2FRobot-W-dancing_on_the_moon.mp4&CSRF-Token=iRhT23U3cncuNQi_uWyYiQ)  
Dancing on a jury provided song [JuryMix](https://stack.anotherfoxguy.com/public-share/Ue65kEaJEv3QsH2/download?download-path=%2FWedstrijd%2FMoon+Walk%2FRobot-W-LineDance.mp4&CSRF-Token=iRhT23U3cncuNQi_uWyYiQ)

If I get the time. Ill try to fix this post to have the videos more embedded.

That's it for now.

As always.

Your gracious host,
Altair.
