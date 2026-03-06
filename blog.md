---
layout: page
title: Blog
permalink: /blog/
---

<div style="background:#f8f8fc; border:1px solid #e8e8ef; border-radius:24px; padding:32px; margin-top:10px;">

**Why I Love Taco Bell**

I love Taco Bell. It’s cheap, it tastes good, and it’s simple. Once you go enough times, you realize ordering there is kind of a skill. If you know the menu well, you can figure out the combinations that give you the most food for the least money. Getting the best calories per dollar takes a little experience.

Going to Taco Bell has also become a bit of a Sunday tradition for me and my girlfriend. It’s an easy plan—no thinking required. Just drive over, order some food, and hang out.

My go-to order is the Build Your Own Luxe Box: a Crunchwrap Supreme, a Baja Blast, a Beefy 3-Layer Burrito, and Cinnamon Twists. The Crunchwrap is the main event, the burrito fills you up, Baja Blast is basically mandatory at Taco Bell, and the Cinnamon Twists are a solid finish.

It’s nothing fancy, but that’s kind of the point. Cheap food, a good combo, and a simple Sunday routine.


---

{% raw %}{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}{% endraw %}

</div>
