---
# Fill-in Speaker1, Speaker2, & speaker1 info below.
# Add tag(s) related to your presentation. Use lowercase tags. Also add "Your Name" as a tag.
title: "Web & Application Professionals Meetup – May"
tags: ["Design", "CSS", "Jekyll"]
meeting_time: "7-9p"
meeting_start: "19:00"
venue: "WELABS" # WELABS || GJ
venue_image: "/images/WE_Labs2.jpeg"
rsvp: "http://www.meetup.com/Uncoded/events/231080180/"
#redirect_from: ["/next/", "/meetup/next/", "/meetups/next/", "/events/next/"]
categories: meetup
layout: post
published: true
speaker1:
  name: "Stephanie Mallon"  
  twt_name: ""
  ig_name: "watermallonstudios"
  company: "WaterMallon Studios"
  bio_desc: ""
  bio_img_path: "/images/people/staff-steph.jpg"
  presentation_type: "PRESENTATION"
  presentation_title: "Designers dealing with CSS & Tech"
  presentation_desc: "Designers don't always know about tech & the systems for which they create designs.  In this talk I'll present some common scenarios I face"
speaker2:
  name: "Mike Stewart"  
  twt_name: "mdrmike_"
  ig_name: "mdrmike"
  company: "Media Done Right"
  bio_desc: "A long time open source evangelist, community organizer, and resident of Long Beach. Stewart started his career in enterprise I.T. implementing projects such as: Customer Relationship Management, Engineering Document Management, and ERP Systems. His knowledge of Microsoft technologies, ERP, and manufacturing led him to employers focused on Warehouse Management Systems, Time & Attendance, and Management Execution Systems. The latter projects utilized early Microsoft web technologies which eventually led him to consulting building websites and web based applications. Ultimately, licensing independence for his clients plus the discovery of the principles behind free software, led him to Drupal as a veritable swiss-army-knife for the web, and free software in general."
  bio_img_path: "/images/people/mike-stewart.jpg"
  presentation_type: "PRESENTATION"
  presentation_title: "Don't wait, Automate!"
  presentation_desc: "A show & tell of tools to help automate your frontend and backend development environment, using best-practices, and utilizing help from giants. Tech: `Yeoman, Grunt, Gulp, Bower, NPM, and maybe Virtualbox/Docker` and why you should use them regardless of your tech stack."
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

{% if page.venue_image %}<img src="{{ base.url }}{{ page.venue_image }}" alt="monthly promotional picture">{% endif %}

