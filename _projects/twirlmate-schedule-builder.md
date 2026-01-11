---
supertitle: Twirlmate 
title: "Contest Schedule Builder: From 15 Hours to 5"
permalink: projects/twirlmate-schedule-builder/
project_url: https://www.twirlmate.com/
tagline: 'Automating 15 hours of scheduling headaches into 5 hours of intelligent workflow. Without sacrificing organizer control.'
overview: "I researched, designed, and built a highly automated, user-centered contest schedule building wizard for the sport of baton twirling, eliminating 170 hours of manual data entry across 7 contests for 4,000 performances."
where: Twirlmate / 2025
role: 'As the sole researcher, designer, and developer, I owned everything from user discovery through launch.'
order: 0
featured: true
cover_image: /assets/images/twirlmate/schedule-builder-2/twirlmate-schedule-builder-cover.png
overlay_slug: twirlmate
read_more: []
published: true
---


<div class="mb-4">
  <h2 class="mw-700 mx-auto mb-0"><span data-sidebar class="text--secondary p d-block text--bold">The Problem</span>Baton twirling contests are logistical nightmares</h2>
<img src="/assets/images/twirlmate/schedule-builder-2/twirlmate-schedule-builder-excel.png" class="my-4 w-100" alt="" />
  <p class="mw-700 mx-auto text--secondary">Contest organizers were spending 15+ hours building schedules in Excel. They'd manually add every contestant name, sort them into divisions, assign performance slots, then check for issues one by one. Find a conflict? Start over. Last-minute registration? Rebuild the whole thing.
  </p>
  <p class="mw-700 mx-auto text--secondary">I built Twirlmate to solve this, a Django/Vue platform for contest management. The hardest problem I solved was automated schedule generation.</p>
</div>

<div class="mw-700 mx-auto mb-4">
  <h2 class="mb-0"><span data-sidebar class="text--secondary p d-block text--bold">The Challenge</span>Contest scheduling is full of constraints</h2>
  <p class="text--secondary">While interviewing 3 event organizers about their contest management workflows and pain points, I discovered that scheduling was the most complex and time-consuming step.</p>
  <img src="/assets/images/twirlmate/schedule-builder-2/twirlmate-schedule-builder-constraints.png" class="mt-4 mb-2 w-100" alt="" />
  <p class="text--secondary">Interviewees also completed a survey, which told me how much time they were spending on scheduling, and where in the process they had the most trouble:</p>
  <img src="/assets/images/twirlmate/schedule-builder-2/twirlmate-schedule-builder-survey.png" class="w-100 my-2" alt="" />
<p class="text--secondary">I proceeded by mapping out the system. Only then could I design the interface and the logic behind it.</p>
<img src="/assets/images/twirlmate/schedule-builder-2/twirlmate-schedule-builder-data-architecture.png" class="w-100 my-2" alt="" />
</div>


<div class="mb-4">
  <h2 class="mw-700 mx-auto mb-0"><span data-sidebar class="text--secondary p d-block text--bold">The Solution</span>Schedule-generation wizard</h2>
  <p class="mw-700 mx-auto text--secondary">I designed a schedule wizard that walks organizers through configuration, then generates conflict-free schedules automatically.</p>
  <p class="mw-700 mx-auto text--secondary">The interface lets organizers define their contest structure: how many divisions, which event types, venue constraints, and spacing rules. </p>
<p class="mw-700 mx-auto text--secondary">It's complex but not overwhelming—organizers configure once, then the system handles the rest.</p>
<p class="mw-700 mx-auto text--secondary">The backend logic is where the real work happens. The algorithm:</p>
<ol class="mw-700 mx-auto text--secondary">
  <li><p class="my-0">Assigns performance order to contestants</p></li>
  <li><p class="my-0">Detects conflicts (someone performing too recently)</p></li>
  <li><p class="my-0">Skips conflicting contestants initially</p></li>
  <li><p class="my-0">Auto-inserts spacing ("byes") based on contest rules</p></li>
  <li><p class="my-0">Circles back to place skipped contestants with proper gaps</p></li>
  <li><p class="my-0">Bulk-creates all performances in a single database operation for speed</p></li>
</ol>
<img src="/assets/images/twirlmate/schedule-builder-2/twirlmate-schedule-builder-code-snippet.png" class="my-4 mw-700 mx-auto " alt="" />

<p class="mw-700 mx-auto text--secondary">From there, the event organizer fine-tunes the schedule, resolving any remaining conflicts and handling last-minute changes. The result: 15 hours of manual work reduced to 3 hours.</p>
</div>

<img src="/assets/images/twirlmate/schedule-builder-2/twirlmate-schedule-builder-cover.png" class="mb-4 w-100" alt="" />

<div class="mb-4">
  <h2 class="mw-700 mx-auto mb-0"><span data-sidebar class="text--secondary p d-block text--bold">The Impact</span>7 contests. 4K performances. $82K in revenue.</h2>
  <p class="mw-700 mx-auto text--secondary">Three organizations now use Twirlmate for their contests. The platform has scheduled 4,000 performances and generated $82,000 in revenue.</p>
<p class="mw-700 mx-auto text--secondary">Organizers call it the "quickest state contest to date." One told me she couldn't believe how fast setup was compared to the spreadsheet chaos she'd been doing for years.</p>
<p class="mw-700 mx-auto text--secondary">The schedule builder was the technical unlock that made everything else possible. Once organizers trusted the platform to handle their hardest problem, they adopted the rest: registration, tabulation, results publishing.</p>
</div>








