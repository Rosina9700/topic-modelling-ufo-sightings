# Unsupervised Learning Case Study

Webscraping UFO sighting description and conducting topic modelling using tfidf and non-negative matrix factorization (NMF)

## The Data

A data set of UFO sighting reports was collected from [The National UFO Reporting Center Online Database](http://www.nuforc.org/webreports.html); you can see an example report [here](http://www.nuforc.org/webreports/133/S133931.html). The data, downloadable as a zipped `json` file [here](https://s3.amazonaws.com/ufodatafordarren/ufodata.json.zip), contains the URL, raw HTML for that URL, and the time it was scraped for each report in the database along with the remnants of a database id.

## The Problem

Find something interesting in the data! That's not very specific, so here are some thoughts to get you going:
* What state has the most UFO/bigfoot sightings? Can you visualize this/compare them?
* What kind of language is used to describe UFO vs. bigfoot sightings. Does it vary by region or time?

A huge part of the challenge for this case study will be getting the data into a usable form, so don't fret about finding something mind-blowingly insightful in the data. Simply verifying a suspicion you have with a model or summarizing a quality about the data that is difficult to see in the raw data is good data science.
