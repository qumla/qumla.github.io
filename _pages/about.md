---
layout: about
title: home
permalink: /
subtitle:

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: false # adds a vertical scroll bar if there are more than 3 news items
  limit: 3 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  .post > .post-header {
    display: none;
  }

  .qumla-home-logo {
    margin: 0 auto 2rem;
    text-align: center;
  }

  .qumla-home-logo img {
    display: inline-block;
    width: min(620px, 92%);
    height: auto;
  }

  .qumla-home-intro {
    margin: 0 auto 2.5rem;
    max-width: 760px;
    text-align: center;
    font-size: 1.05rem;
    line-height: 1.75;
  }
</style>

<div class="qumla-home-logo">
  <img src="{{ '/assets/img/qumla-full.png' | relative_url }}" alt="QuMLa full logo">
</div>

<div class="qumla-home-intro">
  <p>QuMLa studies quantum machine learning and algorithms at Sejong University.</p>
  <p>Our work connects quantum information theory, learning theory, tensor-network methods, and practical algorithm design for near-term and fault-tolerant quantum computation.</p>
</div>
