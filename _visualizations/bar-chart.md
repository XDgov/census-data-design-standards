---
permalink: /visualizations/bar-chart
layout: styleguide
title: Bar Chart
aka: [Bar Graph]
category: Visualization types
lead: A bar chart displays categorical data with rectangular bars whose length or height corresponds to the value of each data point.
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
tags: [comparative]
guidance-always:
- Always use independent categories of data.
- Always label each category of data.

guidance-recommended:
- It is recommended to use bar charts when comparing large changes in data values.

guidance-not-recommended:
- It is not recommended to include too many bars as the visualization will become difficult to understand.
- It is not recommended to use bar charts when the changes in data values are relatively small.

guidance-never:
- Never omit the space between bars – otherwise the bar chart will appear to be a histogram.
- Never use three dimensional (3D) graphics as they distort the visual calculation of volume.
---

<p>
  Bar charts can be visualized using vertical or horizontal bars. Bar charts are best used to compare a single category of data or several. When comparing more than one category of data, the bars can be grouped together to created a grouped bar chart.
</p>
<p>
  Bar charts use volume to demonstrate differences between each bar. Because of this, bar charts should always start at zero. When bar charts do not start at zero, it risks users misjudging the difference between data values.
</p>

<h2>Examples</h2>

<div class="usa-chart-card">
  <div class="usa-chart-header">
    <h3 class="usa-chart-title">Types of Languages Spoken at Home in New York</h3>
  </div>
  <canvas id="barChart"></canvas>
  <div class="usa-source-container">
    Source: <a href="https://www.census.gov/programs-surveys/acs/" target="_blank">2016 American Community Survey 1-Year Estimates</a>
  </div>
</div>
<div class="usa-chart-card">
  <div class="usa-chart-header">
    <h3 class="usa-chart-title">Population by Age Range</h3>
  </div>
  <canvas id="chart-bar-horizontal"></canvas>
  <div class="usa-source-container">
    <div>
      Source:
      <a href="https://www.census.gov/programs-surveys/acs/" target="_blank">
        2016 American Community Survey 1-Year Estimates
    </a>
    <div>
      Table:
      <a href="https://data.census.gov/cedsci/" target="_blank">DP05</a>
    </div>
  </div>
</div>