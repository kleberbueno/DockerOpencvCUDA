# Docker Opencv CUDA

This repository has a DockerFile to create a docker image based on Ubuntu 20.04.
It is built on CUDA 11.2.1, CUDNN 8.0, OPENCV 4.5.0 and Python 3.8.10.

All the credits go to docker user "thecanarianroot", GitHub Repo: https://github.com/thecanadianroot/opencv-cuda-docker
The DockerFile was based on his repository, just changing CUDA and OPENCV version. Also keep on mind to change CUDA_ARCH_BIN and CUDA_ARCH_PTX according your GPU computer capability.