## TALKS THIS MONTH  
The _Long Beach Web & App Professionals_ ([#WAPRO](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)) group meets monthly to share and learn about the technology that ignites our imagination, builds our skill-set, expands our network, and grows community!

{% if page.speaker1.presentation_title  %}1. <strong>{{ page.speaker1.name }} ([@{{ page.speaker1.twt_name }}]({{ site.base.twitter }}{{ page.speaker1.twt_name }}))</strong> – {{ page.speaker1.presentation_title }}  {% endif %}
{% if page.speaker2.presentation_title  %}1. <strong>{{ page.speaker2.name }} ([@{{ page.speaker2.twt_name }}]({{ site.base.twitter }}{{ page.speaker2.twt_name }}))</strong> – {{ page.speaker2.presentation_title }}  {% endif %}
{% if page.speaker3.presentation_title  %}1. <strong>{{ page.speaker3.name }} ([@{{ page.speaker3.twt_name }}]({{ site.base.twitter }}{{ page.speaker3.twt_name }}))</strong> – {{ page.speaker3.presentation_title }}  {% endif %}
{% if page.speaker4.presentation_title  %}1. <strong>{{ page.speaker4.name }} ([@{{ page.speaker4.twt_name }}]({{ site.base.twitter }}{{ page.speaker4.twt_name }}))</strong> – {{ page.speaker4.presentation_title }}  {% endif %}
1. [PLEASE R.S.V.P.]({{ page.rsvp }})

<!--more-->  

## VALUE

Tech moves too fast to keep up on everything yourself.  There's always someone faster, better, or smarter than you.  Come meet them, connect, and lean on community.  If you're a local business or agency, join us and encourage staff to come.  It's a great way to expand your network of folks active and connected, which leads to both new business and potential new recruits.  Everyone wins!


## TOPICS

The Pros that have worked on/for projects such as Spacex, Riot Games, X-prize, Adobe, Toyota Motor Sports, VMWare, UCLA, CSULB, AARP, and more ... have shared amazing talks this year on tech and projects such as [Bootstrap](http://getbootstrap.com/), [Bower](http://bower.io), [Browserfy](http://browserify.org/), [Headless Drupal](https://github.com/davidhwang/horseman), [iOS Swift](https://developer.apple.com/swift/), [Jekyll](http://jekyllrb.com), [Meteor](https://www.meteor.com/), [Node.js](https://iojs.org/en/), [SASS](http://sass-lang.com/), [Sculpin](http://sculpin.io), [Zapier](http://zapier.com) and more.

Every month we come together to:

* Demo technologies we use, especially those driving the convergence of websites and mobile apps
* Showcase our projects built with cool tech
* Share industry "best practices"
* Newcomer Q&A's
* Network, get to know each other, and otherwise have fun

We have a preference for open-source software, especially server-side.  This year we have meetups focused on the life-cycle and technologies related to website and application development.  We will especially try to delve into situations where mobile and web technologies converge.  The meeting topics we cover will vary monthly and will be tailored to, and by, our community.  Want to see something in particual?  Let us know by tweeting using the hash #WAPRO.  

**Future meetup dates:**   ⛵  6/7  🌊 Fall 2016 TBA

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


{% if page.speaker2.name %}
  **{{ page.speaker2.presentation_type | uppercase }}**  
  {{ page.speaker2.presentation_title | uppercase }}  

  {{ page.speaker2.presentation_desc | markdownify }}
  <blockquote>
  <h3> {{ page.speaker2.name | markdownify }} </h3>

  {% if page.speaker2.company %}<strong>{{ page.speaker2.company }}</strong>{% endif %}  {% if page.speaker2.twt_name %}<a href="https://twitter.com/{{ page.speaker2.twt_name }}">Twitter: @{{ page.speaker2.twt_name }}</a>{% endif %}
  {% if page.speaker2.ig_name %}<a href="https://www.instagram.com/{{ page.speaker2.ig_name }}">Instagram: @{{ page.speaker2.ig_name }}</a>{% endif %}  
  <img src="{{ site.baseurl }}{{ page.speaker2.bio_img_path }}" alt="headshot" class="headshot">
  {{ page.speaker2.bio_desc | markdownify }}  
  </blockquote>
{% endif %}


{% if page.speaker3.name  %}
  **{{ page.speaker3.presentation_type | uppercase }}**  
  {{ page.speaker3.presentation_title | uppercase }}  

  {{ page.speaker3.presentation_desc | markdownify }}
  <blockquote>
  <h3> {{ page.speaker3.name | markdownify }} </h3>

  {% if page.speaker3.company %}<strong>{{ page.speaker3.company }}</strong>{% endif %} {% if page.speaker3.twt_name %}<a href="https://twitter.com/{{ page.speaker3.twt_name }}">Twitter: @{{ page.speaker3.twt_name }}</a>{% endif %}
  {% if page.speaker3.ig_name %}<a href="https://www.instagram.com/{{ page.speaker3.ig_name }}">Instagram: @{{ page.speaker3.ig_name }}</a>{% endif %}
  <img src="{{ site.baseurl }}{{ page.speaker3.bio_img_path }}" alt="headshot" class="headshot">
  {{ page.speaker3.bio_desc | markdownify }}  
  </blockquote>
{% endif %}

{% if page.speaker4.name  %}
  **{{ page.speaker4.presentation_type | uppercase }}**  
  {{ page.speaker4.presentation_title | uppercase }}  

  {{ page.speaker4.presentation_desc | markdownify }}
  <blockquote>
  <h3> {{ page.speaker4.name | markdownify }} </h3>

  {% if page.speaker4.company %}<strong>{{ page.speaker4.company }}</strong>{% endif %} {% if page.speaker4.twt_name %}<a href="https://twitter.com/{{ page.speaker4.twt_name }}">Twitter: @{{ page.speaker4.twt_name }}</a>{% endif %}
  {% if page.speaker4.ig_name %}<a href="https://www.instagram.com/{{ page.speaker4.ig_name }}">Instagram: @{{ page.speaker4.ig_name }}</a>{% endif %}
  <img src="{{ site.baseurl }}{{ page.speaker4.bio_img_path }}" alt="headshot" class="headshot">
  {{ page.speaker4.bio_desc | markdownify }}  
  </blockquote>
{% endif %}

{% if page.prizes %}
  ### PRIZES!  

  We have prizes!  Want to win?  Help us connect with more local tech folk by sharing on your social networks.  This has the benefit of growing your own professional network, too! The person with the most social shares promoting the meetup (tweets+retweets, fb likes/shares, etc) this month which include the hash [**#WAPRO**](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded) and/or **[#UNCODED](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)** will win their choice of prize offerings.  *Minimum of six shares over at least three different dates.  At the discretion of the crowd in attendance, we may give away multiple prizes if the crowd votes that many people have gone above & beyond to help spread the news.  Please share & promote in [good taste. ☺](https://github.com/uncodedlb/uncoded-policies)*
{% endif %}


## SPONSORS

Our sponsors help make our meetups awesome! They feed us, provide a place to gather, share, & learn from each other, and some even give us cool things to giveaway!  Take a moment to thank them, click their logo to visit their twitter/facebook account... and thank them publicly.  *(Please, use hash __#WAPRO__)*

{% if page.sponsors.food.logo %}
  ### FOOD & BEVERAGES

  <a href="{{ site.base.twitter }}{{ page.sponsors.food.twitter }}" target="_blank"><img class="logo" src='{{ page.sponsors.food.logo }}' alt='{{ page.sponsors.food.name }}'></a>
  <p>Come hungry & thirsty! This month food and beverage will be graciously provided by <a href="{{ site.base.twitter }}{{ site.sponsors.food.twitter }}" target="_blank">{{ site.sponsors.food.name }}</a>.  {{ site.sponsors.food.desc }}</p>
  {% if site.sponsors.food.extra %}<p>{{ site.sponsors.food.extra }}</p>{% endif %}
{% endif %}

{% if page.sponsors.venue.logo %}
  ### VENUE SPONSOR

  {% if page.sponsors.venue %}<a href="{{ site.base.twitter }}{{ site.sponsors.venue.twitter }}" target="_blank"><img class="logo" src='{{ site.sponsors.venue.logo }}' alt='{{ site.sponsors.venue.name }}'></a>{% endif %}
  <p>Our venue host this month is courtesy of <a href="{{ site.base.twitter }}{{ site.sponsors.venues.gj.twitter }}" target="_blank">{{ site.sponsors.venues.gj.name }}</a>.  {{ site.sponsors.venues.gj.desc }}</p>
  {% if site.sponsors.venues.gj.extra %}<p>{{ site.sponsors.venues.gj.extra }}</p>{% endif %}
{% endif %}
