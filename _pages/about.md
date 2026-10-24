---
permalink: /
title: "Sultan Muratbek"
description: "Sultan Muratbek is an undergraduate researcher in database systems at UC Berkeley, working on query optimization for multimodal LLM-powered data processing. Applying to Ph.D. programs for Fall 2027."
redirect_from:
  - /about/
  - /about.html
---

<div class="profile">
  <img src="{{ '/images/sultan-muratbek.jpg' | relative_url }}" alt="Photo of Sultan Muratbek">
  <div>
    <h1>Sultan Muratbek</h1>
    <p class="role">Undergraduate Researcher, Sky Computing Lab &amp; BAIR, UC Berkeley<br>B.A. Computer Science (EECS Honors) &amp; Legal Studies, May 2027</p>
    <div class="contact">
      <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
      <a href="{{ '/files/SultanMuratbek-CV.pdf' | relative_url }}">CV (PDF)</a>
      <a href="https://github.com/{{ site.author.github }}">GitHub</a>
      <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a>
      {%- if site.author.googlescholar %}
      <a href="{{ site.author.googlescholar }}">Google Scholar</a>
      {%- endif %}
    </div>
  </div>
</div>

I am a senior at UC Berkeley studying Computer Science (Honors Program) and Legal Studies. I work on **database systems** in the [Sky Computing Lab](https://sky.cs.berkeley.edu/), advised by [Prof. Alvin Cheung](https://people.eecs.berkeley.edu/~akcheung/). My research is on query optimization for AI-powered data processing: making queries that call multimodal LLMs over video, text, and other unstructured data cheaper, faster, and more accurate.

My recent project, [Concord](https://concord-db.github.io/) (CIDR 2027, co-first author), is a video relational algebra that lets an optimizer rewrite semantic video queries across modalities. For example, it can answer a query from a transcript instead of the video, or use the transcript to choose the few clips an MLLM actually needs to watch.

I also work with [Prof. Narges Norouzi](https://eecs.berkeley.edu/~norouzi/) at [BAIR](https://bair.berkeley.edu/) on a lecture-feedback platform, now deployed in six Berkeley courses, that turns slides, transcripts, and interaction signals into insights for instructors.

I love teaching. I have been on the CS 61A course staff since Spring 2024 and have served as Head TA since Summer 2025.

<div class="callout" markdown="1">
**I am applying to Ph.D. programs in Computer Science for Fall 2027.** If our interests overlap, I would love to hear from you.
</div>

<p class="interests"><strong>Interests:</strong> database systems, query optimization, data systems for machine learning, multimodal data management.</p>

## News

<ul class="news">
{%- for item in site.data.news %}
  <li><span class="date">{{ item.date }}</span>{{ item.text | markdownify }}</li>
{%- endfor %}
</ul>

## Publications

<p class="pub-note">* Equal contribution</p>
<ul class="pubs">
{%- for pub in site.data.publications %}
  {% include publication.html pub=pub tldr=true %}
{%- endfor %}
</ul>

## Research Experience

<ul class="entries">
  <li class="entry">
    <span class="what">Sky Computing Lab, UC Berkeley · Undergraduate Researcher</span>
    <span class="when">May 2026 – Present</span>
    <span class="detail">Advisor: <a href="https://people.eecs.berkeley.edu/~akcheung/">Prof. Alvin Cheung</a>. Co-designed Video Relational Algebra and cross-modal temporal pushdown for semantic video queries (<a href="https://concord-db.github.io/">Concord</a>).</span>
  </li>
  <li class="entry">
    <span class="what">Berkeley AI Research (BAIR) · Undergraduate Research Assistant</span>
    <span class="when">Jan 2026 – Present</span>
    <span class="detail">Advisor: <a href="https://eecs.berkeley.edu/~norouzi/">Prof. Narges Norouzi</a>. Building a lecture-feedback platform and a per-lecture knowledge-graph pipeline that finds logical gaps and pacing issues across 55+ lectures.</span>
  </li>
</ul>

## Teaching

<ul class="entries">
  <li class="entry">
    <span class="what">Head Teaching Assistant, <a href="https://cs61a.org">CS 61A</a>: Structure and Interpretation of Computer Programs</span>
    <span class="when">Summer 2025 – Present</span>
  </li>
  <li class="entry">
    <span class="what">Tutor, CS 61A</span>
    <span class="when">Summer 2024 – Spring 2025</span>
  </li>
  <li class="entry">
    <span class="what">Academic Intern, CS 61A</span>
    <span class="when">Spring 2024</span>
  </li>
  <li class="entry">
    <span class="what">Mentor, CS 61C: Machine Structures (Computer Science Mentors)</span>
    <span class="when">Fall 2024</span>
  </li>
</ul>

Section pages and materials for my students are on the [teaching page]({{ '/teaching/' | relative_url }}).

## Education

<ul class="entries">
  <li class="entry">
    <span class="what">University of California, Berkeley</span>
    <span class="when">2023 – May 2027 (expected)</span>
    <span class="detail">B.A. Computer Science (EECS Honors Program) and B.A. Legal Studies. Upsilon Pi Epsilon; Dean's Honors List. <a href="{{ '/markdown/' | relative_url }}">Coursework</a>.</span>
  </li>
</ul>

Outside of research, I play pickleball and soccer and go on long walks.
