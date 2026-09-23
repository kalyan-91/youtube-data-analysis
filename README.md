# 📊 YouTube Data Analytics — Power BI Dashboard

## 📌 Project Overview

This project analyzes **950+ top-ranked YouTube channels from around the world** to understand the factors associated with channel growth, audience size, and earnings.

The analysis combines **MySQL, Python/Pandas, and Power BI** to clean, explore, visualize, and communicate insights from the dataset.

The main goal was not just to build a dashboard, but to answer practical questions about **YouTube channels, subscribers, revenue, content categories, countries, channel age, and growth**.

---

## 🛠️ Tools & Technologies

* **Power BI** — Data visualization and interactive dashboard
* **MySQL Workbench** — Data querying and analysis
* **Python / Pandas** — Data cleaning and preparation
* **GitHub** — Project documentation and version management

---

## 📂 Project Files

| File                     | Description                        |
| ------------------------ | ---------------------------------- |
| `YouTube_Analysis.pbix`  | Power BI dashboard and data model  |
| `YouTube_Data_Story.pdf` | Detailed analysis and key findings |
| `data/`                  | Dataset used for the analysis      |
| `screenshots/`           | Dashboard screenshots              |

---

## 🔍 Questions Explored

The project explores 11 key questions:

1. Which countries have the most top YouTube channels?
2. Do more subscribers mean more revenue?
3. What factors are associated with channel earnings?
4. Do older channels have bigger audiences?
5. Which countries earn the most per subscriber?
6. Does a country's job market relate to YouTube success?
7. Does education relate to average channel size?
8. Which channel categories have more predictable earnings?
9. Does posting more videos lead to faster growth?
10. When did YouTube experience its biggest growth of new top channels?
11. Does Entertainment dominate the top YouTube channels?

---

## 📈 Key Insights

### 🌍 Countries

The United States and India had the highest number of top channels in the dataset, followed by countries such as Brazil, the UK, and Mexico.

### 💰 Subscribers vs Revenue

A larger subscriber count did **not always correspond to higher earnings**. Some channels with around 50 million subscribers were found to earn more than channels with substantially larger subscriber counts.

### 🎬 Content Category

Average earnings differed considerably between content categories. **Shows, Autos & Vehicles, and Sports** had the highest average earnings in this analysis, while Travel & Events, Howto & Style, and Gaming were lower.

### 📅 Channel Age

Channels created around **2008–2009** had the largest average audiences in the analysis. A smaller second wave appeared around 2015.

### 💵 Earnings per Subscriber

The countries with the highest number of channels were not necessarily the countries with the highest earnings per subscriber. **Latvia, Italy, and Turkey** stood out on this measure.

### 📤 Upload Frequency

The analysis did not show that simply uploading more videos leads to faster growth. Some channels with very large numbers of uploads had relatively limited growth.

### 🎭 Entertainment

Entertainment represented a smaller portion of the top-channel dataset than expected. The top tier was distributed across many different content categories.

---

## 📊 Dashboard

The Power BI dashboard provides an interactive way to explore the dataset and investigate relationships between:

* Subscribers
* Earnings
* Channel categories
* Countries
* Channel age
* Video uploads
* Growth patterns

### Dashboard Preview

Add your Power BI screenshots to the `screenshots/` folder and display them here:

```markdown
![Power BI Dashboard](screenshots/dashboard.png)
```

---

## 💡 What I Learned

This project helped me understand that effective data analysis starts with **asking the right questions**.

Different questions require different visualizations. For example:

* Bar charts help compare categories.
* Scatter plots help explore relationships.
* Calculated metrics can reveal insights that are not visible in the raw data.

One useful example was analyzing **earnings per subscriber**, which provided a different perspective from simply looking at total subscribers.

I also learned that data cleaning and preparation depend on the question being investigated rather than following the same process for every dataset.

---

## 📄 Data Story

A detailed explanation of the analysis and findings is available in:

**`YouTube_Data_Story.pdf`**

The report presents the analysis as a series of questions and explains what the data revealed for each one.

---

## 🎯 Project Objective

The objective of this project was to demonstrate an end-to-end data analytics workflow:

**Raw Data → Data Cleaning → SQL Analysis → Power BI**
