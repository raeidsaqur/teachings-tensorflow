# Tensorflow Tutorials and Teachings
Teaching materials for tensorflow.


# CUDA Setup with eGPU 

The initial setup of eGPU with CUDA on MBPro can be quite cumbersome. Hence, detailing the process here.

## Checking clang version on mac.

```
llvm-gcc -v

clang -v

```

### Downgrade to compatible llvm-gcc compiler version

Go to developer [downloads](https://developer.apple.com/download/more/)
and download appropriate verison.


### Useful Commands

```
nvcc --version
which nvcc
echo $CUDA_HOME



```

