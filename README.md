# Parallel AutoML for Neural Networks

## Introduction
Parallel and distributed computing have become crucial for accelerating computational tasks in data-intensive domains. This project leverages these paradigms to enhance Automated Machine Learning (AutoML) for Neural Architecture Search (NAS). By utilizing frameworks such as TensorFlow, PyTorch, and Ray, this project enables faster training and evaluation of neural networks through parallel and distributed computing.

---

## Features
### Key Features
- **Automated Neural Architecture Search (NAS):** Automatically identifies the best network architecture by exploring configurations of layers, neurons, and hyperparameters.
- **Parallel Training:** Evaluates multiple architectures across CPUs/GPUs simultaneously.
- **Efficient Task Scheduling:** Uses Ray for effective parallel task management.
- **Dynamic Resource Allocation:** Ensures optimal CPU and GPU utilization.
- **Evaluation Metrics:** Measures accuracy, F1-score, and computational efficiency.
- **Early Stopping:** Saves resources by halting underperforming models early.
- **Visualization:** Uses TensorBoard for monitoring training progress and performance.

### Tools and Technologies
- **AutoML Frameworks:** KerasTuner for NAS.
- **Deep Learning Frameworks:** TensorFlow and PyTorch.
- **Parallel Computing:** Ray for task distribution.
- **Visualization:** TensorBoard and Matplotlib.
- **Hardware:** Multi-core CPUs and GPUs for parallel processing.

---

## Project Setup

### Prerequisites
- Python 3.10 or later
- Required Libraries: `ray`, `tensorflow`, `keras-tuner`, `sklearn`, `matplotlib`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Parallel-AutoML-for-NN/parallel-automl.git
   cd parallel-automl
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Dataset
The project uses the Breast Cancer dataset from `sklearn.datasets`. It includes 569 samples with features preprocessed for training.

---

## Contribution
We welcome contributions! Please fork the repository and create a pull request with a detailed description of your changes.

---

## Acknowledgments
- **Supervisor:** Dr. Umer Shoaib
- **Contributors:** Anas Majeed, Nauman Ali, Zain Ali
- **Institution:** BS CS VII - C, Parallel and Distributed Computing (CS-424)

---

## Contact
For any queries, please contact the contributors via GitHub or email.
