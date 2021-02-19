## Pytorch
IF INSTALLING THROUGH CONDA:  
CUDA and CuDNN are packaged in pytorch dependacy in conda.  
IT IS INDEPENDANT ON SYSTEM CUDA AND CUDNN.  
Therefore, only need check pytorch.


# Check pytorch has GPU Available:  
Theres a bunch of helpful tips from [Stack Overflow](https://stackoverflow.com/questions/48152674/how-to-check-if-pytorch-is-using-the-gpu)   

Some example code:  
anotherTest.py -> another test of Pytorch GPU utilisation  
gpuTest.py -> test GPU utilisation [Check using `nvidia-smi`]  
pytorchGPUTest.py -> test pytorch can see and use GPU  
testCuDNNVersion.py -> checks if cuDNN enabled, and of what version  