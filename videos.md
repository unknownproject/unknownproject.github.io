---
layout: default
permalink: /videos.html
---
<head>
  <link href="https://vjs.zencdn.net/7.8.3/video-js.css" rel="stylesheet" />

  <!-- If you'd like to support IE8 (for Video.js versions prior to v7) -->
  <script src="https://vjs.zencdn.net/ie8/1.1.2/videojs-ie8.min.js"></script>
</head>
<div id="block1">

  <video id="shh" class="video-js vjs-default-skin" width="800px" height="450px" data-setup ='{}'
      controls preload="none" poster='https://raw.githubusercontent.com/unknownproject/unknownproject.github.io/master/assets/images/SHH.png'
      data-setup='{ "aspectRatio":"800:450", "playbackRates": [1, 1.5, 2] }'>
    <source src="p30_features.mp4" type="video/mp4">
  </video>
<script src="https://vjs.zencdn.net/7.8.3/video.js"></script>
  <p><strong>Silent Hill Homecoming - Feature presentation [v 2.45+]</strong></p>
  </div>

<style>
  #block1 { max-width: 640px; text-align: left; margin: 30px auto; }
  #block1 textarea { width: 100%; height: 100px; }
  
  /* Show the controls (hidden at the start by default) */
  .video-js .vjs-control-bar { 
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }

  /* Make the demo a little prettier */
  body {
    margin-top: 20px;
    background: #222;
    text-align: center; 
    color: #aaa;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    background: radial-gradient(#333, hsl(200,30%,6%) );
  }

  a, a:hover, a:visited { color: #ffb000; }
</style>