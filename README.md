<<<<<<< HEAD

=======
>>>>>>> bd56c2dc5a27b4b2ec165f66eecd0e064d27e505
# Predicting Movie Performance Using IMDb & Box Office Data

## Project Overview
This project analyzes movie metadata, audience ratings, and box office performance to understand the factors that contribute to a movie’s financial and critical success.

Using data from the IMDb **title.basics** dataset, IMDb ratings, and box office gross revenue data, we explored relationships between genres, runtime, release year, and audience ratings with worldwide gross revenue.

Exploratory Data Analysis (EDA) was applied to identify key drivers of performance. The results show that **genre**, **audience rating**, and **gross revenue** have measurable relationships with box office success.

---

## Business Problem
The film industry faces high financial risk when deciding which movies to fund, distribute, or promote. Each project requires significant investment, yet only a small number achieve strong box office and audience success.

### Key Pain Points
- Uncertainty in predicting box office performance before release  
- Difficulty comparing movie projects across genres and time periods  
- Limited clarity on factors influencing audience reception and revenue  

---

## Data Analysis Focus
- Relationship between movie features (genre, runtime, release year) and audience ratings  
- Link between IMDb ratings and box office revenue  
- Identification of consistently high-performing genres  
- Use of metadata and ratings to build a baseline revenue prediction model  

---

## Business Value
These insights support:
- Smarter project selection and investment decisions  
- More effective marketing budget allocation  
- Improved revenue forecasting and financial planning  

---

## Data Sources
- **IMDb Title Basics**: Movie metadata including title, release year, runtime, and genres  
- **IMDb Ratings Dataset**: Audience ratings and number of votes per movie  
- **Box Office Gross Dataset**: Domestic, foreign, and worldwide revenue figures  

The datasets were merged and cleaned to support analysis of performance drivers.

---

## Data Preparation
- Filled missing foreign gross revenue records  
- Filled missing runtime values using median imputation  
- Removed extreme outliers:
  - Runtime: 51,420 minutes  
  - Release Year: 2115  

---

## Data Understanding

### What the Data Represent
- Each row represents a released movie  
- Sample includes films with both audience ratings and box office data  
- Variables capture movie characteristics, audience reception, and financial performance  

### Target Variable
- **Worldwide Gross Revenue** (used as a proxy for financial success)

### Key Variables
**Numerical**
- Runtime (minutes)
- Release Year
- Average Rating
- Number of Votes
- Worldwide Gross Revenue

**Categorical**
- Genres
- Title

> Note: Revenue is highly skewed and requires transformation for analysis.

---

## Key Insights
- Higher IMDb ratings correlate with higher box office revenue  
- Genre significantly influences financial performance  
- Runtime shows a weak but noticeable effect  

![alt text](<Final Data Visualized.png>)
---

## Business Impact
- Supports movie project selection  
- Improves marketing budget allocation  
- Enables early-stage revenue forecasting  

---

## Recommendations
- Focus on consistently high-performing genres  
- Use audience ratings as early performance signals  
- Incorporate additional features such as:
  - Production budget  
  - Cast popularity  
  - Advanced predictive models  

---

## Team
**Group 3**  
- Adelaide Achieng  
- Bramwel Mwangi  
- Denis Mwilaria  
- Patrick Kathurima  

---

## Acknowledgements
DVF-PT06 — Project 1  
