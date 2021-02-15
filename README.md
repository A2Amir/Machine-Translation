## Introduction

In this repository, I will build deep neural networks that function as part of an end-to-end machine translation pipeline. My completed pipeline will accept English text as input and return the Persian translation.

The [notebook](https://github.com/A2Amir/Machine-Translation/blob/main/Machine%20Translation%20.ipynb) consists of four parts:

   - Dataset: **To laod and investigate dataset.**
   - Preprocess: **To convert text to sequence of integers.**
   - Models: **To Create models which accept a sequence of integers as input and returns a probability distribution over possible translations.**
   - Prediction: **To use the trained model to make prediction on test dataset.**


In the **Models section**, I will experiment with various neural network architectures. I will begin by training four relatively simple architectures.

   - Model 1 is a simple GRU
   - Model 2 is a GRU with Embedding
   - Model 3 is a Bidirectional GRU
   - Model 4 is an Encoder-Decoder GRU

After experimenting with the four simple architectures, I will construct a deeper architecture that is designed to outperform all four models which uses **Attention mechanism.**
