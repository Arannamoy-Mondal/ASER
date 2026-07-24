# AI Systems Engineer & Researcher Roadmap

---

# Phase 1 — Scientific Computing

1. [x] NumPy
2. [ ] Broadcasting
3. [ ] Einsum
4. [ ] Matrix Multiplication (MatMul)
5. [ ] Singular Value Decomposition (SVD)
6. [ ] Eigen Decomposition
7. [ ] Principal Component Analysis (PCA)
8. [ ] Fast Fourier Transform (FFT)
9. [ ] Convolution
10. [ ] KD-Tree
11. [ ] Ball Tree
12. [ ] SciPy
13. [ ] Open3D
14. [ ] NetworkX

---

# Phase 2 — Deep Learning From Scratch (Without PyTorch)

1. [ ] Tensor
2. [ ] Automatic Differentiation (Autograd)
3. [ ] Linear Layer
4. [ ] Conv2D
5. [ ] Batch Normalization
6. [ ] Layer Normalization
7. [ ] Dropout
8. [ ] Attention
9. [ ] Optimizer
10. [ ] Learning Rate Scheduler
11. [ ] Backpropagation

---

# Phase 3 — PyTorch Internals

1. [ ] Dataset
2. [ ] DataLoader
3. [ ] Sampler
4. [ ] DistributedSampler
5. [ ] Custom CUDA Extension
6. [ ] Custom Autograd Function
7. [ ] Automatic Mixed Precision (AMP)
8. [ ] Checkpointing
9. [ ] torch.compile
10. [ ] PyTorch Profiler
11. [ ] TorchScript

---

# Phase 4 — Architecture Implementation From Scratch

## Classical Deep Learning

1. [ ] MLP
2. [ ] CNN
3. [ ] AlexNet
4. [ ] VGG
5. [ ] ResNet
6. [ ] DenseNet
7. [ ] U-Net

## Vision Transformers

8. [ ] Vision Transformer (ViT)
9. [ ] Swin Transformer
10. [ ] ConvNeXt

## NLP Architectures

11. [ ] Transformer
12. [ ] BERT
13. [ ] GPT

## Point Cloud

14. [ ] PointNet
15. [ ] PointNet++
16. [ ] DGCNN
17. [ ] Point Transformer V2
18. [ ] Point Transformer V3
19. [ ] Point-BERT
20. [ ] Point-MAE
21. [ ] PointMamba

## Graph Neural Networks

22. [ ] GCN
23. [ ] GraphSAGE
24. [ ] GAT
25. [ ] GATv2
26. [ ] GIN
27. [ ] Graph Transformer
28. [ ] GraphGPS
29. [ ] Graphormer

## Tabular Learning

30. [ ] TabNet
31. [ ] TabTransformer
32. [ ] FT-Transformer
33. [ ] SAINT
34. [ ] TabPFN
35. [ ] TabFM

## Time Series

36. [ ] PatchTST
37. [ ] Informer
38. [ ] Autoformer
39. [ ] FEDformer
40. [ ] Chronos
41. [ ] TimesFM
42. [ ] TimeMamba

## Modern Architectures

43. [ ] Mamba
44. [ ] RWKV
45. [ ] Mixture of Experts (MoE)

---

# Phase 5 — Mathematics

1. [ ] Gradient Descent
2. [ ] Singular Value Decomposition (SVD)
3. [ ] QR Decomposition
4. [ ] Principal Component Analysis (PCA)
5. [ ] Bayesian Inference
6. [ ] Kalman Filter
7. [ ] Particle Filter
8. [ ] Graph Laplacian
9. [ ] Spectral Clustering

---

# Phase 6 — Algorithms & Data Structures

1. [ ] Sorting Algorithms
2. [ ] Trees
3. [ ] Graph Algorithms
4. [ ] Trie
5. [ ] Union-Find (Disjoint Set Union)
6. [ ] KD-Tree
7. [ ] R-Tree
8. [ ] Octree
9. [ ] Bounding Volume Hierarchy (BVH)
10. [ ] Segment Tree
11. [ ] Fenwick Tree

