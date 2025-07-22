# 🧠 AI Career Advisor

This is a machine learning project that helps people find the right career based on their **personality** and **interests**.

It uses real job skills data from the O*NET database to give smart and personalized career suggestions.

---

## 📌 What This Project Does

- Asks for your **personality type** (like Introvert, Extrovert, etc.)
- Asks what you’re **interested in** (like Tech, Business, Design, etc.)
- Then it **predicts the best career** that matches you
- You also get to know what skills are important for that job

---

## 📊 Dataset Used

- The data comes from [O*NET Skills Dataset](https://www.onetcenter.org/database.html)
- We used a file called `Skills.xlsx`
- From this data, we kept only those skills which are important (value 50 or above)

---

## 🔧 How It Works

1. Load the skills data from the Excel file  
2. Filter the important skills  
3. Add two features: **Personality** and **Interest** (just random values for now, but can be replaced with user input later)  
4. Use machine learning (Random Forest Classifier) to train a model  
5. Save the model so it can be used later  
6. Use the model to suggest the best career

---

## 🚀 Example Result

```python
Recommended career: Software Developer
