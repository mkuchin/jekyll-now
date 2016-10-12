---
layout: page
title: Open Data Projects
permalink: /open-data/
---
I love to explore and visualise public data in a simple and useful way.

##  [Open Wage](https://openwage.com.au)

Visualising average salary by occupation, state and region, gender gap and average annual growth in Australia.

Used datasets:

* [Individual income by occupation and SA4 location](https://data.gov.au/dataset/ad-hoc-data-requests/resource/d198f1da-614e-42cf-b480-5cee7d2ef752)
* [Taxation Statistics 2013-14](https://data.gov.au/dataset/taxation-statistics-2013-14)

Used technologies:

* Backend: [Groovy/Grails 3.1](https://grails.org/) and [ElasticSearch](https://www.elastic.co/products/elasticsearch)
* Frontend: [Bootstrap 3](http://getbootstrap.com/), [Chart.js](http://www.chartjs.org/), [jQuery UI autocomplete](https://jqueryui.com/autocomplete/)
* Built and deployed with [Jenkins](https://jenkins.io/), [Docker](https://www.docker.com/) and [SaltStack](https://saltstack.com/)
* Hosted on AWS with EC2, CloudFront and Route 53. 

## [ABN check](http://abncheck.com.au)

Alternative to Australian Business Register lookup tool with change tracking and visual stats.

Used datasets:

* [ABN Bulk Extract](https://data.gov.au/dataset/abn-bulk-extract)

Used technologies:

* Backend: [Groovy/Grails 2.5](https://grails.org/), [MongoDB](https://www.mongodb.com/) and [ElasticSearch](https://www.elastic.co/products/elasticsearch)
* Frontend: [Bootstrap 3](http://getbootstrap.com/), [Google Charts](https://developers.google.com/chart/)

