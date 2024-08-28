# Jupyter Notebook Course Lab

This repository contains the Jupyter Notebook for the course labs. Follow the instructions below to set up your environment and run the notebook.

## Course Link

[UChicagoX QCS11000 Course](https://learning.edx.org/course/course-v1:UChicagoX+QCS11000+3T2023/home)

## Requirements

- Python 3.8: [Download Python 3.8](https://www.python.org/downloads/release/python-388/)
- Terminal access:
  - **Linux and macOS**: Open the Terminal app
  - **Windows**: Options include [Git Bash](https://git-scm.com/download/win) or [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/learn/modules/get-started-with-windows-subsystem-for-linux/). You can also use Command Prompt or PowerShell, but some commands may differ.

## Setting Up Your Environment

1. **Install Python 3.8**:
   - Download and install from [here](https://www.python.org/downloads/release/python-388/).

2. **Open a Terminal**:
   - **Linux and macOS**: Open the Terminal app.
   - **Windows**: Use Git Bash, WSL, Command Prompt, or PowerShell.

3. **Create and Activate a Python Virtual Environment** (optional but recommended):
   - Follow the guide [here](https://realpython.com/python-virtual-environments-a-primer/).

4. **Install Jupyter Notebook**:
   - Run the following command in your terminal:
     ```sh
     python3 -m pip install jupyter
     ```

5. **Launch Jupyter Notebook**:
   - Navigate to your class directory:
     ```sh
     pwd
     cd your/class/directory
     ```
   - Start Jupyter Notebook:
     ```sh
     python3 -m jupyter notebook
     ```
   - This command will open the Jupyter application in a browser window. Select the `labX.ipynb` notebook file you downloaded.

6. **Install Required Python Packages**:
   - In the Jupyter menu, select `New -> Python` and run the following command in a cell:
     ```python
     !pip install numpy matplotlib networkx qiskit~=0.34.0
     ```

Follow these steps to set up your environment and run the Jupyter Notebook for the course lab.