---

# Phase 7 — Learning Paradigms

## Self-Supervised Learning

1. [ ] SimCLR
2. [ ] MoCo
3. [ ] BYOL
4. [ ] SimSiam
5. [ ] DINO
6. [ ] Masked Autoencoders (MAE)
7. [ ] Point-MAE
8. [ ] BERT Masked Language Modeling
9. [ ] GPT Causal Language Modeling

---

## Semi-Supervised Learning

10. [ ] Pseudo Labeling
11. [ ] Mean Teacher
12. [ ] FixMatch
13. [ ] MixMatch
14. [ ] FlexMatch
15. [ ] Noisy Student

---

## Active Learning

16. [ ] Least Confidence Sampling
17. [ ] Margin Sampling
18. [ ] Entropy Sampling
19. [ ] BALD
20. [ ] Core-Set Selection
21. [ ] BADGE
22. [ ] Learning Loss
23. [ ] VAAL
24. [ ] Region-Based Active Learning
25. [ ] Chunk-Based Active Learning

---

## Continual Learning

26. [ ] Elastic Weight Consolidation (EWC)
27. [ ] Learning without Forgetting (LwF)
28. [ ] Experience Replay
29. [ ] Incremental Learning

---

## Transfer Learning

30. [ ] Fine-Tuning
31. [ ] Domain Adaptation
32. [ ] Domain Generalization
33. [ ] Multi-Task Learning

---

# Phase 8 — Uncertainty & Calibration

1. [ ] Monte Carlo Dropout
2. [ ] Deep Ensemble
3. [ ] Evidential Deep Learning
4. [ ] Dirichlet Prior Network
5. [ ] Temperature Scaling
6. [ ] Conformal Prediction
7. [ ] Model Calibration

---

# Phase 9 — GPU Programming

1. [ ] CUDA
2. [ ] OpenCL
3. [ ] Triton
4. [ ] Kernel Fusion
5. [ ] Shared Memory
6. [ ] Warp Programming
7. [ ] Tensor Cores

---

# Phase 10 — Distributed AI

1. [ ] Distributed Data Parallel (DDP)
2. [ ] Fully Sharded Data Parallel (FSDP)
3. [ ] DeepSpeed
4. [ ] Ray
5. [ ] vLLM
6. [ ] NCCL
7. [ ] MPI

---

# Phase 11 — Systems Optimization

1. [ ] FlashAttention
2. [ ] Quantization
3. [ ] LoRA
4. [ ] QLoRA
5. [ ] KV Cache
6. [ ] Paged Attention
7. [ ] Speculative Decoding

---

# Phase 12 — Research Programming (Hands-On Implementations)

1. [ ] Transformer
2. [ ] FlashAttention
3. [ ] Mamba
4. [ ] Mixture of Experts (MoE)
5. [ ] Diffusion Models
6. [ ] CLIP
7. [ ] Segment Anything Model (SAM)
8. [ ] DINO / DINOv2
9. [ ] Masked Autoencoder (MAE)
10. [ ] Point-MAE
11. [ ] PointMamba
12. [ ] Graph Transformer
13. [ ] GraphGPS
14. [ ] TabFM
15. [ ] TimesFM
16. [ ] Chronos
17. [ ] Retrieval-Augmented Generation (RAG)
18. [ ] AI Agent Framework



```
                 Mathematics
                      │
                      ▼
            Scientific Computing
                      │
        ┌─────────────┴─────────────┐
        ▼                           ▼
 Deep Learning Scratch       Algorithms
        │                           │
        ▼                           ▼
 PyTorch Internal          GPU Programming
        │                           │
        └─────────────┬─────────────┘
                      ▼
           Architecture Implementation
                      │
         ┌────────────┼────────────┐
         ▼            ▼            ▼
     Learning  Research Models   Distributed AI
     Paradigms
 ```