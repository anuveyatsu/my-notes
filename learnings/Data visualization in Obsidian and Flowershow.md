---
title: Data visualization in Obsidian and Flowershow
description: Explore various methods to craft compelling data visualizations, including interactive charts, using Obsidian and seamlessly publish your insights with Flowershow.
date: 2025-03-18
---

In this post you can learn about the following methods:

- [[#Excalidraw]] - very basic line and bar chart using inline CSV data.
- [[#Flowershow]] data view components.

## Excalidraw

Quick YouTube video: https://www.youtube.com/watch?v=XBvPQAOjDVc.

See a live example: [[Oil Prices Trending Downward]].

### Notes

- Only line and bar chart is available.
- It looks like I should paste only 2 fields, otherwise, Excalidraw can't figure out which column to use for x and y axis.
- While it can look very basic, I like the fact that you can just edit the chart as a regular Excalidraw, e.g., you can resize, change labels etc manually which provides full flexibility if you want to tell a story with easy to read visuals. 

## Flowershow

Components library: https://storybook.portaljs.org/?path=/docs/components-introduction--docs.

See a live example: [[S&P 500 Responds to US Tariff Policies]].

### Notes

To create the chart in the example above, I needed to copy and paste example component from storybook where inline CSV was used. It was a little bit tedious as editing JSX in Obsidian isn't straightforward. In addition, I needed to use `\n` new line characters in the inline CSV to avoid rendering errors.