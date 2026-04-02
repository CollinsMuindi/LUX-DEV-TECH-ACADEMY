# 📊 Data Analysis Dashboard Project

## 🏷️ Project Title
**Jumia Product Performance Dashboard: Analyzing Pricing, Discounts, and Customer Reviews**


## 🎯 Project Objective
The objective of this project is to design and build an interactive Excel dashboard that analyzes the performance of products listed on Jumia.

Students will explore how pricing, discounts, reviews, and ratings influence product performance and customer engagement. The final dashboard should support data-driven decision-making in an e-commerce context.

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

### Rating Category
- Poor for ratings below 3  
- Average for ratings between 3 and 4.4  
- Excellent for ratings of 4.5 and above  

### Discount Category
- Low Discount for discounts below 20%  
- Medium Discount for discounts between 20% and 40%  
- High Discount for discounts above 40%  

---

## 📈 Data Analysis

### Descriptive Analysis

- What is the average current price, old price, discount percentage, and rating?
- Which product is the most expensive and which is the least expensive?
- What is the average rating and discount by discount category?
- How are products distributed across rating categories?

---

### 📊 Trend and Relationship Analysis

Analyze and interpret:

- The relationship between discount percentage and number of reviews
- The relationship between rating and number of reviews
- Whether higher discounts lead to increased customer engagement
- Whether higher-rated products tend to have more reviews

---

### 🏆 Product Performance Analysis

Identify:

- The top 10 products with the highest discounts
- The top 10 products with the most reviews
- The top 5 highest-rated products
- The bottom 5 lowest-rated products
- A comparison between high-discount and low-discount products based on average rating and number of reviews

---

## 📊 Dashboard Design

### Dashboard Requirements

Create a single interactive Excel dashboard containing the following sections:

### Overview

- Total number of products
- Average rating
- Average discount percentage
- Total number of reviews

### Product Performance

- Top products by rating
- Top products by number of reviews
- Top products by discount percentage

### Trend Analysis

- Visualizations showing discount percentage versus reviews
- Visualizations showing rating versus reviews

### Product Categories

- Breakdown of products by rating category
- Breakdown of products by discount category

---

## 📉 Visualization Guidelines

- Use Pivot Tables as the primary data source
- Use bar charts, column charts, pie/donut charts, and scatter plots
- Apply conditional formatting to highlight high discounts and low ratings
- Include slicers for rating category, discount category, and price range

---

## 🎤 Presentation

### Group Presentation

Each group will:

- Present their dashboard to the class
- Explain the key insights derived from the analysis
- Demonstrate dashboard interactivity using filters and slicers

---

## 💡 Discussion Points

- Which products are performing best and why
- Whether discounts are effective in driving engagement
- Identification of products with high discounts but low ratings
- Recommendations that could help Jumia improve product performance

###  Solution

<img width="765" height="96" alt="image" src="https://github.com/user-attachments/assets/8a541470-ab3e-41b9-a2de-71e3a8319f0f" />

<img width="841" height="180" alt="image" src="https://github.com/user-attachments/assets/382468d5-e0e1-455c-9628-6ccbb1284319" />


<img width="934" height="425" alt="image" src="https://github.com/user-attachments/assets/fbd1cdb8-4643-43bc-81f7-65e8a1c94f31" />

<img width="918" height="422" alt="image" src="https://github.com/user-attachments/assets/5861721b-afac-4cac-b987-87ee1067964c" />

