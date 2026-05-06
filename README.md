# Classical Hopfield Network for Associative Memory

## Overview

This project implements a classical Hopfield Neural Network for associative memory and pattern recovery tasks using structured binary alphabetic patterns.

The network is trained with Hebbian learning and evaluated under different levels of noise and memory capacity. Multiple visualisation experiments are included to analyse training behaviour, convergence dynamics, and retrieval performance.

---

## Features

- Classical Hopfield Network implementation
- Hebbian learning rule
- Structured 10×10 alphabetic patterns
- Noisy pattern recovery
- Weight matrix visualisation
- Training evolution analysis
- Noise robustness experiments
- Capacity evaluation
- Heatmap analysis of retrieval accuracy

---

## Technologies

- Python
- NumPy
- Matplotlib

---

## Installation

Install the required libraries:

```bash
pip install numpy matplotlib
```

---

## How to Run

Run the program using:

```bash
python hopfield.py
```

or

```bash
python3 hopfield.py
```

---

## Project Structure

```text
project/
│
├── hopfield.py
├── README.md
```

---

## Experiments Included

### 1. Stored Pattern Visualisation
Displays the binary alphabetic patterns stored in the network.

### 2. Weight Matrix Before and After Training
Compares the network weight matrix before and after Hebbian learning.

### 3. Weight Evolution
Shows how the weight matrix changes as more patterns are added during training.

### 4. Weight Statistics
Plots the statistical properties of the weight matrix during training.

### 5. Recovery Process
Demonstrates how noisy patterns converge toward stored attractor states.

### 6. Noise vs Accuracy
Evaluates retrieval accuracy under increasing noise levels.

### 7. Capacity Test
Measures how retrieval accuracy changes as more patterns are stored.

### 8. Noise vs Capacity
Analyses the combined effect of noise and memory load.

### 9. Accuracy Heatmap
Provides a visual overview of retrieval performance under different experimental conditions.

---

## Methodology

The implementation uses:

- Binary neuron states (+1 / −1)
- Hebbian learning for weight updates
- Synchronous state updates during recall
- Structured alphabetic memory patterns

Noise is introduced by randomly flipping pattern pixels.

Retrieval performance is evaluated using reconstruction accuracy.

---

## Main Findings

- The network performs well when storing a small number of patterns.
- Retrieval accuracy decreases as noise increases.
- Similar alphabetic structures cause memory interference.
- Larger memory loads significantly reduce recall performance.
- Under high noise conditions, the network may converge to incorrect attractor states.

---

## Example Output

The project generates:

- Pattern visualisations
- Weight matrix heatmaps
- Recovery process figures
- Noise-performance plots
- Capacity-performance plots
- Accuracy heatmaps

---

## References

1. Hopfield, J.J. (1982). *Neural networks and physical systems with emergent collective computational abilities*. Proceedings of the National Academy of Sciences, 79(8), 2554–2558.

2. Haykin, S. (2009). *Neural Networks and Learning Machines*. 3rd Edition. Pearson.

3. Goodfellow, I., Bengio, Y., and Courville, A. (2016). *Deep Learning*. MIT Press.

---

## Author

Yitian Ping
