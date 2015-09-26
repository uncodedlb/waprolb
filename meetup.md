---
layout: default
title: Meetups – Upcoming and Past Meetings
redirect_from: ["/news/", "/meetups/", "/event/", "/events/"]
permalink: "/meetup/"
published: true
---

<div class="info">

<h2>Meetups</h2>
<div class="twitter-embedded">{{ site.twitter.highlight }}</div></div>
<p>We congregate monthly to showcase, learn, share, & network. We meet on the <strong>1st Tuesday</strong> of every month in Long Beach. Please, join us.</p>


<h2>{{page.title}}</h2>
<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.content | truncatewords:99}}
      </div>

      <em class="convince">Still need convincing it's going to be great?  <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read more</a></em>
    </article>
  {% endfor %}
</div>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
