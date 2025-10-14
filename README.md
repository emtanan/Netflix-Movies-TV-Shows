# Netflix Data Analysis

This repository presents an **Exploratory Data Analysis (EDA)** of the [Netflix Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows/data?select=netflix_titles.csv).  
The analysis explores content types, genres, durations, countries, and release year trends on Netflix.

---

## 📊 Dataset Description
The dataset includes information such as:
- Type (Movie or TV Show)
- Title, Director, Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre (Listed In)
- Description

---

## 🎯 Objective
To clean, explore, and visualize Netflix data to understand:
- Distribution of Movies vs TV Shows  
- Most common genres and producing countries  
- Trends of releases over the years  
- Duration and ratings distribution  

---

## ⚙️ Project Structure
```
Netflix-Data-Analysis/
│
├── Data/                      # Dataset (.csv)
│   └── netflix_titles.csv
│
├── Code/                      # Scripts and notebooks
│   ├── netflix_analysis.py
│   └── netflix_analysis_colab.ipynb
│
├── Result/                    # Output PDF and charts
│   └── Netflix_Titles_Data_Analysis.pdf
│
├── README.md
└── requirements.txt
```

---

## 🧩 Methods
- Data preprocessing with **pandas**
- Feature engineering (genre, duration)
- Visualization using **matplotlib**
- Export results as a structured **PDF report**

---

## 📈 Results
The generated report includes:
- Type distribution (Movies vs TV Shows)
- Top genres and countries
- Release trends (3-year rolling mean)
- Movie durations
- Content ratings

📄 **Result Example:**  
[View the PDF Report](Result/Netflix_Titles_Data_Analysis.pdf)

---

## 🧠 Requirements
Install dependencies before running:
```bash
pip install -r requirements.txt
```

---

## 👩‍💻 How to Run
### Option 1 — Run Script
```bash
python Code/netflix_analysis.py
```
Generates a PDF in the `Result/` folder.

### Option 2 — Run in Colab
Open and execute:
```
Code/netflix_analysis_colab.ipynb
```

---

## 🧾 Reference
Dataset source: [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows/data)

---

## ✍️ Authors
**Thanapat Iampramool (6713367)**  
**Emtanan Malarat (6713397)**
