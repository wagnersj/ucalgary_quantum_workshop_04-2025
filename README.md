# University of Calgary - IBM Quantum Workshop

April 14-15, 2025

## The Challenge

For this challenge, you will conduct a utility-scale quantum computation using an IBM Quantum system with over 100 qubits. It will involve mapping a physics problem to a quantum circuit and quantum operator using Qiskit and the Qiskit Runtime. You will need optimize the circuit to take the most advantage of the target hardware in order to obtain high fidelity results. Error mitigation and suppression techniques will be useful for getting the best results.

The challenge notebook will be released into this Github repo on the first day of the challenge (April 14).

## Requirements

- Python 3.9 or higher
- Qiskit v2. or higher
- Qiskit IBM Runtime v0.37 or higher
- Qiskit Aer
- A Jupyter notebook environment (e.g. Jupyter, Colab, Visual Studio Code, etc.)

You will also need an account on the IBM Quantum platform. Please reach out to your course instructor to arrange.

## Installing Qiskit

It is recommended that you use Python enviroments for installing Qiskit. You can facilitate this in one of two ways:

- Use the Python Virtual Environments package (```venv```)
- Use Anaconda or Miniconda Python, and the ```conda``` command

NOTE: Mac computers with M-series CPUs may find difficulty when installing Python packages needed for Qiskit. Notably, this includes the ```scipy``` package, which may invoke the installation commands to compile this module from source code. This is a long process and requires that C/C++ development tools are installed on your system. It is recommended that Mac M-series users use the Anaconda/Miniconda route for setting up their Python/Qiskit programming environment, and use the ```conda``` command to install ```scipy``` prior to installing Qiskit packages.

### Install with Virtual Environments (```venv```)

Check that Python is installed on your system by running the ```python --version``` command. If it is not installed, then download the latest version of Python from: https://www.python.org/downloads/ . If Python is already installed, verify that the version is v3.9 or higher.

Create a Python virtual environment:
```
python3 -m venv /path/to/virtual/environment
```

Activate this new environment:
```
source /path/to/virtual/environment/bin/activate
```

Now, skip to the Install Qiskit packages section for further instructions.

### Install Anaconda Python or Miniconda.

Install Anaconda from here: [https://www.anaconda.com/download](https://www.anaconda.com/download), OR
install Miniconda from here: [https://docs.anaconda.com/miniconda/miniconda-other-installer-links/](https://docs.anaconda.com/miniconda/miniconda-other-installer-links/)

Create a conda environment and activate:
```
conda create -n qiskit python=3
conda activate qiskit
```

NOTE: For Mac M-series computers, install the ```scipy``` packages as follows:
```
conda install scipy
```

Now, go to the next section Install Qiskit packages section for further instructions.

### Install Qiskit packages:
```
pip install qiskit qiskit-ibm-runtime
```

Install additional Qiskit packages:
```
pip install qiskit-aer 
```

Install Jupyter and other tools:
```
pip install jupyter matplotlib pylatexenc
```

## Further information

- Qiskit Documentation: [https://docs.quantum.ibm.com](https://docs.quantum.ibm.com)
- Qiskit installation instructions: [https://docs.quantum.ibm.com/guides/install-qiskit](https://docs.quantum.ibm.com/guides/install-qiskit)
