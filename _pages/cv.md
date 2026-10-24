---
title: "CV"
permalink: /cv/
redirect_from:
  - /resume
---

<p><a href="{{ '/files/SultanMuratbek-CV.pdf' | relative_url }}">Download PDF</a></p>

## Education

<ul class="entries">
  <li class="entry">
    <span class="what">University of California, Berkeley</span>
    <span class="when">Expected May 2027</span>
    <div class="detail">B.A. Computer Science · B.A. Legal Studies · CS GPA 3.97/4.00<br>
    Honors: EECS Honors Program, Upsilon Pi Epsilon (UPE) Computer Science Honor Society, Dean's Honors List<br>
    Relevant coursework: Advanced Topics in Computer Systems (graduate), Database Systems, Operating Systems, Algorithms, Computer Networks, Security, Programming Languages &amp; Compilers, Machine Learning, Deep Neural Networks · <a href="{{ '/markdown/' | relative_url }}">Full list</a></div>
  </li>
</ul>

## Publications

<p class="pub-note">* Equal contribution</p>
<ul class="pubs">
{%- for pub in site.data.publications %}
  {% include publication.html pub=pub %}
{%- endfor %}
</ul>

## Research Experience

<ul class="entries">
  <li class="entry">
    <span class="what">Sky Computing Lab, UC Berkeley · Undergraduate Researcher</span>
    <span class="when">May 2026 – Present</span>
    <div class="detail">Advised by Prof. Alvin Cheung.
      <ul>
        <li>Co-first author, <em>Concord: A Video Relational Algebra for Cross-Modal Query Optimization</em> (arXiv:2609.05756; accepted to CIDR 2027). Co-designed Video Relational Algebra (VRA), a nested algebra over videos, transcripts, frames, detections, and tracks that enables query rewrites across modality, temporal extent, and processing granularity.</li>
        <li>Co-developed and evaluated cross-modal temporal pushdown that sent only 2.47–5.32% of source-video duration to the MLLM across 8.5 hours of footage, reducing estimated MLLM cost by up to 87.2% and cold-start query time by up to 80.9%.</li>
      </ul>
    </div>
  </li>
  <li class="entry">
    <span class="what">Berkeley Artificial Intelligence Research Lab (BAIR) · Undergraduate Research Assistant</span>
    <span class="when">Jan 2026 – Present</span>
    <div class="detail">Advised by Prof. Narges Norouzi.
      <ul>
        <li>Develop and maintain a lecture-feedback platform in Python (Flask), JavaScript, and Azure SQL that ingests slides, transcripts, and interaction signals to produce instructor-facing insights, deployed in 6 UC Berkeley courses.</li>
        <li>Design a per-lecture knowledge-graph pipeline that extracts concepts, definitions, and prerequisite dependencies to identify logical gaps and pacing issues across 55+ lectures.</li>
        <li>Conducted structured interviews with 5 UC Berkeley CS professors and translated findings into product requirements and system features for actionable instructor feedback.</li>
      </ul>
    </div>
  </li>
</ul>

## Teaching

<ul class="entries">
  <li class="entry">
    <span class="what">Head Teaching Assistant, CS 61A: Structure and Interpretation of Computer Programs</span>
    <span class="when">Jun 2025 – Present</span>
    <div class="detail">
      <ul>
        <li>Maintain course infrastructure and build internal automation and assessment tooling for a course serving 1,000+ students per semester.</li>
        <li>Lead instruction on recursion, data structures, OOP, interpreters, and functional programming; earned a 4.40/5.00 teaching effectiveness rating.</li>
      </ul>
    </div>
  </li>
  <li class="entry">
    <span class="what">Tutor, CS 61A</span>
    <span class="when">Summer 2024 – Spring 2025</span>
    <div class="detail">Taught small sections of five students weekly; ran office hours, project parties, and final exam review sessions.</div>
  </li>
  <li class="entry">
    <span class="what">Mentor, CS 61C: Machine Structures · Computer Science Mentors</span>
    <span class="when">Fall 2024</span>
    <div class="detail">Taught a bi-weekly section of seven students.</div>
  </li>
  <li class="entry">
    <span class="what">Academic Intern, CS 61A</span>
    <span class="when">Spring 2024</span>
    <div class="detail">Assisted weekly lab sections and attended pedagogy workshops.</div>
  </li>
</ul>

## Projects

<ul class="entries">
  <li class="entry">
    <span class="what">Relational Database Management System · Java</span>
    <span class="when">Jan 2026 – May 2026</span>
    <div class="detail">Built core components of a relational DBMS, including B+ tree indexing, cost-based query optimization, two-phase locking, and ARIES-style crash recovery; implemented Grace Hash Join, Sort-Merge Join, and Page Nested Loop Join as physical execution operators.</div>
  </li>
  <li class="entry">
    <span class="what">Pintos OS Kernel · C</span>
    <span class="when">Jan 2025 – May 2025</span>
    <div class="detail">Extended the Pintos instructional kernel with a priority scheduler, synchronization primitives, system calls, and a buffered file system; diagnosed race conditions and low-level memory bugs.</div>
  </li>
  <li class="entry">
    <span class="what">Transformer Architecture · PyTorch</span>
    <span class="when">Nov 2025</span>
    <div class="detail">Implemented a Transformer encoder-decoder with multi-head attention, residual connections, positional encoding, and masked autoregressive decoding; trained a decoder-only variant on TinyStories for next-token prediction.</div>
  </li>
</ul>

## Skills

- **Languages:** Python, Java, C, Go, OCaml, SQL, JavaScript/TypeScript
- **Technologies:** Linux/Unix, Git, Docker, PostgreSQL, Azure SQL, Flask, PyTorch, AWS, GCP
