---
title: 'Web & Application Professionals Meetup – Mar'
tags: []
meeting_time: 7-9p
meeting_start: '19:00'
venue: WELABS # WELABS || GJ
venue_image:
rsvp: https://www.meetup.com/Uncoded/events/238251035/
redirect_from:
  - /next/
  - /meetup/next/
  - /meetups/next/
  - /events/next/
categories: meetup
layout: post
published: true
speaker1:
  name: Kyle Taborski
  twt_name: ktabors
  ig_name:
  company: Adobe (Livefyre)
  bio_desc: Kyle Taborski has been a web software engineer for fifteen years working at a variety of small to large companies. I've mostly done Java and JavaScript development.
  bio_img_path: /images/people/kyle-taborski.png
  presentation_type: PRESENTATION
  presentation_title: Adobe (Livefyre) - Displaying User Gnereated Content (UGC)
  presentation_desc: "At Adobe (Livefyre) we help publishers and marketers engage with their audiences via user generated content (UGC). Starting with conversations using our comments, reviews and rating apps and moving into Media Walls, Carousels, Maps, Live Blogs, Sidenotes, etc. In most of these we display third party UGC from places like Twitter, Facebook, Instagram, Tumblr, and YouTube.

I'll walk though how the data from diverse sources is normalized and how different apps display the UGC. We display the UGC within our curation tools as well as our frontend apps. There is an evolution to how we've tried to best display UGC. I'll talk about what works and what doesn't work. This is a Javascript talk.

Livefyre is Adobe's UGC content platform. We are deployed on some of the most trafficked news sites. We have curate rules pulling in specific client defined content from the Twitter firehouse, Facebook API, Instagram API, etc. We deal with massive amounts of data and page views. For example 2.5B requests per day to via stream API, 1MM pieces of content added to apps dally, and 2.1MM documents indexed to search daily. We will look at how we display all this content to users."
speaker2:
  name:
  twt_name:
  ig_name:
  company:
  bio_desc:
  bio_img_path:
  presentation_type:
  presentation_title:
  presentation_desc:
speaker3:
  name:
  twt_name:
  ig_name:
  company:
  bio_desc:
  bio_img_path:
  presentation_type:
  presentation_title:
  presentation_desc:
speaker4:
  name:
  twt_name:
  ig_name:
  company:
  bio_desc:
  bio_img_path:
  presentation_type:
  presentation_title:
  presentation_desc:
---

{% if page.venue_image %}![monthly promotional picture]({{ base.url }}{{ page.venue_image }}){% endif %}

... more info posted soon! As always, I could use your help and input as we continue to work out details for presentations, venues, topics, etc. If you or someone you know would like to come share about App or Web development either this month or in the future, please contact us: [www.waprorlb.org/contact/](/contact)

With your suggestions we'll continue to improve the WAPRO format in 2017\. Our goals are to entice locals and guests to come share and inspire with best practices, interesting and/or fun projects, and cool tech tricks.

**Upcoming meetup dates:** ⛵ 3/21 🌷 4/20 🌤 5/16 ⛵ 6/22

<!--more-->

## TALKS THIS MONTH

