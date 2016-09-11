---
title: I need a hug ;(
categories: [Apps]
tags: [iOS, Apps, Mashape, API, Github]
comments: true
---


<div>
	<img align="middle" src="/img/apps/cuteme.jpg" >
</div>

New App idea
------------
Just a few days back while I was trying to ponder over  "How can some people be so bad at driving", while I was on my way to home I had a little fight with my buddy. Just as the fight got over I thought to myself "What is there was an app that could compliment the user to lighten his/her mood or spring a smile on their face??". The thought over it for few more minutes and thought "Why not the app give out an compliment to the user not as text but voice!".
There are lots of API out there to convert text to speech [Mashape.com Text to Speech](https://www.mashape.com/explore?query=text%20to%20speech&page=1), and whole lot of them are free and simple to use. This may not be really a new idea and I am sure there are apps out there that are already doing the same but hey there are 
times when you have to re invent the wheel.;)

Design
------------
I'm not very good at mobile designing but this is a simple design that is in my mind. Just a button and text with the compliment and well it does not kill some one to get just one more compliment ;) so there is a button for that too.


![Design](/img/apps/cuteme-Design.jpg)


Something more
------------
Not Just compliments but how about some ice breakers or cool lines to say ;) :P. why should the app be too simple, the iPhone is mighty powerful and there will be a whole lot of things that could be done!. May be option to select if the voice that actually compliments you is boy or a girl. May you can record your lovers voice, your parents voice or your friend or siblings voice and play it later as compliment off course. But as of now I need to start with the basic text to speech.


But from where the speech is going to come?
------------
This is tricky, May be I can try some AI and generate some techie compliments? However as start I need to read from a file (JSON) 
<pre><code>
[{"1":"You are looking fine night!"}, {"2":"Howz my baby?"}, {"3":"Misssing you!"}]
</code></pre>


and fire a request to the API and get the result. Then I can event let user download more such files (more compliments Yay!) but again why should the app be so simple? My hands are itching to try out something in AI!


By the way
------------
All the code that I code will be on Github (thank god for open source and Source control!) 



