---
layout: page
title: Say Hi
permalink: /contact/
navigable: true
scss: say-hi
---

I'd love to hear from you. Click (or tap) one of these.

It's as simple as that. 😺

<ul class="say-hello">
    {% for contact in site.contact %}
    <li><a href="{{contact.link}}"><ion-icon name="{{contact.icon}}"></ion-icon> {{contact.name}}</a></li>
    {% endfor %}
</ul>