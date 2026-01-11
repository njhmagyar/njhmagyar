---
supertitle: Twirlmate
title: Reducing friction in a multi-step flow
permalink: projects/twirlmate/
project_url: https://www.twirlmate.com/
tagline: 'I redesigned a mobile registration experience, decreasing combined account setup and checkout times from 8 to 5 minutes.'
overview: 'Multi-step registration flows often fail when they assume users will complete steps in a "logical" order. In this case, a contest registration platform required account setup before registration. But users arrived with one goal: register for a specific event. This mismatch between system design and user intent caused confusion, abandonment, and required manual intervention to complete registrations. <br><br>I redesigned the mobile registration experience, transforming a disjointed onboarding flow into a seamless customer journey; achieving a usability score of 89 (well above the industry average of 67) and reducing average time between sign up and checkout from 8 to 3 minutes.'
where: Twirlmate / 2025
role: 'As the sole designer and developer on the project, I leveraged my visual creativity and coding skills to solve a critical user experience bottleneck while ensuring technical feasibility.'
order: 1
featured: false
cover_image: /assets/images/twirlmate/twirlmate-cover-4-mobile-2.svg
cover_video: /assets/videos/twirlmate-yellow.mp4
overlay_slug: twirlmate
read_more: []
published: false
---

<div class="mb-4">
  <h2 data-sidebar class="mw-700 mx-auto mb-0">Assumptions ≠ Reality</h2>
  <p class="mw-700 mx-auto mb-4 text--secondary">
    The platform assumed users would create accounts first, then register for events later. So when users arrived with immediate intent to register for a specific contest, there was a 4-click gap between the end of the onboarding flow and the desired registration page.
  </p>
  <img src="/assets/images/twirlmate/twirlmate-problem.svg" class="w-100 rounded" alt="" />
</div>

<div class="mw-700 mx-auto mb-4">
  <h2 data-sidebar class="mb-0">Real users, real revenue loss</h2>
  <p class="text--secondary">As the only person managing customer support, I saw the problem firsthand:</p>
  <ul class="text--secondary">
    <li><p class="my-0"><strong class="text--black">Customers:</strong> frustrated with the system architecture</p></li>
    <li><p class="my-0"><strong class="text--black">Directors:</strong> concerned about fewer attendees and lost revenue</p></li>
    <li><p class="my-0"><strong class="text--black">My business:</strong> increased customer support and manual registration effort</p></li>
  </ul>
</div>

<div class="mb-4">
  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar class="mb-0">Best UX over quick wins</h2>
    <p class="text--secondary">I explored 3 solutions to the problem and weighed the tradeoffs between them:</p>
    <p class="text--secondary"><strong class="text--black">Option 1: Post-Setup Redirection</strong> - After account creation, redirect users to find their contest again on the event list page.</p>
    <ul class="text--secondary">
      <li><p class="my-0"><strong class="text--black">Pros:</strong> Lowest technical and design lift</p></li>
      <li><p class="my-0"><strong class="text--black">Cons:</strong> Didn't fully close the gap between account setup and registration page (3-click gap remained)</p></li>
    </ul>
    <p class="text--secondary"><strong class="text--black">Option 2: Context Preservation</strong> - Use backend functionality to remember which contest users were registering for and redirect them after account setup.</p>
    <ul class="text--secondary">
      <li><p class="my-0"><strong class="text--black">Pros:</strong> Medium technical lift, no UI changes needed</p></li>
      <li><p class="my-0"><strong class="text--black">Cons:</strong> Still a disruptive experience (took users away from their primary goal)</p></li>
    </ul>
    <p class="text--secondary"><strong class="text--black">Option 3: Contextual Account Creation</strong> - Embed account setup directly within the registration process.</p>
    <ul class="text--secondary">
      <li><p class="my-0"><strong class="text--black">Pros:</strong> Kept the user in the context of the contest and maximized flexibility for both new and returning users</p></li>
      <li><p class="my-0"><strong class="text--black">Cons:</strong> Largest technical and design lift (major feature overhaul)</p></li>
    </ul>
    <p class="text--secondary">I ultimately went with option 3 because it provided the best user experience: attendees could remain focused on pursuing their primary goal (contest registration) while satisfying system requirements (account setup) all in one continuous flow.</p>
  </div>
  <div class="nhm-image-wrapper">
    <img src="/assets/images/twirlmate/twirlmate-main-problem-fix.svg" class="w-100" alt="" />
  </div>
</div>

<div class="mb-4">
  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar class="mb-0">5 minutes faster, 36% more usable</h2>
    <p class="text--secondary">Usability testing with 5 target users showed:</p>
      <ul class="text--secondary">
      <li><p class="my-0">Task completion time dropped <strong class="text--black">from 8 minutes to 3 minutes</strong> (62.5% reduction).</p></li>
      <li><p class="my-0">Usability scores jumped <strong class="text--black">from "marginally acceptable" (SUS: 67) to "excellent" (SUS: 89).</strong></p></li>
      <li><p class="my-0">Users completed the flow without confusion or manual intervention.</p></li>
    </ul>
  </div>
  <img src="/assets/images/twirlmate/twirlmate-cover-4-mobile-2.svg" class="w-100 rounded" alt="" />
</div>

<div class="align--center mb-4">
  <h2>Want to see more?</h2>
  <a class="nhm-btn--blue" href="https://www.twirlmate.com/" target="_blank">
    View the Live Site
  </a>
</div>





