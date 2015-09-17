---
# Fill-in Speaker1, Speaker2, & Speaker3 info below.
# Add tag(s) related to your presentation. Use lowercase tags. Also add "Your Name" as a tag.
title: "Web & Application Professionals Meetup – October"
tags: ["accessibility", "php", "Patrick Wall", "John Arroyo"]
meeting_time: "6:30-9p"
venue: "GJ" # WELABS || GJ
redirect_from: ["/next/", "/meetup/next/", "/meetups/next/", "/events/next/"]
categories: meetup
layout: post
published: true
speaker1:
  name: "John Arroyo"               # Speaker Full Name
  twt_name: "arroyolabs"           # Twitter Handle, sans @
  company: "Founder, Arroyo Labs"            # Speakers Employer
  bio_desc: "Founder of Arroyo Labs.  Software developer and technologist, & music composer"           # Speaker Biography. markdown ok.
  bio_img_path: "/images/people/John-Arroyo.jpg"       # Path to image, ex: '/images/people/foobar.jpg'
  presentation_type: "PRESENTATION"  # PRESENTATION || SHOWCASE || DEMO || PANEL
  presentation_title: "The new PHP and the enterprise Mash-Up" # Catchy Title of Presentation.
  presentation_desc: "Despite its historic shortcoming, PHP has grown up to be a solid technology powering large portions of the web including large enterprises.  I’ll discuss modern ways to leverage the language and its large open source ecosystem.  I’ll outline and demo various architectures and ideas that bring together the best of PHP alongside other languages and frameworks.  I’ll also show how our Erdiko project and things like composer can bring mash-ups to the enterprise."  # Full Description of talk.  markdown ok.
speaker2:
  name: "Patrick Wall"               # Speaker Full Name
  twt_name: "kwallcompany"           # Twitter Handle, sans @
  company: "CTO, KWALL"            # Speakers Employer
  bio_desc: "With more than a decade of IT experience Patrick leads the KWALL development team. Patrick oversees all web development, network infrastructure, and hosting services. Patrick has managed website information systems for such large companies as Chrysler and EDS. These experiences provided the expert experience sought after by agencies and development firms. As a central member of the Open Source community, Patrick manages and contributes modules and code, and also teaches people interested in Drupal at local training sessions. Patrick has spoken at multiple conferences and events on highly technical presentations relating to web development and content management systems."           # Speaker Biography. markdown ok.
  bio_img_path: "/images/people/patrick-wall.jpg"       # Path to image, ex: '/images/people/foobar.jpg'
  presentation_type: "PRESENTATION"  # PRESENTATION || SHOWCASE || DEMO || PANEL
  presentation_title: "Accessibility in Websites" # Catchy Title of Presentation.
  presentation_desc: "I'll go over the general requirements for accessibility you need to take into consideration when building a website:<ul><li>The standards of [WCAG 2.0](http://www.w3.org/TR/WCAG20/) and [Section 508](http://www.hhs.gov/web/section-508/index.html), and scanners to help you achieve them</li><li>Tools you can use in Drupal and outside of it to still have an awesome website while being accessible</li><li>The benefits of accessibility beyond being socially responsible and legally compliant</li></ul>"  # Full Description of talk.  markdown ok.
speaker3:
  name: ""               # Speaker Full Name
  twt_name: ""           # Twitter Handle, sans @
  company: ""            # Speakers Employer
  bio_desc: ""           # Speaker Biography. markdown ok.
  bio_img_path: ""       # Path to image, ex: '/images/people/foobar.jpg'
  presentation_type: ""  # PRESENTATION || SHOWCASE || DEMO || PANEL
  presentation_title: "Additional talk TBD -- As always, come prepared to share a lightning talk" # Catchy Title of Presentation.
  presentation_desc: ""  # Full Description of talk.  markdown ok.
---

**Meetup: {{ page.date | date: "%B %-d, %Y" }}**  

### TALKS THIS MONTH  
The _Long Beach Web & App Professionals_ ([#WAPRO](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)) group meets monthly to share and learn about the technology that ignites our imagination, builds our skill-set, expands our network, and grows community!

{% if page.speaker1.presentation_title != ""  %}- {{ page.speaker1.name }} ([@{{ page.speaker1.twt_name }}](https://twitter.com/{{ page.speaker1.twt_name }})) – {{ page.speaker1.presentation_title }}  {% endif %}
{% if page.speaker2.presentation_title != ""  %}- {{ page.speaker2.name }} ([@{{ page.speaker2.twt_name }}](https://twitter.com/{{ page.speaker2.twt_name }})) – {{ page.speaker2.presentation_title }}  {% endif %}
{% if page.speaker3.presentation_title != ""  %}- {{ page.speaker3.name }} ([@{{ page.speaker3.twt_name }}](https://twitter.com/{{ page.speaker3.twt_name }})) – {{ page.speaker3.presentation_title }}  {% endif %}



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



### PRIZES!  

We have prizes!  Want to win?  Help us connect with more local tech folk by sharing on your social networks.  This has the benefit of growing your own professional network, too! The person with the most social shares promoting the meetup (tweets+retweets, fb likes/shares, etc) this month which include the hash [**#WAPRO**](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded) and/or **[#UNCODED](https://twitter.com/intent/tweet?text=I%27m%20excited%20for%20the%20%23WAPRO%20meetup%20this%20month!%20meetup.com%2Funcoded%2Fevents%2F%20%40uncodedlb%20%23uncoded)** will win their choice of prize offerings.  *Minimum of six shares over at least three different dates.  At the discretion of the crowd in attendance, we may give away multiple prizes if the crowd votes that many people have gone above & beyond to help spread the news.  Please share & promote in [good taste. ☺](https://github.com/uncodedlb/uncoded-policies)*
