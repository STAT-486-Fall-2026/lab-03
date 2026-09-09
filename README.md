# Lab 03: Scikit-learn Regression Pipelines

<!-- STAT 486 · Fall 2026 -->

## Objective

Build, evaluate, tune, interpret, and serialize scikit-learn regression pipelines using oceanographic data.

## Before you begin

You need Git, a GitHub account, and [uv](https://docs.astral.sh/uv/getting-started/installation/) installed on your computer.

## Set up your submission repository

### 1. Create your private submission repository

On [`STAT-486-Fall-2026/lab-03`](https://github.com/STAT-486-Fall-2026/lab-03), select **Use this template** and then **Create a new repository**. Set the owner to the `STAT-486-Fall-2026-Labs` organization, name the repository exactly:

```text
lab-03-<netid>
```

For example, a student whose NetID is `jdoe42` must create `lab-03-jdoe42`. Use your institutional NetID even if it differs from your GitHub username. Make the repository **private**, then create it. Do not fork the starter repository.

### 2. Clone your repository

Copy the HTTPS URL for **your repository**, then run the following commands. Replace the NetID placeholder.

```bash
git clone https://github.com/STAT-486-Fall-2026-Labs/lab-03-<netid>.git
cd lab-03-<netid>
```

### 3. Create and lock your environment

The starter repository includes a lab-specific `pyproject.toml`. From the repository directory, run:

```bash
uv sync
```

This creates your local `.venv` and generates `uv.lock`. Keep the supplied `pyproject.toml` unchanged unless the lab directions explicitly say otherwise. Commit the generated `uv.lock` with your work, but never commit `.venv`.

### 4. Complete the lab

Open `lab-03.ipynb` in your preferred editor and configure it to use the Python interpreter or notebook kernel in this repository's `.venv`.

Complete every prompt and response space in the notebook. The repository includes the training data and new-value data in `data/`, so no download is required. Run the notebook from top to bottom before submitting. Your final model must be saved as `lab-03-final-model.joblib` and must accept the raw columns in `data/ocean_data_newvalues.csv`.

### 5. Commit and push your work

```bash
git add lab-03.ipynb lab-03-final-model.joblib uv.lock
git commit -m "Complete Lab 03"
git push
```

## Submission

Paste the root URL of your repository into the Canvas Lab 03 submission textbox:

```text
https://github.com/STAT-486-Fall-2026-Labs/lab-03-<netid>
```

Do not open a pull request and do not upload the notebook file to Canvas.
