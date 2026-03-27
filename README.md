# Movie-Recommendation System

## Overview

This project builds a **Movie Recommendation System** using content-based filtering techniques.

The system recommends movies based on similarity between features.

---

## How it Works

The recommendation system follows these steps:

1- Data Collection

* Uses TMDB datasets (`tmdb_5000_credits.csv`)

2️- Data Preprocessing

* Merge datasets
* Handle missing values
* Extract important features (cast, crew)

3- Feature Engineering

* Combine selected features into a single text column (tags)

4- Text Vectorization

* Apply **TF-IDF** to convert text into numerical vectors

5- Similarity Calculation

* Use **Cosine Similarity** to measure similarity between movies

6- Recommendation

* Given a movie, return top similar movies

---

## Dataset

* Source: TMDB 5000 Movie Dataset
* Files used:

  * `tmdb_5000_credits.csv`

---


## How to Run

### Clone the repository

```bash

git clone https://github.com/engasmaaibrahim/Movie-Recommendation-System.git
cd Movie-Recommendation-System

```

### Create and activate virtual environment

#### On Windows:

```bash

python -m venv env
env\Scripts\activate

```

#### On Mac/Linux:

```bash

python3 -m venv env
source env/bin/activate

```

---

### 3- Install dependencies

```bash

pip install -r requirements.txt

```

---

### Run Jupyter Notebook

```bash

jupyter notebook

```

Then open:

```
main.ipynb
```

---

## Author

**Asmaa Ibrahim**
AI & Machine Learning Engineer
