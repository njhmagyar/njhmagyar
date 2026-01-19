---
supertitle: Michigan Online
title: "Implementing a flexible, scalable design system"
permalink: projects/michigan-online-design-system/
project_url: https://www.twirlmate.com/
tagline: 'I built 5 Wagtail (Python) page models, 13 HTML/CSS components, and 21 total variants to accelerate the creation of 4 audience-specific catalog pages and 80+ blog posts.'
overview: "Michigan Online serves 200K+ account holders and a funnel of 12M global learners. The site's design had evolved only in minor ways over five years. It was time for a visual refresh.<br><br>The team saw this as an opportunity to improve not just what the site looked like, but how it was built. We executed a design system-driven approach using a pattern library and a more robust, testable set of components."
where: U-M Center for Academic Innovation / September 2025 - March 2026
role: "I worked as one of two full-stack developers alongside 5 UX designers, 2 project managers, 1 product manager, and 2 marketing team members to rebuild the site. I scoped designs for technical feasibility and reusability, prioritized high-impact components, and applied BEM CSS conventions, accessible HTML, and modular Wagtail blocks to build flexible, scalable, testable components."
order: 1
featured: true
cover_image: /assets/images/michigan-online/design-system/mo-design-system-cover.png
overlay_slug: michigan-online
read_more: []
published: true
---

<img src="/assets/images/michigan-online/design-system/mo-design-system-process.png" class="my-4 mw-700 mx-auto" alt="" />
<div class="mb-4">
  <h2 class="mw-700 mx-auto mb-0"><span data-sidebar class="text--secondary p d-block text--bold">The Problem</span>Building 28 pages, 40 components, 174 instances in 6 months on a small team</h2>
  <p class="mw-700 mx-auto text--secondary">Creating "reusable" components is harder than it sounds, especially on a small team working under a 6-month deadline. Each component needed to handle real-world content variations, adapt to different contexts, and stay maintainable as the system evolved.</p>
  <p class="mw-700 mx-auto text--secondary">I built 13 components (including 4 of the top 5 most-used ones) over the course of the project, each requiring careful thinking about flexibility, abstraction, and edge cases. Every component was a design problem and an engineering problem.
  </p>
  <img src="/assets/images/michigan-online/design-system/mo-design-system-component-instances-chart.png" class="my-4 mw-700 mx-auto" alt="" />
</div>

<div class="mb-4">
  <h2 class="mw-700 mx-auto mb-0"><span data-sidebar class="text--secondary p d-block text--bold">The Process</span>Thinking strategically and systematically</h2>
  <p class="mw-700 mx-auto  text--secondary">During development, I adhered to the following guiding principles:</p>
  <ol class="mw-700 mx-auto">
    <li><p class="text--secondary my-0">Minimize decision fatigue for content editors</p></li>
    <li><p class="text--secondary my-0">Power abstraction with shared HTML anatomy</p></li>
    <li><p class="text--secondary my-0">Chunk implementation in modular steps</p></li>
  </ol>
  <h3 class="p Nunito-bold mw-700 mx-auto mb-0">1. Minimize decision fatique for content editors</h3>
  <p class="mw-700 mx-auto  text--secondary">Testimonial cards needed to work across different page sections, each with their own background color. Instead of forcing content creators to manually select the right color for each visual element in every context, I built the card to auto-adapt its background color based on the parent section. One background choice, one component, zero decision fatigue.</p>
  <img src="/assets/images/michigan-online/design-system/mo-design-system-background-variants.png" class="mt-4 mb-2 mw-700 mx-auto" alt="" />
  <img src="/assets/images/michigan-online/design-system/mo-design-system-testimonials.png" class="mt-4 mb-2 w-100" alt="" />
  <h3 class="p Nunito-bold mw-700 mx-auto mb-0">2. Power abstraction with shared HTML anatomy</h3>
  <p class="mw-700 mx-auto  text--secondary">The accent cards came in two visually distinct variants. But on closer examination, I determined they could share the same underlying structure. I built them with a single HTML structure and CSS modifier classes, changing the visual style without touching the markup. The cards also handle optional CTAs and variable content length (especially headings, where height needed to match across cards in the same row).</p>
  <img src="/assets/images/michigan-online/design-system/mo-design-system-accent-cards-mockup.png" class="mt-4 mb-2 mw-700 mx-auto" alt="" />
  <img src="/assets/images/michigan-online/design-system/mo-design-system-accent-cards.png" class="mt-4 mb-2 w-100" alt="" />
  <h3 class="p Nunito-bold mw-700 mx-auto mb-0">3. Chunk implementation in modular steps</h3>
  <p class="mw-700 mx-auto  text--secondary">The display header component was one of the most-used components in the redesign, and contained 6+ variants. To balance configurability with minimal decision fatigure, I paired design-approved background colors, accent shapes, and clipping masks for a constrained set of options.</p>
  <p class="mw-700 mx-auto  text--secondary">When building the component, I worked in small chunks; starting with the background color options, then adding the clipping mask/shapes with proper aspect ratios to prevent image distortion, and bringing them all together with a streamlined set of CSS modifiers.</p>
  <img src="/assets/images/michigan-online/design-system/mo-design-system-display-header-mockup.png" class="mt-4 mb-2 w-100" alt="" />
  <img src="/assets/images/michigan-online/design-system/mo-design-system-cover.png" class="mt-4 mb-2 w-100" alt="" />
</div>

<div class="mb-4">
  <h2 class="mw-700 mx-auto mb-0"><span data-sidebar class="text--secondary p d-block text--bold">The Impact</span>Increased development velocity by 66%</h2>
  <p class="mw-700 mx-auto text--secondary">I built 13 components with 21 variants used 66 times to serve 200K+ users and a 12M global learner funnel.</p>
<p class="mw-700 mx-auto text--secondary">The impact of this work really shined in the latter half of the 6 month sprint, when the team was able to create new pages with mostly existing components in less than a week, rather than the initial 3+ weeks needed to develop new elements from scratch.</p>
<p class="mw-700 mx-auto text--secondary">The most collaborative part was scoping the blog CMS blocks: meeting with devs, designers, and content folks to prioritize what to build and iterate on the authoring experience until we could recreate 80+ blog posts in the new system.</p>
<p class="mw-700 mx-auto text--secondary">The design system is live, powering the Michigan Online rebrand with flexible, maintainable components built to last.</p>
<img src="/assets/images/michigan-online/design-system/mo-design-system-full-page.png" class="my-4 w-100 rounded border-1-gray-tag" alt="" />
</div>








