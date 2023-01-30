
# Network_Intrusion_Detection

I took an interest in understanding how IDS works and decided to develop a machine learning project to imitate an IDS. Hence the goal of this project is to be able to mimic the behaviour of an IDS in order to be able to detect anomaly access. Throughout this project, many algorithms have been selected to better fit the criteria such as random forest tree, xgbboost, catboost, decision trees and etc. 

## Disclaimer
This project has been tested through google colab. Hence you will notice some codes that will throw you an error as your python packages might not all be installed. This is specifically the case with lines such as "!pip install JohnDoe". an easy workaround is to either install each package manually inside the terminal by issuing the same commands without "!", as an example "pip install JohnDoe", or install required libraries to be able to use those lines. 

# Getting Started

## Prerequisites
- Jupyter Notebook capable IDE (wether google colab or system based install)
- Python 3.8+

## Git Installation
Download the git installer from [Git](https://git-scm.com/downloads) follow the installation steps to install git on your device. If using linux, use the following inside terminal:

```
git --version 
```
If the output shows git with a version, then skip Git installation section as you already have git installed

If git was not installed, do the following
```
sudo apt-get update; sudo apt-get install git -y
```
## Anaconda Installation
Download and install anaconda according to [anaconda documentation: Installing on Windows](https://docs.anaconda.com/anaconda/install/windows/) or [anaconda documentation: Installing on Linux](https://docs.anaconda.com/anaconda/install/linux/) with respects to your operating system.

## Jupyter Notebook
### For Windows :
- Open Anaconda Navigator
- Hover Jupyter notebook and click Install 

### For Linux
- Activate the environment using
```
conda activate "your-env-name"
```
- Install jupyter using pip3
```
pip3 install jupyter
```
## Project Cloning 

To clone this project use the following
```
git clone https://github.com/kasra-sal/Network_Intrusion_Detection.git
```

# Demo
As this was done in google colab, you should be able to view the output of the codes on the book that is shared on my repo. Simply either run the book on your pc or refer to the one on my repository. 
