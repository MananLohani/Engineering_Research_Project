# Classification of environments in an Immersive Virtual Reality based experiment

## Overview

This project analyses three key parameters which are routinely used in a virtual reality experiment namely blink rate, pupil diameter and NASA-TLX score. It then uses various combinations of these parameters as input to three state of the art classifiers namely Support Vector Machines, Logistic Regression and Random Forest. The results of these classification experiments are then analysed further to outline several interesting observations. This project is a part of the course "Introduction to Engineering Research" in Technical University of Delft(TUD). 

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methods](#methods)
4. [Installation](#installation)
5. [Contact](#contact)

## Introduction

The research question being analysed is "How effective are pupil diameter, blink rate and NASA TLX scores in classifying between different Immersive Virtual Rehabilitation setups for a participant?"

## Dataset
The project uses the dataset from a series of experiments conducted at the Motor Learning and Neurorehabilitation Lab in Technical University of Delft (TUD). Twenty-four healthy participants(Twelve male, twelve female) aged between 20 to 25 were selected from TUD for this experiment. The dataset is located under the datasets folder with each participant information stored in the corresponding folder numbered from P1 to P24. 

## Methods

The methodology for this project can further be understood by refering to the paper located in [Overleaf Document](https://www.overleaf.com/project/662924fd9658074c72060de8)

- **Data Collection:** The experiment dataset has been used for further analysis in this project. 
- **Data Analysis:** The extraction of each parameter along with the classification algorithms have been developed in tracking_code.ipynb

## Installation

To work with this project, open a new terminal in your system and type the below command to clone the repository. After that you can open the python notebook to view the entire analysis that has been conducted.

```bash
# Clone the repository
git clone https://github.com/MananLohani/Engineering_Research_Project.git

# Navigate to the project directory
cd Engineering_Research_Project
```
## Contact
- **Project Lead:** Manan Lohani (m.j.lohani@student.tudelft.nl)
