---
supertitle: Twirlmate 
title: "Contest Schedule Builder: From 50 Hours to 3"
permalink: projects/twirlmate-schedule-builder/
project_url: https://www.twirlmate.com/
tagline: 'Automating 50 hours of scheduling headaches into 3 hours of intelligent workflow. Without sacrificing organizer control.'
overview: 'Event organizers spent 50+ hours manually scheduling baton twirling contests in Excel, coordinating hundreds of athletes while avoiding judge-coach conflicts and timing overlaps—often with errors still slipping through.<br><br>I designed and built an intelligent scheduling wizard that automates conflict detection and algorithmic schedule generation while preserving organizer flexibility through real-time editing and drag-and-drop controls.<br><br>By shifting data entry from organizers to families during registration and balancing performances across lanes, the system reduced scheduling time by 80-90% and eliminated errors almost entirely.<br><br>The result: organizers now complete schedules in 1-5 hours with 100% satisfaction and adoption in the first season.'
where: Twirlmate / 2025 - Used by 7 contests to schedule 4,000+ performances
role: 'As the sole designer and developer, I conducted user research with event organizers, designed the complete user experience from registration through schedule generation, and built the full-stack solution using Django and Vue.js.'
order: 1
featured: false
cover_image: /assets/images/twirlmate/schedule-builder/twirlmate-schedule-cover.png
overlay_slug: twirlmate
read_more: []
published: false
---

<div class="mb-4">
  <h2 class="mw-700 mx-auto mb-0"><span data-sidebar>The Challenge</span>: Manual Chaos in Excel</h2>
  <p class="mw-700 mx-auto text--secondary">A never-ending game of guesswork to create conflict-free schedules</p>
  <img src="/assets/images/twirlmate/schedule-builder/twirlmate-schedule-before-after.png" class="w-100" alt="" />
  <p class="mw-700 mx-auto text--secondary">Event organizers spent 50+ hours manually building schedules in Excel, coordinating 250+ athletes across 1,250 performances while avoiding judge-coach conflicts, timing overlaps, and convention violations. Despite this massive time investment, errors were common: missing performances, scheduling conflicts, and cascading problems from last-minute changes.
  </p>
</div>

<div class="mb-4">
  <h2 class="mw-700 mx-auto mb-0"><span data-sidebar>The Solution</span>: Intelligent Automation Meets Human Control</h2>
  <p class="mw-700 mx-auto text--secondary">A wizard that handles the complexity while preserving organizer flexibility</p>
  <img src="/assets/images/twirlmate/schedule-builder/twirlmate-schedule-flow.png" class="w-100 rounded" alt="" />
  <p class="mw-700 mx-auto text--secondary">I designed a multi-step wizard that captures scheduling preferences (lane configuration, block structure, lineup ordering), then automatically generates conflict-free schedules using a greedy algorithm that balances performances across lanes while respecting judge-coach relationships, timing constraints, and sport conventions.</p>
  <p class="mw-700 mx-auto text--secondary">Organizers retain full control through an editable interface that highlights conflicts in real-time and allows drag-and-drop adjustments, manual additions, and regeneration.</p>
  <p class="mw-700 mx-auto text--secondary">By shifting athlete data entry from organizers to families during registration, the system eliminated the 25+ hours of manual setup that plagued existing solutions.
  </p>
</div>

<div class="mb-4">
  <h2 class="mw-700 mx-auto mb-0"><span data-sidebar>Technical Innovation</span>: Speed Through Smart Architecture</h2>
  <p class="mw-700 mx-auto text--secondary">Generating 1,250 performances in under a minute</p>
  <img src="/assets/images/twirlmate/schedule-builder/twirlmate-schedule-builder-pseudocode.png" class="w-100 rounded" alt="" />
  <p class="mw-700 mx-auto text--secondary">Built with Django and Vue, the system uses prefetching and in-memory storage to minimize database queries during generation, processing schedules through batched requests (one per outlined event). The algorithm works greedily: for each event, it finds the lane with fewest performances, checks for conflicts, and optimizes for minimal future scheduling issues.</p>
  <p class="mw-700 mx-auto text--secondary">When I discovered that top-of-schedule edits caused performance bottlenecks (updating everything downstream), I restructured generation to happen independently per event block, transforming 10-second freezes into instant updates.</p>
</div>

  <img src="/assets/images/twirlmate/schedule-builder/twirlmate-schedule-builder-chart-1.png" class="w-100 rounded" alt="" />
  <img src="/assets/images/twirlmate/schedule-builder/twirlmate-schedule-builder-chart-2.png" class="w-100 rounded" alt="" />
  <img src="/assets/images/twirlmate/schedule-builder/twirlmate-schedule-builder-chart-3.png" class="w-100 rounded" alt="" />
</div>x








