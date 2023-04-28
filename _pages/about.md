---
permalink: /
title: ""
excerpt: "Welcome"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Hi.  

I'm Philipp, a doctoral researcher at Technical University Munich and the Postdam Institute for Climate Impact Research. I work at the intersection of deep learning and Earth system modelling to develop new methods that combine the strengths from data-driven machine learning and physics-based models. 

Reasearch topics that I am particularly excited about are:

- __Generative modelling__ of geophysical fields using deep learning for image synthesis and translation. Generative models lend themselves naturally to various tasks in Earth system modelling such as bias correction and downscaling of numerical simulations but also for purely data-driven probabilistic forecasts.

- __Predicting extremes__, such as extreme rainfall events, accurately is important in both the climate modelling and weater forecasting context. In order to make ML models learn to predict rare extremes events, the sparse training data needs to be utilized effectively. This includes developing suitable loss functions, data representation and sampling strategies for training as well as evaluation criteria.

- __Hybrid models__ that combine differential equations (i.e. knowledge-based models) with machine learning algroithms (data-driven models). In order to effectively combine these two approaches *online learning* methods need to be developed that allow to train the ML algorithm while interacting with the rest of the model, e.g., by making the entire hybrid model accessible (differentiable) for gradient-based optimzation. 

- __Interpretable AI__ methods for making deep neural networks more transparent. Especially for high-stakes predictions of extreme events it is important to infer how the black-box models such as neural networks arrive at their forecast. 

- __Generalization under distribution shifts__ of machine leanring models. When modelling climate phenomena and many other real-world problems the data distribution which was seen during training might undergo shifts which leads to out-of-sample predictions. The ensure that the ML model does not violate first principles, e.g., such as physical conservation laws, is a crucial and challenging problem.


