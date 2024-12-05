# Sephora Product Analysis  

## 📜 Project Overview  
This project analyzes the relationship between the price of skincare products and their customer ratings on Sephora. It also examines product categories, such as cleansers, moisturizers, and sunscreens, to identify which tend to receive the highest customer ratings. The findings aim to provide actionable insights for businesses to optimize their product offerings and enhance customer satisfaction.  

---

## 🎯 Goals  
1. **Determine if a correlation exists** between product price and customer ratings.  
2. **Identify top-rated product categories** based on customer feedback.  
3. Provide data-driven recommendations to help businesses improve their product strategies.  

---

## 🛠️ Methodology  

### **1. Data Preprocessing**  
Preprocessing ensured that the data was clean, consistent, and ready for analysis.  

- **Data Inspection:**  
  Reviewed the dataset for missing or null values.  

- **Handling Missing Values:**  
  - Filled categorical fields like `skin_tone`, `eye_color`, and `skin_type` with the placeholder `'unknown'`.  
  - Replaced missing text fields like reviews or titles with `'no review'` or `'no title'`.  

- **Standardizing Values:**  
  - Lowercased text in fields to ensure consistency (e.g., `"Moisturizer"` became `"moisturizer"`).  
  - Ensured numerical columns were properly formatted.  

- **Adding Product Categories:**  
  - Manually categorized products into groups such as cleansers, moisturizers, masks, sunscreens, lip balms, and wellness items using Sephora’s website as a reference.  

### **2. Data Visualization and Analysis**  

- **Correlation Analysis:**  
  - Assessed the relationship between product price and customer ratings.  
  - Found a weak correlation, suggesting price has little influence on customer ratings.  

- **Category Performance Analysis:**  
  - Created bar graphs to display the average ratings within each category.  
  - Identified moisturizers as the top-rated category, followed by cleansers and sunscreens.  

---

## 📊 Results  

1. **Correlation Insights:**  
   - Weak correlation between price and ratings indicates that other factors, such as product quality or user experience, are more impactful in shaping customer feedback.  

2. **Category Performance:**  
   - **Top-rated categories:**  
     - Moisturizers  
     - Cleansers  
     - Sunscreens  

---

## 🌟 Key Learnings  

- **Customer Priorities:**  
  Price alone does not determine customer satisfaction. Businesses should focus on enhancing product quality and effectiveness.  

- **Category Strengths:**  
  Products in the moisturizer, cleanser, and sunscreen categories consistently meet customer expectations and represent opportunities for growth.  

---

## 🚀 Impact  

By leveraging these findings, businesses can:  
- Reassess pricing strategies to align with customer value perception.  
- Focus on high-performing product categories to drive satisfaction and loyalty.  
- Use data insights to inform product development and marketing strategies.  

