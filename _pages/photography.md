---
layout: single
title: "Photography"
permalink: /photography/
author_profile: true
---

<style>
  .photo-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 1.5rem;
    padding: 1rem 0;
  }
  .photo-item {
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    cursor: pointer;
  }
  .photo-item:hover {
    transform: translateY(-5px) scale(1.03);
    box-shadow: 0 8px 25px rgba(0,0,0,0.15);
  }
  .photo-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }
</style>

<div class="photo-gallery">
  
  <div class="photo-item">
    <img src="/assets/images/photography/photo-01.jpg" alt="你的照片描述 1">
  </div> 
  
  </div>
