# **User Engagement & Sentiment Analysis for Businesses (Yelp Dataset, SQL + Python)**  

![](https://github.com/adarshraj18/User_Engagement_and_Sentiment_Analysis_for_Businesses/blob/main/User%20Engagement%20Analysis.png)

## **About Yelp** 

![](https://github.com/adarshraj18/User_Engagement_and_Sentiment_Analysis_for_Businesses/blob/main/About%20Yelp.png)


Yelp is a crowd-sourced platform that allows users to **discover and review local businesses**. Through its web and mobile applications, users contribute:  
- **Reviews:** Detailed feedback and ratings for businesses.  
- **Tips:** Quick suggestions or recommendations.  
- **Check-ins:** Logs of visits that reflect customer engagement.  

Yelp’s database provides a **holistic view of user behavior**, capturing interactions across different business types (restaurants, retail, services, etc.). This project leverages Yelp’s data to **analyze the dynamics of user engagement and sentiment** that drive **business success**, with a particular focus on **restaurants** as a case study.  

---

## **1. Introduction**  
In a competitive marketplace, understanding what drives **business success** is crucial. This project leverages Yelp data to explore **how user engagement, sentiment, and trends impact business performance**, with a focus on restaurants. By combining **SQL for data modeling** and **Python for advanced analysis**, the study reveals actionable insights that businesses can use to **boost engagement, enhance customer satisfaction, and optimize strategies**.

---

## **2. Problem Statement**  
Yelp reviews and interactions offer a rich source of customer behavior data. However:  
- Do **more reviews, tips, and check-ins** actually lead to better ratings?  
- How does **sentiment (“useful,” “funny,” “cool”)** shape perceptions of success?  
- Do engagement patterns **vary by geography, time, and user segments**?  

This project answers these questions to **quantify the drivers of business success** on Yelp.

---

## **3. Research Objectives**  
- **Quantify Correlations:** Measure how reviews, tips, and check-ins affect ratings and review counts.  
- **Sentiment Impact:** Understand how “useful,” “funny,” and “cool” reviews influence success.  
- **Geographical Trends:** Identify top-performing cities and states.  
- **Temporal Patterns:** Uncover seasonal trends, peak hours, and long-term engagement shifts.  
- **User Segmentation:** Compare elite vs non-elite users’ contribution to engagement.  
- **Strategic Insights:** Provide recommendations for businesses to **amplify growth**.

---

## **4. Dataset Overview**  
The analysis uses **150K+ business records** from Yelp, focusing on **35K open restaurants** across **8 metropolitan areas in the USA and Canada**.  

**Data Sources (5 JSON Files):**  
- **business.json:** Name, location, categories, ratings  
- **review.json:** User reviews and sentiments  
- **user.json:** Attributes including elite status  
- **tip.json:** Tips provided by users  
- **checkin.json:** Check-in activity  

These were transformed into SQL tables for scalable querying and integrated with Python for advanced analytics.

---

## **5. Methodology & Tools**  
- **SQL:** JSON ingestion, data cleaning, KPI computation, correlation analysis.  
- **Python:** Data integration and advanced analytics.  
- **Analytics Techniques:** Segmentation, sentiment analysis, time-series trends, and engagement scoring.

---

## **6. Key Analyses & Insights**  

### **6.1. Engagement vs Success**  
- Engagement (reviews, tips, check-ins) **positively correlates with higher ratings**.  
- Restaurants with **4.0 stars** showed **the highest engagement**, while **5.0 stars** saw a drop, possibly due to **saturation** or **selective audiences**.

---

### **6.2. Sentiment Matters**  
- Reviews marked “**useful**,” “**funny**,” and “**cool**” strongly align with **higher success scores**.  
- These attributes signal **authentic, engaging feedback** that drives **visibility and credibility**.

---

### **6.3. Elite vs Non-Elite Users**  
- Though **elite users** are fewer, they contribute **disproportionately to reviews**, driving long-term engagement.  
- Engaging with elite users can **amplify brand advocacy** and **repeat visits**.

---

### **6.4. Geographic Trends**  
- **Philadelphia** leads in overall success score, followed by **Tampa, Indianapolis, and Tucson**, suggesting **prime locations for expansion**.

---

### **6.5. Temporal & Seasonal Patterns**  
- **Peak Hours:** 4 PM – 1 AM dominates engagement, aligning with **dining and leisure hours**.  
- **Seasonality:** Engagement is highest between **November – March**, indicating opportunities for **seasonal campaigns**.  
- **COVID Impact:** Temporary drop in engagement, with high-rated businesses recovering faster.

---

### **6.6. Interconnected Engagement**  
- Higher activity in one channel (e.g., reviews) **drives activity in others** (tips, check-ins).  
- Businesses should adopt **holistic engagement strategies** to amplify visibility.

---

## **7. Recommendations for Businesses**  
- **Collaborate with Elite Users:** Use exclusive offers or partnerships to boost influence.  
- **Optimize Peak Hours:** Adjust staffing and promotions to match engagement spikes.  
- **Leverage Sentiment:** Encourage authentic “useful” and “funny” reviews to improve discoverability.  
- **Expand Strategically:** Target cities with higher success scores for growth.  
- **Sustain Engagement:** Focus on consistent quality to maintain long-term user interaction.

---

## **8. Tools & Skills Demonstrated**  
- **SQL:** Aggregations, Correlations, JSON to SQL integration, Time-Series Analysis.  
- **Python:** Data integration and advanced analysis.  
- **Analytics:** KPI Design, Segmentation, Engagement Modeling.

---

## **9. Conclusion**  
This project shows that **business success on Yelp is multi-dimensional**, driven by:  
- **User engagement** (reviews, tips, check-ins)  
- **Sentiment quality** (useful, funny, cool)  
- **Strategic factors** (geography, timing, elite influence)  

By understanding these dynamics, businesses can **boost visibility, attract loyal customers, and scale smarter**.