The _Long Beach Web & App Professionals_ ([#WAPRO](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)) group meets monthly to share and learn about the technology that ignites our imagination, builds our skill-set, expands our network, and grows community!

{% if page.speaker1.presentation_title %}1\. **{{ page.speaker1.name }} ([@{{ page.speaker1.twt_name }}]({{ site.base.twitter }}{{ page.speaker1.twt_name }}))** – {{ page.speaker1.presentation_title }} {% endif %} {% if page.speaker2.presentation_title %}1\. **{{ page.speaker2.name }} ([@{{ page.speaker2.twt_name }}]({{ site.base.twitter }}{{ page.speaker2.twt_name }}))** – {{ page.speaker2.presentation_title }} {% endif %} {% if page.speaker3.presentation_title %}1\. **{{ page.speaker3.name }} ([@{{ page.speaker3.twt_name }}]({{ site.base.twitter }}{{ page.speaker3.twt_name }}))** – {{ page.speaker3.presentation_title }} {% endif %} {% if page.speaker4.presentation_title %}1\. **{{ page.speaker4.name }} ([@{{ page.speaker4.twt_name }}]({{ site.base.twitter }}{{ page.speaker4.twt_name }}))** – {{ page.speaker4.presentation_title }} {% endif %}

1. [PLEASE R.S.V.P.]({{ page.rsvp }})

### ABOUT WAPRO

The Long Beach Web & App Professionals (#WAPRO) group meets monthly to share and learn about the technology that ignites our imagination, builds our skill-set, expands our network, and grows community!

### MEETING TOPICS

In the past we've had professionals present that have worked on projects such as Spacex, Riot Games, X-prize, Adobe, Toyota Motor Sports, VMWare, UCLA, CSULB, AARP, and more ... using technologies such as [Bootstrap](http://getbootstrap.com/), [Bower](http://bower.io), [Browserfy](http://browserify.org/), [Headless Drupal](https://github.com/davidhwang/horseman), [iOS Swift](https://developer.apple.com/swift/), [Jekyll](http://jekyllrb.com), [Meteor](https://www.meteor.com/), [Node.js](https://iojs.org/en/), [SASS](http://sass-lang.com/), [Sculpin](http://sculpin.io), [Zapier](http://zapier.com) and more.

Every month we come together to:

* Demo technologies we use, especially those driving the convergence of websites and mobile apps
* Showcase our projects built with cool tech
* Share industry "best practices"
* Newcomer Q&A's
* Network, get to know each other, and otherwise have fun

We have a preference for open-source software, especially server-side. This year we have meetups focused on the life-cycle and technologies related to website and application development. We will especially try to delve into situations where mobile and web technologies converge. The meeting topics we cover will vary monthly and will be tailored to, and by, our community. Want to see something in particual? Let us know by tweeting using the hash #WAPRO.

If you have interest or work in Web or Application Development, add our meetup to your calendar now and join us! Our meetups are FREE and open to [EVERYONE](https://github.com/uncodedlb/uncoded-policies).

{% include venue.md %}

### DETAILS

{% if page.speaker1.name  %}
  **{{ page.speaker1.presentation_type | uppercase }}**  
  {{ page.speaker1.presentation_title | uppercase }}  

  {{ page.speaker1.presentation_desc | markdownify }}  

  <blockquote>
  <h3> {{ page.speaker1.name | markdownify }} </h3>

  {% if page.speaker1.company %}<strong>{{ page.speaker1.company }}</strong>{% endif %}  {% if page.speaker1.twt_name %}<a href="https://twitter.com/{{ page.speaker1.twt_name }}">Twitter: @{{ page.speaker1.twt_name }}</a>{% endif %}
  {% if page.speaker1.ig_name %}<a href="https://www.instagram.com/{{ page.speaker1.ig_name }}">Instagram: @{{ page.speaker1.ig_name }}</a>{% endif %}
  <img src="{{ site.baseurl }}{{ page.speaker1.bio_img_path }}" alt="headshot" class="headshot">
  {{ page.speaker1.bio_desc | markdownify }}  
  </blockquote>
{% endif %}


{% if page.prizes %}

## PRIZES!

We have prizes! Want to win? Help us connect with more local tech folk by sharing on your social networks. This has the benefit of growing your own professional network, too! The person with the most social shares promoting the meetup (tweets+retweets, fb likes/shares, etc) this month which include the hash [**#WAPRO**](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded) and/or **[#UNCODED](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)** will win their choice of prize offerings. _Minimum of six shares over at least three different dates. At the discretion of the crowd in attendance, we may give away multiple prizes if the crowd votes that many people have gone above & beyond to help spread the news. Please share & promote in [good taste. ☺](https://github.com/uncodedlb/uncoded-policies)_ {% endif %}

# SPONSORS

Our sponsors help make our meetups awesome! They feed us, provide a place to gather, share, & learn from each other, and some even give us cool things to giveaway! Take a moment to thank them, click their logo to visit their twitter/facebook account... and thank them publicly. _(Please, use hash **#WAPRO**)_

{% if page.sponsors.food.logo %}

## FOOD & BEVERAGES

[![{{ page.sponsors.food.name }}]({{ page.sponsors.food.logo }})]({{ site.base.twitter }}{{ page.sponsors.food.twitter }})

Come hungry & thirsty! This month food and beverage will be graciously provided by [{{ site.sponsors.food.name }}]({{ site.base.twitter }}{{ site.sponsors.food.twitter }}). {{ site.sponsors.food.desc }}

 {% if site.sponsors.food.extra %}

{{ site.sponsors.food.extra }}

{% endif %} {% endif %}



{% if page.sponsors.venue.logo %}

## VENUE SPONSOR

{% if page.sponsors.venue %}[![{{ site.sponsors.venue.name }}]({{ site.sponsors.venue.logo }})]({{ site.base.twitter }}{{ site.sponsors.venue.twitter }}){% endif %}

Our venue host this month is courtesy of [{{ site.sponsors.venues.gj.name }}]({{ site.base.twitter }}{{ site.sponsors.venues.gj.twitter }}). {{ site.sponsors.venues.gj.desc }}

 {% if site.sponsors.venues.gj.extra %}

{{ site.sponsors.venues.gj.extra }}

{% endif %} {% endif %}
