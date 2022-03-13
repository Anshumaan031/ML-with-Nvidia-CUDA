# Python programming with CUDA

CUDA (or Compute Unified Device Architecture) is a parallel computing platform and application programming interface (API) that allows software to use certain types of graphics processing unit (GPU) for general purpose processing, an approach called general-purpose computing on GPUs (GPGPU).

Download CUDA from here: https://developer.nvidia.com/cuda-10.0-download-archive

Download CUDNN from here: https://developer.nvidia.com

To create a new anaconda environment with the name test_gpu (In anaconda prompt)
```bash
conda activate test_gpu

print(tf.test.is_gpu_available())

print(tf.test.is_built_with_cuda())

conda info --envs

conda create test_gpu python==3.6

python --version
```

To check python version in the current environment
```bash
python --version
```
In the new environment download tensorflow gpu
```bash
pip install tensorflow-gpu

```

To test whether the current environment is configured wiht a gpu, and if gpu is connected to cuda.
```bash
python 

print(tf.test.is_gpu_available())

print(tf.test.is_built_with_cuda())

```

However the environment created is not default. So everytome you open conda, you have to manually switch to the new environment temporarily.

To display the list of all conda environments
```bash
conda info --envs

```

To change to the new environment

```bash
conda activate test_gpu

```

## Documentations

[CUDA](https://developer.nvidia.com/cuda-zone) 

[CUDNN](https://developer.nvidia.com/cudnn)

[Parallel Computing](https://www.heavy.ai/technical-glossary/parallel-computing#:~:text=Parallel%20computing%20refers%20to%20the,part%20of%20an%20overall%20algorithm.) 


## Authors

- [@Anshumaan - <anshumaan.phukan@uavtech.ai>](https://github.com/Anshumaan031)
