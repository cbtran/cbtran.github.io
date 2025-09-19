---
title: "Software"
layout: archive
permalink: /software/
classes: wide
author_profile: true
---

Please contact me for any issues regarding the code below.

---

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Projects</title>

  <style>
  .project-cards {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Two equal-width columns */
    gap: 20px;
    width: 100%;
    padding: 0 20px;
  }

  @media (max-width: 700px) {
    .project-cards {
      grid-template-columns: 1fr; /* Stack cards on smaller screens */
    }
  }

  .project-card-link {
    text-decoration: none;
    color: inherit;
    display: block;
  }

  .project-card {
    background-color: #fff;
    border-radius: 6px;
    overflow: hidden;
    box-shadow: 0 3px 8px rgba(0, 0, 0, 0.08);
    transition: transform 0.2s ease;
    display: flex;
    flex-direction: column; 
    width: 100%;
    height: auto;
    justify-content: flex-start;
    padding: 10px;
  }

  .project-card:hover {
    transform: scale(1.03);
  }

  .project-card img {
    width: 100%;
    margin-bottom: 15px; 
    box-shadow: none !important;
    object-fit: contain;
  }

  .project-card .title {
    font-size: 1rem;
    color: #000;
    margin: 0;
    font-weight: bold;
    text-transform: none !important;
  }

  .project-card .description {
    font-size: 0.9em;
    color: #555;
    line-height: 1.4;
    margin-top: 5px; 
    text-align: left;
  }

  </style>
</head>
<body>

  <div class="project-cards">
    <a href="/assets/project/FGLMtrunc/docs/index.html" class="project-card-link">
      <div class="project-card">
        <img src="/assets/img/qfuncMM.png">
        <p class="title">qfuncMM</p>
        <p class="description"> R package of a mixed model approach to functional connectivity estimation.</p>
      </div>
    </a>

    <a href="/assets/project/FGLMtrunc/docs/index.html" class="project-card-link">
      <div class="project-card">
        <img src="/assets/img/FGLMtrunc.png">
        <p class="title">FGLMtrunc</p>
        <p class="description"> R package of a truncated estimation in functional generalized linear regression models.</p>
      </div>
    </a>

    <a href="/assets/project/robsel/docs/index.html" class="project-card-link">
      <div class="project-card">
        <img src="/assets/img/robsel.png">
        <p class="title">robsel</p>
        <p class="description">R package of an algorithm to estimate the graphical lasso regularization parameter..</p>
      </div>
    </a>
  </div>

</body>
</html>
