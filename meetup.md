---
layout: default
title: Meetups
redirect_from: ["/meetups/"]
permalink: /meetup/
published: true
date: "2015-07-30 15:21:43 PST"                                                  # posted date
last_modified_at: "2017-05-25 01:31:54 PDT"                                     # last_modified_at date
---

<div class="info">
<h2>Meetups</h2>
<p>We congregate monthly to showcase, learn, share, & network. Most recently we've been meeting on either the last Thursday of the month.  But depending on venue restrictions, we mix it up.  Please, join us.</p>

<div class="posts">
  {% assign secondloop = "false" %}
  {% for post in site.posts %}
    {% if forloop.first == true %}
      <h2>Upcoming {{page.title}}</h2>
      {% assign rsvp_text = "Please R.S.V.P. for accurate headcount (food/drink)"%}
      {% assign secondloop = "true" %}
    {% elsif secondloop == "true" %}
      {% assign secondloop = "false" %}
      <h2>Past {{page.title}}</h2>
      {% assign rsvp_text = "Link to old meetup"%}
    {% endif %}

    <article class="post">
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

      <div class="entry">

        {% if post.image %}
        <figure class="banner">
        {% include mdr/banner_image.html %}
        </figure>
        {% endif %}
        {% if secondloop == "true" %}<h4><a href="{{ post.rsvp }}" target="_blank" ref="nofollow">{{ rsvp_text }}</a></h4>{% endif %}
        {{ post.excerpt }}
      </div>

      {% if secondloop == "true" %}
      <em class="convince">Still need convincing it's going to be great?  <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read more</a></em>
      {% endif %}
    </article>
  {% endfor %}
</div>
