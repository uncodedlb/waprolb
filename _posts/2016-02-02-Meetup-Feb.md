---
# Fill-in Speaker1, Speaker2, & Speaker3 info below.
# Add tag(s) related to your presentation. Use lowercase tags. Also add "Your Name" as a tag.
title: "Web & Application Professionals Meetup – Feb"
tags: ["SEO", "Steve Kochan", "", ""]
meeting_time: "7-9p"
venue: "GJ" # WELABS || GJ
venue_image: "/images/GJ-presentation.jpeg"
rsvp: "http://www.meetup.com/uncoded/events" # "http://www.meetup.com/Uncoded/events/225429587/"
redirect_from: ["/next/", "/meetup/next/", "/meetups/next/", "/events/next/"]
categories: meetup
layout: post
published: true
speaker1:
  name: "Steve Kochan"               # Speaker Full Name
  twt_name: "COMFREIGHT"           # Twitter Handle, sans @
  company: "Gunn|Jerkens"            # Speakers Employer
  presentation_type: "PRESENTATION"  # PRESENTATION || SHOWCASE || DEMO || PANEL
  bio_desc: "Steve Kochan is the Project Manager at Gunn Jerkens, Founder and CEO of ComFreight.com (a bootstrapped and recently profitable SaaS startup from Long Beach) and former Executive Director of LB Tech."
  bio_img_path: "https://media.licdn.com/mpr/mpr/shrinknp_200_200/AAEAAQAAAAAAAAPHAAAAJGUyMTBmNzNhLTI5NjgtNDVjZC04NmVjLThmN2NhODRiZDcyNQ.jpg"
  presentation_title: "Analytics: Fail Less, Validate Faster (Part II)"
  presentation_desc: "Part two of an explanation of quicks ways to validate a business or application idea using quick to deploy forms or landing pages and a small paid advertising budget using PPC to find out if that idea is really worth doing. Find out if your idea has actual interest and initial traction and quickly ascertain your initial cost per acquisition before building the entire product. Intro to product marketing research."
speaker2:
  name: ""               # Speaker Full Name
  twt_name: ""           # Twitter Handle, sans @
  company: ""            # Speakers Employer
  bio_desc: ""           # Speaker Biography. markdown ok.
  bio_img_path: ""       # Path to image, ex: '/images/people/foobar.jpg'
  presentation_type: ""  # PRESENTATION || SHOWCASE || DEMO || PANEL
  presentation_title: "" # Catchy Title of Presentation.
  presentation_desc: ""  # Full Description of talk.  markdown ok.
speaker3:
  name: ""               # Speaker Full Name
  twt_name: ""           # Twitter Handle, sans @
  company: ""            # Speakers Employer
  bio_desc: ""           # Speaker Biography. markdown ok.
  bio_img_path: ""       # Path to image, ex: '/images/people/foobar.jpg'
  presentation_type: ""  # PRESENTATION || SHOWCASE || DEMO || PANEL
  presentation_title: "" # Catchy Title of Presentation.
  presentation_desc: ""  # Full Description of talk.  markdown ok.
---

**Meetup: {{ page.date | date: "%B %-d, %Y" }}**  
{% if page.venue_image != "" %}<img src="{{ base.url }}{{ page.venue_image }}" alt="monthly promotional picture">{% endif %}

