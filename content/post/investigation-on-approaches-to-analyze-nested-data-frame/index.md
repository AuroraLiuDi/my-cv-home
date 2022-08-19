---
title: Investigation on approaches to analyze nested data frame
date: 2022-08-19T10:42:06.240Z
summary: This note recommends a few approaches that might be of interest in
  analyzing nested behavioral data.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Projects targeting individual difference in conceptual representations usually collect nested data. For instance, to examine how people represent emotional concepts, the experimenter might require participants to rate the semantic similarity between all possible combination of 18 emotional words. Under this circumstance, we will have a 1 x 153 vector for each participant. How to further use these data, say, to predict some certain psychological construct? Here are a few approaches that I have used in my projects, that might be of interest:

* Supervised machine learning

  Supervised training means that the input and output value are both pre-defined in the dataset, and the model, by taking in inputs in the training set and find a way to project them to the outputs, eventually arrive at a stage where classification or regression can be completed with a test set. Famous examples for doing so can be found below:  

  * SVM (& SVR)
  * RVM (& RVR)
* Clustering combined with traditional statistics