---
# Fill-in Speaker1, Speaker2, & speaker1 info below.
# Add tag(s) related to your presentation. Use lowercase tags. Also add "Your Name" as a tag.
title: "Web & Application Professionals Meetup – Apr"
tags: ["ReactJS", "Automation", "Agile", "Project Management", "Amara Omoregie", "Fred Garbutt", "Mike Stewart", "Innovatory", "Media Done Right", "Gunn|Jerkens"]
meeting_time: "7-9p"
meeting_start: "19:00"
venue: "GJ" # WELABS || GJ
venue_image: "/images/WAPRO_2016_04.jpg"
rsvp: "http://www.meetup.com/Uncoded/events/228760530/" # "http://www.meetup.com/Uncoded/events/225429587/"
redirect_from: #["/next/", "/meetup/next/", "/meetups/next/", "/events/next/"]
categories: meetup
layout: post
published: true
speaker1:
  name: "Amara Omoregie"  
  twt_name: "amaraREPS"
  ig_name: "amaraREPS"
  company: "Innovtory"
  bio_desc: "Amara Omoregie is a Managing Partner at Innovatory, the creative services division of We Labs. She is passionate about sales, marketing, and business development and has a major soft spot for entrepreneurs with innovative ideas. Mostly known for her bicoastal temperament and obsession with food, wine, and coffee, she likes long walks on the beach and hates hot chocolate."
  bio_img_path: "http://amarareps.com/wp-content/uploads/2014/03/team_amara-w560h640.jpg"
  presentation_type: "PRESENTATION"
  presentation_title: "Get Agile! Project Management for Freelance Developers"
  presentation_desc: "Project Managers and Developers love to hate each other, especially when they are the same person. Do you struggle with managing timelines, scope creep, and client's overall expectations? Learn some tips and tricks on how to structure a project for success from the beginning by taking control of the process and leading the entire thing from start to finish. We'll also look at ways to manage and scope projects in an effort to make projects more profitable, through Agile Project Management, and deliver them on-time. There will be plenty of time for a Q&A and to share horror stories/scenarios for how to deal with unruly clients that make projects that start out exciting, turn into nightmares."
speaker2:
  name: "Avo jeez0 (Fred Garbutt)"  
  twt_name: "avocadojesus"
  ig_name: "avocadojesus"
  company: "Freelancer"
  bio_desc: "IRC poet, writer of code, master of karaoking spice girls ballades"
  bio_img_path: "/images/people/fred-garbutt.jpg"
  presentation_type: "PRESENTATION"
  presentation_title: "WTFlux"
  presentation_desc: "A quick dive into react to understand what flux is, when/why you should use it, and how to implement it on a  very basic level."

---

{% if page.venue_image %}<img src="{{ base.url }}{{ page.venue_image }}" alt="monthly promotional picture">{% endif %}

## TALKS THIS MONTH  
The _Long Beach Web & App Professionals_ ([#WAPRO](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)) group meets monthly to share and learn about the technology that ignites our imagination, builds our skill-set, expands our network, and grows community!

{% if page.speaker1.presentation_title  %}1. <strong>{{ page.speaker1.name }} ([@{{ page.speaker1.twt_name }}]({{ site.base.twitter }}{{ page.speaker1.twt_name }}))</strong> – {{ page.speaker1.presentation_title }}  {% endif %}
{% if page.speaker2.presentation_title  %}1. <strong>{{ page.speaker2.name }} ([@{{ page.speaker2.twt_name }}]({{ site.base.twitter }}{{ page.speaker2.twt_name }}))</strong> – {{ page.speaker2.presentation_title }}  {% endif %}
{% if page.speaker3.presentation_title  %}1. <strong>{{ page.speaker3.name }} ([@{{ page.speaker3.twt_name }}]({{ site.base.twitter }}{{ page.speaker3.twt_name }}))</strong> – {{ page.speaker3.presentation_title }}  {% endif %}
1. [PLEASE R.S.V.P.]({{ page.rsvp }})

<!--break-->

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

**Future meetup dates:**  🌤 5/12 ⛵ 6/9 🌊 7/14 🌤

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


### AFTER HOURS + AWESOME PRIZES

![Reservation](/images/exibitionrm_reservation_2016_04.png)
We have a reservation at [Exhibition Room](http://www.theexhibitionroom.com/), arguably *the best speakeasy in California.*  If you'd like to join, please [tweet your RSVP](https://twitter.com/intent/tweet?text=Sounds%20awesome%20to%20spend%20%40waprolb%20%23afterhours%20%40ExhibitionRm%20speakeasy.%20I%27ll%20dress%2020%27s%20themed%20or%20biz%20casual!%20%23ThisIsLB%20%23uncoded%20%23wapro) to [@waprolb](https://twitter.com/waprolb) [@ExhibitionRm](https://twitter.com/ExhibitionRm) using hashtag #afterhours.  Be sure to wear 1920's themed attire or business casual.  (no shorts, flip-flops, t-shirts, etc).  

We'll also have prizes for those that RSVP and join us at either Exhibition room, or the larger venue, [Roxanne's Cocktail Lounge & New Latin Grill ](http://www.roxanneslounge.com/) (all ages + relaxed dress code).



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
