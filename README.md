# Building-Modeling
## Introduction
Accurate modeling of building energy systems is a cornerstone of modern smart building research, enabling applications ranging from energy consumption prediction, demand response, and optimal control. As buildings account for more than 30% share of global energy consumption, developing reliable and efficient building models has become increasingly critical for achieving sustainability goals.

Building modeling approaches are broadly categorized into three paradigms, each reflecting a different balance between physical interpretability and data-driven flexibility:

**White-box models** are grounded in first-principles physics, explicitly encoding physical laws, like thermodynamic laws, heat transfer equations, and HVAC system dynamics. Tools such as [EnergyPlus](https://energyplus.net/), [TRNSYS](https://www.trnsys.com/), and [OpenStudio](https://openstudio.net/) fall into this category. While highly interpretable and generalizable across buildings, these models demand detailed architectural and mechanical specifications, making them labor-intensive to construct and calibrate.

**Black-box models** take a purely data-driven approach, learning the input-output behavior of a building directly from operational data without any explicit physical assumptions. This category encompasses a wide spectrum of machine learning and deep learning techniques — including recurrent neural networks (RNNs), transformers, federated learning frameworks, and end-to-end learning pipelines — which have demonstrated strong predictive performance, particularly when large-scale sensor data is available.

**Gray-box models** occupy the middle ground, combining physical structure with data-driven parameter estimation. Representative approaches include Physics-Informed Neural Networks (PINNs), which embed governing differential equations as soft constraints during neural network training, and Resistance-Capacitance (RC) thermal network models, which abstract building thermal dynamics into compact equivalent circuits whose parameters are identified from data. These hybrid methods offer improved sample efficiency and interpretability compared to pure black-box approaches, while relaxing the detailed input requirements of white-box simulators.
This repository provides a structured overview of these three modeling paradigms, surveying representative methods, tools, and recent advances in each category.

## White-box Models


## Black-box Models


## Gray-box Models
