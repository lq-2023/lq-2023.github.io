---
title: "Welcome"
weight: 1
---

LQ 2022 is a workshop co-located with the ECML/PKDD 2022 conference.

Learning to Quantify (LQ - also known as “quantification“, or “supervised prevalence estimation“, or “class prior estimation“), is the task of training class prevalence estimators via supervised learning. In other words, the task of these trained models is to estimate, given an unlabelled sample of data items and a set of classes, the prevalence (i.e., relative frequency) of each such class in the sample.

LQ is interesting in all applications of classification in which the final goal is not determining which class (or classes) individual unlabelled data items belong to, but estimating the percentages of data items that belong to the classes of interest, i.e., estimating the distribution of the unlabelled data items across the classes. Example disciplines whose interest in labelling data items is at the aggregate level (rather than at the individual level), are the social sciences, political science, market research, ecological modelling, and epidemiology.

While LQ may in principle be solved by classifying each data item in the sample and counting how many such items have been labelled with a certain class, it has been shown that this “classify and count” method yields suboptimal quantification accuracy. As a result, quantification is now no longer considered a mere byproduct of classification, and has evolved as a task of its own.

The goal of this workshop is to bring together all researchers interested in methods, algorithms, evaluation measures, evaluation protocols, and methodologies for LQ, as well as practitioners interested in the practical application of the above to managing large quantities of data.