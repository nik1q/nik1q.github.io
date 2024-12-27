---
layout: page
title: Portfolio
subtitle: My Portfolio
---

<style>
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
  }
  .project-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 15px;
    text-align: center;
    transition: transform 0.3s ease;
  }
  .project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }
  .project-image {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 5px;
  }
  .project-title {
    margin-top: 10px;
    font-weight: bold;
  }
  .project-description {
    margin: 10px 0;
    font-size: 0.9em;
  }
  .project-link {
    display: inline-block;
    margin-top: 10px;
    padding: 5px 10px;
    background-color: #007bff;
    color: white;
    text-decoration: none;
    border-radius: 5px;
  }
</style>

<div class="project-grid">
  <div class="project-card">
    <img src="https://github.com/nik1q/nik1q.github.io/raw/master/assets/img/JavaWaehrungRechner.png" alt="JavaWaehrungRechner" class="project-image">
    <h3 class="project-title">Java Währungsrechner</h3>
    <p class="project-description">Ein einfacher Währungsrechner, der Wechselkurse von einer API abruft und die Umrechnung zwischen verschiedenen Währungen ermöglicht.</p>
    <a href="https://github.com/nik1q/JavaWaehrungRechner" class="project-link">Zum Projekt</a>
  </div>
  
  <div class="project-card">
    <img src="https://github.com/nik1q/nik1q.github.io/raw/master/assets/img/DateiRechner.png" alt="DateiRechner" class="project-image">
    <h3 class="project-title">Datei Rechner</h3>
    <p class="project-description">Ein Projekt, das verschiedene Rechnungs- und Dateimanipulationsfunktionen in Java bietet.</p>
    <a href="https://github.com/nik1q/DateiRechner" class="project-link">Zum Projekt</a>
  </div>
</div>
