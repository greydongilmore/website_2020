---
# Course title, summary, and position.
linktitle: Time Series Analysis
summary: Tutorial page for slides and midterm/exam review material.
weight: 1

# Page metadata.
title: Time Series Analysis
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  ch_08:
    name: Time Series Analysis
    weight: 1
---

# Time Series Analysis

Time series analysis refers to the analysis of change in the trend of the data over a period of time. Time series analysis has a variety of applications. One such application is the prediction of the future value of an item based on its past values. Future stock price prediction is probably the best example of such an application. In this tutorial, we will see how we can perform time series analysis with the help of Keras. We will be predicting the future stock prices of the Apple Company (AAPL), based on its stock prices of the past 5 years.
