# Oct2021HKUST

Materials for the speical lecture on quantum computing (22, 29, Oct) at HKUST(Hong Kong University of Science and Technology)

- Host: Prof. Gyu-Boong Jo,https://ultracold.ust.hk/ 
- Instructor: Soyoung (Sophy) Shin, 
  - PhD Candidat of Seoul National University
  - Research Scientist of Cambridge Quantum Computing Japan
  - Qiskit Advocate
- Support: Inho Choi, Undergraduate, HKUST / Qiskit Advocate
 

# Before we go:


## Python Crash Course

Qiskit, and thus the lecture, is using Python. If you’re not familiar with Python, you can learn how the basics from the Qiskit Textbook chapter on [Python and Jupyter Notebooks](https://qiskit.org/textbook/ch-prerequisites/python-and-jupyter-notebooks.html). Jupyter notebooks are an interactive way to program and are the most common method for communicating Qiskit work. All lecture and assignments for the lecture are provided as Jupyter Notebooks. You can run these Notebooks with your local laptop with Qiskit installed or upload it to the IBM Quantum platform(IQX) to use. If you want to run Notebooks at IQX need an account and next part will guide you how to make it.

## IBM Quantum Account

You can register an account [here](https://auth.quantum-computing.ibm.com/auth/idaas?redirectTo=https%3A%2F%2Fquantum-computing.ibm.com%2F). You will be using the IBM Quantum Lab, which hosts Jupyter Notebooks for you. If you are not familiar with Jupyter or the IBM Quantum Lab, you can read the [Quantum Lab Guide](https://quantum-computing.ibm.com/lab/docs/iql/#qlab) for more information on how it is structured and what features are available.

## Working on the Labs locally

For a guide on setting up Qiskit on your own computer, have a look at the ['Getting Started'](https://qiskit.org/documentation/getting_started.html) page in the Qiskit documentation. When you install Qiskit using pip, make sure you run the following command instead of that provided by the Qiskit documentation. This will make sure you have the correct dependencies.

```bash
pip install qiskit[all]
```
