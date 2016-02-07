---
# Fill-in Speaker1, Speaker2, & Speaker3 info below.
# Add tag(s) related to your presentation. Use lowercase tags. Also add "Your Name" as a tag.
title: "Web & Application Professionals Meetup – Nov 10 (Date Change!)"
tags: ["docker", "bootstrap", "Tom Friedhof", "Mike Stewart"]
meeting_time: "6:30-9p"
venue: "WELABS" # WELABS || GJ
venue_image: ""
rsvp: "http://www.meetup.com/Uncoded/events/" # "http://www.meetup.com/Uncoded/events/225429587/"
categories: meetup
layout: post
published: true
speaker1:
  name: "Tom Friedhof / Senior Developer"               # Speaker Full Name
  twt_name: "ActiveLAMP"           # Twitter Handle, sans @
  company: "ActiveLAMP<br>
**Phone:** 310.943.0246 ext 102<br>
6080 Center Drive #600, Los Angeles, CA 90045"            # Speakers Employer
  bio_img_path: "/images/people/tom-friedhof.jpg"       # Path to image, ex: '/images/people/foobar.jpg'
  presentation_type: "PRESENTATION"  # PRESENTATION || SHOWCASE || DEMO || PANEL
  bio_desc: "Tom has been designing and developing for the web since 2002 and got involved with Drupal in 2006. Previously he worked as a systems administrator for a large mortgage bank, managing servers and workstations, which is where he discovered his passion for automation and scripting. On his free time he enjoys camping with his wife and three kids."           # Speaker Biography. markdown ok.
  presentation_title: "Introduction to Docker" # Catchy Title of Presentation.
  presentation_desc: "Tom will introduce the in-and-outs of Docker and the basics on how to use for building websites and applications."  # Full Description of talk.  markdown ok.
speaker2:
  name: "Mike Stewart"               # Speaker Full Name
  twt_name: "MediaDoneRight"           # Twitter Handle, sans @
  company: "www.MediaDoneRight.com"            # Speakers Employer
  bio_desc: "A long time open source evangelist, community organizer, and resident of Long Beach. Stewart started his career in enterprise I.T. implementing projects such as: _Customer Relationship Management_, _Engineering Document Management_, and _ERP Systems_. His knowledge of Microsoft technologies, ERP, and manufacturing led him to employers focused on Warehouse Management Systems, Time & Attendance, and Management Execution Systems. The latter projects utilized early Microsoft web technologies which eventually led him to consulting building websites and web based applications. Ultimately, licensing independence for his clients plus the discovery of the principles behind free software, led him to Drupal as a veritable swiss-army-knife for the web, and free software in general. "           # Speaker Biography. markdown ok.
  bio_img_path: "/images/people/mike-stewart.jpg"       # Path to image, ex: '/images/people/foobar.jpg'
  presentation_type: "PRESENTATION"  # PRESENTATION || SHOWCASE || DEMO || PANEL
  presentation_title: "Future   HTML5 Technologies" # Catchy Title of Presentation.
  presentation_desc: "An open discussion + some cool demo(s) about future web & application development.  I've got a lot on my mind ranging from _Living Styleguides_, _Bootstrap 4_, _Web Components_, and _Nextgen Content Management Systems_ such as ([GRAV](http://getgrav.org/), [Bolt](https://bolt.cm/features), [BackBee](http://www.backbee.com), and [Drupal 8](https://www.drupal.org/drupal-8.0)).  What will the effect be on future website and app development?  How will these technologies affect workflow?  Let's share!"  # Full Description of talk.  markdown ok.
speaker3:
  name: ""               # Speaker Full Name
  twt_name: ""           # Twitter Handle, sans @
  company: ""            # Speakers Employer
  bio_desc: ""           # Speaker Biography. markdown ok.
  bio_img_path: ""       # Path to image, ex: '/images/people/foobar.jpg'
  presentation_type: ""  # PRESENTATION || SHOWCASE || DEMO || PANEL
  presentation_title: "" # Catchy Title of Presentation.
  presentation_desc: ""  # Full Description of talk.  markdown ok.
sponsors:
  food:
    name: ""
    logo: ""
    twitter: ""
    desc: ""
    extra: ""
  prize:
    pearson:
      name: ""
      image: ""
      logo: ""
      twitter: ""
      desc: ""
      extra: ""
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

The Pros that have worked on/for projects such as Spacex, Riot Games, X-prize, Adobe, Toyota Motor Sports, VMWare, UCLA, CSULB, AARP, and more ... have shared amazing talks this year on tech and projects such as [Bootstrap](http://getbootstrap.com/), [Bower](http://bower.io), [Browserfy](http://browserify.org/), [Headless Drupal](https://github.com/davidhwang/horseman), [iOS Swift](https://developer.apple.com/swift/), [Jekyll](http://jekyllrb.com), [Meteor](https://www.meteor.com/), [Node.js](https://iojs.org/en/), [SASS](http://sass-lang.com/), [Sculpin](http://sculpin.io), [Zapier](http://zapier.com) and more.

Every month we come together to:

* Demo technologies we use, especially those driving the convergence of websites and mobile apps
* Showcase our projects built with cool tech
* Share industry "best practices"
* Newcomer Q&A's
* Network, get to know each other, and otherwise have fun

We have a preference for open-source software, especially server-side.  This year we have meetups focused on the life-cycle and technologies related to website and application development.  We will especially try to delve into situations where mobile and web technologies converge.  The meeting topics we cover will vary monthly and will be tailored to, and by, our community.  Want to see something in particual?  Let us know by tweeting using the hash #WAPRO.  

**Future meetup dates:**  10/6  ⛅  11/3  ⛈  12/1  ☔  1/5  ☃

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



## SPONSORS

Our sponsors help make our meetups awesome! They feed us, provide a place to gather, share, & learn from eachother, and some even give us cool things to giveaway!  Take a moment to thank them, click their logo to visit their twitter/facebook account... and thank them publicly.  *(Please, use hash __#WAPRO__)*

{% if page.sponsors.food.name != "" %}
### FOOD & BEVERAGES
{% endif %}
{% if page.sponsors.food.logo != "" %}<a href="{{ site.base.twitter }}{{ page.sponsors.food.twitter }}" target="_blank"><img class="logo" src='{{ page.sponsors.food.logo }}' alt='{{ page.sponsors.food.name }}'></a>
<p>Come hungry & thirsty! This month food and beverage will be graciously provided by <a href="{{ site.base.twitter }}{{ page.sponsors.food.twitter }}" target="_blank">{{ page.sponsors.food.name }}</a>.  {{ page.sponsors.food.desc }}</p>{% endif %}
{% if page.sponsors.food.extra %}<p>{{ page.sponsors.food.extra }}</p>{% endif %}
