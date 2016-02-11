---
# Fill-in Speaker1, Speaker2, & speaker1 info below.
# Add tag(s) related to your presentation. Use lowercase tags. Also add "Your Name" as a tag.
title: "Web & Application Professionals Meetup – Mar"
tags: ["", "", "", ""]
meeting_time: "7-9p"
venue: "WELABS" # WELABS || GJ
venue_image: "/images/WAPRO_2016_03.jpg"
rsvp: "http://www.meetup.com/uncoded/events/" # "http://www.meetup.com/Uncoded/events/225429587/"
#redirect_from: ["/next/", "/meetup/next/", "/meetups/next/", "/events/next/"]
categories: meetup
layout: post
published: true
speaker1:
  name: "Nelson Abalos Jr"  
  twt_name: "thepixelgeek"
  ig_name: "pxlgk"
  company: "Webflow"
  bio_desc: "Nelson is on an endless journey to design, learn, and inspire.  He has been designing websites since the days before Geocities was bought (and ultimately discontinued) by Yahoo. During his off time you can find him either playing with his LEGO bricks, biking around town or hanging out with his family."
  bio_img_path: "/images/people/nelson-abalos.png"
  presentation_type: "PRESENTATION"
  presentation_title: "Creating happiness on that bridge between Web Designers and Web Developers"
  presentation_desc: "The old waterfall workflow to create a website from scratch has yet to evolve.  The amount of pain points that a creative team must tackle has increased significantly due to the rise of mobile devices.  In this talk, we’ll discuss these pain points, the root cause of them, and how we as a web design and development community can work together to fix it."
speaker2:
  name: "Karim Amer"
  twt_name: "kaftoot"
  ig_name: # if null, must be not be instantiated
  company: "freelancer"
  bio_img_path: "/images/people/karim-amer.jpg"
  bio_desc: "I am Karim. I've lived half of my life between Egypt and the States. I'm a huge Manchester united fan, a web developer, and *functional programming* language enthusiast"
  presentation_type: "DEMO"
  presentation_title: "Restful API in Python"
  presentation_desc: "We are going to build a restful API using DJango rest framework"
speaker3:
  name: "Loc Nguyen"
  twt_name: "locn"
  ig_name:  # if null, must be not be instantiated
  company: "Production Point"
  presentation_type: "PRESENTATION"
  bio_desc: "Loc runs a dev shop that specializes in making software for businesses who need to build quickly for their customers. His favorite tools to juice development time are Angular, React, Node and Cordova."
  bio_img_path: "/images/people/loc-nguyen.jpeg"
  presentation_title: "Stair stepping ES6 and TypeScript into an Angular App"
  presentation_desc: "Read the source of your favorite libraries and you may get lost. JavaScript illuminati and tutorial authors are talking another language now. You need to catch up while it's easy. We'll cover Webpack, the most useful syntactic sugar from ES6/TS, and refactor a 'real' Angular app."
speaker4:
  name: "Aaron Pedersen"
  twt_name: "aaronpedersen"
  company: "DevelopmentArc"
  presentation_type: "PRESENTATION"
  bio_desc: "As co-founder and principle at [DevelopmentArc](http://www.developmentarc.com/), a boutique development firm and parent company of [Pedanco](https://pedanco.com/), Aaron Pedersen’s passion lies in helping businesses streamline process making teams work more effectively through innovative technology solutions. A published author, expert speaker, and sought-after business consultant and trainer, Aaron works with a wide range of companies, from Fortune 500 corporations and multi-chain hospitality companies to emerging brands and seed-round startups including Toyota Motor Sports, DHAP Digital, Adobe, KitchenNetwork, CoreLogic, PWC, Yahoo, and FitStar."
  bio_img_path: "/images/people/aaron-pedersen.jpg"
  presentation_title: "Two men's goal to create a monolithic application but..."
  presentation_desc: "...it turns out its harder todo these days. Aaron Pedersen will provide a deep dive and detail the ecosystem of his software, Pedanco. Pedanco is a Guest Feedback and Recovery platform for the hospitality industry. Built using Rails and Heroku, the software's ecosystem has expanded over it's 4 years of development to include many  services and technologies, making it less like a monolithic application, and more robust and distributed. Service and technology including Postgres, ElasticSearch, NewRelic, Postmark and many more."



---

**Meetup: {{ page.date | date: "%B %-d, %Y" }}**  
{% if page.venue_image %}<img src="{{ base.url }}{{ page.venue_image }}" alt="monthly promotional picture">{% endif %}

## TALKS THIS MONTH  
The _Long Beach Web & App Professionals_ ([#WAPRO](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)) group meets monthly to share and learn about the technology that ignites our imagination, builds our skill-set, expands our network, and grows community!

{% if page.speaker1.presentation_title  %}1. <strong>{{ page.speaker1.name }} ([@{{ page.speaker1.twt_name }}]({{ site.base.twitter }}{{ page.speaker1.twt_name }}))</strong> – {{ page.speaker1.presentation_title }}  {% endif %}
{% if page.speaker2.presentation_title  %}1. <strong>{{ page.speaker2.name }} ([@{{ page.speaker2.twt_name }}]({{ site.base.twitter }}{{ page.speaker2.twt_name }}))</strong> – {{ page.speaker2.presentation_title }}  {% endif %}
{% if page.speaker3.presentation_title  %}1. <strong>{{ page.speaker3.name }} ([@{{ page.speaker3.twt_name }}]({{ site.base.twitter }}{{ page.speaker3.twt_name }}))</strong> – {{ page.speaker3.presentation_title }}  {% endif %}
{% if page.speaker4.presentation_title  %}1. <strong>{{ page.speaker4.name }} ([@{{ page.speaker4.twt_name }}]({{ site.base.twitter }}{{ page.speaker4.twt_name }}))</strong> – {{ page.speaker4.presentation_title }}  {% endif %}
1. [PLEASE R.S.V.P.]({{ page.rsvp }})

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

**Future meetup dates:**  🌷  4/5  🌤  5/3  ⛵  6/7  🌊

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
