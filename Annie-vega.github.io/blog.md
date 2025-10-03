---
layout: page
title: Conversation Starters Blog
subtitle: Deep thoughts and rabbit holes
---

<div class="text-center">
  <img src="/img/Conversation_starters_logo.png" alt="Conversation Starters Logo" style="max-width: 300px; height: auto;">
</div>

## About the Blog

[Conversation Starters](https://www.instagram.com/conversation_starters_blog/) is a blog where I share some trains of thoughts, deep internal and external debates, ideas that resonated with me, or what I like to call, **very deep rabbit holes**. 

They are *(mostly)* ready to be shared with the world but **they still a work in progress, open to be discussed and challenged by anyone with interesting arguments and different points of view.**

These ideas evolved while talking with the people around me and **I would like you to join the conversation** and complement them with your unique background and experiences. 

***Diversity is the key to make this a great and insightful conversation.***

## Subscribe

Subscribe [here](http://eepurl.com/hcIy_D) to receive the deep rabbit holes directly in your inbox.

## Latest Article

Check the latest article [here](http://conversationstarters.annievega.com/).

## Recent Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
