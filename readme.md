# Explaining And Understanding Nvidia GPU Libraries
This short document is meant to explain Nvidia GPU libraries, and how to test for these libraries

## What is CUDA

## What is GPU Drivers

### CUDA vs Drivers

## What is cuDNN

## What is CUDA Toolkit

## Check CUDA, cuDNN 

### nvcc --version
Installed as part of CUDA Toolkit.  
* Tool to check CUDA version
* `nvcc --version` in command line.

### nvidia-smi
[Explanation Guide](https://medium.com/analytics-vidhya/explained-output-of-nvidia-smi-utility-fc4fbee3b124)  
* Tool to monitor Nvidia GPU

### check cuDNN  
Theres no direct way to check system installed cuDNN.  
Depends on which version of cuDNN files you copied over to CUDA directory.  

## TL;DR
CUDA -> Library/platform for Nvidia GPU utilisation.  
cuDNN -> Additional Libraries for Neural Network Purposes.  
CUDA ToolKit -> More tools like GUI, CUDA SDK.   
Device Drivers -> Determines what CUDA and CuDNN GPU can support. [Keep Updated]  

## Links
* CUDA Toolkit vs CUDA -> [Link to StackOverflow Explanation](https://stackoverflow.com/questions/28176050/what-is-the-difference-between-the-cuda-tookit-and-the-cuda-sdk)
* cuDNN Installation Guide -> [Link to official doc guide](https://docs.nvidia.com/deeplearning/cudnn/install-guide/index.html)  
Ensure you install CUDA Toolkit + Update CUDA first