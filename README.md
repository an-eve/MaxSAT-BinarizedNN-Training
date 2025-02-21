# Binarized NN with MaxSAT

## Overview
This project trains **Binarized Neural Networks (BNNs)** using **MaxSAT**, encoding the problem as a SAT instance for optimization.

## Implementation
- **BNN without hidden layer**: Direct mapping.
- **BNN with hidden layer**: Improved non-linearity handling.

## Results
| Model | Solver Cost | Train Acc | Test Acc |
|-------|------------|-----------|----------|
| BNN (No Hidden Layer) | 27 | 0.75 | 0.54 |
| BNN (Hidden Layer) | 2 | 1.00 | 0.80 |

