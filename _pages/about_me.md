---
layout: page
title: about me
permalink: /about/
description: Seongwook Shin profile
nav: true
nav_order: 2
---

<style>
  .about-me-hero {
    display: grid;
    grid-template-columns: minmax(230px, 270px) minmax(0, 1fr);
    gap: 2rem;
    align-items: start;
    margin-bottom: 2.5rem;
  }

  .about-me-profile {
    min-width: 0;
  }

  .about-profile-image {
    display: block;
    width: 100%;
    max-width: 160px;
    aspect-ratio: 4 / 5;
    border-radius: 8px;
    object-fit: cover;
    background: var(--global-card-bg-color, #f7f7f7);
  }

  .about-basic-info {
    margin-top: 1rem;
    font-size: 0.97rem;
  }

  .about-basic-info h2,
  .about-greeting h2,
  .career-block h3 {
    margin-top: 0;
  }

  .about-basic-info h2 {
    margin-bottom: 0.35rem;
    font-size: 1.35rem;
  }

  .about-basic-info h3 {
    margin: 0.85rem 0 0.25rem;
    font-size: 1rem;
  }

  .about-basic-info p {
    margin: 0.25rem 0;
  }

  .profile-links,
  .career-list,
  .interest-list {
    padding-left: 1.15rem;
  }

  .profile-links li,
  .career-list li,
  .interest-list li {
    margin: 0.35rem 0;
  }

  .about-greeting {
    min-width: 0;
    font-size: 1.02rem;
    line-height: 1.75;
  }

  .career-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1.5rem 2rem;
  }

  .career-block {
    min-width: 0;
  }

  .career-meta {
    color: var(--global-text-color-light, #666);
  }

  @media (max-width: 720px) {
    .about-me-hero,
    .career-grid {
      grid-template-columns: 1fr;
    }

    .about-profile-image {
      max-width: 160px;
    }
  }
</style>

<div class="about-me-hero">
  <aside class="about-me-profile">
    <img class="about-profile-image" src="{{ '/assets/img/profile-placeholder.svg' | relative_url }}" alt="Seongwook Shin profile image">

    <div class="about-basic-info">
      <h2>Seongwook Shin</h2>
      <p>Assistant Professor</p>
      <p>Department of Quantum Information Science and Engineering, Sejong University, Seoul</p>

      <h3>Profiles</h3>
      <ul class="profile-links">
        <li><a href="mailto:seongwook_shin@sejong.ac.kr">seongwook_shin@sejong.ac.kr</a></li>
        <li><a href="https://scholar.google.co.kr/citations?user=n3o1O6UAAAAJ&amp;hl=en">Google Scholar</a>: 170 citations, h-index 6, i10-index 3 <span class="career-meta">(May 2026)</span></li>
      </ul>
    </div>
  </aside>

  <section class="about-greeting">
    <h2>Greeting</h2>
    <p>Welcome to QuMLa. My research focuses on quantum machine learning, quantum algorithms, and the theoretical tools needed to understand when quantum models can offer meaningful computational advantages.</p>
    <p>At QuMLa, we study quantum models through ideas from learning theory, tensor networks, and quantum information. We are especially interested in clarifying the resources behind quantum learning algorithms and building methods that remain useful on realistic quantum devices.</p>
    <p>I am glad to connect with students and researchers interested in quantum information science, machine learning theory, and algorithmic foundations for quantum computation.</p>
  </section>
</div>

## Career

<div class="career-grid">
  <section class="career-block">
    <h3>Current Appointment</h3>
    <ul class="career-list">
      <li>Assistant Professor, Department of Quantum Information Science and Engineering, Sejong University, Seoul.</li>
    </ul>
  </section>

  <section class="career-block">
    <h3>Education</h3>
    <ul class="career-list">
      <li>Doctoral degree, Seoul National University <span class="career-meta">(Sep. 2024)</span>.</li>
      <li>Bachelor's degree, Yonsei University <span class="career-meta">(Aug. 2018)</span>.</li>
    </ul>
  </section>

  <section class="career-block">
    <h3>Scholarships and Fellowships</h3>
    <ul class="career-list">
      <li>Kwanjeong Fellowship, Kwanjeong Foundation of Korea <span class="career-meta">(2015.03 - 2017.02)</span>.</li>
      <li>Research program for cultivating follow-up generation of science and engineering, National Research Foundation of Korea <span class="career-meta">(2019.03 - 2021.08)</span>.</li>
      <li>Education and Training Program of the Quantum Information Research Support Center, National Research Foundation of Korea <span class="career-meta">(2024.10 - 2026.10)</span>.</li>
    </ul>
  </section>

  <section class="career-block">
    <h3>Teaching Experience</h3>
    <ul class="career-list">
      <li>Teaching Assistant, Seoul National University: Physics experiment, Physics 101, and General relativity.</li>
      <li>Best BK Tutor award for General relativity <span class="career-meta">(Spring 2020)</span>.</li>
    </ul>
  </section>

  <section class="career-block">
    <h3>Patent</h3>
    <ul class="career-list">
      <li>Exponential data encoding for quantum machine learning, Korean patent 1020230079802 <span class="career-meta">(2023)</span>.</li>
    </ul>
  </section>
</div>

## Research Interests

<ul class="interest-list">
  <li>Quantum machine learning: classical representation of QML models, dequantization of QML algorithms, and quantum resources in models.</li>
  <li>Machine learning: learning theory and complexity.</li>
  <li>Quantum algorithms: variational quantum algorithms on noisy quantum machines and quantum singular value transform.</li>
</ul>
