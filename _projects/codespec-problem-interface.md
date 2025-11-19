---
supertitle: Codespec
title: Designing and building a scaffolded learning experience for novice programmers
permalink: projects/codespec-problem-interface/
project_url: https://www.codespec.org/
tagline: A computer science (CS) education researcher and I created a web application that allowed learners to solve coding problems using 5 research-based problem types of increasing difficulty. CS educators affirmed the tool’s pedagogical potential and learners praised the scaffolded design. 
overview: "In 2021, there were two ways to practice programming online: block-based editors or writing the code from scratch. No platform successfully bridged the gap between these two modes. <br><br>Academic research confirmed “current introductory computer programming instruction and assessments may fail to scaffold the acquisition of [programming skills” [14], especially when it came to serving both novice and experienced learners with the same tool. <br><br>There was no one-size-fits-all solution. <br><br>So, a computer science (CS) education researcher and I created a web application that allowed learners to solve coding problems using 5 research-based problem types of increasing difficulty. <br><br>CS educators affirmed the tool’s pedagogical potential and learners praised the scaffolded design."
where: After winning first prize and $10,000 at the 2021 University of Michigan Learning Levers competition, we continued to develop the tool at Carnegie Mellon University (2022-2024).
role: As the sole designer and lead developer, I partnered with an academic researcher to <strong class="text--black">design 705 interfaces</strong> (186 Django templates and 519 Vue.js components) and <strong class="text--black">build 486 backend endpoints</strong> (spanning authentication, course management, problem authoring, administrative tools, and a comprehensive REST API). 
order: 2
featured: true
cover_image: /assets/images/codespec/problem-interface/faded-parsons.gif
read_more: []
prototype_id: ""
published: true
---


