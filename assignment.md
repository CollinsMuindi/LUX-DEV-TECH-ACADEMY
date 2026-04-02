# 📊 Data Analysis Dashboard Project

## 🏷️ Project Title
**Jumia Product Performance Dashboard: Analyzing Pricing, Discounts, and Customer Reviews**

---

## 🎯 Project Objective
The objective of this project is to design and build an interactive Excel dashboard that analyzes the performance of products listed on Jumia.

Students will explore how pricing, discounts, reviews, and ratings influence product performance and customer engagement. The final dashboard should support data-driven decision-making in an e-commerce context.

---

## 📁 Dataset Overview
The dataset contains product-level data with the following columns:

- **Product** – Name of the product  
- **Current Price** – Current selling price in Kenyan Shillings (KSh)  
- **Old Price** – Original price before discount in Kenyan Shillings (KSh)  
- **Discount** – Discount percentage applied to the product  
- **Reviews** – Number of customer reviews  
- **Rating** – Average customer rating out of 5  

---

## 🧹 Data Cleaning and Preparation

- Check for and handle missing values, especially in the Reviews and Rating columns  
- Identify and remove duplicate product entries  
- Convert price columns into numeric format by removing "KSh", commas, and text  
- Use Split Text to Columns under Data tab OR Find and Replace (Ctrl + H)  
- Ensure the Discount column is numeric and properly formatted as a percentage  
- Use Find and Replace (Ctrl + H), LEFT/RIGHT, or Text Split  
- Convert the Rating column from text format (e.g. "4.5 out of 5") into numeric values  
- Convert negative reviews to positive  

---

## ➕ Data Enrichment

Create the following additional columns:

### Discount Amount (KSh)