# 📊 Google Play Store Apps EDA

This project performs **Exploratory Data Analysis (EDA)** on the **Google Play Store dataset**, which contains details about apps available on the Google Play Store.  
The goal is to extract meaningful insights, clean the dataset, and visualize patterns related to app categories, ratings, installations, reviews, and more.

---

## 📂 Project Structure

```
├── 1_EDA_Google_playstore_data.ipynb   # Jupyter Notebook with analysis
├── GooglePlayStore.csv                  # Dataset file
└── README.md                            # Project documentation
```

---

## 📌 Objectives

- Perform **data cleaning** (handling missing values, duplicates, and inconsistent data).  
- Conduct **descriptive statistics** to understand dataset distribution.  
- Create **visualizations** to uncover patterns in:
  - App categories
  - Ratings distribution
  - Installs & reviews
  - Free vs. Paid apps
  - Price distribution
  - Content rating
- Identify **business insights** for app developers and publishers.

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- Libraries:
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`

---

## 📊 Dataset

**File:** `GooglePlayStore.csv`  
- Contains metadata of apps in the Google Play Store.  
- Columns include:
  - `App` – App name  
  - `Category` – App category  
  - `Rating` – User rating  
  - `Reviews` – Number of reviews  
  - `Installs` – Number of installations  
  - `Type` – Free/Paid  
  - `Price` – Price of the app  
  - `Content Rating` – Age group suitability  
  - `Genres` – App genres  
  - `Last Updated` – Last updated date  
  - `Current Ver` – Current version  
  - `Android Ver` – Minimum Android version required  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Ajithkumar237/Google-PlayStore-EDA.git
   cd Google-PlayStore-EDA
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook EDA_Google_playstore_data.ipynb
   ```

---

## 📈 Key Insights (Examples)

- Certain categories (e.g., **Games, Family, Tools**) dominate the Play Store.  
- **Free apps** have significantly higher installs compared to paid apps.  
- Apps with higher ratings tend to have more installs.  
- Content rated for **"Everyone"** is the most common.  

*(Detailed insights are in the notebook.)*

---

## 🤝 Contribution

Contributions are welcome!  
If you’d like to improve the analysis, add visualizations, or enhance the dataset cleaning, feel free to fork the repo and create a pull request.



