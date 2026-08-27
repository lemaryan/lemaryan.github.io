---
title: "sketches"
permalink: /drawings/
author_profile: false
---

<style>
/* Experience page */

.experience-container {
  width: 100%;
  margin: 30px 0;
}

.experience-box {
  width: 100%;
  box-sizing: border-box;
  padding: 28px 32px;
  margin-bottom: 22px;

  /* Matches your site's background */
  background-color: transparent;

  border: 1px solid rgba(0, 0, 0, 0.12);
  border-radius: 12px;

  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.experience-box:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
}

.experience-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 20px;
  margin-bottom: 12px;
}

.experience-title {
  font-size: 20px;
  font-weight: 700;
  color: inherit;
  margin: 0;
}

.experience-date {
  font-size: 14px;
  color: #888;
  white-space: nowrap;
}

.experience-description {
  font-size: 16px;
  line-height: 1.65;
  color: inherit;
}

.experience-description p {
  margin: 4px 0;
}

/* Mobile */
@media screen and (max-width: 700px) {
  .experience-box {
    padding: 22px;
  }

  .experience-header {
    display: block;
  }

  .experience-date {
    display: block;
    margin-top: 5px;
  }
}
</style>


<div class="experience-container">

  <!-- Descartes Learning Club -->
  <div class="experience-box">
    <div class="experience-header">
      <h2 class="experience-title">
        Descartes Learning Club
      </h2>

      <div class="experience-date">
        Fall 2026
      </div>
    </div>

    <div class="experience-description">
      <p>Taught kids fun math</p>
      <p>One of my fav jobs :)</p>
    </div>
  </div>


  <!-- nano@stanford -->
  <div class="experience-box">
    <div class="experience-header">
      <h2 class="experience-title">
        nano@stanford
      </h2>

      <div class="experience-date">
        Summer 2024
      </div>
    </div>

    <div class="experience-description">
      <p>Monitored a lot of cool machines</p>
      <p>Made the AFM standard operating procedures</p>
      <p>For the lab name that will never be said. go bears!!</p>
    </div>
  </div>


  <!-- Medical Scribe -->
  <div class="experience-box">
    <div class="experience-header">
      <h2 class="experience-title">
        Medical Scribe, Dr. Ngoc Nguyen
      </h2>

      <div class="experience-date">
        Summer 2023
      </div>
    </div>

    <div class="experience-description">
      <p>Documented ophthalmology diagnoses, medications, and procedures</p>
      <p>learned so many many medical acronyms...</p>
    </div>
  </div>

</div>

