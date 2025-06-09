---
title: Master Thesis Maksim Borovlev
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>A9 Map + BIM Viewer</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      width: 100%;
      overflow: hidden;
      font-family: sans-serif;
    }

    .map-container {
      position: relative;
      width: 100%;
      height: 100%;
    }

    iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }

    .viewer-button {
      position: absolute;
      bottom: 20px;
      left: 50%;
      transform: translateX(-50%);
      background: #007bff;
      color: white;
      padding: 14px 26px;
      font-size: 16px;
      border-radius: 8px;
      text-decoration: none;
      z-index: 1000;
      box-shadow: 0 2px 6px rgba(0,0,0,0.3);
    }

    .viewer-button:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="map-container">
    <!-- Fullscreen map -->
    <iframe src="A9_CS_Average_P0.html"></iframe>

    <!-- Floating button -->
    <a class="viewer-button" href="https://autode.sk/4krPuP0" target="_blank">Open Autodesk Viewer</a>
  </div>
</body>
</html>
