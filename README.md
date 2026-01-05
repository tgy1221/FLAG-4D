# FLAG-4D: Flow-Guided Local-Global Dual-Deformation Model for 4D Reconstruction

**Guan Yuan Tan, Ngoc Tuan Vu, Arghya Pal, et al.**

### **[AAAI 2026]** | [Paper](Coming Soon!) | [Project Page ]([https://tgy1221.github.io](https://tgy1221.github.io/flag4d/index.html#))

## Abstract

We introduce FLAG-4D, a novel framework for generating novel views of dynamic scenes by reconstructing how 3D Gaussian primitives evolve through space and time. Existing methods, often relying on a single MLP for temporal deformation, struggle with complex motions and fine-grained details. FLAG-4D overcomes this with a **dual-deformation network**: an **Instantaneous Deformation Network (IDN)** for fine-grained local deformations and a **Global Motion Network (GMN)** for long-range dynamics, synergistically refined via **mutual learning**. The GMN robustly integrates dense motion features from a pretrained optical flow backbone, which are temporally fused and aligned with each Gaussian's evolving state via a **deformation-guided attention mechanism**. Extensive experiments demonstrate that FLAG-4D achieves state-of-the-art performance, producing temporally coherent reconstructions with superior detail preservation.

## Getting Started
Code will be released soon! 

### 1. Installation

First, clone the repository:
```bash
git clone https://github.com/tgy1221/FLAG-4D.git
cd FLAG-4D
