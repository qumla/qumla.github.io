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
    width: min(700px, 92%);
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
    max-width: 900px;
  }

  .qumla-intro-card {
    position: relative;
    overflow: hidden;
    border-radius: 8px;
    padding: 1.6rem 1.8rem;
    font-size: 1.05rem;
    line-height: 1.75;
    border: 1px solid rgba(42, 157, 159, 0.42);
    background: linear-gradient(135deg, rgba(42, 157, 159, 0.08), rgba(20, 33, 61, 0.035));
    box-shadow: 0 18px 45px rgba(20, 33, 61, 0.08);
    text-align: center;
  }

  .qumla-intro-card p {
    margin-bottom: 0.85rem;
  }

  .qumla-intro-card p:last-child {
    margin-bottom: 0;
  }

  .qumla-intro-title {
    margin: 0 0 0.45rem;
    font-size: clamp(1.55rem, 3vw, 2.15rem);
    font-weight: 500;
    line-height: 1.2;
  }

  .qumla-intro-affiliation {
    margin-bottom: 1.15rem;
    font-size: 1.08rem;
  }

  .qumla-focus-tags {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 0.55rem;
    margin-top: 1.25rem;
  }

  .qumla-focus-label {
    color: var(--global-text-color);
    font-size: 0.9rem;
    font-weight: 700;
    line-height: 1.2;
  }

  .qumla-focus-tags .qumla-topic {
    border: 1px solid rgba(42, 157, 159, 0.35);
    border-radius: 999px;
    padding: 0.35rem 0.72rem;
    color: var(--global-text-color);
    font-size: 0.88rem;
    line-height: 1.2;
  }

  html[data-theme="dark"] .qumla-intro-card {
    background: linear-gradient(135deg, rgba(42, 157, 159, 0.16), rgba(235, 222, 194, 0.07));
    box-shadow: 0 18px 45px rgba(0, 0, 0, 0.25);
  }

  @media (max-width: 575.98px) {
    .qumla-intro-card {
      padding: 1.25rem;
    }
  }
</style>

<div class="qumla-home-logo">
  <img class="qumla-logo-light" src="{{ '/assets/img/qumla-full.png' | relative_url }}" alt="QuMLa full logo">
  <img class="qumla-logo-dark" src="{{ '/assets/img/qumla-full-dark.png' | relative_url }}" alt="QuMLa full logo">
</div>

<div class="qumla-home-intro">
  <section class="qumla-intro-card" aria-labelledby="qumla-intro-title">
    <h2 class="qumla-intro-title" id="qumla-intro-title">Quantum Machine Learning and Algorithms group</h2>
    <p class="qumla-intro-affiliation"><a href="https://dept.sejong.ac.kr/qisedpt/index.do">Department of Quantum Information Science and Engineering</a>, Sejong University.</p>
    <p>How will quantum computing benefit humanity? Our primary research area is <strong>Quantum machine learning and Quantum algorithms</strong>. We explore how quantum computers can enhance machine learning and what unique advantages quantum computers hold compared to classical counterparts.</p>
    <p>Would it be capable of <em>better</em> thought if the <em>brain</em> of artificial intelligence were quantum?</p>
    <p>Not only quantum machine learning and algorithms, we study and raise questions regarding the broader field of <strong>Quantum Information Theory</strong>.</p>
    <div class="qumla-focus-tags" aria-label="Research focus areas">
      <span class="qumla-focus-label">Research Topics :</span>
      <span class="qumla-topic">Quantum Machine Learning</span>
      <span class="qumla-topic">Quantum Algorithms</span>
      <span class="qumla-topic">Quantum Information Theory</span>
    </div>
  </section>
</div>
