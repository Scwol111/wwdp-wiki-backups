---
title: Untitled Page
description: 
published: true
date: 2024-12-22T17:45:59.950Z
tags: 
editor: markdown
dateCreated: 2024-12-22T17:28:02.843Z
---

<midi-player
  src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/twinkle_twinkle.mid"
  sound-font visualizer="#myPianoRollVisualizer">
</midi-player>

<midi-visualizer type="piano-roll" id="myPianoRollVisualizer" 
  src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/twinkle_twinkle.mid">
</midi-visualizer>

<midi-player
  src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/twinkle_twinkle.mid"
  sound-font visualizer="#myStaffVisualizer">
</midi-player>

<midi-visualizer type="staff" id="myStaffVisualizer" 
  src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/twinkle_twinkle.mid">
</midi-visualizer>

<script src="https://cdn.jsdelivr.net/combine/npm/tone@14.7.58,npm/@magenta/music@1.23.1/es6/core.js,npm/focus-visible@5,npm/html-midi-player@1.5.0"></script>

<p>For more information, see <a href="https://github.com/cifkao/html-midi-player" target="_blank">the <strong>html-midi-player</strong> repository</a> on GitHub.</p>