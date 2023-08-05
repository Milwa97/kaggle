# Kaggle NLP Challenges with Hugging Face Pre-trained Models

## Table of Contents

1. [Introduction](#introduction)
2. [Setup](#setup)
3. [Notebook Descriptions](#notebook-descriptions)
4. [Usage](#usage)
5. [License](#license)

## Introduction

This repository contains Jupyter notebooks showcasing solutions to various Kaggle challenges 
related to Natural Language Processing (NLP). Due to luck of time and resources, the solutions are implemented using 
Hugging Face pre-trained models. Each notebook focuses on a specific Kaggle challenge,
providing challenge description, data preprocessing, fine-tuning models and results. 
For each challenge two training approaches are presented: pytorch and pytorch-lightning


## Setup

To use the notebooks in this repository, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/Milwa97/kaggle
   ```

2. Install the required dependencies. It is recommended to create a virtual environment:

   ```bash
   cd kaggle
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Download the datasets for the specific Kaggle challenges you are interested in. 
Update the notebook paths and file references accordingly.

4. Run jupyter notebook and navigate to the challenge You are interested in:

   ```bash
   jupyter notebook
   ```
   

## Notebooks Descriptions

1. Text Classification of Coronavirus Tweets
   - Utilizes the BERT model for text classification on Coronavirus Tweets
   - Preprocesses text data, fine-tunes the BERT model, and evaluates its performance.

2. Named Entity Recognition using BERT
   - Implements Named Entity Recognition using BERT.
   - Shows how to convert text annotations to NER training data and evaluate the model.

3. Contradictory, My Dear Watson
   - TO DO

...


## Usage

Each notebook is designed to be self-contained and can be run sequentially. 
Simply open the notebook in Jupyter and execute each cell step-by-step. 
Remember to modify paths and file references to match your local setup and data locations.
The notebooks can run both on GPU or CPU. To successfully run the notebooks,
it is recommended to have a GPU with at least 4 GB of memory.
Insufficient GPU memory might lead to training failures or out-of-memory errors.


## License

This repository is licensed under the MIT License. Feel free to use the code and notebooks for your educational and personal projects.

---