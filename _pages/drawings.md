---
title: "sketches"
permalink: /drawings/
author_profile: false
---

<style>
.drawings-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  width: 100%;
}

.drawing-box {
  width: 100%;
  height: 350px;
  border-radius: 12px;
  overflow: hidden;
  background-color: transparent;
}

.drawing-box img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform 0.2s ease;
}

.drawing-box:hover img {
  transform: scale(1.03);
}

/* Tablet */
@media screen and (max-width: 800px) {
  .drawings-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Phone */
@media screen and (max-width: 500px) {
  .drawings-grid {
    grid-template-columns: 1fr;
  }
}
</style>


<div class="drawings-grid">

  <div class="drawing-box">
    <img src="/images/drawings/drawing1.jpg" alt="Drawing 1">
  </div>

  <div class="drawing-box">
    <img src="/images/drawings/drawing2.jpg" alt="Drawing 2">
  </div>

  <div class="drawing-box">
    <img src="/images/drawings/drawing3.jpg" alt="Drawing 3">
  </div>

  <div class="drawing-box">
    <img src="/images/drawings/drawing4.jpg" alt="Drawing 4">
  </div>

  <div class="drawing-box">
    <img src="/images/drawings/drawing5.jpg" alt="Drawing 5">
  </div>

  <div class="drawing-box">
    <img src="/images/drawings/drawing6.jpg" alt="Drawing 6">
  </div>

</div>
