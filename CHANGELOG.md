# Changelog

All notable changes to BitNeural32 are documented in this file.

## [0.0.10] - 2026-02-08
- **BUGFIX: Fixed reading custom QAT layers**

## [0.0.4-0.0.9] - 2025-12-28
- **QAT Fixes**

## [0.0.3] - 2025-12-28
- **Update Path fix**

## [0.0.2] - 2025-12-28
- **Update Readme**

## [0.0.1] - 2025-12-28

### Features
- **Quantization-Aware Training (QAT) Layers**: `TernaryDense`, `TernaryConv1D`, `TernaryConv2D`, `TernaryLSTM`, `TernaryGRU` for in-the-loop quantization during training
- **Keras 3.x Support**: Full compatibility with standalone Keras 3.0+ (TensorFlow 2.16+)
- **LSTM/GRU Layers**: Full recurrent layer implementation with quantized weights and batch weight unpacking for 5-10x speedup
- **Core Layers**: Dense, Conv1D, Conv2D, ReLU, LeakyReLU, Softmax, Sigmoid, Tanh, MaxPooling1D, Flatten, Dropout
- **Weight Compression**: 94% size reduction via 1.58-bit quantization
- **Python Compiler**: Automated Keras → C bytecode conversion
- **Board Profiles**: Performance estimation and metrics generation for ESP32, ESP32-S3, and ESP32-C3
- **Padé Approximations**: Fast sigmoid/tanh polynomial approximations without lookup tables
- **Type Safety**: Complete type hints for Python 3.9+
- **Comprehensive Documentation**: Full README with examples, API reference, and troubleshooting
