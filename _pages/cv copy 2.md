---
layout: archive
title: "CV"
permalink: /cv_old/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- Education Section -->
<div style="background: #f8f9fa; border-radius: 12px; box-shadow: 0 2px 10px rgba(0,0,0,0.07); padding: 24px 32px; margin-bottom: 32px; border-left: 6px solid #1a73e8;">
  <div style="display: flex; align-items: center; margin-bottom: 12px;">
    <i class="fas fa-graduation-cap" style="color: #1a73e8; font-size: 1.5em; margin-right: 12px;"></i>
    <h2 style="margin: 0; color: #1a73e8;">Education</h2>
  </div>
  <h3 style="margin-top: 12px;">Bachelor of Technology (B.Tech.)</h3>
  <p style="margin: 0 0 4px 0;"><em>Computer Science and Engineering</em></p>
  <p style="margin: 0 0 4px 0;"><strong>Indian Institute of Technology Dharwad (IITDh)</strong></p>
  <p style="margin: 0;"><span style="background: #e3f2fd; border-radius: 4px; padding: 2px 8px; font-weight: bold;">GPA: 9.5 / 10</span></p>
</div>

<!-- Research Experience Section -->
<div style="background: #fff; border-radius: 12px; box-shadow: 0 2px 10px rgba(0,0,0,0.07); padding: 24px 32px; margin-bottom: 32px; border-left: 6px solid #43b581;">
  <div style="display: flex; align-items: center; margin-bottom: 12px;">
    <i class="fas fa-flask" style="color: #43b581; font-size: 1.5em; margin-right: 12px;"></i>
    <h2 style="margin: 0; color: #43b581;">Research Experience</h2>
  </div>

  <!-- Pre-Doctoral Research Fellow -->
  <div style="margin-bottom: 20px;">
    <h3 style="margin-top: 0;">Pre-Doctoral Research Fellow</h3>
    <p style="margin: 0 0 4px 0;"><em>Microsoft Research India (MSRI)</em> <span style="color: #888;">| July 2024 – Present</span></p>
    <p style="margin: 0 0 8px 0;"><strong>Mentors:</strong> Dr. Debopam Bhattacherjee, Dr. Rohan Gandhi, Dr. Anjaly Prayil</p>
    <h4 style="margin-bottom: 8px;">Projects:</h4>
    <ul style="margin: 0 0 0 16px;">
      <li>
        <strong>Output Length Prediction for LLMs</strong>
        <ul>
          <li>Designed predictors for output sequence length using query context.</li>
          <li>Enabled more efficient routing, scheduling, and memory management in LLM serving pipelines.</li>
          <li>Evaluated predictors across multiple LLMs to ensure generalizability.</li>
        </ul>
      </li>
      <li>
        <strong>Dynamic Response Length Control</strong>
        <ul>
          <li>Built a system that dynamically adjusts response lengths under high GPU utilization.</li>
          <li>Reduced energy consumption while preserving information fidelity.</li>
          <li>Verified approach through large-scale experiments with real workloads.</li>
        </ul>
      </li>
    </ul>
  </div>

  <!-- Undergraduate Research Assistant -->
  <div style="margin-bottom: 20px;">
    <h3 style="margin-top: 0;">Undergraduate Research Assistant</h3>
    <p style="margin: 0 0 4px 0;"><em>Indian Institute of Technology Dharwad (IITDh)</em> <span style="color: #888;">| April 2022 – May 2024</span></p>
    <p style="margin: 0 0 4px 0;">Affiliated to <a href="https://futuregnetworks.iitdh.ac.in/home" target="_blank" style="color: #1a73e8;">Future Generation Lab</a></p>
    <p style="margin: 0 0 8px 0;"><strong>Mentor:</strong> <a href="https://scholar.google.com/citations?user=X-yZFQkAAAAJ&hl=en" target="_blank" style="color: #1a73e8;">Dr. Koteswararao Kondepu</a></p>
    <h4 style="margin-bottom: 8px;">Projects:</h4>
    <ul style="margin: 0 0 0 16px;">
      <li>
        <strong>Energy Analysis of different 5G RAN Architectures</strong>
        <ul>
          <li>Assisted in deploying ORAN architectures: Monolithic, Dis-aggregated, and CUPS.</li>
          <li>Investigated energy consumption for RAN and UE using S-tui and Scaphandre.</li>
          <li>Found a 19.3% energy increase when UEs scaled from 1 to 10 in disaggregated RAN.</li>
        </ul>
      </li>
      <li>
        <strong>Resource Allocator</strong>
        <ul>
          <li>Developed a MERN stack application for remote resource allocation using JWT sessions.</li>
          <li>Used Docker to create containers with specified resources for users.</li>
          <li>Built an open-source FPGA toolchain integrated into the platform.</li>
        </ul>
      </li>
      <li>
        <strong>Edge Assisted Autonomous Surveillance using UAVs</strong>
        <ul>
          <li>Annotated 2000+ images to prepare a custom dataset for object detection.</li>
          <li>Trained YOLOv3 & YOLOv5 models on custom dataset and containerized them.</li>
          <li>Developed scripts to control UAVs based on model inferences.</li>
        </ul>
      </li>
      <li>
        <strong>Automated Controlling Mechanism</strong>
        <ul>
          <li>Implemented Grafana + Kafka framework to alert on CPU and memory over-utilization.</li>
          <li>Automated Slack alerts at 70% utilization; auto-intervention at 80% usage.</li>
        </ul>
      </li>
    </ul>
  </div>

  <!-- Mitacs Globalink Research Intern -->
  <div>
    <h3 style="margin-top: 0;">Mitacs Globalink Research Intern</h3>
    <p style="margin: 0 0 4px 0;"><em>Lakehead University, Ontario, Canada</em> <span style="color: #888;">| May 2023 – July 2023</span></p>
    <p style="margin: 0 0 8px 0;"><strong>Mentor:</strong> Dr. Shafiqul Hai</p>
    <h4 style="margin-bottom: 8px;">Projects:</h4>
    <ul style="margin: 0 0 0 16px;">
      <li>
        <strong>Hardware-Software Codesign of a Convolutional Neural Network</strong>
        <ul>
          <li>Designed CNN for MNIST digits with 98% accuracy; optimized for 1M pixel images in 20ms.</li>
          <li>Implemented block circulant matrix + 16-point FFT to reduce FPGA logical elements by 40%, maintaining 96.89% accuracy.</li>
          <li>Co-authored journal paper: "Power Efficient CNN using Pipelined FFT Architecture" accepted at <em>Embedded Systems Letters</em>.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>



  
