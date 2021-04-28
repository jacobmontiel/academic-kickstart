+++
date = "2019-11-16T11:35:00Z"
title = "scikit-multiflow: machine learning on infinite data streams"
abstract = ""
abstract_short = ""
event = "PyData Cambridge 2019"
event_url = "https://cambridgespark.com/pydata-cambridge-2019/"
location = "Cambridge, UK"

selected = false
math = false

url_pdf = "https://drive.google.com/open?id=14za3eekD0t88sV4qL1nQbrZ1vuv6j5_7"
url_slides = "https://docs.google.com/presentation/d/e/2PACX-1vSkV6hGb0rLRTCGnmUDON46wcChLfmL4rJ0JOlc_xm0ciJSAAKthb8kzuO-ZPijrAbw3BZG0W8jYpkG/pub?start=false&loop=false&delayms=3000"
url_video = ""

+++

![PyData Cambridge](/img/talks/pydata_cambridge_2019.png)

In the field of machine learning on data streams, data is assumed infinite and models are trained and updated continuously, thereby adapting to changes in the data. This talk provides an overview of data stream learning and introduces scikit-multiflow, an open-source Python framework to easily implement algorithms and perform experiments.

As traditional “batch” learning struggles to keep in pace with today’s data deluge, a parallel field emerges — data stream mining. In this field, data is assumed infinite and models are trained and updated continuously, thereby adapting to changes in the data. This talk provides an overview of the core concepts of data stream learning and introduces scikit-multiflow, an open-source Python framework to implement algorithms and perform experiments in the field of machine learning on evolving data streams.

This talk is composed of two main sections:

### An introduction to learning from data streams

* How is stream learning different from the “traditional” batch learning?
* Requirements
* An overview of methods for supervised learning
* Discussion of challenges from changes in the data distribution, known as concept drift
* Evaluating model performance on infinite data streams


### Scikit-multiflow

* What is scikit-multiflow?
* Overview of the core components of scikit-multiflow and available methods
* Demo