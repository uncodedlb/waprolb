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

<blockquote>
<h3>Notice: We're Moving to Tuesday</h3>
<p>Starting September 1st, 2015, we're moving the meetup to the first Tuesday of every Month.</p>
</blockquote>

<h2>{{page.title}}</h2>
<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.content | truncatewords:99}}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