<h2>Technical Skills</h2>
<ul style="list-style-type:none; padding-left:0;">
  <li><strong>Programming Languages:</strong> <span style="color:#333;">C, C++, Python, Bash</span></li>
  <li><strong>Software Stacks:</strong> <span style="color:#333;">Container environments (Docker, Kubernetes), LLM serving (vLLM), Storage systems (Azure Blob Storage, MongoDB)</span></li>
  <li><strong>Hardware Platforms:</strong> <span style="color:#333;">GPUs, FPGAs, CPUs</span></li>
  <li><strong>Tools &amp; Machine Learning Frameworks:</strong> <span style="color:#333;">Jekyll, Git, Keras, TensorFlow</span></li>
  <li><strong>Back-end Technologies:</strong> <span style="color:#333;">MySQL, MongoDB, Node.js</span></li>
  <li><strong>Front-end Technologies:</strong> <span style="color:#333;">HTML, CSS, JavaScript, React.js</span></li>
</ul>


Publications
======
{% assign sorted_publications = site.publications | sort: 'name' | reverse %}
{% for publication in sorted_publications %}
  {% include publication-card.html title=publication.title link=publication.link description=publication.description venue=publication.venue %}
{% endfor %}

Volunteer
=========

**Teaching Assistant**  
*Indian Institute of Technology Dharwad (IITDh)*  
Prepared assignments, assisted in labs, and supported students with doubt clarification.

- **CS-103: Data Structures and Algorithms** — *Spring 2024*  
  Instructors: [Prof. Dileep A. D](https://www.iitdh.ac.in/user-profile/dileep-d)., [Prof. Vandana Bharti](https://www.iitdh.ac.in/user-profile/vandana-bharti)  

- **CS-213: Software Systems Lab** — *Autumn 2023*  
  Instructor: [Prof. Koteswararao Kondepu](https://scholar.google.com/citations?user=X-yZFQkAAAAJ&hl=en)  

- **CS-102: Introduction to Programming in C & Python** — *Spring 2023*  
  Instructors: [Prof. Ramchandra Phawade](https://iitdh.ac.in/prb/), [Prof. Nikhil Hegde](https://hegden.github.io/), [Prof. Bharath B. N.](https://bharathbettagere.github.io/mywebpage/)





Certifications
======
* [Microsoft Global Hackathon 2024 Executive Challenge Winner](https://www.credly.com/badges/6819c675-44cb-403c-8fd9-9ad52771a74c)
* [Mitacs Internship completion certificate](https://drive.google.com/file/d/1uRjsQHKJ4J24tW7rNavE1DJTcGGA-owx/view?usp=drive_link)
* [Google TensorFlow Developer Certification](https://www.credential.net/dfc01baa-6c26-46b9-89a5-be29c3e13e6d#gs.38n1ct)
* [Coursera - Deep Learning Specialization](https://coursera.org/share/17cd396d4e13ed542ff91018697e562b)

Achievements
======
* 1st prize in hack for the industry track in Microsoft Global Hackathon, 2024
* Got selected for Google ML Bootcamp India.
* Received Conference Travel Grant and presented a paper at ANTS 2023, Jaipur, India.
* Received the esteemed Student Travel Grant Award at COMSNETS 2023.
* Secured an exceptional AP grade in Linear Algebra and Research and Development Courses.
* Secured 2nd place in DevHack Hackathon held by PARSEC 2024
* Secured 5th place in Alogostrike coding competition held by PARSEC 2023
* Qualified level-1 in Convolve - A pan IIT Hackathon
* Served as institute-level General Secretary during the 2021-2022 academic year.
* Student mentor at SMP, IIT dharwad


