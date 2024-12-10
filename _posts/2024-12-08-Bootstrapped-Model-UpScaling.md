---
title: Bootstrapped Model UpScaling (BUS)
layout: archive
categories: project
---

- Developed BUS (Bootstrapped Model UpScaling), an innovative method combining nGPT architecture with fractional HyperScaling to enhance Large Language Model (LLM) training efficiency
- Conducted comprehensive comparisons across model sizes ranging from 100k to 100M parameters, demonstrating consistent performance gains and efficient scaling properties.
- Investigated transfer learning's impact on the efficient compute boundary, exploring opportunities to optimize computational resources while maintaining high accuracy.
- Applied singular value decomposition (SVD) to analyze convergence properties, revealing shared spectral characteristics enabling effective knowledge transfer between models of different sizes.
- Performed pretraining on a 100M parameter LLM using a large GPU cluster, showcasing ability to work with substantial computational resources.

### Technologies
- Implemented the entire pipeline using a robust tech stack:
   - Python
   - PyTorch
   - HuggingFace Transformers
   - NumPy
   - SciPy
   - Pandas
   - CUDA for accelerated training


## link to paper
[github link](https://github.com/brianakl/bootstrapped_model_up_scaling)
