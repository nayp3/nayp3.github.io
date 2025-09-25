---
layout: default
title: Portfolio
---


<style>
.portfolio-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.portfolio-item {
  position: relative;
  width: 300px;
  height: 200px;
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

.portfolio-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform 0.3s ease;
}

.portfolio-item:hover img {
  transform: scale(1.05);
}

.portfolio-caption {
  position: absolute;
  bottom: 0;
  background: rgba(0, 0, 0, 0.6);
  color: #fff;
  width: 100%;
  padding: 10px;
  text-align: center;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.portfolio-item:hover .portfolio-caption {
  opacity: 1;
}
</style>

## Portfolio

<div class="portfolio-grid">
  <a href="/projects/project1" class="portfolio-item">
    <img src="/assets/img/project1.jpg" alt="Project 1">
    <div class="portfolio-caption">
      <h3>Project 1</h3>
    </div>
  </a>

  <a href="/projects/project2" class="portfolio-item">
    <img src="/assets/img/project2.jpg" alt="Project 2">
    <div class="portfolio-caption">
      <h3>Project 2</h3>
    </div>
  </a>
</div>
