# 📊 Power BI Twitter Engagement Analysis Dashboard

## 🔍 Project Overview

This Power BI dashboard analyzes and visualizes Twitter engagement metrics to uncover deep insights on tweet performance. The goal is to deliver filtered, time-sensitive visualizations using complex DAX logic based on Tweet metadata and user interactions.

---

## 📁 Dataset Used

- **File Name:** `engagement_report.xlsx`
- **Key Fields:**
  - Tweet Date, Tweet Time, Tweet Hour
  - Engagement Metrics (impressions, likes, retweets, etc.)
  - App interactions (clicks, installs, follows)
  - Cleaned Tweet Text & derived columns (word count, isEvenDate, etc.)

---

## ✅ Tasks Implemented

### 1. 📈 Time-Based Engagement Visual
- **Visual Type:** Line and Column Chart
- **Filters:**
  - Date between `01-01-2020` and `30-06-2020`
  - `Impressions` ≥ 100
  - `Likes` = 0
  - **Time filter:** Between 3 PM and 5 PM IST only
- **Metrics:**
  - Average Engagement Rate
  - Total Impressions

---

### 2. 📊 Click Type by Tweet Category (Clustered Bar Chart)
- **Categories:**
  - Tweets with media, hashtags, or links
- **Filters:**
  - At least 1 click among: URL clicks, profile clicks, hashtag clicks
  - Tweet Date is even
  - Word Count > 40
  - Time filter: 3 PM to 5 PM IST only

---

### 3. 🏆 Top 10 Tweets by Retweets + Likes
- **Visual Type:** Bar Chart with Top N filter
- **Filters:**
  - Exclude weekends
  - Tweet Impression must be even
  - Tweet Date must be odd
  - Word Count < 30
  - Time filter: 3 PM to 5 PM IST only
- **Label:** Tweet user profile

---

### 4. 📊 Replies, Retweets, and Likes for High Media Engagement Tweets
- **Visual Type:** Stacked Column Chart
- **Filters:**
  - Media engagements > median
  - Tweet month: June to August 2020
  - Tweet Date is odd
  - Media Views is even
  - Tweet character count > 20
  - Remove tweets containing the letter ‘S’
  - Time filter: 3 PM–5 PM & 7 AM–11 AM IST

---

### 5. 🔄 App Opens vs Non-App Opens Engagement Rate
- **Visual Type:** Comparative Column Chart
- **Filters:**
  - Tweets from weekdays only (Mon–Fri)
  - Time between 9 AM and 5 PM
  - Impressions = even
  - Tweet Date = odd
  - Character Count > 30
  - Remove words containing ‘D’
  - Display only between 12 PM–6 PM & 7 AM–11 AM IST

---

## 🛠️ Tools & Skills

- Microsoft Power BI (Data View, Model View, Report View)
- Advanced DAX for:
  - Conditional Filtering
  - Time Windows
  - Boolean Flags and Aggregations
- Data Cleaning & Transformation using Power Query
- Visual Best Practices

---

## 📦 Output

- ✅ Final Output: `Anmol_Gupta.pbix`
- 📁 Also Exported: `.pbit` Template for Reusability

---

## 🧠 Key Learning Outcomes

- Mastery in filtering visuals using **dynamic time ranges**
- Crafting **conditional DAX measures** and calculated columns
- Building **clean, user-friendly dashboards** with interactive filtering
- Understanding **real-world business KPIs** on social media metrics

---

## 🏁 How to Use

1. Open `Anmol_Gupta.pbix` in Power BI Desktop.
2. Inspect Report View for each visual task.
3. Use slicers and filters to explore dynamic behaviors.
4. Optional: Export a `.pbit` file for sharing or reuse.

---

## 🙌 Credits

Made with ❤️ by Anmol Gupta  
*Guided and structured with help from OpenAI ChatGPT*
# Twitter-Engagement-Rate-Analysis

