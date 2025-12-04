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
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
    }

    /* Center container */
    .pdf-container {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }

    /* Responsive iframe */
    .pdf-container iframe {
      width: 100%;
      max-width: 800px;   /* optional max width */
      height: 90vh;       /* take up most of viewport height */
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
  </style>
</head>
<body>
  <div class="pdf-container">
    <!-- Embedded PDF -->
    <iframe src="example.pdf"></iframe>

    <!-- Fallback download link -->
    <div class="fallback-link">
      <p>If the PDF doesn’t display, you can 
         <a href="example.pdf" download>download it here</a>.
      </p>
    </div>
  </div>
</body>
</html>

