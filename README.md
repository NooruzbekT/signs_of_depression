# Suicide Detection Project

## Description
This project is designed to analyze and predict signs of depression and suicidal thoughts based on textual data. The dataset is sourced from Kaggle and processed using Python and the pandas library.

## Dataset
We use the [Suicide Watch Dataset](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch), which contains text messages classified as "suicide" and "non-suicide."

## Project Structure
- `main.ipynb` — Main Jupyter Notebook containing the data processing code.

## Installation and Setup
### 1. Clone the Repository
```sh
    git clone https://github.com/NooruzbekT/signs_of_depression
```
### 2. Install Dependencies
It is recommended to use a virtual environment:
```sh
    python -m venv venv
    source venv/bin/activate  # For Linux/macOS
    venv\Scripts\activate  # For Windows
```
### 3. Download the Dataset
Download the CSV file from Kaggle and save it in the `data/` folder.

### 4. Run Jupyter Notebook
```sh
    jupyter notebook
```
Open `main.ipynb` and execute the cells sequentially.

## Data Processing Steps
1. Load data from CSV.
2. Balance classes (25,000 records per class).
3. Clean text by removing links and special characters.
4. Save the processed dataset.

## Contact
For any inquiries or issues, please contact `nookentoktobaev@gmail.com`.

