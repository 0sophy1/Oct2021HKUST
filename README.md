# Oct2021HKUST

Materials for the speical lecture on quantum computing (22, 29, Oct) at HKUST(Hong Kong University of Science and Technology)
(lecture link or description need to be added)

- Host: Prof. Gyu-Boong Jo,https://ultracold.ust.hk/ 
- Instructor: Soyoung (Sophy) Shin, 
  - PhD Candidat of Seoul National University
  - Research Scientist of Cambridge Quantum Computing Japan
  - Qiskit Advocate / Qiskit Localization Co-Lead ( Korean)
- Support:  
    -   Zipeng Wu, TA, HKUST
    -   Inho Choi, HKUST, Qiskit Advocate
 

# Before we go:


## Python Crash Course

Qiskit, and thus the lecture, is using Python. If you’re not familiar with Python, you can learn how the basics from the Qiskit Textbook chapter on [Python and Jupyter Notebooks](https://qiskit.org/textbook/ch-prerequisites/python-and-jupyter-notebooks.html). Jupyter notebooks are an interactive way to program and are the most common method for communicating Qiskit work. All lecture and assignments for the lecture are provided as Jupyter Notebooks. You can run these Notebooks with your local laptop with Qiskit installed or upload it to the IBM Quantum platform(IQX) to use. 

## IBM Quantum Account

You can register an account [here](https://auth.quantum-computing.ibm.com/auth/idaas?redirectTo=https%3A%2F%2Fquantum-computing.ibm.com%2F). You will be using the IBM Quantum Lab, which hosts Jupyter Notebooks for you. If you are not familiar with Jupyter or the IBM Quantum Lab, you can read the [Quantum Lab Guide](https://quantum-computing.ibm.com/lab/docs/iql/#qlab) for more information on how it is structured and what features are available.

## Working on the Labs locally

For a guide on setting up Qiskit on your own computer, have a look at the ['Getting Started'](https://qiskit.org/documentation/getting_started.html) page in the Qiskit documentation. 

Below is simple guide on it:


[Qiskit](https://github.com/Qiskit/qiskit "Qiskit") requires Python 3.6 or later. If you do not have Python, we recommend installing [Anaconda](https://www.anaconda.com/products/individual "Anaconda Individual Edition").

We recommend setting up a virtual environment. With Anaconda, you can follow the instructions [here](https://qiskit.org/documentation/install.html "Qiskit Installation Instructions"). If you are using pip, instructions how to create a virtual environment can be found [here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/).
After creating a new environment, activate it and make sure you have the latest version of pip by:
```
pip install --upgrade pip
```

Afterwards install the Qiskit package via below command, instead of that provided by the Qiskit documentation. This will make sure you have the correct dependencies.

```bash
pip install qiskit[all]
```

(if you are using zsh(Mac OS, etc), the last part needs to be in quotes as:)

```
pip install 'qiskit[all]'
```

Throughout the tutorial we will work with [Jupyter Notebooks](https://jupyter.org/ "Jupyter") which can be installed via 

```
pip install jupyterlab
```

### Testing your localQiskit installation

To check if the installation was successful, you can now start a Python prompt or a Jupyter notebook and run the following commands

```Python
import qiskit
qiskit.__qiskit_version__
```
