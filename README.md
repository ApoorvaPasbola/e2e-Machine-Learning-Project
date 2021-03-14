# e2e-Machine-Learning-Project

# About
The project is an end to end ML project for Housing price prediction using sckit-learn.It shows all the steps which are required to make an ML project i.e. Visualizing,Preprocessing,Selecting Model, Fine-tuning and Testing.

# Prerequisite

1. Python installed in your local. You can check if its installed or not by running the following command in the terminal **python3 --version**. Required virson is python 3 to run the project
2. Pip installed. To check if pip is installed or not **python3 -m pip --version**. To upgrade your pip you can run **python3 -m pip install --user -U pip**
3. VirtualEnv in your local to create a virtual environment. Run the following to install virtualenv **python3 -m pip install --user -U virtualenv**

#  Setup to run the code

1. Create a virtual environment in where the code is cloned from the command **virtualenv machineLearningEnv**. To activate the virtual environment run **source machineLearningEnv/bin/activate** for linux and **.\machineLearningEnv\Scripts\activate** for windows.
2. Install the required dependencies for the project with the following command **python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn**
3. Check if all dependencier are installed correctly or not by running **python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, scikit-learn** in command promnt.
4. Run jupyter notebook in the same path where the Housing.ipynb is present with the virtual activated.
