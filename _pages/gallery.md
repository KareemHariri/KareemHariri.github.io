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
   PhD Defense (2025)
  </h2>
  <div style="display: flex; justify-content: center;">
  <div style="display: flex; justify-content: center;">
    <blockquote class="twitter-tweet" data-media-max-width="560">
   <img src="/images/PhDDefense.jpg"
         alt="PhDDefense"
         class="what"
         onclick="openLightbox(this.src)">

  <p class="gallery-center" style="max-width:760px; margin:1.5rem auto 3rem auto;">
    <em>My colleagues and friends who supported me throughout my PhD journey



## CLEO Conference (2025)

<img src="{{ '/images/CLEO2025.jpg' | relative_url }}" alt="CLEO2025" style="width:1100px; height:auto; margin-left:65px;">


## APS March Meeting Conference (2025)

<img src="{{ '/images/APS2025.jpg' | relative_url }}" alt="APS2025" style="width:1100px; height:auto; margin-left:65px;">


## CLEO Conference (2024)

<img src="{{ '/images/CLEO2024.jpg' | relative_url }}" alt="CLEO2024" style="width:700px; height:auto; margin-left:275px;">


## Midwest Quantum Collaboratory (2023)

<img src="{{ '/images/MQC.jpg' | relative_url }}" alt="MQC" style="width:1100px; height:auto; margin-left:65px;">


## Information in a Photon Class (2022, tought by Saikat Guha)

<img src="{{ '/images/Saikat.jpg' | relative_url }}" alt="Saikat" style="width:1100px; height:auto; margin-left:65px;">


## IDQ's Winter School (2020)

<img src="{{ '/images/IDQwinterschool.jpg' | relative_url }}" alt="IDQwinterschool" style="width:1100px; height:auto; margin-left:65px;">

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
