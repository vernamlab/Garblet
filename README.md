# Garblet: Multi-Party Computation for Protecting Chiplet-Based Systems

**Authors:** Mohammad Hashemi, Shahin Tajik, Fatemeh Ganji  
**Affiliation:** Worcester Polytechnic Institute (WPI), USA  

## Overview

Garblet is a secure multi-party computation (MPC) framework designed for protecting chiplet-based systems. It leverages **Garbled Circuits (GC)** and **Oblivious Transfer (OT)** to enable efficient and secure computation in the presence of potentially compromised chiplets. The framework is implemented on an **AMD/Xilinx UltraScale+** multi-chip module and introduces:

- A **customized hardware OT module** to reduce communication costs.
- An **optimized evaluator engine** for efficient garbled circuit evaluation.
- A **novel circuit decomposition technique** enabling parallel processing across multiple chiplets.
- Secure computation while minimizing overhead compared to traditional server-client MPC setups.

## Key Features

- **Chiplet-Based Secure Computation**: Secure function evaluation between chiplets, preventing malicious chiplets from leaking sensitive information.
- **Efficient Garbled Circuits Implementation**: Reduces communication complexity using a dedicated hardware OT module.
- **Parallel Execution**: A circuit decomposition method enables multiple chiplets to compute in parallel, accelerating execution time.
- **Hardware Security Isolation**: Separates security-critical tasks from general computations for enhanced security.

## Repository Contents

- **Paper PDF**: The research paper presenting Garblet.
- **Implementation Details**: Source code, experimental setup, and evaluation metrics.
- **Benchmark Results**: Performance comparisons with traditional MPC implementations.

## How to Cite

If you use Garblet in your research, please cite:

```
@article{hashemi2025garblet,
  title={Garblet: Multi-party Computation for Protecting Chiplet-based Systems},
  author={Hashemi, Mohammad and Tajik, Shahin and Ganji, Fatemeh},
  journal={Cryptology ePrint Archive},
  year={2025}
}
```

## Contact

For any questions or collaborations, feel free to reach out to:  
📧 fganji@wpi.edu | mhashemi@wpi.edu  

---

This repository is dedicated to advancing **secure computation for chiplet-based architectures**. Contributions and discussions are welcome!
