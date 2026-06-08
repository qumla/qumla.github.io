---
layout: about
title: Home
permalink: /
description: QuMLa is the Quantum Machine Learning and Algorithms research group at Sejong University, studying quantum machine learning, quantum algorithms, and quantum information theory.
keywords: QuMLa, quantum machine learning, quantum algorithms, quantum information theory, quantum computing, Sejong University, Department of Quantum Information Science and Engineering
og_image: https://qumla.github.io/assets/img/qumla-full.png
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
    position: relative;
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

  .qumi-peek {
    display: block;
    position: absolute;
    top: -1.2rem;
    right: clamp(-112px, -9vw, -84px);
    width: clamp(112px, 12vw, 136px);
    height: auto;
    pointer-events: none;
    user-select: none;
    transform: rotate(6deg);
    filter: drop-shadow(0 12px 18px rgba(20, 33, 61, 0.2));
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

  .qumla-recruit-banner {
    margin: 0 auto 1.75rem;
    max-width: 930px;
    border: 1px solid rgba(42, 157, 159, 0.38);
    border-left: 4px solid #2a9d9f;
    border-radius: 8px;
    padding: 1.05rem 1.15rem;
    background: linear-gradient(135deg, rgba(42, 157, 159, 0.1), rgba(20, 33, 61, 0.03));
    box-shadow: 0 16px 34px rgba(20, 33, 61, 0.08);
  }

  .qumla-recruit-banner-main {
    display: flex;
    gap: 1rem;
    align-items: flex-start;
    justify-content: space-between;
  }

  .qumla-recruit-label {
    display: inline-flex;
    border: 1px solid rgba(42, 157, 159, 0.35);
    border-radius: 999px;
    padding: 0.26rem 0.68rem;
    color: #2a9d9f;
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0;
    line-height: 1.2;
  }

  .qumla-recruit-title {
    margin: 0.45rem 0 0.35rem;
    color: var(--global-text-color);
    font-size: clamp(1.15rem, 2.4vw, 1.4rem);
    font-weight: 600;
    line-height: 1.25;
  }

  .qumla-recruit-summary {
    margin: 0;
    color: var(--global-text-color);
    font-size: 0.98rem;
    line-height: 1.55;
  }

  .qumla-recruit-mail {
    display: inline-flex;
    flex: 0 0 auto;
    align-items: center;
    justify-content: center;
    min-height: 2.45rem;
    border: 1px solid #2a9d9f;
    border-radius: 8px;
    padding: 0.6rem 0.95rem;
    background: #2a9d9f;
    color: #ffffff;
    font-weight: 700;
    line-height: 1.2;
    text-decoration: none;
  }

  .qumla-recruit-mail:hover {
    color: #ffffff;
    text-decoration: none;
    filter: brightness(0.95);
  }

  .qumla-recruit-details {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem 1.2rem;
    margin: 0.95rem 0 0;
    border-top: 1px solid var(--global-divider-color);
    padding-top: 0.85rem;
  }

  .qumla-recruit-detail {
    display: flex;
    gap: 0.35rem;
    margin: 0;
    line-height: 1.45;
  }

  .qumla-recruit-detail dt {
    color: #2a9d9f;
    font-weight: 700;
  }

  .qumla-recruit-detail dd {
    margin: 0;
    color: var(--global-text-color);
  }

  .qumla-recruit-list-title {
    margin: 0.8rem 0 0.45rem;
    color: var(--global-text-color);
    font-weight: 700;
  }

  .qumla-recruit-list {
    margin: 0;
    padding-left: 1.2rem;
  }

  .qumla-recruit-list li {
    margin-bottom: 0.3rem;
    color: var(--global-text-color);
    line-height: 1.45;
  }

  html[data-theme="dark"] .qumla-intro-card {
    background: linear-gradient(135deg, rgba(42, 157, 159, 0.16), rgba(235, 222, 194, 0.07));
    box-shadow: 0 18px 45px rgba(0, 0, 0, 0.25);
  }

  html[data-theme="dark"] .qumla-recruit-banner {
    background: linear-gradient(135deg, rgba(42, 157, 159, 0.17), rgba(235, 222, 194, 0.06));
    box-shadow: 0 16px 34px rgba(0, 0, 0, 0.2);
  }

  @media (max-width: 1080px) {
    .qumi-peek {
      display: none;
    }
  }

  @media (max-width: 575.98px) {
    .qumla-home-intro {
      margin-bottom: 1.8rem;
    }

    .qumla-intro-card {
      padding: 1.25rem;
    }

    .qumla-recruit-banner {
      margin-bottom: 1.35rem;
      padding: 0.95rem;
    }

    .qumla-recruit-banner-main {
      display: grid;
      gap: 0.8rem;
    }

    .qumla-recruit-mail {
      width: 100%;
    }

    .qumla-recruit-details {
      display: grid;
      gap: 0.4rem;
    }

    .qumla-recruit-detail {
      display: grid;
      gap: 0.08rem;
    }

    .qumi-peek {
      display: block;
      position: static;
      width: min(180px, 48vw);
      margin: 1rem auto 0;
      transform: none;
    }
  }
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ResearchOrganization",
  "name": "QuMLa",
  "alternateName": "Quantum Machine Learning and Algorithms group",
  "url": "{{ site.url }}{{ site.baseurl }}/",
  "logo": "{{ site.url }}{{ site.baseurl }}/assets/img/qumla-full.png",
  "description": "{{ page.description }}",
  "parentOrganization": {
    "@type": "CollegeOrUniversity",
    "name": "Sejong University",
    "url": "https://www.sejong.ac.kr/"
  },
  "department": {
    "@type": "Organization",
    "name": "Department of Quantum Information Science and Engineering",
    "url": "https://dept.sejong.ac.kr/qisedpt/index.do"
  },
  "knowsAbout": [
    "Quantum machine learning",
    "Quantum algorithms",
    "Quantum information theory",
    "Quantum computing"
  ]
}
</script>

