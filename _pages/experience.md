---
layout: page
permalink: /experiences/
title: Experiences
description: Work experiences in reversed chronological order.
nav: true
nav_order: 7 
---
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Experiment Page</title>
    <style>
        /* Add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
        }
        .experiment {
            margin: 20px;
            border: 1px solid #ccc;
            padding: 20px;
            border-radius: 5px;
            display: flex;
            flex-direction: column;
            align-items: flex-start; /* Align items to the left */
        }
        .experiment img {
            max-width: 100px;
        }
        .company-details {
            display: flex;
            align-items: center;
        }
        .company-name {
            font-family: "Times New Roman", Times, serif;
            font-size: 20px;
            margin-left: 10px;
        }
        .experiment h2 {
            margin-top: 0;
            font-size: 24px;
        }
    </style>
</head>
<body>
    <!-- Example Experiment Section -->
    <div class="experiment">
        <div class="company-details">
            <img src="/assets/img/ETH_logo.png" alt="Company Logo">
            <h2 class="company-name"> Research Assistant at <a href="https://ait.ethz.ch/" target="_blank">Advanced Interactive Technologies Lab</a>, ETH Zürich</h2>
        </div>
        <p>July 2023 - Present</p>
        <p> I am working on Long-Term Action Anticipation (LTA) task utilizing vision-language and large language models, under the supervision of <a href="https://xiwang1212.github.io/homepage/" target="_blank">Dr. Xi Wang</a>  and <a href="https://xianyongqin.github.io/" target="_blank">Dr. Yongqin Xian</a>. We achieved the state-of-the-art performance on LTA Ego4D challenge. </p>
    </div>
    <div class="experiment">
        <div class="company-details">
            <img src="/assets/img/ETH_logo.png" alt="Company Logo">
            <h2 class="company-name"> Research Assistant at <a href="https://krauthammerlab.ch/" target="_blank">KrauthammerLab</a>, University of Zürich</h2>
        </div>
        <p>June 2022 - March 2023</p>
        <p> I improved the transformer-based models on radiolog report generation task from chest X-ray images. I work closely with <a href="https://krauthammerlab.ch/authors/farhadzad/" target="_blank">Dr. Farhad Nooralahzadeh</a> and <a href="https://krauthammerlab.ch/authors/michaelkrauthammer/" target="_blank">PI. Michael Krauthammer</a>. We also collaborated with radiologists at Kyoto University to understand radiology reports.
    </div>
</body>
</html>

