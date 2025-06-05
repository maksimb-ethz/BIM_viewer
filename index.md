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

    .container {
      display: flex;
      flex-direction: column;
      height: 100%;
      width: 100%;
    }

    .map-panel {
      flex: 1;
      border: none;
      height: 100%;
      width: 100%;
    }

    .viewer-button {
      height: 60px;
      text-align: center;
      background: #f5f5f5;
      padding-top: 10px;
      border-top: 1px solid #ccc;
    }

    .viewer-button a {
      display: inline-block;
      padding: 12px 24px;
      background: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      font-size: 16px;
    }

    .viewer-button a:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Top: Fullscreen map -->
    <iframe class="map-panel" src="A9_CS_Average_P0.html"></iframe>

    <!-- Bottom: Viewer button -->
    <div class="viewer-button">
      <a href="https://autode.sk/4krPuP0" target="_blank">Open Autodesk Viewer</a>
    </div>
  </div>
</body>
</html>
