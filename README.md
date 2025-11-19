# 📱 Google Play Store Apps Analysis

## 📌 Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on a dataset of **10,000+ Google Play Store applications**.  
The goal is to understand app market trends, user behavior, rating patterns, popularity indicators, and category competitiveness.  

The analysis focuses on:
- App ratings & distributions  
- Installs and popularity drivers  
- Paid vs free app performance  
- Category-level insights  
- App size impact  
- Sentiment analysis based on user reviews  

---

## 📂 Dataset
The project uses **two datasets**:

1️⃣ `googleplaystore.csv` — App metadata  
2️⃣ `googleplaystore_user_reviews.csv` — Sentiment polarity from user reviews  

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Jupyter Notebook / VS Code**

---

## 📊 Key Analyses & Insights

### **1. Data Cleaning**
- Converted installs (e.g., `1,000+`) → integers  
- Cleaned price column (`$4.99` → `4.99`)  
- Converted app sizes (e.g., `19M`, `900k`) into MB  
- Removed duplicates and handled missing values  
- Standardized data types across all columns  

---

### **2. Core EDA**
- Rating distribution (most apps rated between 3–4.5)
- Category count visualization
- Top installed apps and categories
- Genre distributions
- Installs vs Ratings scatter analysis

---

### **3. Advanced Insights**
- **Paid vs Free Apps:** Free apps dominate volume; paid apps have slightly higher median ratings  
- **Price vs Installs:** Higher prices → lower downloads (negative trend)  
- **Size vs Installs:** Medium-sized apps (~20–40 MB) tend to rank higher in installs  
- **Reviews vs Installs:** High positive correlation  
- **Category Competitiveness:** Categories like *Communication, Social, Tools* are both crowded and high-install sectors  

---

### **4. Sentiment Analysis (User Reviews)**
Using the user reviews dataset, we calculated **Sentiment Polarity** per app.

Insights:
- **Most positive categories:** Books & Reference, Education  
- **Most negative categories:** Tools, Communication (due to performance issues and ads)  

---

## 📁 Project Structure

Google-Play-Store-Apps-Analysis/
│
├── Google_Play_EDA.ipynb # Main notebook
├── googleplaystore.csv # Raw dataset
├── googleplaystore_user_reviews.csv # Sentiment data
├── googleplay_cleaned.csv # Cleaned dataset
├── plots/ # All charts saved here
│ ├── rating_distribution.png
│ ├── category_count.png
│ ├── paid_vs_free_ratings.png
│ ├── price_vs_installs.png
│ ├── sentiment_by_category.png
│ └── ...more
├── requirements.txt # Required libraries
└── README.md


---

## 🚀 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/Anjusri-E/Google-Play-Store-Apps-Analysis.git
 
2.Install required libraries:

pip install -r requirements.txt

3.Open the notebook:

jupyter notebook Google_Play_EDA.ipynb


4.Run all cells to reproduce the analysis and plots.

📝 Conclusion

This analysis provides valuable insights into how apps perform on the Google Play Store, including the impact of:

category,

pricing,

app size,

user sentiment, and

installs & reviews.

Developers and app businesses can use these results to prioritize features, improve user experience, and target high-growth categories.

🔗 GitHub Repository

https://github.com/Anjusri-E/Google-Play-Store-Apps-Analysis

👩‍💻 Author

Anjusri
Data Analyst 