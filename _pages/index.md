---
layout: page
title: New Wander Home
id: home
permalink: /
description: Find a new wander.
---

# Explore resources and ideas 🌱

<!-- <p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Your first note]]</span> to get started on your exploration.
</p> -->

This is a [[digital garden]] to explore resources and ideas I come across.

I’m [[Lukas Murdock]] 👋&nbsp; A young Designer, Developer, and Marketer living in the United States.

I love getting to know people around the world. If you have anything you’d like to share, please don’t hold back. [Life’s short, hit send](/lukas-murdock#contact-me) 🤟

If this helps you in any way, [consider buying me a coffee ☕️](https://www.buymeacoffee.com/lukasmurdock) or donating to a charity of your choice. Might I recommend [charity:water](https://www.charitywater.org/lukas-murdock).

## New Wander talks

{% assign episodes = site.notes | where:"category","podcast" | sort: 'episode' | reverse %}
{% for note in episodes %}

  <img src="{{ note.image }}"/>
  <a href="{{ note.url }}">{{ note.title }}</a>

{% endfor %}

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
