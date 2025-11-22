---
layout: splash
title: "Esteban Flores"
author_profile: false
---
<!-- ====== INTRO SECTION ====== -->
<div style="display:flex; flex-wrap:wrap; gap:3rem; margin:2rem 0; align-items:flex-start;">
  <!-- LEFT: 2-COLUMN IMAGE GRID -->
  <div style="
      display:grid;
      grid-template-columns: 320px 0px;
      grid-template-rows: 1fr 1fr;
      column-gap: 1rem;
      row-gap: 1rem;   /* <-- FIXED */
      align-items:stretch;
    ">
    <!-- Headshot spans both rows of column 1 -->
    <img src="{{ '/assets/images/headshot.jpg' | relative_url }}"
         style="grid-row: 1 / span 2; width:100%; border-radius:8px; object-fit:cover;">
    <!-- Top-right image (top-aligned) -->
    <img src="{{ '/assets/images/image6.png' | relative_url }}"
         style="width:100%; border-radius:8px; object-fit:cover;">
    <!-- Bottom-right image (bottom-aligned) -->
    <img src="{{ '/assets/images/image8.jpg' | relative_url }}"
         style="width:100%; border-radius:8px; object-fit:cover;">
  </div>
  <!-- RIGHT COLUMN — TEXT -->
  <div style="flex:1; min-width:300px;">
    <h2 style="margin-top:0;">Robotics Student at ETH Zurich</h2>
    <p>
      Robotics MS student at ETH Zurich focused on autonomy, simulation, and 
      sensing for safer and more efficient real-world systems.
    </p>
    <p>
      Former GT CRAB Lab researcher(locomotion, autonomy) and Zipline Intern(test, state estimation) looking for internship and research opportunities.   
    </p>
    <p>
      <strong>Nationality:</strong> U.S. Citizen <br>
      <strong>Interests:</strong> Autonomy, Simulation, State Estimation, Planning
    </p>
  </div>
</div>
---

## Autonomy and Locomotion of multilegged-robots
Undergraduate research in the Complex Rheology and Biomechanics Lab at the Georgia Institute of Technology focused on sensing and control of centipede-like robots 
 <video controls style="width:90%; display:block; margin:1rem auto;">
    <source src="{{ '/assets/videos/no_fall_recovery_web_cfr.mp4' | relative_url }}" type="video/mp4">
  </video>
<div class="feature__wrapper">
<!-- CARD 1: Tactile Sensing -->
<div class="feature__item" style="display:flex; flex-direction:column;">
  <h3 class="feature__title">Tactile Sensing Locomotion</h3>

  <div style="flex:0 0 auto;">
    <video controls style="width:100%; display:block; margin:0.5rem auto;">
      <source src="{{ '/assets/videos/iros_antenna_sensing_2x_web.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>

  <p style="margin-top:auto;">
    Closed-loop locomotion using tactile antenna sensors to detect obstacles and modulate 
    the robot’s gait in real time.
  </p>
</div>

<!-- CARD 2: IMU Fall Recovery -->
<div class="feature__item" style="display:flex; flex-direction:column;">
  <h3 class="feature__title">Automatic Fall Recovery</h3>

  <div style="flex:0 0 auto;">
    <video controls style="width:100%; display:block; margin:0.5rem auto;">
      <source src="{{ '/assets/videos/fall_recovery_web.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>

  <p style="margin-top:auto;">
    Onboard IMU signals are used to detect unstable body configurations and trigger fall 
    recovery maneuvers, improving robustness on rough terrain.
  </p>
</div>

<!-- CARD 3: Simulation & Design -->
<div class="feature__item" style="display:flex; flex-direction:column;">
  <h3 class="feature__title">Simulation & Robot Design</h3>

  <div style="flex:0 0 auto;">
    <img 
      src="{{ '/assets/images/IMG_7406.jpeg' | relative_url }}"
      alt="MuJoCo simulation"
      style="width:100%; display:block; margin:0.5rem auto;"
    >
  </div>

  <p style="margin-top:auto;">
    Built a 5-segment MuJoCo model of a multilegged undulatory robot, including XML model 
    definition, tuning, and Python controllers that reproduce physical gaits for sim-to-real studies.
  </p>
</div>
</div>
<!-- # **Autonomy Experiments** -->

<!-- ## **Tactile Sensing Based Locomotion**
<div style="margin-bottom:2rem;">
<video controls style="width:100%; display:block; margin:0 auto;">
  <source src="{{ '/assets/videos/iros_antenna_sensing_2x_web.mp4' | relative_url }}" type="video/mp4">
</video>
</div>

## **IMU-Based Fall Recovery**
<div style="margin-bottom:2rem;">
<video controls style="width:100%; display:block; margin:0 auto;">
  <source src="{{ '/assets/videos/fall_recovery_web.mp4' | relative_url }}" type="video/mp4">
</video>
</div>

--- -->

# **Georgia Tech Solar Racing**
Mechanical lead of new multi-occupant, semi-monocoque fully solar powered vehicle designed to race in the American Solar Challenge and Formula Sun Grand Prix. 
<img 
  src="{{ '/assets/images/image6.png' | relative_url }}"
  alt="GT Solar Rendering"
  style="width:70%; display:block; margin:0.5rem auto;">

<!-- TWO-COLUMN LAYOUT FOR THE CARDS -->
<div style="
  display:flex;
  flex-wrap:wrap;
  gap:2rem;
  margin-top:1.5rem;
">

  <!-- CARD LEFT -->
  <div style="flex:1; min-width:280px;">
    <h3 class="feature__title">Composite Material Testing</h3>
    <img 
      src="{{ '/assets/images/image5.jpg' | relative_url }}"
      style="width:100%; border-radius:6px; margin:0.5rem 0;"
    >
    <p>
      Hands-on testing, analysis, and modelling of composite layups for structural performance 
      and manufacturability in solar vehicle frames.
    </p>
  </div>

  <!-- CARD RIGHT -->
  <div style="flex:1; min-width:700px;">
    <h3 class="feature__title">Mechanical Design</h3>
    <img 
      src="{{ '/assets/images/image9.png' | relative_url }}"
      style="width:100%; border-radius:6px; margin:0.5rem 0;"
    >
    <p>
      Design and structural FEA of key vehicle components for crash, performance, and weight optimization. 
    </p>
  </div>

<!-- </div> -->


</div>

---

<div style="text-align:center; margin-top:3rem;">
  <a href="{{ '/assets/cv.pdf' | relative_url }}" class="btn btn--primary btn--large">Download CV (PDF)</a>
  &nbsp;&nbsp;
  <a href="{{ '/projects/' | relative_url }}" class="btn btn--light-outline btn--large">Projects</a>
</div>