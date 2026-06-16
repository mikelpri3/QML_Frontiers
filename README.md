# 🌌 QML Frontiers

Welcome to **QML Frontiers**, a repository dedicated to exploring the capabilities and frontiers of Quantum Machine Learning (QML). This repository contains hands-on tutorials and the practical implementation of a Final Degree Project (Bachelor's Thesis) focusing on solving various problems using quantum algorithms.

## ⚙️ Installation

To run the notebooks and reproduce the experiments, you need to install the required dependencies. It is recommended to use a virtual environment.

Clone the repository and install the requirements using `pip`:

```bash
git clone https://github.com/mikelpri3/QML_Frontiers.git
cd QML_Frontiers
pip install -r requirements.txt
```

## 📂 Repository Structure

The repository is organized into several key directories:

### 📖 `tutorials/`
This folder contains various introductory and exploratory tutorials for **Qiskit** and **PennyLane**. These notebooks dive into the core capabilities of both libraries. 
> **Note:** Some of these tutorials are written in Spanish.

### 🎓 `project/`
This folder is the core of the repository. It contains the experimental part of a Final Degree Project, consisting of 5 different Jupyter Notebooks, each tackling a distinct problem using QML techniques:

*   📉 **`IBM_Transaction.ipynb` (Fraud Detection):** Focuses on tackling data imbalance and dealing with low variance in Principal Components (PCA).
*   🧬 **`PBMC_Quantum_SVM.ipynb` (Quantum SVM):** Explores Quantum Support Vector Machines, running tests with varying amounts of qubits and different data dimensionalities.
*   🔊 **`iris_noise_techniques.ipynb` (Noise Mitigation):** A detailed comparison between perfect (ideal) simulators and noisy simulators, implementing and evaluating various anti-noise/mitigation techniques.
*   👨‍⚕️ **`medmnist_TTN_CNN.ipynb` (Image Classification):** A hybrid approach classifying pneumonia in medical images using Hybrid Quantum-Classical models (TTN + CNN).
*   🌙 **`moons_NN_QNN.ipynb` (Ansatz Optimization):** Focuses on the non-linear separation of the `make_moons` dataset, exploring techniques to optimize the quantum circuit ansatz.

### 🔬 Development & Data Folders

*   📊 **`data/`**: Currently contains the `pbmc3k` dataset used for the quantum SVM experiments.
*   🧮 **`gram_matrices/`**: Stores the pre-computed Gram matrices saved from the `PBMC_Quantum_SVM` tests to save computational time during re-runs.
*   🗑️ **`failed_experiments/`**: Contains discarded versions of previous experiments. These were set aside either due to the excessive simplicity of the datasets or suboptimal implementations of the quantum techniques. 

## 🛠️ Main Technologies Used
*   **Python 3**
*   **Qiskit** (IBM Quantum)
*   **PennyLane** (Xanadu)
*   **PyTorch / TensorFlow** (for hybrid models)
*   **Scikit-Learn, Pandas, NumPy**

---
*Created by [mikelpri3](https://github.com/mikelpri3)*
