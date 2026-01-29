# PINNs-for-approximately-solving-PDEs-
This repository implements (PINNs) to solve PDEs, specifically focusing on the Heat Equation and Linear Elasticity Equations. Unlike traditional deep learning models that act as "black boxes," PINNs incorporate the underlying physical laws directly into the neural network's loss function. 
## 📝 Research Overview
[cite_start]This repository is based on our research paper: **"Physics-Informed Neural Networks for Approximately Solving Partial Differential Equations"**[cite: 23].

* [cite_start]**Authors:** Thi Thanh Mai Ta, **Thi Huong Giang Nguyen** (Hanoi University of Science and Technology)[cite: 25].
* [cite_start]**Conference:** Student Scientific Research Conference (SVNCKH 2024-2025)[cite: 47].
* [cite_start]**Key Contribution:** Explored the use of PINNs to solve PDEs by incorporating physical laws directly into the neural network's loss function using automatic differentiation[cite: 26, 56, 108].
* **Full Paper:** [📄 Download/View Research Paper (PDF)](./2025-05-06_15-37-38_Physics-Informed Neural Networks for Approximately Solving Partial.pdf)

## 🧪 Methodology & Implementation
* [cite_start]**Architecture:** Fully connected feedforward neural networks (FNN)[cite: 28, 71].
* [cite_start]**Optimization:** A hybrid approach using **Adam** (for initial convergence) and **L-BFGS** (for fine-tuning accuracy)[cite: 29, 205, 206].
* **PDEs Solved:**
    * [cite_start]**Steady-State Heat Equation:** Achieved $L_2$ error as low as $1.241 \times 10^{-6}$ with $L=5, N=32$ architecture[cite: 208, 209].
    * [cite_start]**Linear Elasticity Equation:** Successfully simulated 2D beam deformation under various boundary conditions (Cantilever & Fixed-fixed ends)[cite: 248, 268, 357].