<div class="mb-4">
    <div class="mw-700 mx-auto mb-4">
      <h2 data-sidebar>Five Research-Based Problem Types</h2>
      <p class="text--secondary">
        Prior computer science education research served as the foundation for 
        the 5 problem types we sought to combine, each with their own advantages 
        and disadvantages.
      </p>
      <h3 class="mb-0">Pseudocode</h3>
      <p class="text--secondary mt-point-five">
        Solving a problem using plain English blocks that represent the underlying code.
      </p>
      <img src="/assets/images/codespec/problem-interface/pseudocode.gif" class="w-100 rounded" alt />
      <ul class="text--secondary">
        <li><p class="my-0"><strong class="text--black">Strength:</strong> planning a solution ahead of time reduing cognitive load for learners [16]</p></li>
        <li><p class="my-0"><strong class="text--black">Weakness:</strong> advanced learners may find these exercises pointless for easy problems</p></li>
      </ul>
      <h3 class="mb-0">Parsons (Code Blocks)</h3>
      <p class="text--secondary mt-point-five">Solving a problem using mixed-up code blocks</p>
      <img src="/assets/images/codespec/problem-interface/parsons.gif" class="w-100 rounded" alt />
      <ul class="text--secondary">
        <li><p class="my-0"><strong class="text--black">Strength:</strong> allows learners to focus on concepts instead of syntax. Block-based problems have also been found to maximize engagement [5, 15]</p></li>
        <li><p class="my-0"><strong class="text--black">Weakness:</strong> learners may struggle if the expected solution doesn't match their own mental model</p></li>
      </ul>
      <h3 class="mb-0">Faded Parsons (Fill-in-the-Blank Blocks)</h3>
      <p class="text--secondary mt-point-five">Solving a problem using mixed-up code blocks with blanks</p>
      <img src="/assets/images/codespec/problem-interface/faded-parsons.gif" class="w-100 rounded" alt />
      <ul class="text--secondary">
        <li><p class="my-0"><strong class="text--black">Strength:</strong> these exercises have been found to be "significantly more effective for teaching pattern comprehension and pattern application over code-writing and code-tracing exercises"</p></li>
        <li><p class="my-0"><strong class="text--black">Weakness:</strong> expected blank values may not match learner's mental models</p></li>
      </ul>
      <h3 class="mb-0">Fix Code</h3>
      <p class="text--secondary mt-point-five">Solving a problem by fixing errors in buggy code</p>
      <img src="/assets/images/codespec/problem-interface/fix-code.gif" class="w-100 rounded" alt />
      <ul class="text--secondary">
        <li><p class="my-0"><strong class="text--black">Strength:</strong> provides opportunities to practice code reading and code tracing</p></li>
        <li><p class="my-0"><strong class="text--black">Weakness:</strong> error messages may be unintuitive and/or intimidating to novice learners</p></li>
      </ul>
      <h3 class="mb-0">Write Code</h3>
      <p class="text--secondary mt-point-five">Writing code from scratch</p>
      <img src="/assets/images/codespec/problem-interface/write-code.gif" class="w-100 rounded" alt />
      <ul class="text--secondary">
        <li><p class="my-0"><strong class="text--black">Strength:</strong> allows learners to use total creative freedom to solve the problem</p></li>
        <li><p class="my-0"><strong class="text--black">Weakness:</strong> greatest risk for syntax issues (forgetting a colon at the end of a function), semantic errors (using the wrong data type), or typos (misspelling a variable name)</p></li>
      </ul>
    </div>
  </div>

  <div class="mw-700 mx-auto mb-4">
    <h2 data-sidebar>Our Value Proposition: Strong Scaffolding</h2>
    <p class="text--secondary">
      I analysed 7 competitor block-based programming practice platforms. None of them supported a fluid progression of problem solving modes from pseudocode to writing code from scratch, confirming the uniqueness of our offering.
    </p>
    <img src="/assets/images/codespec/comparative-analysis/cover.png" alt class="w-100 rounded" />
  </div>

  <div class="mb-4">
    <div class="mw-700 mx-auto mb-4">
      <h2 data-sidebar>Prioritizing Learner Agency Through Tab-Based Design</h2>
      <p class="text--secondary mb-4">I explored several options for combining the 5 problem types into 1 learning experience:</p>
      <p class="text--secondary"><strong class="text--black">Alternating problem types</strong> - learners would see and solve each problem type 1 at a time in order to complete the overall exercise.</p>
      <img src="/assets/images/codespec/tabs/codespec-tabs--one-option.png" alt class="w-100 rounded" />
      <ul class="text--secondary mb-4">
        <li>
          <p class="my-0">
            <strong class="text--black">Pros:</strong> Least cluttered UI, kept learners focused on the material, avoides having to name the problem types (which could result in unfamiliar labels)
          </p>
        </li>
        <li>
          <p class="my-0">
            <strong class="text--black">Cons:</strong> Took away all agency from the learner and potentially increased frustration, forcing beginners to attempt problem types that were too difficult and advanced learners to complete trivial exercises
          </p>
        </li>
      </ul>
      <p class="text--secondary"><strong class="text--black">Dropdown toggle</strong> - learners would use a dropdown to switch between modes</p>
      <img src="/assets/images/codespec/tabs/codespec-tabs--dropdown.png" alt class="w-100 rounded" />
      <ul class="text--secondary mb-4">
        <li><p class="my-0"><strong class="text--black">Pros:</strong> Minimized additional controls in the UI, provided learners complete agency over which problem types to attempt</p></li>
        <li><p class="my-0"><strong class="text--black">Cons:</strong> Only displayed the current problem type and obscured all possible options (learners may not notice the dropdown and miss the other choices), problem type labels such as "Parsons" are likely unfamiliar to many learners</p></li>
      </ul>
      <p class="text--secondary"><strong class="text--black">Problem type tabs</strong> - each problem type is displayed in the interface, from easiest to hardest (left to right)</p>
      <img src="/assets/images/codespec/tabs/codespec-tabs--tabs.png" alt class="w-100 rounded" />
      <ul class="text--secondary mb-4">
        <li><p class="my-0"><strong class="text--black">Pros:</strong> Provided complete agency to learners, displayed all options at once, minimized clicks required to change the problem type</p></li>
        <li><p class="my-0"><strong class="text--black">Cons:</strong> Potential for unfamiliar tab labels, busiest/most cluttered interface that could be overwhelming to some users</p></li>
      </ul>
      <p class="text--secondary">
      My co-founder and I ultimately chose the tab-based design because it potentially offered the greatest learner agency, clearest display of all options, and quickest way to switch between problem types.
      </p>
    </div>
  </div>

  <div class="mb-4">
    <div class="mw-700 mx-auto mb-4">
      <h2 data-sidebar>1- vs 2-Column Layout: Why Not Both?</h2>
      <p class="text--secondary">
        Historically, Parsons problem libraries such as JSParsons have displayed block-based problems using a 2-column layout: mixed up blocks on the left and the solution area on the right.
      </p>
      <img src="/assets/images/codespec/codespec-two-column.png" alt class="w-100 rounded" />
      <p class="text--secondary"><strong class="text--black">Pros:</strong> Reduced drag-and-drop distance between the two work areas (offering the best usability/accessibility), afforded easy comparison between used and unused blocks</p>
      <p class="text--secondary"><strong class="text--black">Cons:</strong> Limited problem authors to short blocks or risked obscuring block content to learners</p>
      <p class="text--secondary">
        Given the limitations of the traditional 2-column layout, I explored a single column version of block-based problem types.
      </p>
      <img src="/assets/images/codespec/codespec-single-column.png" alt class="w-100 rounded" />
      <p class="text--secondary"><strong class="text--black">Pros:</strong> Allowed for longer blocks without hiding any of the content, condensed unused block area kept drag-and-drop distance low</p>
      <p class="text--secondary"><strong class="text--black">Cons:</strong> Mixed up blocks are less scannable, interface may introduce vertical scrolling for long block-based solutions</p>
      <p class="text--secondary">
        Neither option seemed like a clear winner, so for the first round of usability testing I offered learners both options and the ability to switch between them.
      </p>
    </div>
  </div>

  <div class="mb-4">
    <div class="mw-700 mx-auto mb-4">
      <h2 data-sidebar>Usability Testing: Round 1 Insights</h2>
      <p class="text--secondary">
        I prepared a clickable prototype of the interface. My co-founder and I then tested it with 7 participants who ranged from novice programmers to PhD computer science education researchers.
      </p>
      <img src="/assets/images/codespec/codespec-ui-feedback.png" alt class="w-100 rounded" />
      <h3>What went well?</h3>
      <p class="text--secondary"><strong class="text--black">Grid lines support indentation:</strong> To reinforce the idea of indenting blocks, my co-founder encouraged use of a grid in the solution area, which appealed to participants.</p>
      <p class="text--extra-large p-3 bg-gray--light rounded"><em>
      "These gridlines are interesting, I guess they help you indent the [blocks] that you drag [and drop]."
      </em></p>
      <p class="text--secondary"><strong class="text--black">Strong preference for 1-column layout:</strong> 5/7 learners preferred the single column layout, as it afforded better readability of the code blocks, especially for longer solutions.</p>
      <p class="text--extra-large p-3 bg-gray--light rounded"><em>
      "I already couldn't see everything to the right. And now I can't even see everything all the way down. Like, I can't see everything. So it's hard to understand that code."</em></p>
      <h3>Where did the design fail?</h3>
      <p class="text--secondary"><strong class="text--black">Pseudocode indentation:</strong> Our design enforced proper order AND indentation for all block-based problem types, including pseudocode. But one participant pointed out:</p>
      <p class="text--extra-large p-3 bg-gray--light rounded"><em>
      "When I'm writing pseudocode, indentation doesn't matter quite as much."
      </em></p>
      <p class="text--secondary">We decided to leave the indentation requirement despite this feedback, as my co-founder and I saw pedagogical value in getting learners to think about indentation earlier in their planning process.</p>
      <p class="text--secondary"><strong class="text--black">Unfamiliar tab names:</strong> As expected, participants struggled to understand the "Parsons" and "Faded Parsons" tab names.</p>
      <p class="text--extra-large p-3 bg-gray--light rounded"><em>
      "I have no idea what [Parsons] means."
      </em></p>
      <p class="text--secondary">I proposed the plain language alternatives of "Blocks" and "Fill-in-the-Blank".</p>
  </div>

  <div class="mb-4">
    <div class="mw-700 mx-auto mb-4">
      <h2 data-sidebar>Implementing Accessible Drag-and-Drop</h2>
      <video src="/assets/images/codespec/codespec-keyboard-ux.mov" class="d-block w-100 rounded--mega object-fit--contain" alt="Problem interface navigationvia keyboard" autoplay muted loop playsinline></video>
      <p class="text--secondary">
        One of the biggest technical challenges I faced when building the interface was making the problem interface keyboard accessible. <a href="https://www.npmjs.com/package/vuedraggable" class="text--link">Vuedraggable</a>, the NPM package I selected for the primary drag-and-drop interaction, did not offer an out-of-the-box solution for keyboard users.
      </p>
      <p class="text--secondary">So I modeled a custom approach after the recommendations found in <a href="https://medium.com/salesforce-ux/4-major-patterns-for-accessible-drag-and-drop-1d43f64ebf09" class="text--link">"4 Major Patterns for Accessible Drag and Drop"</a>. Users press the <code class="text--code">space bar</code> to select a block, <code class="text--code">enter</code> to move it to the solution grid, <code class="text--code">delete</code> to move a solution block, <code class="text--code">arrow keys</code> to move a block around the solution grid, and <code class="text--code">space bar</code> again to release it.</p>
  </div>

  <div class="mb-4">
    <div class="mw-700 mx-auto mb-4">
      <h2 data-sidebar>Coming Soon: More Development Highlights</h2>
      <p class="text--secondary">
        I'm still putting this case study together. Up next I'll talk about:
      </p>
      <ul>
        <li>
          <p class="text--secondary">Designing the Parsons problem data architecture</p>
        </li>
        <li>
          <p class="text--secondary">Tracking problem solving activity with click stream analytics</p>
        </li>
        <li>
          <p class="text--secondary">Developing an intelligent hint algorithm</p>
        </li>
      </ul>
      <p class="text--secondary">
        Thanks for reading!
      </p>
  </div>