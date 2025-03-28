# QST-2025
This repository contains jupyter notebooks for "Hands-on training session using Qiskit" as a part of Two Day Workshop on "Quantum Science and Technology" organized by Department of Physics, Pondicherry University in association with IAPT RC-13.

# Prerequisite Download and Installation for Workshop
This guide will help you to set up Python (via Miniconda), install Jupyter Lab and required Qiskit packages for the training session.

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
## Step 2: Open Anaconda Prompt or Terminal to install Required Packages
Activate and work in base environment by running:

```sh
conda activate
```
## Step 3: Install Jupyter Lab
Jupyter Lab is an interactive coding environment useful for running Python code.

```sh
conda install -c conda-forge jupyter -y
```

## Step 4: Install Qiskit and other Required Packages
Qiskit is an open-source software stack for quantum computing, developed by IBM, allowing users to build and run quantum circuits on various hardware, including IBM's quantum computers.
1. Install `qiskit` along with _visualization_ capability via `pip` package manager
```sh
pip install qiskit[visualization]
```
2. Install `qiskit-aer` : Qiskit Aer is high-performance quantum computing simulator with realistic noise models.
```sh
pip install qiskit-aer
```
3. Install a few other required packages.
- `qiskit-algorithms` : Qiskit Algorithms is a library of quantum algorithms for quantum computing with Qiskit.
- `qiskit-experiments` : This can be used for characterizing, calibrating, and benchmarking experiments on quantum devices through Qiskit.
- `qiskit-ibm-runtime` : A client for Qiskit Runtime service, a cloud-based service for quantum computations on real quantum backends.
```
pip install qiskit-algorithms qiskit-experiments qiskit-ibm-runtime
```
# Create an IBMid on **[IBM Quantum](https://quantum.ibm.com/)** Platform
Through this platform you can access:
- IBM's latest quantum processing units (QPUs)
- IBM Quantum Learning: Courses, Tutorials and Composer
- Qiskit and API Documentations

# Launch Jupyter Lab
Run the following command from terminal.
```sh
jupyter lab
```
Above command will start a server from your terminal, to provide you with an interactive coding environment in your default browser (Recommended: Chrome, Firefox, Safari).
- Do not close the terminal during coding.
- You can stop the server by clicking Shut Down form File option in Mene Bar in Jupyter Lab environment or by pressing `CTRL+C` twice from you terminal window.

---
## You are now ready to start coding with Qiskit!
Training notebooks will be available in [`Tutorials`](https://github.com/crystaldot/QST-2025/tree/main/Tutorials) directory.
