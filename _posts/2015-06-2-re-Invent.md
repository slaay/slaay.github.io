---
title: Reinvent! really?
categories: [Coding]
tags: [Coders, Programmers, IoT, Mandrill]
comments: true
---


<div>
	<img align="middle" src="/img/reinvent/caveman-wheel-cartoon.jpg" >
</div>

Reinvent the wheel..WHY?
------------
You may have heard people say something that goes like this "No need to reinvent the wheel", haven't you?. According to me this means that there are things which
exists out in the wild which you should be using instead of making something the same thing!. In software world, people come up with brilliant idea and brilliant products however while turning those ideas into reality, software guys commit the mistake of re inventing the wheel.

For example
------------
Let me give you an example of good friend Slaay Lee who happens to be developing the next big thing in [IOT](), a app that sends email notifications to all you buddies out there about the exercise you are doing. The app reads the GPS data and process the information about how much distance you have covered and send a nice little map with breadcrumbs to your pals, pretty neat!. But what Slaay Lee does is, he goes ahead and create a mailing app to handle all this mailing part.
Thus wasting a whole lot of time actually designing, developing, testing, maintaining it (basically re inventing the wheel).

What Slaay Lee could have done?
------------
Well he could have just created a free account on [Mandrill](https://www.mandrill.com/) (Email delivery API from Mailchimp) and used the API to send the mails.

{% highlight ruby %}
require 'mail'

Mail.defaults do
  delivery_method :smtp, {
    :port      => 587,
    :address   => "smtp.mandrillapp.com",
    :user_name => MANDRILL_USERNAME,
    :password  => MANDRILL_PASSWORD
  }
end
{% endhighlight %}

Even though its a free account, you get loads of free emails per hour, day, month!. There are awesome [reports and analysis and delivery reports](http://mandrill.com/features/) even more loads of feature and SDKs for iOS and Android.
There are so many features to use that Slaay Lee will spend ages coding and testing all those if he goes ahead and tries to develop something for his app.

What are other example of the "Wheel"
------------
Other examples would be Slaay Lee using spreed sheets to manage his bugs! or folder back to manage his code! (oh no!), instead of something like [MantisBT](http://www.mantisbt.org/) or [fogbugz](http://www.fogcreek.com/fogbugz/) or [Github](github.com/slaay) or [Bitbucket](https://bitbucket.org/) or [HipChat](www.hipchat.com/‎) or [Mashape](https://www.mashape.com) or [Trello](https://trello.com/). These are just a few
example, the web is full of amazing tool that could make life of Slaay Lee so much easier and better.