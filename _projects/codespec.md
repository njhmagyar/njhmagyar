---
supertitle: Codespec
title: Optimizing an AI-powered user experience
permalink: projects/codespec/
project_url: https://www.codespec.org/
tagline: I transformed a confusing content authoring flow into a guided collaboration experience between computer science instructors and GenAI.
overview: Codespec is an online programming practice environment where learners of all levels can solve each problem 5 ways. For this project, I employed informal interviewing, user-centered design thinking, AI-powered prototyping, and usability testing to transform a confusing content authoring flow into a guided collaboration experience between computer science instructors and GenAI.
where: Codespec / 2025
role: As co-founder and a solo designer, I iterated on a critical UX challenge and presented a recommendation to my co-founder.
order: 5
featured: false
cover_image: /assets/images/codespec/codespec-cover-new.png
cover_video: /assets/videos/codespec.mp4
overlay_slug: codespec
read_more: []
prototype_id: "codespec-prototype"
published: true
---
<div class="mb-4" id="codespec-prototype">
  <div class="prototype-container" style="position: relative;">
    <!-- Dark background to prevent white flash -->
    <div style="position: absolute; top: 0; left: 0; right: 0; height: 600px; background: #171e32; border-radius: 8px; z-index: 1;"></div>
    <iframe src="https://www.nathanmagyar.com/codespec-gen-ai-problems/" width="100%" height="600" frameborder="0" style="border-radius: 8px; position: relative; z-index: 2;"></iframe>
  </div>
  <p class="text--small text--secondary mt-1 mw-700 mx-auto">
    <em>Note: This is a functional prototype built with HTML, CSS, and JavaScript to demonstrate the user interface and flow.</em>
  </p>
</div>

<div class="mb-4">
  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar>Suboptimal GenAI Workflow</h2>
    <p class="text--secondary mt-0">
      Codespec offers instructors a way to create problems with the help of generative AI, but the process was confusing to them. Key issues included:
    </p>
    <p class="text--secondary mt-0">
      A. Lack of context in the problem creation flow: "What step am I on?"
    </p>
    <p class="text--secondary mt-0">
      B. Mismatch between which content the user needed to provide vs GenAI: "Can't I just provide a theme and have GenAI create the title/instructions?"
    </p>
    <p class="text--secondary mt-0">
      C. Non-linear/unclear steps in the workflow: "Where do I go next?"
    </p>
  </div>
  <img src="/assets/images/codespec/codespec-genai-before.png" class="d-block w-100 rounded" alt="" />
</div>


<div class="mw-700 mx-auto mb-4">
  <h2 data-sidebar>Collect V1 Feedback</h2>
  <p class="text--secondary">
    In order to improve upon the first version of the workflow, I had to understand its strengths and weaknesses. So I interviewed a researcher who had used it, asking non-leading, open-ended questions.
  </p> 
  <p class="text--secondary">
    I also clicked through the workflow myself with mindset of a user who was brand new to the platform.
  </p>  
</div>

<div class="mb-4">
  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar>Define Personas</h2>
    <p class="text--secondary">
      Armed with a list of painpoints, I drafted personas in which to ground my design.
    </p>
    <p class="text--secondary">
      Despite differences in programming knowledge, both user types are open to leveraging GenAI tools and would like to maximize output while minimizing time investment.
    </p>
  </div>
  <img src="/assets/images/codespec/codespec-personas.png" class="w-100" alt="" />
</div>

<div class="mb-4">
  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar>Delegate responsibilities</h2>
    <p class="text--secondary">
      The researcher I first interviewed was dissatisfied with the GenAI authoring experience. They wanted a more collaborative flow where they provided basic context (e.g., difficulty, theme, programming concepts) and GenAI took a pass at the rest.
    </p>
    <p class="text--secondary">
      I responded by breaking the parts of a problem down into separate pieces, and determining which were more appropriate for users to specify vs GenAI.
    </p>
  </div>
  <img src="/assets/images/codespec-human-in-the-loop.svg" class="mxh-300 nhm-card__image" alt="" />
</div>

