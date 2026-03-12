---
layout: archive-full
title: "Gallery"
permalink: /gallery/
author_profile: false
sidebar: false
classes: wide
---

<style>
  .gallery-wrap {
    max-width: 1100px;
    margin: 0 auto;
  }

  .gallery-wrap {
    max-width: 750px;
    margin: 0 auto;
  }

  .gallery-center {
    text-align: center;
  }

  .gallery-row {
    display: flex;
    gap: 40px;
    align-items: center;
    margin: 60px 0;
  }

  .gallery-text {
    flex: 1;
    text-align: left;
  }

  .gallery-thumb {
    border-radius: 6px;
    cursor: zoom-in;
    display: block;
    height: auto;
  }

  .gallery-thumb.small {
    width: 220px;
  }

  .gallery-thumb.medium {
    width: 260px;
  }

  .gallery-thumb.large {
    width: 320px;
  }

  .gallery-thumb.poster {
    width: 420px;
  }

  .lightbox {
    display: none;
    position: fixed;
    z-index: 9999;
    inset: 0;
    background: rgba(0, 0, 0, 0.88);
    justify-content: center;
    align-items: center;
    padding: 30px;
  }

  .lightbox.open {
    display: flex;
  }

  .lightbox img {
    max-width: 92vw;
    max-height: 88vh;
    border-radius: 8px;
    box-shadow: 0 8px 30px rgba(0,0,0,0.35);
  }

  .lightbox-close {
    position: absolute;
    top: 18px;
    right: 24px;
    font-size: 34px;
    line-height: 1;
    color: white;
    cursor: pointer;
    user-select: none;
  }

  @media (max-width: 900px) {
    .gallery-row {
      flex-direction: column;
      text-align: center;
    }

    .gallery-text {
      text-align: center;
    }
  }
</style>

  <div class="gallery-wrap">

  <h2 class="gallery-center" style="margin-bottom: 1rem;">
   RLE Photoshoot (2026)
  </h2>
  <div style="display: flex; justify-content: center;">
  </div>
   <img src="/images/Vladan postdocs.jpg"
         alt="Vladan postdocs"
         class="what"
         onclick="openLightbox(this.src)">

  <p class="gallery-center" style="max-width:760px; margin:1.5rem auto 3rem auto;">
      <em>Postdoctoral Researchers of the Experimental Atomic Physics Group </em><br>
 </p>

<div class="gallery-wrap">

  <h2 class="gallery-center" style="margin-bottom: 1rem;">
   PhD Defense (2025)
  </h2>
  <div style="display: flex; justify-content: center;">
  </div>
   <img src="/images/PhDDefense.jpg"
         alt="PhDDefense"
         class="what"
         onclick="openLightbox(this.src)">

  <p class="gallery-center" style="max-width:760px; margin:1.5rem auto 3rem auto;">
    <em>My colleagues and friends who supported me throughout my PhD journey</em><br>
 </p>

<div class="gallery-wrap">

  <h2 class="gallery-center" style="margin-bottom: 1rem;">
   CLEO Conference (2025)
  </h2>
  <div style="display: flex; justify-content: center;">
  </div>
   <img src="/images/CLEO2025.jpg"
         alt="CLEO2025"
         class="what"
         onclick="openLightbox(this.src)">

  <p class="gallery-center" style="max-width:760px; margin:1.5rem auto 3rem auto;">


<div class="gallery-wrap">

  <h2 class="gallery-center" style="margin-bottom: 1rem;">
   APS March Meeting Conference (2025)
  </h2>
  <div style="display: flex; justify-content: center;">
  </div>
   <img src="/images/APS2025.jpg"
         alt="APS2025"
         class="what"
         onclick="openLightbox(this.src)">

  <p class="gallery-center" style="max-width:760px; margin:1.5rem auto 3rem auto;">


<div class="gallery-wrapp">

  <h2 class="gallery-center" style="margin-bottom: 1rem;">
   CLEO Conference (2024)
  </h2>
  <div style="display: flex; justify-content: center;">
  </div>
   <img src="/images/CLEO2024.jpg"
         alt="CLEO2024"
         class="what"
         onclick="openLightbox(this.src)">

  <p class="gallery-center" style="max-width:460px; margin:1.5rem auto 3rem auto;">



<div class="gallery-wrap">

  <h2 class="gallery-center" style="margin-bottom: 1rem;">
   Midwest Quantum Collaboratory (2023)
  </h2>
  <div style="display: flex; justify-content: center;">
  </div>
   <img src="/images/MQC.jpg"
         alt="MQC"
         class="what"
         onclick="openLightbox(this.src)">

  <p class="gallery-center" style="max-width:760px; margin:1.5rem auto 3rem auto;">


<div class="gallery-wrap">

  <h2 class="gallery-center" style="margin-bottom: 1rem;">
   Information in a Photon Class (2022, tought by Saikat Guha)
  </h2>
  <div style="display: flex; justify-content: center;">
  </div>
   <img src="/images/Saikat.jpg"
         alt="Saikat"
         class="what"
         onclick="openLightbox(this.src)">

  <p class="gallery-center" style="max-width:760px; margin:1.5rem auto 3rem auto;">


  <div class="gallery-wrap">

  <h2 class="gallery-center" style="margin-bottom: 1rem;">
   IDQ's Winter School (2020)
  </h2>
  <div style="display: flex; justify-content: center;">
  </div>
   <img src="/images/IDQwinterschool.jpg"
         alt="IDQwinterschool"
         class="what"
         onclick="openLightbox(this.src)">

  <p class="gallery-center" style="max-width:760px; margin:1.5rem auto 3rem auto;">


<div id="lightbox" class="lightbox" onclick="closeLightbox(event)">
  <span class="lightbox-close" onclick="closeLightbox(event)">&times;</span>
  <img id="lightbox-img" src="" alt="Expanded gallery image">
</div>

<script>
  function openLightbox(src) {
    document.getElementById('lightbox-img').src = src;
    document.getElementById('lightbox').classList.add('open');
    document.body.style.overflow = 'hidden';
  }

  function closeLightbox(event) {
    if (
      event.target.id === 'lightbox' ||
      event.target.classList.contains('lightbox-close')
    ) {
      document.getElementById('lightbox').classList.remove('open');
      document.getElementById('lightbox-img').src = '';
      document.body.style.overflow = '';
    }
  }

  document.addEventListener('keydown', function (event) {
    if (event.key === 'Escape') {
      document.getElementById('lightbox').classList.remove('open');
      document.getElementById('lightbox-img').src = '';
      document.body.style.overflow = '';
    }
  });
</script>
