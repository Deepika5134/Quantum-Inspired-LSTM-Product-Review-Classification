# Enhancing Product Review Classification Using Quantum-Inspired LSTM with Nature-Inspired Optimization

## Overview
This repository is for a student major project exploring product-review sentiment classification with a standard LSTM, a quantum-inspired LSTM (QLSTM), and a Red Deer Optimization (RDO)-based hyperparameter-selection approach. The notebook also contains additional comparison experiments.

## Current status
- Notebook included: `notebooks/major_code.ipynb`
- Dataset: not included in this repository. Place your authorized CSV at `data/reviews.csv` for local use, then update the notebook's file paths to `../data/reviews.csv` when running from the `notebooks` folder, or use the path appropriate to your environment.
- The notebook has not yet been fully re-run and validated from top to bottom in this packaged folder. Treat all reported metrics and plots as unverified until you execute the notebook and confirm they are generated from the current dataset.

## Dataset format expected by the notebook
The notebook expects a CSV with at least these columns:
- `content`: review text
- `score`: rating used to derive positive/negative sentiment labels

Do not upload a dataset unless you have permission to redistribute it. The provided `reviews.csv` file is intentionally excluded from Git.

## Setup
Recommended: run in Google Colab or a Python environment with compatible TensorFlow dependencies. Install packages listed in `requirements.txt`. The notebook downloads NLTK resources for stopwords; VADER experiments may also require the VADER lexicon.

## Run
1. Put your permitted dataset at `data/reviews.csv`.
2. Open `notebooks/major_code.ipynb` in Jupyter or Google Colab.
3. Update dataset paths for the environment you are using.
4. Run cells in order and inspect errors, metric calculations, and plots.
5. Document actual results only after a successful run.

## Attribution and project ownership
The notebook currently included in this repository was downloaded from the public repository `https://github.com/KeerthanaM44/QLSTM-with-RDO`. Please verify the source repository's license and permissions before redistributing or presenting the notebook. Keep attribution, preserve any applicable license, and clearly identify which parts were developed by your project team versus adapted from existing work. Do not claim third-party code as entirely original.

## Repository structure
- `notebooks/`: research and experiment notebook
- `data/`: local dataset location; CSV files are ignored by Git
- `src/`: space for reusable project code
- `results/`: space for verified plots and evaluation summaries
