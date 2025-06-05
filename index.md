---
title: Master Thesis Maksim Borovlev
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>A9 Map + Autodesk Viewer</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      overflow: hidden;
    }
    .container {
      display: flex;
      width: 100%;
      height: 100%;
    }
    .panel {
      flex: 1;
      height: 100%;
      border: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Left: Fullscreen A9 map -->
    <iframe class="panel" src="A9_CS_Average_P0.html"></iframe>

    <!-- Right: Fullscreen Autodesk Viewer -->
    <iframe class="panel" src="https://autode.sk/4krPuP0" allowfullscreen></iframe>
  </div>
</body>
</html>
