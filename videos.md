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
{ src: '30_features.mp4"', type: 'video/mp4'}],
});
</script>

<!--<head>
  <link href="https://vjs.zencdn.net/7.8.3/video-js.css" rel="stylesheet" />

  <!-- If you'd like to support IE8 (for Video.js versions prior to v7) -->
  <script src="https://vjs.zencdn.net/ie8/1.1.2/videojs-ie8.min.js"></script>
</head>

<body>
<center>
  <video
    id="my-video"
    class="video-js"
    controls
    preload="auto"
    width="640"
    height="360"
    poster="https://raw.githubusercontent.com/unknownproject/unknownproject.github.io/master/assets/images/SHH.png"
    data-setup="{}"
  >
    <source src="p30_features.mp4" type="video/mp4" />
    <p class="vjs-no-js">
      To view this video please enable JavaScript, and consider upgrading to a
      web browser that
      <a href="https://videojs.com/html5-video-support/" target="_blank"
        >supports HTML5 video</a
      >
    </p>
  </video>
</center>
  <script src="https://vjs.zencdn.net/7.8.3/video.js"></script>
</body>-->