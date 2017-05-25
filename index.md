---
layout: default
title:  #Web & Applications Professionals – Long Beach, CA
permalink: /
published: true
date: "2015-01-21 14:16:51 PST"                                                 # posted date
last_modified_at: "2017-05-25 02:28:20 PDT"                                     # last_modified_at date
---

<div class="posts">
  {% for post in site.posts %}
    {% if forloop.first == true %}
    <aside class="post">

      <h2>Next Meetup Event</h2>

      <div class="entry">
        <figure class="banner">
          <a href="{{ site.baseurl }}{{ post.url }}">{% include mdr/banner_image.html %}</a>
        </figure>
        <meta property="startDate" content="{{ post.meeting_start | time_tag }}">

        <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.meeting_start | date: "%B %d, %Y" }}  @{{ post.meeting_start | date: "%l%P" }}</a></h3>

      </div>
    </aside>

    {% endif %}
  {% endfor %}
</div>


---

_the geeks that make the **apps** and the **interwebz** congregate monthly to
showcase, **learn**, **share**, & network. we meet the **3rd Tuesday** at
alternating venues in long beach. come._

We call ourselves **Web & Application Professionals** ... #WAPRO

<iframe width="720" height="405" src="https://www.youtube.com/embed/4vW2bO6b2kg" frameborder="0" allowfullscreen></iframe>

WAPRO [meets monthly](/meetups/) to showcase our cool tech projects, share best practices, network with each other, help newcomers, and the values of open source software (F/OSS).  The technology and projects we discuss is typically directed towards the professionals that build websites and mobile applications.  Although we don't cater to beginners, we welcome everyone to join us, we actively work with CSULB and LBCC students, and often revisit _IT fundamentals_ in our talks.  We strive to meet in a professional, relaxed, respectful, and open venue for [all people](https://github.com/uncodedlb/uncoded-policies/blob/master/UCC.md) in our community.


<aside>
## What topics do we cover?
{% include boilerplate/meeting_topics.html %}
</aside>

In the future we'll cover everything we can related to web or app development, especially convergent technologies.  We also hope to cover associated topics, such as design, UX, testing, workflows, tools, and more. Interested in sharing a talk? Yes! [Contact us](/about/)!

>  The __Web & App Professionals meetup__ (#wapro) is a community intiative of [Uncoded](http://uncoded.org).  

{% comment %}
## Get Connected

We need your help. We've already had some amazing talks in our short history.  But we only know so many folks locally.  We believe a vibrant tech community shares and talk socially.  

Help us connect with each other by using the social hash *#WAPRO*.  

If you're really excited to help us spread the word to connect with other locals doing cool things in tech! Please do this:

1. [Download a flyer](/images/wapro-promotion-flyer.pdf) (Or click the image below)
2. Print the flyer
3. Finally, post it in a public place.  For example, post in your favorite cafe, or campus commons, or a workplace breakroom.  _But always be sure to obtain permission to post._  😄

[![flyer]({{ site.baseurl }}/images/wapro-promotion-flyer-base.svg)]({{ site.baseurl }}/images/wapro-promotion-flyer.pdf)
{% endcomment %}
