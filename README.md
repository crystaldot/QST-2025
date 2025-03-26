# QST-2025
This repository contains jupyter notebooks for "Hands-on training session using Qiskit" as a part of Two Day Workshop on "Quantum Science and Technolog" organized by Department of Physics Pondicherry University in association with IAPT RC-13.

# Prerequisite Download and Installs for Workshop
### Setting Up Python, Jupyter, and Qiskit
This guide will help you set up Python (via Miniconda), install Jupyter Lab, Jupyter Notebook and required Qiskit packages for quantum computing.

## Step 1: Install Miniconda (Recommended)
Miniconda provides a lightweight environment with package management using `conda`.

### Download Miniconda
- **Windows:** [Download Latest version of Miniconda](https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe)
- **Mac or Linux:** [Choose and Download latest version of Miniconda](https://repo.anaconda.com/miniconda/)

### Install Miniconda
1. Run the downloaded installer and follow the installation steps.
2. Ensure that you select the option to **add Miniconda to your system PATH** (on Windows).
3. Open a terminal (Command Prompt, PowerShell, or Terminal) and verify the installation by running:

   ```sh
   conda --version
   ```
## Step 2: Open Anaconda Prompt or Terminal to install required packages
Activate and work in base environment by running:

```sh
conda activate
```
## Step 3: Install Jupyter Lab and Jupyter Notebook
Jupyter Lab or Jupyter Notebook is an interactive coding environment useful for running Python code.

```sh
conda install -c conda-forge jupyter -y
```

## Step 4: Install Qiskit and other required packages
Qiskit is an open-source quantum computing framework.

### Installing via pip
```sh
pip install qiskit
```
For visualization and quantum circuit drawing, install:
```sh
pip install qiskit[visualization]
```
Install Qiskit Aer (Quantum Simulator)
```sh
pip install qiskit-aer
```
## To start Jupyter Lab run:
```sh
jupyter lab
```

---
### You are now ready to start coding with Qiskit in Jupyter Notebook!
For more details, visit [Qiskit Documentation](https://qiskit.org/documentation/).

