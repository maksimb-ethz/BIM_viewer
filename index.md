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
      height: 100%;
      display: flex;
    }
    .panel {
      flex: 1;
      height: 100%;
      border: none;
    }
    .viewer-placeholder {
      flex: 1;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: sans-serif;
      font-size: 20px;
    }
    .viewer-placeholder a {
      padding: 12px 20px;
      background: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 6px;
    }
  </style>
</head>
<body>
  <!-- Left: Static map -->
  <iframe class="panel" src="A9_CS_Average_P0.html"></iframe>

  <!-- Right: Placeholder with link -->
  <div class="viewer-placeholder">
    <a href="https://autode.sk/4krPuP0" target="_blank">
      Open Autodesk Viewer
    </a>
  </div>
</body>
</html>
