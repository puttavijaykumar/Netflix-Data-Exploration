#  Netflix Content Analysis – Exploratory Data Analysis

> An in-depth analytical study of Netflix's content catalog covering 8,800+ movies and TV shows. This project demonstrates advanced data cleaning, feature engineering, and visualization techniques to uncover meaningful patterns in Netflix's global content strategy.

---

##  Project Overview

This comprehensive Exploratory Data Analysis (EDA) uncovers how Netflix strategically builds its global catalog. The analysis examines over 8,800 titles across multiple dimensions to reveal content trends, patterns, and insights that drive Netflix's business strategy.

**Key Areas of Analysis:**
- Temporal trends in content acquisition and production
- Genre and geographic distribution patterns
- Content ratings and audience targeting strategies
- Duration analysis for movies and episodic content
- Textual insights from content descriptions
- Creator influence and contribution patterns
- Advanced feature engineering for deeper insights

---

##  Tech Stack

| Category | Tools |
|----------|-------|
| **Language** | Python 3.8+ |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Text Analysis** | NLTK, WordCloud, Scikit-Learn |
| **Environment** | Jupyter Notebook / Google Colab |

---

##  Dataset Details

**Source:** [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/) – Kaggle  
**Size:** ~8,800 titles | 12 features  
**Last Updated:** Regularly maintained

### Core Columns
```
type, title, director, cast, country, date_added, release_year, 
rating, duration, listed_in (genres), description
```

---

##  Quick Start

### 1️ Clone the Repository
```bash
git clone https://github.com/yourusername/Netflix-EDA.git
cd Netflix-EDA
```

### 2️ Install Dependencies
```bash
pip install -r requirements.txt
```

**Or install individually:**
```bash
pip install pandas numpy matplotlib seaborn wordcloud scikit-learn jupyter
```

### 3️3 Launch the Analysis
```bash
jupyter notebook netflix_eda.ipynb
```

### 4️4 Run All Cells
Execute the notebook sequentially to generate all visualizations and insights.

---

##  Data Cleaning & Preparation

The project employs rigorous data preprocessing to ensure data quality:

 **Missing Value Handling** – Strategic imputation and removal of incomplete records  
 **DateTime Conversion** – Standardizing date columns for temporal analysis  
 **Feature Extraction** – Creating new features (year_added, month_added, age_on_netflix)  
 **Multi-value Column Exploding** – Splitting genres, countries, and cast members  
 **Duration Normalization** – Standardizing duration formats across content types  
 **Duplicate Removal** – Ensuring data integrity and consistency  

---

##  Key Analyses & Visualizations

### 1. Content Type Distribution
Comparative analysis of movies versus TV shows in Netflix's catalog, revealing the platform's strategic content mix.

### 2. Content Addition Trends
Time-series visualization showing Netflix's content growth trajectory, particularly after global expansion post-2015.

### 3. Genre Popularity Analysis
Ranked visualization of the top 15 genres, revealing what content drives Netflix's catalog diversity.

### 4. Duration & Season Patterns
- Movie runtime distributions across genres
- TV show season counts and episodic patterns

### 5. Geographic Content Production
Top 15 countries producing Netflix content, highlighting global production hubs.

### 6. Rating Distribution Analysis
Maturity rating prevalence, showing Netflix's audience targeting strategy (TV-MA, TV-14, PG-13, etc.).

### 7. Content Age Engineering
Novel feature showing the gap between content release and Netflix acquisition—a key business insight.

### 8. Genre-Duration Relationships
Box plot analysis revealing duration patterns across top-performing genres.

### 9. Descriptive Text Analysis
Word cloud visualization highlighting dominant themes and keywords in content descriptions.

### 10. Bigram (Two-word Phrase) Analysis
Co-occurrence patterns revealing thematic clusters ("young woman," "best friends," "high school").

### 11. Director Influence Analysis
Top directors by content volume, identifying key creative contributors and production partners.

---

##  Key Insights Discovered

###  Content Maturity Evolution
Netflix has strategically shifted toward mature content (TV-MA, TV-14), reflecting audience demand and competitive positioning. Family-oriented content remains proportionally lower, indicating targeted demographic strategy.

###  Acquisition Strategy Variance
- **Movies:** Acquired significantly after release, averaging 5-10 years post-launch
- **TV Shows:** Acquired closer to release, reflecting investment in original series and current content
- **Implication:** Netflix balances licensed library content with original productions

###  Production Timeline Revolution
Post-2015 expansion shows a marked diagonal trend toward same-year Netflix Originals, demonstrating shift from licensing to in-house production.

###  Thematic Patterns
Dominant word pairs ("young woman," "best friends," "high school") reveal Netflix's focus on relationship-driven, coming-of-age narratives targeting younger demographics.

###  Creator Concentration
Select directors (e.g., Raúl Campos, Marcus Raboy) appear frequently due to recurring series and comedy specials, indicating strategic creator partnerships.

---

##  Project Structure

```
Netflix-EDA/
├── netflix_eda.ipynb          # Main analysis notebook
├── netflix_titles.csv         # Dataset
├── requirements.txt           # Dependencies
├── README.md                  # This file
└── visualizations/            # Generated plots (optional)
    ├── genre_distribution.png
    ├── content_trends.png
    └── word_cloud.png
```

---

##  Skills Demonstrated

This project showcases proficiency in:

✔️ **Data Manipulation** – Advanced Pandas operations (groupby, merge, explode)  
✔️ **Data Visualization** – Multi-layer visualizations using Matplotlib and Seaborn  
✔️ **Feature Engineering** – Creating meaningful features for business insights  
✔️ **Statistical Analysis** – Distribution analysis, correlation studies  
✔️ **Text Processing** – NLP techniques, text cleaning, word frequency analysis  
✔️ **Time-Series Analysis** – Trend detection and temporal pattern recognition  
✔️ **Business Acumen** – Translating data patterns into strategic insights  

---

##  Future Enhancements

This project provides a foundation for advanced analytics and ML applications:

 **Predictive Modeling** – Build genre classifiers using description text  
 **Recommendation Engine** – Content recommendation system using embeddings  
 **Interactive Dashboard** – Deploy insights via Streamlit or Power BI  
 **Sentiment Analysis** – Analyze emotional tone of content descriptions  
 **Geographic Deep-Dive** – Regional preference analysis and localization patterns  
 **Hypothesis Testing** – Statistical validation of business assumptions  

---

##  Learning Outcomes

By studying this project, you'll gain practical expertise in:

- Real-world dataset challenges and solutions
- Production-grade data pipeline design
- Advanced visualization storytelling
- Translating data into business intelligence
- Portfolio-quality code organization
- Jupyter notebook best practices

---

##  Contributing

Contributions are welcome! Feel free to:
- Report bugs or data issues
- Suggest new analyses or visualizations
- Improve code efficiency or readability
- Share insights or findings

---

##  License

This project is open-source and available under the MIT License. See LICENSE file for details.

---

##  Acknowledgments

**Dataset Creator:** Putta Vijay Kumar  
**Source:** [Netflix Movies & TV Shows Dataset – Kaggle](https://www.kaggle.com/)  
**Inspiration:** Real-world data analysis practices in the entertainment industry

---

##  Author

**Your Name**  
 Email: your.email@example.com  
 LinkedIn: [Your Profile](https://linkedin.com/)  
 Portfolio: [Your Website](https://yourportfolio.com/)

---

##  If You Find This Useful

Please consider giving this repository a star! It motivates continuous improvement and helps others discover quality data science projects.

---

**Last Updated:** November 2025  
**Python Version:** 3.8+  
**Status:**  Production Ready