<div class="mb-4">
  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar>Map the workflow</h2>
    <p class="text--secondary">
      While the researcher wanted GenAI to take a first pass at writing the problem, they still wanted to retain control throughout the process to ensure pedagogical quality.
    </p>
    <p class="text--secondary">
      So I mapped a user journey that reflected a prompt-generate-review cycle, keeping the author in the driver's seat at all times.
    </p>
  </div>
  <div class="bg-gray--light rounded">
    <img src="/assets/images/codespec-loop.svg" class="w-100" alt="" />
  </div>
</div>

<div class="mb-4">
  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar>Sketch Wireframes</h2>
    <p class="text--secondary">
      With this flow in mind, I sketched out each screen. I imagined a linear wizard-like experience, where
      each step focused on a few key pieces about the problem.
    </p>
    <p class="text--secondary">
      I wanted the interface to feel approachable and clean, so authors could focus on the content rather than trying understand how to use the system.
    </p>
  </div>
  <img src="/assets/images/codespec/codespec-sketches.png" class="w-100" alt="" />
</div>

<div class="mb-4">
  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar>Prototype with Claude Code</h2>
    <img src="/assets/images/codespec-claude-chat.svg" class="mxh-500 nhm-card__image" alt="" />
    <p class="text--secondary">
      To bring the design to life, I collaborated with Claude in small, specific, example-rich steps.
    </p>
    <p class="text--secondary">I stated my end goal up front, but emphasized the importance of working incrementally:</p>
    <p class="text--secondary">
      "Using HTML, CSS, and JavaScript, I want to prototype a wizard flow
      for authoring programming practice problems with GenAI. The interface should look and feel like Codespec's
      production website (https://www.codespec.org). Let's create the prototype step by step.
    </p>
    <p class="text--secondary">
      Start by retrieving Codespec's stylesheet and JavaScript files, and saving them to a folder on my computer. Link to them from an index.html file in the same folder. You can create boilerplate HTML structure (head, body, main) but nothing else yet."
    </p>
  </div>
  <img src="/assets/images/codespec/codespec-claude-reveal.png" class="w-100" alt="" />
</div>

<div class="mb-4">
  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar>Validate the Redesign</h2>
    <p class="text--secondary">
      Once the prototype was complete, I went back to the researcher I first interviewed and asked them to click through it. Along the way I prompted them to share their first impressions of each step.
    </p>
    <p class="text--secondary">
      Qualitative feedback indicated the redesign met the primary goals of:
    </p>
    <p class="text--secondary mt-0">
      A. more clearly showing instructors where they're at in the overall creation flow
    </p>
    <p class="text--secondary mt-0">
      B. balancing efficiency and quality control in the GenAI-powered authoring process
    </p>
    <p class="text--secondary mt-0">
      C. more clearly guiding instructors to the appropriate next step
    </p>
  </div>
  <img src="/assets/images/codespec/codespec-new-problem--before-after.png" class="w-100" alt="" />
</div>

<div class="mw-700 mx-auto mb-4">
  <h2 data-sidebar>Better collaboration, faster authoring</h2>
  <p class="text--secondary">
    Using informal interviewing, user-centered design thinking, AI-powered prototyping, and usability testing, I transformed a confusing content authoring flow into a guided collaboration experience between computer science instructors and GenAI.
  </p>
</div>
<div class="mb-4" id="codespec-prototype">
  <div class="prototype-container" style="position: relative;">
    <!-- Dark background to prevent white flash -->
    <div style="position: absolute; top: 0; left: 0; right: 0; height: 600px; background: #171e32; border-radius: 8px; z-index: 1;"></div>
    <iframe src="https://www.nathanmagyar.com/codespec-gen-ai-problems/" width="100%" height="600" frameborder="0" style="border-radius: 8px; position: relative; z-index: 2;"></iframe>
  </div>
  <p class="text--small text--secondary mt-1 mw-700 mx-auto">
    <em>Note: This is a functional prototype built with HTML, CSS, and JavaScript to demonstrate the user interface and flow.</em>
  </p>
</div>
