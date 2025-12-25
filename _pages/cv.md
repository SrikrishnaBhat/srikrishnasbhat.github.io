---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


This section has my Industry Experience.
To download the full CV, [click here](../files/srikrishnasbhat_cv.pdf).

# Industry Experience
**Jan 2019 — Feb 2022**     **Senior Software Engineer (Band 7A), IBM India Software Labs**
                            *Bengaluru, Karnataka, India*

- Migrating IBM Watson Machine Learning (WML) Deployment Service into the on-premises Cloud Pak for Data environment by
refactoring the Scala code and redesigning the Kubernetes container setup to provide a more secure deployment environment.
- Implementing WML team spaces feature in the WML Deployment service using Scala and Akka micro-services. This feature was
implemented to provide multiple teams with better collaboration operations.
- Worked with clients in troubleshooting model issues and setting up Pytorch, Tensorflow and XGBoost model pipelines in the IBM
WML Deployment service to be used as a backend in their applications.


**Jul 2017 — Jan 2019**     **Software Engineer, IBM India Software Labs**
                            *Bengaluru, Karnataka, India*

- Wrote the kubernetes and flask service code for deploying scikit-learn, xgboost, pytorch and tensorflow models. This feature
allowed customers to deploy python-based models in the WML Cloud environment.
- Guided interns in the development of batch scoring architecture for WML deployment service for python models using Amazon
S3 and IBM Cloud Object Storage to provide capability to query backend Machine Learning (ML) programs with large ML scoring
requests.


**Jan 2017 — Jun 2017**     **Project Intern, IBM India Software Labs**
                            *Bengaluru, Karnataka, India*

- Wrote the early code and design of scikit-learn and xgboost model deployment of WML deployment service in Python Flask


**May 2016 — Jul 2016**     **Research Intern, National Tsing Hua University**
                            *Hsinchu, Taiwan*

- Worked on the problem of Automated Theatrical Performance Analysis to detect and rate actions performed by actors using
Siamese network for detecting actor poses with the Caffe library for neural networks. Since this was a two month early stages of
the project, most of the project time was spent on exploration of algorithms and testing.


**May 2015 — Aug 2015**     **Research Intern, Siemens Research Technology Centre**
                            *Bengaluru, Karnataka, India*

- Ported architecture of constant-time (O(1)) sorting algorithms from Artificial Neural Networks to Spiking Neural Networks using
the CARLsim neurosimulator, written in C++



 
## Talks

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
## Teaching

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>