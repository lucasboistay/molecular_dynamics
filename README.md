# Molecular Dynamics and Ab Initio Simulations : Developing a Predictive Model for Molecular Energy Configurations


This project involves utilizing results from ab initio molecular dynamics simulations to develop a model capable of predicting the energy associated with specific molecular configurations. It leverages two datasets: the first encompasses simulations on the dynamics of the Zundel ion (H2O-H-H2O), while the second focuses on a Mo2S4 aggregate. Each dataset contains about 10,000 atomic configurations and their corresponding potential energies, providing a comprehensive basis for accurate energy prediction in molecular systems.

<!-- TOC -->
* [Molecular Dynamics and Ab Initio Simulations : Developing a Predictive Model for Molecular Energy Configurations](#molecular-dynamics-and-ab-initio-simulations--developing-a-predictive-model-for-molecular-energy-configurations)
  * [Installation](#installation)
  * [Data set](#data-set)
  * [Strategy](#strategy)
  * [Results](#results)
  * [References](#references)
    * [Videos](#videos)
    * [Articles](#articles)
    * [Books](#books)
    * [Websites](#websites)
    * [Others](#others)
<!-- TOC -->

## Installation

To install, open in console (or Powershell on Windows) and copy : 

````shell
git clone https://github.com/lucasboistay/molecular_dynamics.git
cd molecular_dynamics
````

Then, for good measure, it's always good to make a VirtualEnvironment (check [documentation](https://docs.python.org/3/library/venv.html#how-venvs-work)), if you don't have 
the venv library install on your python, do : 
````shell
python -m pip install virtualenv
````

Then, once it's downloaded :

````shell
python -m venv ./.venv/
./venv/Scripts/activate
````

You are now in the Virtual Environment, but there is no library installed. To get them, install with the command :
````shell
python -m pip install --upgrade pip
pip install -r "requirements.txt"
````

Be careful if you use PyCharm or any other IDE, to use the interpreter found in the .venv/Scripts/python.exe !

Now, you can open and run the notebook
````shell
jupyter notebook main.ipynb
````

## Data set

## Strategy

## Results

## References

### Videos

- [Brief Introduction to ab initio Molecular Dynamics (AIMD)](https://www.youtube.com/watch?v=BeUCOsGC_eM)
- 

### Articles

### Books

### Websites

### Others