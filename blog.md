---
layout: page
title: Blog
permalink: /blog/
---

<div style="background:#f8f8fc; border:1px solid #e8e8ef; border-radius:24px; padding:32px; margin-top:10px;">

  <p style="font-size:1.08em; line-height:1.7; margin-bottom:20px;">
    Short posts about things I enjoy, experiences I’ve had, and topics I find interesting.
  </p>

  <hr>

  <ul style="list-style:none; padding-left:0; margin-top:20px;">
    {% for post in site.posts %}
      <li style="margin-bottom:18px;">
        <a href="{{ post.url }}" style="font-size:1.2em; font-weight:600; text-decoration:none;">
          {{ post.title }}
        </a><br>
        <span style="color:#666; font-size:0.95em;">
          {{ post.date | date: "%B %d, %Y" }}
        </span>
      </li>
    {% endfor %}
  </ul>

</div>
