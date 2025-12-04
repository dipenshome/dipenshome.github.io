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
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive PDF Embed</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }
    /* Center container */
    .pdf-container {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }
    /* Responsive embed */
    .pdf-container embed {
      width: 100%;
      max-width: 800px;   /* optional max width */
      height: 90vh;       /* default height for desktops */
      border: none;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
      background: #fff;
    }
    /* Fallback link styling */
    .fallback-link {
      margin-top: 15px;
      font-size: 16px;
    }
    .fallback-link a {
      color: #007BFF;
      text-decoration: none;
    }
    .fallback-link a:hover {
      text-decoration: underline;
    }
    /* 📱 Mobile adjustments */
    @media (max-width: 768px) {
      .pdf-container embed {
        height: 70vh;   /* smaller height for tablets */
      }
    }
    @media (max-width: 480px) {
      .pdf-container embed {
        height: 60vh;   /* even smaller height for phones */
      }
    }
  </style>
</head>
<body>
  <div class="pdf-container">
    <!-- Embedded PDF -->
    <embed src="https://dipenshome.github.io/files/CV_Dipen_Shome__ME_.pdf" type="application/pdf">
    <!-- Fallback download link -->
    <div class="fallback-link">
      <p>If the PDF doesn’t display, you can 
         <a href="https://dipenshome.github.io/files/CV_Dipen_Shome__ME_.pdf">download it here</a>.
      </p>
    </div>
  </div>
</body>
</html>