## TALKS THIS MONTH  
The _Long Beach Web & App Professionals_ ([#WAPRO](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)) group meets monthly to share and learn about the technology that ignites our imagination, builds our skill-set, expands our network, and grows community!

{% if page.speaker1.presentation_title != ""  %}- {{ page.speaker1.name }} ([@{{ page.speaker1.twt_name }}](https://twitter.com/{{ page.speaker1.twt_name }})) – {{ page.speaker1.presentation_title }}  {% endif %}
{% if page.speaker2.presentation_title != ""  %}- {{ page.speaker2.name }} ([@{{ page.speaker2.twt_name }}](https://twitter.com/{{ page.speaker2.twt_name }})) – {{ page.speaker2.presentation_title }}  {% endif %}
{% if page.speaker3.presentation_title != ""  %}- {{ page.speaker3.name }} ([@{{ page.speaker3.twt_name }}]({{ site.base.twitter }}{{ page.speaker3.twt_name }})) – {{ page.speaker3.presentation_title }}  {% endif %}
- [PLEASE R.S.V.P.]({{ page.rsvp }})

##VALUE

Tech moves too fast to keep up on everything yourself.  There's always someone faster, better, or smarter than you.  Come meet them, connect, and lean on community.  If you're a local business or agency, join us and encourage staff to come.  It's a great way to expand your network of folks active and connected, which leads to both new business and potential new recruits.  Everyone wins!


##TOPICS

The Pros that have worked on/for projects such as Spacex, Riot Games, X-prize, Adobe, Toyota Motor Sports, VMWare, UCLA, CSULB, AARP, and more ... have shared amazing talks this year on tech and projects such as [Bootstrap](http://getbootstrap.com/), [Bower](http://bower.io), [Browserfy](http://browserify.org/), [Headless Drupal](https://github.com/davidhwang/horseman), [iOS Swift](https://developer.apple.com/swift/), [Jekyll](http://jekyllrb.com), [Meteor](https://www.meteor.com/), [Node.js](http://iojs.org), [SASS](http://sass-lang.com/), [Sculpin](http://sculpin.io), [Zapier](http://zapier.com) and more.

Every month we come together to:

* Demo technologies we use, especially those driving the convergence of websites and mobile apps
* Showcase our projects built with cool tech
* Share industry "best practices"
* Newcomer Q&A's
* Network, get to know each other, and otherwise have fun

We have a preference for open-source software, especially server-side.  This year we have meetups focused on the life-cycle and technologies related to website and application development.  We will especially try to delve into situations where mobile and web technologies converge.  The meeting topics we cover will vary monthly and will be tailored to, and by, our community.  Want to see something in particual?  Let us know by tweeting using the hash #WAPRO.  

**Future meetup dates:**  ⛅  11/10  ⛈  12/1  ☔  1/5  ☃

If you have interest or work in Web or Application Development, add our meetup to your calendar now and join us! Our meetups are FREE and open to [EVERYONE](https://github.com/uncodedlb/uncoded-policies).


{% include venue.md %}


### DETAILS  
{% if page.speaker1.name != "" %}
**{{ page.speaker1.presentation_type | uppercase }}**  
{{ page.speaker1.presentation_title | uppercase }}  

{{ page.speaker1.presentation_desc | markdownify }}  

> ### {{ page.speaker1.name | markdownify }}{% if page.speaker1.company %}
> {{ page.speaker1.company }}{% endif %}  ([@{{ page.speaker1.twt_name }}](https://twitter.com/{{ page.speaker1.twt_name }}))  
> <img src="{{ site.baseurl }}{{ page.speaker1.bio_img_path }}" alt="headshot" class="headshot">
> {{ page.speaker1.bio_desc | markdownify }}  
{% endif %}
{% if page.speaker2.name != ""  %}
**{{ page.speaker2.presentation_type | uppercase }}**  
{{ page.speaker2.presentation_title | uppercase }}

{{ page.speaker2.presentation_desc | markdownify }}  

> ### {{ page.speaker2.name | markdownify }}{% if page.speaker2.company %}
> {{ page.speaker2.company }}{% endif %}  ([@{{ page.speaker2.twt_name }}](https://twitter.com/{{ page.speaker2.twt_name }}))  
> <img src="{{ site.baseurl }}{{ page.speaker2.bio_img_path }}" alt="headshot" class="headshot">
> {{ page.speaker2.bio_desc | markdownify }}  
{% endif %}
{% if page.speaker3.name != ""  %}
**{{ page.speaker3.presentation_type | uppercase }}**  
{{ page.speaker3.presentation_title | uppercase }}

{{ page.speaker3.presentation_desc | markdownify }}  

> ### {{ page.speaker3.name | markdownify }}{% if page.speaker3.company %}
> {{ page.speaker3.company }}{% endif %}  ([@{{ page.speaker3.twt_name }}](https://twitter.com/{{ page.speaker3.twt_name }}))  
> <img src="{{ site.baseurl }}{{ page.speaker3.bio_img_path }}" alt="headshot" class="headshot">
> {{ page.speaker3.bio_desc | markdownify }}  
{% endif %}



### PRIZES!  

We have prizes!  Want to win?  Help us connect with more local tech folk by sharing on your social networks.  This has the benefit of growing your own professional network, too! The person with the most social shares promoting the meetup (tweets+retweets, fb likes/shares, etc) this month which include the hash [**#WAPRO**](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded) and/or **[#UNCODED](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)** will win their choice of prize offerings.  *Minimum of six shares over at least three different dates.  At the discretion of the crowd in attendance, we may give away multiple prizes if the crowd votes that many people have gone above & beyond to help spread the news.  Please share & promote in [good taste. ☺](https://github.com/uncodedlb/uncoded-policies)*


## SPONSORS

Our sponsors help make our meetups awesome! They feed us, provide a place to gather, share, & learn from eachother, and some even give us cool things to giveaway!  Take a moment to thank them, click their logo to visit their twitter/facebook account... and thank them publicly.  *(Please, use hash __#WAPRO__)*

### FOOD & BEVERAGES

{% if site.sponsors.food.logo != "" %}<a href="{{ site.base.twitter }}{{ site.sponsors.food.twitter }}" target="_blank"><img class="logo" src='{{ site.sponsors.food.logo }}' alt='{{ site.sponsors.food.name }}'></a>{% endif %}
<p>Come hungry & thirsty! This month food and beverage will be graciously provided by <a href="{{ site.base.twitter }}{{ site.sponsors.food.twitter }}" target="_blank">{{ site.sponsors.food.name }}</a>.  {{ site.sponsors.food.desc }}</p>
{% if site.sponsors.food.extra %}<p>{{ site.sponsors.food.extra }}</p>{% endif %}

### VENUE SPONSOR

{% if site.sponsors.venues.gj.logo != "" %}<a href="{{ site.base.twitter }}{{ site.sponsors.venues.gj.twitter }}" target="_blank"><img class="logo" src='{{ site.sponsors.venues.gj.logo }}' alt='{{ site.sponsors.venues.gj.name }}'></a>{% endif %}
<p>Our venue host this month is courtesy of <a href="{{ site.base.twitter }}{{ site.sponsors.venues.gj.twitter }}" target="_blank">{{ site.sponsors.venues.gj.name }}</a>.  {{ site.sponsors.venues.gj.desc }}</p>
{% if site.sponsors.venues.gj.extra %}<p>{{ site.sponsors.venues.gj.extra }}</p>{% endif %}

### PRIZES

{% if site.sponsors.prize.pearson.logo != "" %}<a href="{{ site.base.twitter }}{{ site.sponsors.venues.gj.twitter }}" target="_blank"><img class="logo" src='{{ site.sponsors.prize.pearson.logo }}' alt='{{ site.sponsors.prize.pearson.name }}'></a>{% endif %}
<p>Prizes this month are being provided courtesy of <a href="{{ site.base.twitter }}{{ site.sponsors.prize.pearson.twitter }}" target="_blank">{{ site.sponsors.prize.pearson.name }}</a>.  {{ site.sponsors.prize.pearson.desc }}</p>
{% if site.sponsors.prize.pearson.extra %}<p>{{ site.sponsors.prize.pearson.extra }}</p>{% endif %}
