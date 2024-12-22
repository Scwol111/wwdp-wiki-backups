---
title: Untitled Page
description: 
published: true
date: 2024-12-22T18:12:26.305Z
tags: 
editor: markdown
dateCreated: 2024-12-22T17:28:02.843Z
---

<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
<div class="player">
  <div class="title">MIDI Player</div>
  <div class="visualizer">
    <div class="bars">
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
    </div>
  </div>
  <div class="controls">
    <button class="btn" id="prevBtn"><i class="fas fa-backward"></i></button>
    <button class="btn" id="playBtn"><i class="fas fa-play"></i></button>
    <button class="btn" id="nextBtn"><i class="fas fa-forward"></i></button>
  </div>
  <input type="file" id="fileInput" class="file-input" accept=".mid,.midi">
  <label for="fileInput" class="file-label">Выберите MIDI файл</label>
  <div class="progress">
    <div class="progress-bar"></div>
  </div>
</div>