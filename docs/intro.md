---
sidebar_position: 1
---

# Quick Start

SIMCA is a **Python/Qt application** to perform optical simulations for Coded Aperture Snapshot Spectral Imaging (CASSI).


## Step 1 : Installation

Follow the steps below to install SIMCA:

```bash
# Clone the repository from GitLab
git clone git@gitlab.laas.fr:arouxel/simca.git
cd simca
```

After cloning the repository, you will need to create a dedicated Python environment. For the purpose of these instructions, we will use Miniconda. If you don't have Miniconda installed, you can find the instructions [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html).

```bash
# Create a new Python environment
conda create -n simca-env python=3.9

# Activate the environment
conda activate simca-env
```

Next, you'll need to install the necessary Python packages that SIMCA relies on. These are listed in the `requirements.txt` file in the repository.

```bash
# Install necessary Python packages with pip
pip install -r requirements.txt
```

## Step 2 : Add Scenes to analyze and/or acquire

Get the standard scenes from this [link](https://cloud.laas.fr/index.php/s/zfh5RFmsjYfk108).

Copy and paste the `datasets` folder in the root directory of SIMCA.

&#x1F389 You now have scenes to analyze &#x1F389

## Step 3 : Start the application

```bash
# run the app
python main.py
```




