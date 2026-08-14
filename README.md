# Intro
This is the accompanying Github repository for the paper submission to Transactions in GIS. 


# Directory Guide


# Run guide
To completely recreate this Autoresearch experiment, this repository requires that you have a Python environment running at least `Python 3.12.13`, a valid Anthropic API key defined in a `.env` file, and all of the packages installed from `requirements.txt`. 

## Step 1
Confirm that your environment has a valid install of Python with at least version 3.12.13

```
Python --version
```

## Step 2
Rename the `.env.example` file to `.env` and change the [INSERT HERE] text with your Anthropic API key.

## Step 3
Within your virtual environemnt or Anaconda environment install all of the packages installed in `requirements.txt`

```
pip install -r requirements.txt
```

## Step 4
To reproduce the autoresearch experiment, run the code cells within the `Experiment.ipynb` file

## Step 5
To reproduce the figures in the paper, run the code cells within the `Figures.ipynb` file


