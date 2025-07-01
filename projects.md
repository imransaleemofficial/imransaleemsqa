---
title: Projects
permalink: /projects/
---

<style>
  .tabs { margin-bottom: 1rem; }
  .tab-button {
    padding: 0.5rem 1rem;
    margin-right: 0.5rem;
    cursor: pointer;
    background: #f0f0f0;
    border: none;
    border-radius: 4px;
  }
  .tab-button:hover { background: #e0e0e0; }
  .tab-content { display: none; }
  #zweidevs { display: block; } /* show Zweidevs by default */
</style>

<div class="tabs">
  <button class="tab-button" onclick="openTab('zweidevs')">Zweidevs Pvt Ltd</button>
  <button class="tab-button" onclick="openTab('acceltor')">Acceltor Ltd</button>
</div>

<div id="zweidevs" class="tab-content">
  
#### Practice Tool Ai  
**Description:** A site where students can learn English through AI mediums—Reading, Writing, Listening, Speaking test modules—and join live classes if available. Subscription-based platform.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** Next.js + Python  

---

#### Mental Edge AI  
**Description:** Mental Edge AI is an AI-driven cognitive performance platform designed to strengthen mental resilience and focus. It leverages adaptive machine-learning algorithms to deliver personalized brain-training exercises, mindfulness sessions, and real-time mood analyses. By learning from user interactions and biometric inputs (e.g., heart-rate variability), it fine-tunes recommendations—helping professionals, athletes, and students optimize productivity, reduce stress, and track well-being.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** Next.js + Python  

---

#### AAB Books App  
**Description:** An app where students of a particular school of thought can access all their books—a religious study platform.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** Flutter  

---

#### RGM Guru  
**Description:** A site where ship employees can view all details and perform calculations needed to navigate from one side of the sea to another.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** Next.js + Python  

</div>

<div id="acceltor" class="tab-content">
  
#### Dr. Mark Kohout – Completed  
**Description:** Surgery site where patients can contact Dr Kohout to book examinations and surgery dates.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** WordPress  

---

#### Tc Detailing UK – Completed  
**Description:** Car-detailing site where users can book appointments for car repairs and detailing.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** WordPress  

---

#### Fitgeeks – Completed  
**Description:** Food-ordering site for healthy meals, targeted at athletes, available near Fitgeeks restaurants.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** WordPress  

---

#### Major Tom – Completed  
**Description:** Portfolio site where Major Tom showcases his journey through space via 3D animations.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** WordPress + Custom JS (Node.js)  

---

#### MP3 – Development In Progress  
**Description:** Music-streaming site where users can enjoy and browse music.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** WordPress  

---

#### Manikiye Paris – Development In Progress  
**Description:** Salon-booking site with modern 3D animations.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** Webflow  

---

#### Professional Training Center – Development In Progress  
**Description:** E-learning site where users can purchase and access online training courses.  
- **Figma QA:** Design + Flows  
- **Site QA:** Design + Functionalities  
- **Technology Stack:** WordPress  

</div>

<script>
function openTab(tabId) {
  const contents = document.getElementsByClassName('tab-content');
  for (let i = 0; i < contents.length; i++) {
    contents[i].style.display = 'none';
  }
  document.getElementById(tabId).style.display = 'block';
}
</script>
