---
# Fill-in Speaker1, Speaker2, & Speaker3 info below.
# Add tag(s) related to your presentation. Use lowercase tags. Also add "Your Name" as a tag.
title: "Web & Application Professionals Meetup"
tags: ["Patrick Goddard", "Drupal", "John Boranprasit", "Charity Distribution"]
meeting_time: "7-9p"
venue: "WELABS" # WELABS || GJ
venue_image: ""
#redirect_from: ["/next/", "/meetup/next/", "/meetups/next/", "/events/next/"]
rsvp: "http://www.meetup.com/Uncoded/events/227624634/" # "http://www.meetup.com/Uncoded/events/225429587/"
categories: meetup
layout: post
published: true
speaker1:
  name: "Patrick Goddard"               # Full Name
  twt_name: "patrickfgoddard"           # Twitter (sans @)
  company: "https://patrickgoddard.bandcamp.com/"            # Company Name
  bio_img_path: "https://f1.bcbits.com/img/0001634364_20.jpg"       # Bio image, ex: '/images/people/foobar.jpg'
  presentation_type: "DEMO"  # PRESENTATION || SHOWCASE || DEMO || PANEL
  bio_desc: ""           # Speaker Biography. markdown ok.
  presentation_title: "Drupal 8 -vs- the World" # Catchy Title of Presentation.
  presentation_desc: "This demo will be an introduction to the latest version of Drupal and a survey of similar tools. We'll look at the features that make Drupal 8 different from all previous versions and contrast these features with similar tools, such as [WordPress](https://wordpress.org/), [Joomla](https://www.joomla.org/), [Jekyll](https://jekyllrb.com/),  [Grav](http://bolt.cm/), [Django](https://www.djangoproject.com/) (reverse alphabetical)."  # Full Description of talk.  markdown ok.
speaker2:
  name: "Charoun John Boranprasit"               # Full Name
  twt_name: "cjboranp"           # Twitter (sans @)
  company: "Kwall"            # Company Name
  bio_img_path: "http://www.kwallcompany.com/sites/default/files/styles/profile_page/public/pictures/picture-155-1447372751.jpg"       # Bio image, ex: '/images/people/foobar.jpg'
  presentation_type: "PRESENTATION"  # PRESENTATION || SHOWCASE || DEMO || PANEL
  bio_desc: "John has been developing Drupal professionally since 2004 specializing in E-commerce customization. He discovered his passion for programming from Seneca College in Toronto, Canada. John believes that programming saves people time and time is a commodity we can never get back."           # Speaker Biography. markdown ok.
  presentation_title: "How to script a Charity website to spin up a site in less than 5 minutes." # Catchy Title of Presentation.
  presentation_desc: "I wanted to do more than just program. I want to help people. My talents are in programming so I tend to get asked to build a site for everyone. Recently I wanted to find more ways to be involved in helping people so I built a platform to pulls in functionality and installs a complete CMS system. This presentation outlines how I did it and how you can do it too."  # Full Description of talk.  markdown ok.
speaker3:
  name: ""               # Full Name
  twt_name: ""           # Twitter (sans @)
  company: ""            # Company Name
  bio_img_path: ""       # Bio image, ex: '/images/people/foobar.jpg'
  presentation_type: ""  # PRESENTATION || SHOWCASE || DEMO || PANEL
  bio_desc: ""           # Speaker Biography. markdown ok.
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

The Pros that have worked on/for projects such as Spacex, Riot Games, X-prize, Adobe, Toyota Motor Sports, VMWare, UCLA, CSULB, AARP, and more ... have shared amazing talks this year on tech and projects such as [Bootstrap](http://getbootstrap.com/), [Bower](http://bower.io), [Browserfy](http://browserify.org/), [Headless Drupal](https://github.com/davidhwang/horseman), [iOS Swift](https://developer.apple.com/swift/), [Jekyll](http://jekyllrb.com), [Meteor](https://www.meteor.com/), [Node.js](http://iojs.org), [SASS](http://sass-lang.com/), [Sculpin](http://sculpin.io), [Zapier](http://zapier.com) and more.

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
