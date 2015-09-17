---
# Presenters: Follow the "skeleton" to add info about your talk.
# Note letter cAsE and "extra two spaces" at the end of a few important lines.
# Start by adding lowercase tag(s) related to your presentation.  Also add "Your Name" as a tag.
title: "Web & Application Professionals Meetup – September"
meeting_time: "6:30-9p"
venue: "WELABS"
tags: [zapier, collectible, aCoin, "Brandon Halvorson", "Greg Gerber"]
categories: meetup
layout: post
#redirect_from: ["/next/", "/meetup/next/", "/meetups/next/", "/events/next/"]
published: true
speaker1:
  name: "Brandon Halvorson"
  company: "Assignment Creative"
  personal: "Founder/C.E.O of Assignment Creative, music lover, and craft beer drinker."
  title: "A NEW CREATIVE MARKETPLACE BUILT WITH A COLLECTIBLE YOU CAN'T TOUCH"
  type: "SHOWCASE"
  twit: "acreative_"
  ipath: "/images/people/brandon-halvorson.jpg"
  desc: "What is a collectible and how has it changed in the era of cryptocurrency? A demo and discussion on how an intangible digital product can change the music industry and more. In addition to the demo, we'd like to spark a discussion on if/how users will build a relationship (like your favorite record/painting/G.I. Joe Collectable) but with a 'file' thats value/worth is based on the access it provides OR a psychological attachment. Presented by Assignment Creative.  "
speaker2:
  name: "Greg Gerber"
  company:
  personal: "Solopreneur operating on the fringe"
  title: "ZAPIER, AUTOMATE EVERYTHING <em>(with lights, this time)</em>"
  type: "PRESENTATION"
  twit: "gerbz"
  ipath: "/images/people/gerbz.png"
  desc: ""
---

**Meetup: {{ page.date | date: "%B %-d, %Y" }}**  

### ABOUT WAPRO  
The Long Beach Web & App Professionals (WAPRO) group meets monthly to share and learn about the technology that ignites our imagination, builds our skill-set, expands our network, and grows community!  

The Pros that have worked on/for projects such as Spacex, Riot Games, X-prize, Adobe, Toyota Motor Sports, VMWare, UCLA, CSULB, AARP, and more ... have shared amazing talks this year on tech and projects such as [Bootstrap](http://getbootstrap.com/), [Bower](http://bower.io), [Browserfy](http://browserify.org/), [Headless Drupal](https://github.com/davidhwang/horseman), [iOS Swift](https://developer.apple.com/swift/), [Jekyll](http://jekyllrb.com), [Meteor](https://www.meteor.com/), [Node.js](http://iojs.org), [SASS](http://sass-lang.com/), [Sculpin](http://sculpin.io), [Zapier](http://zapier.com) and more.

Every month we come together to:

* Demo technologies we use, especially those driving the convergence of websites and mobile apps
* Showcase our projects built with cool tech
* Share industry "best practices"
* Newcomer Q&A's
* Network, get to know each other, and otherwise have fun


We have a preference for open-source software, especially server-side.  This year we have meetups focused on the life-cycle and technologies related to website and application development.  We will especially try to delve into situations where mobile and web technologies converge.  The meeting topics we cover will vary monthly and will be tailored to, and by, our community.  Let us know what you'd like to see at an upcoming meetup by tweeting using the hash #WAPRO.  

If you have interest or work in Web or Application Development, add our meetup to your calendar now and join us! Our meetups are FREE and open to [EVERYONE](https://github.com/uncodedlb/uncoded-policies).  


### TALKS THIS MONTH  
- {{ page.speaker1.name }} ([@{{ page.speaker1.twit }}](https://twitter.com/{{ page.speaker1.twit }})) – {{ page.speaker1.title }}  
- {{ page.speaker2.name }} ([@{{ page.speaker2.twit }}](https://twitter.com/{{ page.speaker2.twit }})) – {{ page.speaker2.title }}


--------

{% include venue.md %}


### DETAILS  

**{{ page.speaker1.type | uppercase }}**  
{{ page.speaker1.title | uppercase }}  

{{ page.speaker1.desc | markdownify }}  

> ### {{ page.speaker1.name | markdownify }}{% if page.speaker1.company %}, {{ page.speaker1.company }}{% endif %}  ([@{{ page.speaker1.twit }}](https://twitter.com/{{ page.speaker1.twit }}))  
> <img src="{{ site.baseurl }}{{ page.speaker1.ipath }}" alt="headshot" class="headshot">
> {{ page.speaker1.personal | markdownify }}  

**{{ page.speaker2.type | uppercase }}**  
{{ page.speaker2.title | uppercase }}

{{ page.speaker2.desc | markdownify }}  

> ### {{ page.speaker2.name | markdownify }}{% if page.speaker2.company %}, {{ page.speaker2.company }}{% endif %}  ([@{{ page.speaker2.twit }}](https://twitter.com/{{ page.speaker2.twit }}))  
> <img src="{{ site.baseurl }}{{ page.speaker2.ipath }}" alt="headshot" class="headshot">
> {{ page.speaker2.personal | markdownify }}  





### PRIZES!  

The person in attendance with the most social shares promoting the meetup (tweets+retweets, fb likes/shares, etc) this month which include the hashes **#WAPRO** and **#UNCODED** will win their choice of prize offerings.  Minimum of six shares over at least three different dates.  At the discretion of the crowd in attendance, we may give away prizes if the crowd votes that multiple people have gone above & beyond to help spread the news.  Please share & promote in [good taste. ☺](https://github.com/uncodedlb/uncoded-policies)
