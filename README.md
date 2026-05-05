# Encrypted_Network_Traffic_Behavioural_Analysis

## Python Environment and Kernel Setup

To ensure a reproducible and isolated development environment, a dedicated Python virtual environment was created for this project instead of modifying the system Python installation.

Initially, the notebook could not execute because the Jupyter kernel (ipykernel) was missing, and the default python command was not recognised in the system PATH. Additionally, the installed Python distribution was externally managed, preventing direct package installation to the global environment. To resolve this, a local virtual environment was created using the full Python executable path.

## Environment Setup Steps in vs terminal
**1. Create virtual environment(optional)**
c:/Users/badia/.local/bin/python3.14.exe (where your python is installed) -m venv venv 
a folder should appear named 'venv'

**2. Activate the virtual environment(optional)**
venv\Scripts\activate
the terminal should show (venv) in green in terminal. 

**3. Install required Jupyter kernel**
pip install ipykernel

**4. Register the environment as a notebook kernel**
python -m ipykernel install --user --name internetworking-project

**5. Select kernel in VS Code**
a. Open the notebook
b. Click Select Kernel > python environments > venv
you should be able to add code now

**6. Data_Processing.ipynb**
Run all code in Data_Processing.ipynb to prepare the data in your environment.
a Data folder should appear, under it should be Raw_Data/combined_raw_data.csv & Sample_Data/sample_data.csv

**7. Data_Analysis_plus_Modelling.ipynb**
Run the first 4 codes and data should be known


