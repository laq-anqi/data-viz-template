---
title: "Interactive Neighborhood & Restaurant Charts "
date: 2019-05-12
published: true
tags: [dataviz, altair, vega-lite, holoviews]
excerpt: "Embedding interactive charts on static pages using Jekyll."
altair-loader:
  altair-chart: "charts/neighborhood_chart.json"
hv-loader:
  holoviews-chart1: "charts/PriceChart.html"
  holoviews-chart2: "charts/Res_Rating_heatmap.html"
  holoviews-chart3: "charts/Average_Rating.html"
toc: true
toc_sticky: true
---

This post will show examples of embedding interactive charts produced using [Altair](https://altair-viz.github.io) [Vega-Lite](https://vega.github.io/vega-lite/) and [Holoviews](http://holoviews.org/index.html).

## Altair Chart

Below is an interactive chart of the relationship between Total Population, Percentage of Population from Selection Countries and Boroughs in different neighborhoods in NYC.

<div id="altair-chart"></div>

## Holoviews Charts

Below is a series of interactive chars showing: 

1)Counts of restaurants of different price levels by country tpyes in NYC

<div id="holoviews-chart1"></div>

2)Density of restaurants of different rating levels by country types in NYC

<div id="holoviews-chart2"></div>

3)Average rating level of restaurants by country types in NYC

<div id="holoviews-chart2"></div>

