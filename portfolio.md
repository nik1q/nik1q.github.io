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
    <img src="https://via.placeholder.com/250x150?text=Tic-Tac-Toe" alt="Tic-Tac-Toe" class="project-image">
    <h3 class="project-title">Tic-Tac-Toe</h3>
    <p class="project-description">Ein klassisches Tic-Tac-Toe-Spiel, implementiert in Python.</p>
    <a href="https://github.com/nik1q/Tic-Tac-Toe" class="project-link">Zum Projekt</a>
  </div>
  
  <div class="project-card">
    <img src="https://via.placeholder.com/250x150?text=Hangman" alt="Hangman" class="project-image">
    <h3 class="project-title">Hangman</h3>
    <p class="project-description">Ein interaktives Hangman-Spiel, entwickelt in Python.</p>
    <a href="https://github.com/nik1q/Hangman" class="project-link">Zum Projekt</a>
  </div>
  
  <div class="project-card">
    <img src="https://via.placeholder.com/250x150?text=Minesweeper" alt="Minesweeper" class="project-image">
    <h3 class="project-title">Minesweeper</h3>
    <p class="project-description">Eine Python-Implementierung des beliebten Minesweeper-Spiels.</p>
    <a href="https://github.com/nik1q/Minesweeper" class="project-link">Zum Projekt</a>
  </div>
  
  <div class="project-card">
    <img src="https://via.placeholder.com/250x150?text=Blackjack" alt="Blackjack" class="project-image">
    <h3 class="project-title">Blackjack</h3>
    <p class="project-description">Ein Blackjack-Spiel, programmiert in Python.</p>
    <a href="https://github.com/nik1q/Blackjack" class="project-link">Zum Projekt</a>
  </div>
</div>
