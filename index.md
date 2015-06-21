---
title       : Investigating UFO sightings in the USA
subtitle    : We are not alone
author      : emilliman5
job         : Research Fellow
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The National UFO Resource Center
The [NUFORC](http://nuforc.org) is an organization "Dedicated to the Collection and Dissemination of Objective UFO Data" 

This raised the following questions:
  1.  Are there hotspots of UFO sightings?
  2.  How have sighting reports changed over time?

The NUFORC DB has:
  78451 records spanning the dates: 1969-01-01, 2015-06-06 for the US. With ~20,000 more sightings reported around the world.

--- .class #id 

## UFO sightings over the last 45 years
<img src="assets/fig/unnamed-chunk-1-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

It appears that the incidence of UFO reporting has been exponentially increasing as the internet gained popularity and became commonplace.

--- .class #id

## Geographical distribuition of sightings across the US
<img src="assets/fig/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />
Aggregate sightings plotted across the US (left) and my home state (Michigan, right). Due to some geocoding constraints Version 1 of the app only covers the USA. Future releases will make use of the google map's API (need to workaaround the query limit). The top plot shows the aggregate sighting counts over the duration of the database at each uniquely identified locale.

--- .class #id

## Sightings by Location by Year
<img src="assets/fig/unnamed-chunk-3-1.png" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" style="display: block; margin: auto;" />

If we break up sightings by decade we see that the more populated areas always tend to have the most reported sightings... Whether this is because extra-terrestrial races are drawn to the bright lights and dense population or some other confounding factor remains to be explored.

--- .class #id
