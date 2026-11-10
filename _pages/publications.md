---
layout: page
permalink: /papers/
title: papers
description: ""
nav: true
nav_order: 2
---

<div class="publications">

<h2 id="job-market-paper">job market paper</h2>
{% bibliography --query @*[category=job_market_paper] --group_by none %}

<h2 id="publications">publications</h2>
{% bibliography --query @*[category=publication] --group_by none %}

<h2 id="working-papers">working papers</h2>
{% bibliography --query @*[category=working_paper] --group_by none %}

<h2 id="works-in-progress">works in progress</h2>
{% bibliography --query @*[category=work_in_progress] --group_by none %}

</div>
