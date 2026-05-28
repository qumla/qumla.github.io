---
layout: page
title: Members
permalink: /members/
description: people in the research group
nav: true
nav_order: 2
---

<style>
  .members-list {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    margin: 1rem 0 2rem;
  }

  .member-row {
    display: flex;
    align-items: flex-start;
    gap: 1rem;
    padding: 1rem 0;
    border-bottom: 1px solid var(--global-divider-color, #e5e5e5);
  }

  .member-photo {
    flex: 0 0 96px;
    width: 96px;
    height: 116px;
    border-radius: 8px;
    object-fit: cover;
    background: var(--global-card-bg-color, #f7f7f7);
  }

  .member-info {
    min-width: 0;
  }

  .member-info h3 {
    margin: 0 0 0.25rem;
    font-size: 1.05rem;
  }

  .member-info p {
    margin: 0.1rem 0;
  }

  .member-contact {
    margin-top: 0.35rem;
  }

  .member-contact p {
    margin: 0.1rem 0;
  }

  .pi-career {
    margin: 0.5rem 0 0;
    padding-left: 1.15rem;
  }

  .pi-career li {
    margin: 0.25rem 0;
  }

  @media (max-width: 480px) {
    .member-row {
      gap: 0.75rem;
    }

    .member-photo {
      flex-basis: 76px;
      width: 76px;
      height: 92px;
    }
  }
</style>

## Principal Investigator

<div class="members-list">
  <div class="member-row">
    <img class="member-photo" src="{{ '/assets/img/profile-placeholder.svg' | relative_url }}" alt="Seongwook Shin profile image placeholder">
    <div class="member-info">
      <h3>Seongwook Shin</h3>
      <p>Principal Investigator</p>
      <div class="member-contact">
        <p>Email: seongwook_shin(at)sejong.ac.kr</p>
        <p>Google Scholar: <a href="https://scholar.google.co.kr/citations?user=n3o1O6UAAAAJ&amp;hl=ko" target="_blank" rel="noopener">Seongwook Shin</a></p>
      </div>
      <ul class="pi-career">
        <li>Assistant Professor, Sejong Univ (2026.02 - Present)</li>
        <li>Postdoctoral researcher, Freie Universit&auml;t Berlin (PI: Jens Eisert) (2024.10 - 2026.02)</li>
        <li>Ph.D. in Physics, Seoul National Univ (Advisor: Hyunseok Jeong) (2018.09 - 2024.08)</li>
        <li>BSc in Physics, Yonsei Univ (2013.03 - 2018.08)</li>
      </ul>
    </div>
  </div>
</div>

## Graduate Students

<div class="members-list">
  <div class="member-row">
    <img class="member-photo" src="{{ '/assets/img/profile-placeholder.svg' | relative_url }}" alt="Graduate student profile image placeholder">
    <div class="member-info">
      <h3>Hiring!</h3>
      <p>Graduate Student</p>
      <p>-</p>
    </div>
  </div>
</div>

## Undergraduate Researchers

<div class="members-list">
  <div class="member-row">
    <img class="member-photo" src="{{ '/assets/img/profile-placeholder.svg' | relative_url }}" alt="Undergraduate researcher profile image placeholder">
    <div class="member-info">
      <h3>Hiring!</h3>
      <p>Undergraduate Researcher</p>
      <p>-</p>
    </div>
  </div>
</div>

## Alumni

<div class="members-list">
  <div class="member-row">
    <img class="member-photo" src="{{ '/assets/img/profile-placeholder.svg' | relative_url }}" alt="Alumni profile image placeholder">
    <div class="member-info">
      <h3>Alumni Name</h3>
      <p>Position / Institution</p>
    </div>
  </div>
</div>
