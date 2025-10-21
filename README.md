# 🎬 Netflix Dataset Analysis

### 📊 Problem Statement 1: Content Trends Analysis for Strategic Recommendations

This project analyzes **Netflix content trends** — exploring how the platform’s movie and TV show catalog has evolved over time.  
The goal is to generate **data-driven insights** to guide content strategy, identify audience preferences, and explore geographical and genre trends.

---

## 🚀 Project Overview

Netflix has one of the largest collections of digital entertainment content in the world.  
Understanding trends in **genres, release years, content types, and countries** can help drive smarter production and acquisition decisions.

This project performs:
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Genre and Country Analysis
- Yearly Content Trends
- Strategic Recommendations

---

## 🧠 Key Objectives

1. Analyze the **growth trend** of Movies vs. TV Shows over time  
2. Identify **top performing genres** and their evolution  
3. Study **country-wise content distribution**  
4. Visualize **global Netflix presence** using a choropleth map  
5. Provide **strategic insights** for future content planning  

---

## 🧩 Dataset Information

| Column | Description |
|--------|--------------|
| `Show_ID` | Unique identifier for each show |
| `Title` | Name of the show |
| `Category` | Type – Movie or TV Show |
| `Director` | Director of the title |
| `Cast` | Leading actors |
| `Country` | Country of production |
| `Release_Date` | Date when content was released |
| `Rating` | Maturity rating |
| `Duration` | Duration (minutes or seasons) |
| `Description` | Short summary of the title |

📁 Dataset File: `Netflix Dataset.csv`

---

## 🧹 Data Cleaning

- Converted `Release_Date` to datetime format  
- Extracted `Year` from release date  
- Filled missing values in `Director`, `Cast`, `Country`, `Rating`  
- Derived `Main_Genre` from the first listed genre  

---

## 📈 Exploratory Data Analysis (EDA)

### 1️⃣ Movies vs TV Shows Released per Year
Visualizes how the count of movies and TV shows changes yearly.

![Movies vs TV Shows](images/movies_vs_tvshows.png)

---

### 2️⃣ Top 10 Genres on Netflix
Highlights the most common genres on the platform.

![Top 10 Genres](images/top_10_genres.png)

---

### 3️⃣ Movies vs TV Shows by Country (Top 10)
Shows the content distribution for the top producing countries.

![Country Distribution](images/country_distribution.png)

---

### 4️⃣ Global Netflix Content – Choropleth Map
A map visualizing which countries contribute the most to Netflix’s catalog.

![Choropleth Map](images/choropleth_map.png)

---

### 5️⃣ Trend of Popular Genres Over Time
Tracks the popularity of the top 5 genres year-over-year.

![Genre Trends](images/genre_trends.png)

---

## 💡 Insights & Strategic Recommendations

📍 **Content Type Trends:**  
Movies dominate Netflix’s early years, but TV shows show increasing growth after 2016.  

🌍 **Country Contribution:**  
The U.S. remains the top contributor, followed by India, the U.K., and Canada.  

🎭 **Genre Preferences:**  
Dramas, Comedies, and Documentaries are consistently popular — suggesting strong audience retention.  

📅 **Future Focus:**  
Netflix could increase investment in localized content (especially from Asia & Europe) and explore underrepresented genres like Sci-Fi and Animation.  

---

## 🛠️ Tools & Libraries Used

- **Python** 🐍  
- **Pandas**, **NumPy** – Data manipulation  
- **Matplotlib**, **Seaborn**, **Plotly Express** – Visualization  
- **Google Colab / Jupyter Notebook** – Development environment  

---

## 📂 Project Structure

```

Netflix-Dataset-Analysis/
│
├── Netflix Dataset.csv
├── netflix_analysis.ipynb
├── images/
│   ├── movies_vs_tvshows.png
│   ├── top_10_genres.png
│   ├── country_distribution.png
│   ├── choropleth_map.png
│   └── genre_trends.png
└── README.md

````

---

## 👨‍💻 Author

**Devansh Singh Raghuvanshi**  
🎓 B.Tech Computer Science (Class of 2025)  
📧 [devanshsinghraghuvanshi@gmail.com](mailto:devanshsinghraghuvanshi@gmail.com)  
🌐 [LinkedIn](#) | [GitHub](#)

---

## ⭐ How to Run

### 1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflix-dataset-analysis.git
````

### 2. Navigate to the project folder:

   ```bash
   cd netflix-dataset-analysis
   ```

### 3. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```

### 4. Run the notebook:

   ```bash
   jupyter notebook netflix_analysis.ipynb
   ```

---

## 📊 License

This project is open-source and available under the MIT License.

---
