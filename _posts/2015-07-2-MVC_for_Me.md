---
title: MVC for Me!
categories: [Coding]
tags: [MVC, .NET, ASP, Delphi]
comments: true
---


<div>
  <img align="middle" src="/img/Dotnet/mvc.jpg" >
</div>

How I thought myself little bit of MVC
------------
(**Newbie alert, don't kill me if I said something wrong!**) <br/>
Model--View--Controller
The heart and soul of architectural pattern for user interface for a lot of modern development platforms. I was recently introduced to MVC (first time while learning iOS), though it took me a while to get he hang of it but it was worth digging my head into it.
Some one recently said to me "It will not be a waste as what you learn will not be forgotten". Its of those very important things that are not thought in school.

Just magic!
------------
Its just magical to see how data, action and the stuff that you see on screen can be handled so nicely using MVC pattern. Once you get your head around it
you will love to use it in everything you code. Alas! you cannot use it every ;(. I suppose Objective C and Asp.Net developers are lucky (and not to forget PhP guys) as the very nature some of their projects are built are based on MVC! and are more aware of it than others. while other toil away in spaghetti world.
Not that MVC cannot be implement in other platforms, its just that a lot of developers may not be aware of it.

Some of the magic of MVC

  * Vastly improves the testability of the presentation tier
  * Makes a logical separation of concerns at the UI tier
  * Provides more direct access to the underlying HTML of the page

What is MVC?
------------
Basically M-> Model V-> View D -> Data
  * Model
     * You will write you business logic in you Model.
     * Database access related code or data from some web service
     * All that data is made available for the View to access it.
  	 * Example : This will be your C# code to access MS SQL code to get the list of football (Arsenal ;)) players from a remote database.
  * View
  	 * View is what the user will see.
  	 * Your View will access the data from Model.
  	 * Render it the way you want he user to see it.
  	 * Example : your application is showing a list of Arsenal players in a grid

  * Controller
  	 * The actions which the users performs.
  	 * Controller will tell the Model the to get some new data the user has asked for.
  	 * Example : The user has clicked on a button to get single player details. So the controller will contact the Model to get that single players data,
  	   the model will get the data and the view will show the data.

  check the image above.

MVC MVC MVC
------------
Its not that using MVC will make you a great coder and surely not using it will not make you a bad coder either. Its has it advantages and there are always those projects where you will have to make a big deal of change to implement it however its always great to know about it and use it whenever you can!.

Here are some of the MVC related stuff that I find really interesting.

   * ASP MVC 
   		<br/> [www.asp.net](http://www.asp.net/mvc)
   * w3c
   		<br/> [w3schools mvc intro](http://www.w3schools.com/aspnet/mvc_intro.asp)
   * Delphi 
   		<br/>[MVC in Delphi ?](http://programmers.stackexchange.com/questions/252028/best-practices-for-implementing-mvvm-and-mvc-in-delphi-pascal)
   		<br/>[MVC pattern in Delphi](http://stackoverflow.com/questions/6873469/delphi-7-trying-to-understand-the-mvc-pattern)
   		<br/>[Arnaud Bouchez - Delphi MVC](http://www.slideshare.net/ArnaudBouchez1/architecture-delphi-from-rad-to-mvc)
   * Apple 
   		<br/>[Apple MVC](https://developer.apple.com/library/mac/documentation/General/Conceptual/CocoaEncyclopedia/Model-View-Controller/Model-View-Controller.html)
   * PHP
   		<br/>[CcodeIgniter](http://www.codeigniter.com/)

   * Move ON
   		<br/>[MVC is dead](https://cirw.in/blog/time-to-move-on)		