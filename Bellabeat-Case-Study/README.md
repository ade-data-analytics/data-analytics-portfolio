# 🧘‍♀️ Bellabeat Fitness Data Analysis  
### By: Ade (ade-data-analytics)

---

## 📌 Project Overview  
Bellabeat is a wellness technology company that manufactures smart devices for women.  
The goal of this analysis is to understand **user behavior**, identify **activity patterns**, and generate insights that can help Bellabeat improve product strategy and marketing decisions.

This project focuses on analyzing:  
- Daily step patterns  
- Sleep vs activity relationship  
- Calories burned over time  
- User activity segmentation (Low / Medium / High)

---

## 🎯 Business Task  
**How can Bellabeat leverage smart device data to improve user engagement and encourage healthier habits?**

---

## 🛠 Tools Used  
- **R** — data cleaning & preparation  
- **Tableau** — data visualization  
- **CSV files** — raw and cleaned datasets  
- **GitHub** — portfolio documentation  

---

## 📂 Dataset Information  
Bellabeat data was collected from Fitbit users, including:  
- Daily activity metrics  
- Sleep duration  
- Calories burned  
- User demographic activity levels  

Key datasets used in this analysis:  
- `Bellabeat_daily_activity_final_data.csv`  
- `users_segments.csv`  

---

## 🧹 Data Cleaning & Preparation  
Performed in **R**:

1. Removed duplicates  
2. Standardized date formats  
3. Merged activity, sleep, and calorie tables  
4. Created daily averages  
5. Grouped users into **Low / Medium / High** activity categories  
6. Exported cleaned dataset for Tableau

Cleaned datasets uploaded in this folder:
- `Bellabeat_daily_activity_final_data.csv`
- `users_segments.csv`

---

# 📸 Dashboard Visuals

<p align="center">
  <img src="screenshots/steps_trend.png" width="70%">
  <br><em>Daily Average Steps Over Time</em>
</p>

<p align="center">
  <img src="screenshots/sleep_vs_steps.png" width="70%">
  <br><em>Relationship Between Sleep Duration and Daily Step Count</em>
</p>

<p align="center">
  <img src="screenshots/calories_trend.png" width="70%">
  <br><em>Daily Average Calories Burned Over Time</em>
</p>

<p align="center">
  <img src="screenshots/users_segments.png" width="70%">
  <br><em>Distribution of User Activity Levels (Low / Medium / High)</em>
</p>

---

# 📊 Key Insights

### **1️⃣ Daily Activity Patterns**
- Users average **7,000–10,000 steps** per day.  
- Occasional dips suggest days of inactivity or weekends.

---

### **2️⃣ Sleep vs Activity**
- Users who sleep longer tend to have **moderate to high daily step counts**.  
- Very low sleep groups correlate with lower activity.

---

### **3️⃣ Calories Burned**
- Average calories burned range between **2,200–2,600 kcal**.  
- Major calorie dips correspond with lower step counts.

---

### **4️⃣ User Segmentation**
Based on daily activity:

- **Low activity:** 14 users  
- **Medium activity:** 15 users  
- **High activity:** few users  

Most users fall in **low to medium** categories — opportunity for engagement growth.

---

# 💡 Business Recommendations

### ✔ 1. Gamify Physical Activity  
Introduce challenges, streaks, and badges to motivate users to walk more.

### ✔ 2. Improve Sleep Coaching  
Provide bedtime reminders, sleep hygiene tips, and personalized notifications.

### ✔ 3. Push Personalized Activity Insights  
Users should receive messages like:  
> “Walking 1,500 more steps daily can help you reach your weekly goal.”

### ✔ 4. Target Low-Activity Users  
Send motivational nudges, small achievable goals, and weekly progress summaries.

### ✔ 5. Integrate Social Features  
Allow users to share progress, join groups, or challenge friends.

---

## 📁 Folder Structure  
Bellabeat-Case-Study/
│
├── README.md
├── Bellabeat_Dashboard.pdf
├── Bellabeat_daily_activity_final_data.csv
├── users_segments.csv
└── screenshots/
├── steps_trend.png
├── sleep_vs_steps.png
├── calories_trend.png
└── users_segments.png


---

## 📝 How to Reproduce  
1. Load datasets into R  
2. Clean & merge tables  
3. Create summary metrics  
4. Import final CSV into Tableau  
5. Rebuild the four visualizations  
6. Export dashboard PDF or screenshots  

---

## 🎯 Conclusion  
This analysis provides insights into user activity, sleep patterns, and calorie expenditure.  
These insights can support **product improvements, personalized user coaching, and marketing strategies** to help Bellabeat enhance user engagement and promote healthier lifestyles.

---
