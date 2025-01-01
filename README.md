# Multi-Channel-Multi-Kernel-Convolution

An optimized C implementation of multi-channel, multi-kernel convolution for convolutional neural networks (CNNs), designed to achieve high performance on modern multi-core processors. This project focuses on parallelization and code optimization techniques, leveraging Intel SSE4 vector instructions and OpenMP to efficiently handle computationally intensive convolution layers in CNNs.

## Key Features
- **Support for Various Input Configurations:**
  - Image dimensions: 16x16 to 512x512
  - Kernel sizes: 1, 3, 5, 7
  - Channels and kernels: 32 to 2048 (powers of 2)
- **Performance Optimization:**
  - Enhanced locality of data access
  - Multi-threaded execution across pipelined, superscalar processor cores
- **Technology Used:**
  - SSE4 vectorized instructions
  - OpenMP for parallel processing

## Purpose
This project emphasizes parallelization and code optimization to speed up real-world computations on modern hardware. It is a practical demonstration of achieving efficiency in convolutional operations, which form the backbone of image processing in CNNs.

