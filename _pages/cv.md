---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CV | Dipen Shome</title>

  <style>
    body {
      margin: 0;
      padding: 0;
      background: #f2f2f2;
      font-family: Arial, sans-serif;
    }

    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .pdf-frame {
      width: 100%;
      height: 85vh;
      border: none;
      box-shadow: 0 0 12px rgba(0,0,0,0.25);
      background: #ffffff;
    }

    @media (max-width: 768px) {
      .pdf-frame {
        height: 70vh;
      }
    }

    .fallback {
      margin-top: 16px;
      font-size: 16px;
      text-align: center;
    }

    .fallback a {
      color: #0066cc;
      text-decoration: none;
    }

    .fallback a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>
  <div class="container">

    <!-- Embedded PDF using iframe -->
    <iframe
      src="https://dipenshome.github.io/files/CV_Dipen_Shome__ME_.pdf"
      class="pdf-frame"
    >
    </iframe>

    <!-- Fallback link -->
    <div class="fallback">
      If the PDF does not load,  
      <a href="https://dipenshome.github.io/files/CV_Dipen_Shome__ME_.pdf" target="_blank">
        click here to download it
      </a>.
    </div>
  </div>
</body>
</html>

