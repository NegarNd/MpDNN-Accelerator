# MpDNN-Accelerator

N. Neda, S. Ullah, A. Ghanbari, A. Kumar, M. Modarressi and H. Mahdiani, "MpDNN: MultiPrecision Deep Neural Network Acceleration on FPGAs", In preparation, University of Tehran, Iran & Technische Universitt Dresden, Germany

# Abstract

**Quantization is a promising approach to reduce the computational load of neural networks. The minimum bit-width that preserves the original accuracy varies significantly across different neural networks and even across different layers of a single neural network. Most existing designs overprovision accelerators with sufficient bit-width to preserve the required accuracy across a wide range of neural networks. In this research, we present MpDNN, a multi-precision deep neural network accelerator with dynamically adjustable bit-width. The design supports run-time splitting an arithmetic operator into multiple independent operators with smaller bit-width, effectively increasing throughput when lower precision is required. The proposed architecture is designed for FPGAs, in that the multipliers and bit-width adjustment mechanism are optimized for the LUTbased structure of FPGAs. Experimental results show that by enabling run-time precision adjustment mpDNN can offer 3-15x improvement in throughput.**


