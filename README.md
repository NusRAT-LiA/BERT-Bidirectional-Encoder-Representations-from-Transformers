# BERT Implementation from Scratch in PyTorch

code: https://colab.research.google.com/drive/1qMFUnpR41DDdHZwGl4JRplTrAMKhHaYO?usp=sharing


This repository contains a PyTorch implementation of BERT (Bidirectional Encoder Representations from Transformers) built from scratch. The model includes essential components such as self-attention, position encoding, and transformer encoder layers. It supports pretraining tasks like Masked Language Modeling (MLM) and Next Sentence Prediction (NSP).

## Features
- **BERT Base Architecture**: 12-layer Transformer encoder
- **Pre-training Tasks**: MLM (15% masking) + NSP
- **Custom Tokenizer**: Built on WikiText-2 vocabulary
- **Training Pipeline**: Batch processing and loss tracking
- **Inference API**: Predict masked tokens in input sentences
