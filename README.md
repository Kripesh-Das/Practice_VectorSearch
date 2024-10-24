# Project Title

## Overview
This project appears to be a data analysis or machine learning project, given the presence of a Jupyter notebook and a JSON file with BM25 values.

## Project Structure
- `.env`: Environment variables file.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `bm25_values.json`: JSON file containing BM25 values.
- `experiments.ipynb`: Jupyter notebook for running experiments.
- `requirements.txt`: List of Python dependencies.

## Setup
1. **Clone the repository:**
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Create a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**
    - Copy `.env.example` to `.env` and fill in the required values.

## Usage
1. **Run Jupyter Notebook:**
    ```sh
    jupyter notebook experiments.ipynb
    ```

2. **Load and analyze the data in `experiments.ipynb`.**

