---
permalink: /visualizations/pie-chart
layout: styleguide
title: Pie Chart
aka: [Circle Chart]
category: Visualization types
components:
  - Agency Logo
  - Axes
  - Colors
  - Grids
  - Labels
  - Legends
  - Source
  - Titles
  - Typography
lead: A pie chart is a circular graph that presents values as proportionate slices.
tags: [comparative]
guidance-always:
- Always consider using a bar chart or displaying values directly before using a pie chart.
- Always include a legend or label slices directly.
guidance-not-recommended:
- It is not recommended to include large gaps between each slice, such as in an exploded pie chart.
- It is not recommended to use multi-level pie charts as they are difficult to decipher.
guidance-never:
- Never use three dimensional (3D) graphics as they distort the visual calculation of volume.
---
<div class="usa-viz-warning">
  Before using a pie chart, consider using a
  <a href="{{ site.baseurl }}/visualizations/bar-chart">bar chart</a>
  or displaying numeric values directly for improved usability.
</div>

<p>
  Pie charts are one of the most commonly used data visualizations but are often
  not the most effective way to compare data values. This is mainly due to the 
  size of each slice and the number of data categories being represented. Pie
  charts can also be represented as a doughnut chart, which is generally better
  for users to compare the size of each slice or arc.
</p>

<h2>Examples</h2>
<div class="usa-chart-card">
  <div class="usa-chart-header">
    <h3 class="usa-chart-title">Average Percent Population Change in Cities and Towns Since 2010</h3>
    <h4 class="usa-chart-subtitle">Population between 10,000 and 49,999</h4>
  </div>
  <canvas id="chart-pie"></canvas>
  <div class="usa-source-container">
    <div>
      Source: 
        <a href="https://www.census.gov/programs-surveys/poptest.html" target="_blank">
          U.S. Census Bureau. Vintage 2017 Population Estimates
        </a>
  </div>
</div>