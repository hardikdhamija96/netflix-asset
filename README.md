# 📊 Netflix Content Analysis & Business Insights

A complete exploratory data analysis of Netflix's content catalog to uncover trends, audience preferences, and strategic recommendations for global growth.

**Author:** [Hardik Dhamija](https://www.linkedin.com/in/hardikdhamija)  
**Role:** Aspiring Data Scientist | Python | SQL | EDA | Power BI  

---

## 🔍 Business Problem

As Netflix expands globally, it faces the challenge of aligning its content strategy with regional preferences and shifting viewer trends. This project aims to explore:
- What kind of content dominates Netflix’s platform?
- Which countries and genres are leading in production?
- How is Netflix targeting different audience segments?
- Are there gaps or growth opportunities in content strategy?

---

## 🎯 Objective

To conduct a structured data exploration and visualization to help answer business questions such as:
- Trends in content type (Movies vs TV Shows)
- Popular genres and rating distributions
- Country-wise content production
- Patterns in release dates and content length
- Audience targeting using rating categories

---

## 🧾 Dataset Overview

- **Source:** Netflix Title Dataset (`netflix.xlsx`)
- **Size:** 8,807 records × 12 features
- **Key Features:**
  - `type`, `title`, `country`, `release_year`, `rating`, `duration`, `listed_in` (genres)
- **Derived Columns:**
  - `duration_int`, `year_added`, `num_genres`, `rating_category`, `is_multi_country`, etc.

---

## 🛠️ Techniques Used

- **Data Cleaning & Preprocessing**
  - Handling missing values (e.g., "Unrated", "Unknown")
  - Standardizing date and duration formats
  - Feature engineering (cast size, number of genres, etc.)

- **Exploratory Data Analysis**
  - Univariate & bivariate visualizations using `seaborn` and `matplotlib`
  - Country, genre, and rating-wise comparisons
  - Time trend analysis (year-wise/month-wise additions)

- **Business Insight Mapping**
  - Linking EDA findings to actionable insights
  - Strategic gaps and improvement opportunities

---

## 📈 Key Insights

1. **Audience Targeting:**  
   ~80% of content is made for Mature & Teen audiences. Family/Kids content is underrepresented.

2. **Geographic Focus:**  
   U.S. dominates content share, but countries like India, UK, and Japan are growing contributors.

3. **Genre Patterns:**  
   Top genres include International Movies, Dramas, Comedies. TV shows lean towards niche genres.

4. **Format Preferences:**  
   - Most **movies** last ~90–120 mins  
   - Most **TV shows** have 1–2 seasons

5. **Growth Trend:**  
   Sharp rise in content additions post-2015, peaking around 2019–2020.

---

## 📌 Recommendations

- Invest in more **Family/Kids** content to balance the current mature-heavy catalog.
- Plan seasonal releases during **July & December** for higher engagement.
- Continue global expansion, especially in **India, UK, Canada**.
- Use **TV shows** to experiment with niche genres and regional content.
- Add longer-format content in **thrillers, docuseries**, and dramas.
- Encourage **ensemble cast & cross-genre** content to widen appeal.

---

## 📊 Sample Visuals

<img src="https://raw.githubusercontent.com/hardikdhamija96/netflix-asset/main/content_rating.png" width="600">

---

## 🚀 How to Run

1. Clone this repo or open the notebook directly on Google Colab:
   [📎 Business_Case_Netflix_EDA.ipynb](https://colab.research.google.com/github/hardikdhamija96/netflix-asset/blob/main/Business_Case_Netflix_Data_Exploration_and_Visualization.ipynb)

2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
3. Run the notebook step-by-step to reproduce the analysis.

## 💡 Future Scope
- NLP on description for sentiment/emotion classification.

- Predictive modeling (e.g., genre prediction, content success).

- Integration with external data (IMDb, Google Trends, etc.)

## Created with ❤️ by Hardik Dhamija
