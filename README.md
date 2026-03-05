# Book Data Analysis & Machine Learning Pipeline

An end-to-end data science project that collects book data using web scraping, performs exploratory data analysis (EDA), trains machine learning models, and stores processed data in a structured database.

This project demonstrates a practical machine learning workflow including **data acquisition, preprocessing, analysis, model development, and database integration**.

# Project Overview

The goal of this project is to build a complete data pipeline for analyzing book datasets and extracting insights using machine learning techniques.

The pipeline includes:

- Web scraping to collect book data
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Machine learning model training
- Database storage for structured data management

This project simulates a **real-world data engineering and machine learning workflow**.

# 🏗 Project Pipeline


Web Scraping
      ↓
Raw Dataset
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Machine Learning Model Training
      ↓
Model Evaluation
      ↓
Database Storage


# 📊 Data Collection

Book data is collected through web scraping from publicly available book listing websites.

### Extracted Features

- Book Title  
- Author  
- Genre  
- Price  
- Rating  
- Number of Reviews  
- Book Description  
- Availability  

### Tools Used

- Python  
- BeautifulSoup  
- Requests  
- Pandas  

The collected data is stored in structured format for further analysis.

# Exploratory Data Analysis (EDA)

EDA was conducted to understand patterns and trends within the dataset.

Key analysis includes:

- Distribution of book ratings
- Genre popularity
- Relationship between number of reviews and ratings
- Price vs rating patterns

### Visualization Libraries

- Matplotlib
- Seaborn

# Machine Learning Model

A machine learning model was trained to analyze patterns in the dataset and generate predictive insights.

### ML Workflow

1. Data preprocessing  
2. Feature engineering  
3. Model training  
4. Model evaluation  

### Algorithms Used

- Linear Regression
- Random Forest
- Gradient Boosting

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

# Database Storage

Processed data and model results are stored in a database for persistent storage and further analysis.

### Database Technology

- SQLite / MySQL / PostgreSQL

### Stored Data

- Raw scraped dataset
- Cleaned dataset
- Model outputs

# Tech Stack

**Programming Language**

- Python

**Data Collection**

- BeautifulSoup
- Requests

**Data Processing**

- Pandas
- NumPy

**Visualization**

- Matplotlib
- Seaborn

**Machine Learning**

- Scikit-learn

**Database**

- SQL / SQLite / MySQL


# Project Structure


book-ml-pipeline
│
├── data
│   ├── raw
│   └── processed
│
├── notebooks
│   └── eda.ipynb
│
├── scraping
│   └── scraper.py
│
├── models
│   └── train_model.py
│
├── database
│   └── db_pipeline.py
│
├── requirements.txt
└── README.md


#  Installation

Clone the repository

```bash
git clone https://github.com/yourusername/book-ml-pipeline.git
```

Navigate to the project directory

```bash
cd book-ml-pipeline
```

Install dependencies

```bash
pip install -r requirements.txt
```

# Usage

Run the web scraper

```bash
python scraper.py
```

Perform EDA and analysis

```bash
jupyter notebook notebooks/eda.ipynb
```

Train the machine learning model

```bash
python train_model.py
```

Store processed data in the database

```bash
python db_pipeline.py
```

---

# Future Improvements

- Implement NLP analysis for book descriptions
- Build a book recommendation system
- Deploy the model using FastAPI
- Create a Streamlit dashboard for interactive insights


#  Key Learnings

This project demonstrates practical experience in:

- Web scraping
- Data preprocessing and analysis
- Machine learning model development
- Data pipeline creation
- Database integration


#  Author

Harikrishnan NT

Harikrishnan N T  
Aspiring AI/ML Engineer
