# 📊 YouTube Video Performance Analysis

## 🧩 Project Objective

🎯 **Goal**:  
Analyze the performance of YouTube videos across multiple channels to uncover key insights that help improve content strategy, viewer engagement, and monetization outcomes.

---

## 📌 Key Questions Answered

1. Which content category performs best in terms of total views?
2. Does video length impact the number of views?
3. Which day of the week receives the highest average views?
4. Are monetized videos performing better than non-monetized ones?
5. Which channel has the highest engagement rate?

---

## 📁 Dataset Overview

- **Dataset Name**: YouTube Video Performance Data  
- **Source**: Synthetic dataset (500+ records)  
- **Format**: `.csv`  
- **Purpose**: Analyze video performance across categories, length, monetization, and days.

### 🔑 Key Columns

| Column Name         | Description                                  |
|---------------------|----------------------------------------------|
| Video_ID            | Unique video identifier                      |
| Channel_Name        | YouTube channel name                         |
| Title               | Title of the video                           |
| Category            | Video category (e.g., Education, Entertainment) |
| Views               | Total number of views                        |
| Likes               | Total likes                                  |
| Comments            | Total comments                               |
| Duration_seconds    | Length in seconds                            |
| Upload_Date         | Date of upload                               |
| Monetized           | Yes / No                                     |
| Engagement_Rate     | (Likes + Comments) / Views                   |
| Weekday             | Day of the week from `Upload_Date`           |

---

## 🧼 Data Cleaning & Feature Engineering

- Checked and handled missing values
- Converted columns to correct data types (e.g., dates)
- Created new columns:
  - `Weekday`
  - `Engagement_Rate`
  - `Title Length`

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Key Analyses

1. **Total Views by Category**  
2. **Average Views by Video Length** (Short, Medium, Long)  
3. **Average Views by Day of the Week**  
4. **Views Comparison: Monetized vs Non-Monetized Videos**  
5. **Engagement Rate by Channel**  
6. **Views vs Duration** (Scatter plot)

---

## 📌 Insights & Conclusion

- 📚 **Education** category receives the most views.
- ⏱️ **Medium-length videos (5–10 mins)** perform the best.
- 📅 **Saturday and Sunday** show the highest average views.
- 💸 **Monetized videos** have more views than non-monetized ones.
- ❤️ **Channel XYZ** has the best audience engagement.
- 🔗 Strong correlation between views, likes, and comments.

---

## 🧰 Tools & Technologies Used

- Python  
- Pandas & NumPy  
- Matplotlib  
- Jupyter Notebook  
- Excel / CSV files  

---

## 📎 Files Included

- `YouTube_Video_Performance_Analysis.ipynb` – Jupyter notebook  
- `YouTube_Analysis_Report.pdf` – Summary report  
- `youtube_data.csv` – Dataset  
---

## 🙋‍♀️ Author

**Aakanksha Saini**  
_Data Analyst | Python | Advance Excel | Power BI | SQL_  
📍 Moradabad, India  
📫 [LinkedIn](www.linkedin.com/in/aakanksha87)  
📧 Email: aakankshasingh472@gmail.com
