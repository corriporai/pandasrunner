---
toc: false
layout: post
description: Saying hello to runpandas! Brief presentation and motivation to getting started.
categories: [general]
image: images/pandalogo.png
title: Welcome to runpandas
comments: true
author: Marcel Caraciolo
sticky_rank: 1
---

## What is runpandas ?

Welcome to the [runpandas](https://github.com/corriporai/runpandas) library. The framework was developed by me, [Marcel Caraciolo](https://github.com/marcelcaraciolo) targeted at getting the most from your running data.

Recent technological advances to GPS-enabled tracking devices is transforming the aspects of training and competition in fitness activities such as running, cycling and swimming. Those devices produces detailed tracking data among several sports data available for anyone interested at its analysis. This enables a descriptive analysis associated with the related data, such as performance, impact of volume of training or just reviewing the historical activities. There are several devices or applications for sports tracking offered by manufacturers of the tracking devices, such as Garmin, Polar, and through a wide range of applications for devices such as smartphones and smartwatches, e.g., Strava, Endomondo, and Runtastic Running GPS Tracker. 

Limiting to range of data science open-source packages available, there is only a handful of packages specific to sport data and their analysis. Within Python ecosystem, one of the most popular programming languages for data science, there is a gap to fill between the collection of tracking data and the analysis of such data. [Pandas](https://pandas.pydata.org/) is a popular package for data analysis, and several specific domain libraries as built on top of it. At my research at time, I didn't find many sports data analysis package within the Python + Pandas ecosystem.

As a possible alternative, runpandas package comes as a set of utilities to import sports data from GPS-enabled devices or even track activities applications, and, after careful processing,
organises them in data frames which can provide information about the units of measurement (e.g. distance and speed units) as well of any data operations that have been carried out (e.g., personal best records, heart efforts, elevation gain). Runpandas extends the datatypes used by pandas, so it can benefit its core operations for the handling of measurement units and for summarising and visualising tracking data.

![]({{ site.baseurl }}/images/pandalogo.png "runpandas' logo")


## Real motivation behind runpandas

Many runners use Strava, Garmin , Nike plus , Runstatic App (iOS and Android) to track running activities. The APP and its companion website jointly provide many visual charts with analytical metrics to help runners review their running performances to set up new training plans or make adjustments. To a data scientist runner like me, it would be ideal that our data be downloaded and analyzed locally in my own way to have more fun or get different analysis.

Don't get me wrong, I am huge fan and user of several running apps, but sometimes I get frustrated with the data processing and visualization that major providers offer, or sometimes I want just to play around with my tracking data and plot my running routes using Maps libraries or to calculate my personal best times for specific distances. Runpandas is an ellegible solution for data science runners like me, fans of digging sports data combined with all possibilities of rich analysis matching against weather, temperature, marathons, routes datasets.  So, welcome to the world of running analytics, where data science meets the running.

## How can I get started ?
---

If you read until here, it is probably because you are interested at runpandas or the possibilities of performing your own analysis. I will give you some options:

- If you want to check the documentation for more details on using `runpandas`: [Read the Docs](https://www.runpandas.run/en/latest/)
- If you already know the library, and want to contribute: [Github](https://github.com/corriporai/runpandas)
- You are just a curious or a runner, and wants to see the some examples:
- Another introduction to `runpandas` is my undergoing book **Analysing your own running data with Python** on Jupyter notebooks: 


-----

> **Marcel Caraciolo**,<br>
> Computer Engineer and Bioinformatics Specialist at Genomika Einstein laboratory. Currently responsible for lab systems product management. Interested at data science, productivity techiques and product management. Amateur runner and lego architecture sets lover.<br>
>[@marcelcaraciolo](https://twitter.com/marcelcaraciolo) [corriporai.github.io/pandasrunner](https://corriporai.github.io/pandasrunner/)<br>

-----
