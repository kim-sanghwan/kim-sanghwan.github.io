---
layout: page
permalink: /experiences/
title: Experiences
description: #Work experiences in reversed chronological order.
nav: true
nav_order: 7
---



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
            align-items: center;
        }
        .experiment img {
            max-width: 100px;
        }
        .experiment-details {
            margin-left: 20px;
            display: flex;
            flex-direction: column;
            font-size: 18px;
        }
        .company-name {
            font-family: "Times New Roman", Times, serif; /* Change font for company name */
            font-size: 20px;
        }
        .period {
            font-family: "Verdana", Geneva, sans-serif; /* Change font for period */
            font-size: 18px;
        }
        .title {
            font-family: "Courier New", Courier, monospace; /* Change font for title */
            font-size: 24px;
            font-weight: bold;
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
        <a href="https://www.ethz.ch" target="_blank">
              {% include figure.html
              path="assets/img/ETH_logo.png"
              alt=page.profile.image -%}
        </a>
        <div class="experiment-details">
        	<p class="title">Experiment Title</p>
            <h2 class="company-name">Company Name</h2>
            <p class="period">January 2023 - March 2023</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et justo in lorem cursus bibendum.</p>
        </div>
    </div>
    <!-- Add more experiment sections as needed -->


</body>
</html>

