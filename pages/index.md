---
layout: default
permalink: /
---

<!-- Quick About Me Section -->
<section class="row justify-content-center mt-5 mb-5">
  <div class="col-lg-4 col-md-6 text-center mt-4">
    <img src="{{ site.author.image }}" alt="{{ site.title }}"
      class="circle-image wow animated zoomIn"
      data-wow-delay=".1s"/>
  </div>
  <div class="col-lg-4 col-md-6 mt-4 align-items-center">
    <h1 class="pb-2 border-bottom"><b>{{ site.author.name }}</b></h1>
    <p class="mt-3">
      I am a <b>Full Stack Web Developer</b>, bringing up infrastructure
      to working condition and transforming specifications into source
      code.
    </p>
    <p>
      I also am capable of <b>Systems Design</b>, whipping up architectural
      plans for your solution needs.
    </p>
  </div>
</section>

<section class="mb-5">
  <h2>Featured Projects</h2>
  {% include projects/index.html %}
</section>

<section class="mb-5">
  <h2>Work Experience</h2>
  <div class="col mt-4">
    <div class="timeline-body bg-themed">
      <div class="timeline-item">
        <div class="content">
          <h2>Web Developer and DevOps Intern, LexMeet Incorporated</h2>
          <h6 class="date">Aug 2022 to Oct 2022</h6>
          <p>
            Initially I worked as a front-end developer intern, implementing
            an interface with a team of 3 students. I eventually took the
            role of leader, planning deliverables and guiding my teammates
            towards writing both effective and maintainable code. I also
            designed a multi-tenancy system architecture for one of their
            platforms, which was approved and I have built the foundations
            using Laravel, PostgreSQL, and Docker until the end of my
            internship as a DevOps intern.
          </p>
        </div>
      </div>
      <!-- Senior High School -->
      <div class="timeline-item">
        <div class="content">
          <h2>Freelance Web Developer</h2>
          <h6 class="date">2019 to present</h6>
          <p>
            I have both designed and implemented web applications for
            different clients, mostly using Django or PHP. My most
            recent commission involves working with the Manila Wrestling
            Federation on getting their  own website for showcasing the
            organization's activities and the propagation of PH
            Wrestling as a proper sport and entertainment point.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
