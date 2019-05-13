---
title: "Interactive Neighborhood & Restaurant Charts "
date: 2019-05-12
published: true
tags: [dataviz, altair, vega-lite, holoviews]
excerpt: "Embedding interactive charts on static pages using Jekyll."
altair-loader:
  altair-chart: "charts/neighborhood_chart.json"
hv-loader:
  holoviews-chart: "charts/measlesHoloviews.html"
toc: true
toc_sticky: true
---

This post will show examples of embedding interactive charts produced using [Altair](https://altair-viz.github.io) [Vega-Lite](https://vega.github.io/vega-lite/) via [Observable](https://observablehq.com/), and
[Holoviews](http://holoviews.org/index.html).

## Altair Example

Below is an interactive chart of the relationship between Total Population, Percentage of Population from Selection Countries and Boroughs in different neighborhoods in NYC.

<div id="altair-chart"></div>

This was produced using Altair and embedded in this static web page.

## Holoviews Example

Lastly, the measles incidence produced using the Holoviews package:

<div id="holoviews-chart"></div>


