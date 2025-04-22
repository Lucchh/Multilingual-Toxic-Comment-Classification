# Multilingual Toxic Comment Classification

## Dataset

The project uses two large CSV files that are not included in this repository due to their size:

1. `milestone3_df.csv` (295.46 MB)
2. `jigsaw-toxic-comment-train-processed-seqlen128.csv` (387.87 MB)

### How to Obtain the Dataset

1. Download the files from the original source:
   - [Jigsaw Multilingual Toxic Comment Classification Dataset](https://www.kaggle.com/c/jigsaw-multilingual-toxic-comment-classification/data)

2. Place the downloaded files in the root directory of this project.

### Data Processing

The dataset has been preprocessed and saved in the following files:
- `milestone3_df.csv`: Contains processed data from milestone 3
- `jigsaw-toxic-comment-train-processed-seqlen128.csv`: Contains the processed training data with sequence length of 128

## Setup

1. Create a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Project Structure

- `milestone4.ipynb`: Contains the main analysis and model development
- `milestone5.ipynb`: Contains the final model implementation and results
- `requirements.txt`: Lists all Python dependencies 