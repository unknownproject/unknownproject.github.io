---
layout: default
permalink: /videos.html
---

<link href="https://unpkg.com/video.js@7.3.0/dist/video-js.min.css" rel="stylesheet">
    <script src="https://unpkg.com/video.js@7.3.0/dist/video.min.js"></script>
<script src="newskin.js"></script>

<video id="player" class="video-js"></video>
<script>
var Player = videojs("player", { 
"controls": true, 
"autoplay": false, 
"preload": "auto" ,
"poster": "https://raw.githubusercontent.com/unknownproject/unknownproject.github.io/master/assets/images/SHH.png",
"width": 960,
"height": 400,
sources: [
{ src: '30_features.mp4"', type: 'video/mp4'}]});
</script>