<section class="qumla-recruit-banner" aria-labelledby="intern-banner-title">
  <div class="qumla-recruit-banner-main">
    <div>
      <span class="qumla-recruit-label">Recruitment Notice</span>
      <h2 class="qumla-recruit-title" id="intern-banner-title">Undergraduate Interns: July-December 2026</h2>
      <p class="qumla-recruit-summary">
        QuMLa is recruiting undergraduate interns for the July-December research period.
      </p>
    </div>
    <a class="qumla-recruit-mail" href="mailto:seongwook_shin@sejong.ac.kr?subject=QuMLa%20Undergraduate%20Intern%20Application">Send application email</a>
  </div>
  <dl class="qumla-recruit-details">
    <div class="qumla-recruit-detail">
      <dt>Application</dt>
      <dd>June 8-June 20, 2026</dd>
    </div>
    <div class="qumla-recruit-detail">
      <dt>Email</dt>
      <dd><a href="mailto:seongwook_shin@sejong.ac.kr">seongwook_shin@sejong.ac.kr</a></dd>
    </div>
  </dl>
  <p class="qumla-recruit-list-title">In the email, please include:</p>
  <ul class="qumla-recruit-list">
    <li>&#47588;&#51452; &#51201;&#50612;&#46020; &#54620; &#48264; &#54617;&#44368;&#50640; &#45208;&#50732; &#49688; &#51080;&#45716;&#51648;</li>
    <li>&#47924;&#50631;&#51012; &#48176;&#50864;&#44256; &#49910;&#51008;&#51648; (&#44288;&#49900; &#48516;&#50556;)</li>
    <li>&#45224;&#49457; &#51648;&#50896;&#51088;&#51032; &#44221;&#50864; &#44400; &#48373;&#47924; &#44228;&#54925;</li>
  </ul>
</section>

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
  <img class="qumi-peek" src="{{ '/assets/img/qumi-peek.png' | relative_url }}" alt="" aria-hidden="true">
</div>
