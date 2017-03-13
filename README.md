# OpenAC
Open Artificial Intelligence Compute Framework

Open AI Compute (OpenAC) is a framework for developing efficient AI (Artificial Intelligence) computing systems across heterogeneous platforms consisting of CPUs, GPUs, DSPs, FPGAs, and other ASSPs and ASICs, for both cloud and client applications.

## Why OpenAC

Computing industry is witnessing a boom of customized AI accelerators (FPGAs, ASICs and ASSPs), which aims to provide 10x - 1000x efficiency compared to general purpose computing devices. At the same time, AI algoirthms and frameworks are evolving very fast. A set of stable APIs that abstracts the AI computing could dramatically benefit the industry (as well as academia) in the following aspects:
 - A compatible new accelerator can be easily integrated to an existing system (a cloud service or a mobile app)
 - A compatible device can be easily integrated to supported DL frameworks (Caffe, CNTK, Keras, MxNet, Tensorflow, Theano, Torch …)
 - A well-defined project can potentially boost the customized computing (FPGA, ASICs and ASSPs) eco-system 

## Philosophy of OpenAC
### Symbolic computing
- AI computation (inference or training) is represented as a graph
- Computing device is responsible to process a subgraph
- Device may only support a limited set of operations
### Stochastically correct
- Ensure accuracy (over test set), not numerical precision
- Computing solution provider can do pruning, quantization, compression with {accuracy, test data, training data, sub-graph, input tensor}
### Explicit service level agreement (SLA)
- Online service has rigid latency requirement
- Caller can query the device capability, and estimate the performance

## Scenarios

### Host application calls a local accelerator

### A FPGA team develop AI accelerator for Cloud vendors

### Mobile app calls an AI service in cloud

# Getting started


# Documentation

# Contributors
Jian Ouyang, Xiao Lin, Ming Wu,  Wenqiang Wang, Ningyi Xu 
