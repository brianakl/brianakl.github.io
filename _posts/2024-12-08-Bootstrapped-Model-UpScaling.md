---
title: Bootstrapped Model UpScaling (BUS)
layout: archive
categories: project
---

## Short Intro

In this paper I had the idea of exploring model growth, or making LLMs grow in number of parameter during training. If an efficient method can be found this can mean that lots of compute resources can be saved by not having to start with training such a large model.

Earlier this year I had thought that there must be a way to expand a models size, since both large and small models are solving the same problem, they are also exploring the same problem space, although the smaller model has a lower dimensional projection of it. 

Concurrent to my research, Samragh et al. at Apple proved the 

## Tools Used

This entire pipeline was implemented using Python, PyTorch, and HuggingFace Transformers, leveraging Numpy, Scipy, and Pandas for data analysis and visualization, while utilizing CUDA for accelerated training.

## link to paper
[github link](https://github.com/brianakl/bootstrapped_model_up_scaling)
