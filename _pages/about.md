---
layout: about
title: Home
permalink: /
subtitle:
selected_papers: true
social: false
announcements:
  enabled: true
  scrollable: false
  limit: 3
latest_posts:
  enabled: false
  scrollable: true
  limit: 3
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

  .qumla-home-logo .qumla-logo-dark {
    display: none;
  }

  html[data-theme="dark"] .qumla-home-logo .qumla-logo-light {
    display: none;
  }

  html[data-theme="dark"] .qumla-home-logo .qumla-logo-dark {
    display: inline-block;
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
  <img class="qumla-logo-light" src="{{ '/assets/img/qumla-full.png' | relative_url }}" alt="QuMLa full logo">
  <img class="qumla-logo-dark" src="{{ '/assets/img/qumla-full-dark.png' | relative_url }}" alt="QuMLa full logo">
</div>

<div class="qumla-home-intro">
  <p>This is Quantum machine learning and algorithm group in <a href="https://dept.sejong.ac.kr/qisedpt/index.do">Department of Quantum Information Science and Engineering</a>, Sejong University.</p>
  
  <p>How will quantum computing benefit humanity? Our primary research area is <strong>Quantum machine learning and Quantum algorithms</strong>. We explore how quantum computers can enhance machine learning and what unique advantages quantum computers hold compared to classical counterparts.</p>
  
  <p> Would it be capable of <em>better</em> thought if the <em>brain</em> of artificial intelligence were quantum ? </p>
  
  <p> Not only quantum machine learning and algorithms, we study and raise questions regarding the broader field of <strong>Quantum Information Theory</strong>.</p>
</div>
