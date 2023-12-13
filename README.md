# Machine Learning Project Repository

This repository contains the code and resources for a machine learning project. Below are the steps to set up and run the project in a Conda environment.

## Setup and Execution

### Prerequisites
- Ensure [Anaconda](https://www.anaconda.com/products/individual) is installed on your system.

### Step 1: Activate Conda Base Environment
First, activate the base Conda environment:

```bash
conda activate
```

### Step 2: Clone the GitHub Repository
Clone this repository to your local machine:

```bash
git clone [URL of the repository]
```

### Step 3: Change Directory
Navigate to the `ML_Project` directory:

```bash
cd ML_Project
```

### Step 4: Create Custom Conda Environment
Create a new Conda environment using the `environment.yaml` file:

```bash
conda env create -f environment.yaml
```

### Step 5: Activate the New Conda Environment
Activate the newly created Conda environment:

```bash
conda activate ml-proj
```

### Step 6: Start Jupyter Notebook
Launch Jupyter Notebook within this environment:

```bash
jupyter notebook
```

### Step 7: Open and Run the Project Code
- In the Jupyter Notebook server, navigate to the `Project Code` file.
- Open it and run the code cells.

### Training and Evaluation
- The repository includes checkpoints that can be loaded for evaluation.
- Alternatively, you can train the models from scratch and then proceed with the evaluation.

## Loading Checkpoints for Evaluation
To load the saved checkpoints for evaluation, refer to the specific instructions within the `Project Code` file.

## Training from Scratch
If you prefer to train the models from scratch, simply run the training cells in the `Project Code` file before proceeding to the evaluation.

---