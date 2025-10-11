# Top-UK-Youtubers-2024

# 🎯 Objective

The goal is to identify the **top YouTubers in the UK in 2024** to help the Head of Marketing decide which creators to partner with for upcoming marketing campaigns.

---

## ❗ Key Pain Point

The **Head of Marketing** wants clear insights on **who the top YouTubers are in 2024** to determine the best influencers for brand collaborations and advertising campaigns.

---

## 💡 Ideal Solution

Create an **interactive dashboard** that provides detailed insights into the **top UK YouTubers in 2024**, including:


- 📊 **Subscriber count**  
- 👀 **Total views**  
- 🎥 **Total videos**  
- 💬 **Engagement metrics** (likes, comments, etc.)

This dashboard will enable the **marketing team** to make **data-driven decisions** on which YouTubers to collaborate with for maximum campaign impact.


# 🧩 User Story

As the **Head of Marketing**, I want to use a **dashboard** that analyzes **YouTube channel data in the UK**,  
so that I can easily identify the **top-performing channels** based on metrics like **subscriber count** and **average views**.

With this information, I’ll be able to make **informed decisions** about which YouTubers to collaborate with,  
helping to **maximize the effectiveness** of each marketing campaign.

---

## 📊 Data Source

### 🔍 What Data Is Needed?
To achieve the project objective, we need data on the **top UK YouTubers in 2024**, including:

- 🏷️ **Channel names**  
- 👥 **Total subscribers**  
- 👀 **Total views**  
- 🎥 **Total videos uploaded**

---

### 🌐 Where Is the Data Coming From?
The data is sourced from **Kaggle** (Excel extract).  
You can find and download the dataset [here]([#](https://www.kaggle.com/datasets/bhavyadhingra00020/top-100-social-media-influencers-2024-countrywise?resource=download))

# 🚀 Project Stages

1. 🎨 **Design**  
2. 💻 **Development**  
3. 🧪 **Testing**  
4. 📈 **Analysis**

---

## 🧠 Design Stage

### 🧩 Dashboard Components Required

Based on the project requirements, the dashboard should be designed to answer key analytical questions such as:

- 🔝 **Who are the top 10 YouTubers with the most subscribers?**  
- 🎥 **Which 3 channels have uploaded the most videos?**  
- 👀 **Which 3 channels have the most total views?**  
- 📊 **Which 3 channels have the highest average views per video?**  
- ⚖️ **Which 3 channels have the highest views-per-subscriber ratio?**  
- 💬 **Which 3 channels have the highest subscriber engagement rate per video uploaded?**

---

For now, these are the **core questions** our dashboard aims to answer.  
As the **analysis progresses**, additional insights and metrics may be added to enhance the dashboard’s usefulness.

# 📊 Dashboard Mockup

### 🖼️ What Should It Look Like?

The dashboard should display clear, interactive visuals that make it easy to identify top-performing YouTube channels based on key metrics.

### 📈 Recommended Visuals

Some of the data visuals that may be appropriate for answering our analytical questions include:

- 📋 **Table** — for displaying detailed channel information (subscribers, views, videos).  
- 🌳 **Treemap** — to show proportional comparisons, such as total views by channel.  
- 🧮 **Scorecards** — to highlight key summary metrics like total subscribers or average engagement rate.  
- 📊 **Horizontal Bar Chart** — to rank top YouTubers based on subscribers, views, or uploads.  

---

### 🧠 Dashboard Mockup Preview

**Dashboard-Mockup:** ![Dashboard Mockup](assets/images/dashboard_mockup.png)


# 🛠️ Tools & Technologies

| 🧰 **Tool**      | 🎯 **Purpose** |
|------------------|----------------|
| **Excel**        | Exploring and performing initial data analysis then Cleaning, testing, and analyzing the data |
| **Power BI**     | Visualizing data through interactive dashboards |
| **GitHub**       | Hosting project documentation and version control |
| **Mokkup AI**    | Designing the wireframe/mockup of the dashboard |


# ⚙️ Pseudocode

### 🧭 General Approach

The following outlines the step-by-step process for creating this solution from start to finish:

1. 📥 **Get the data**  
2. 📊 **Explore the data in Excel**  
3. 🧹 **Clean the data** using Excel  
4. 🧪 **Test the data** in Excel to ensure accuracy  
5. 📈 **Visualize the data** in Power BI  
6. 🔍 **Generate insights** and key findings based on visual analysis  
7. 📝 **Write documentation and commentary** explaining the process and results  
8. 🌐 **Publish the final output** (data and report) on GitHub Pages  

---

# 🔍 Data Exploration Notes

### 🧾 Overview

This stage involves scanning the dataset for **errors, inconsistencies, missing values, or unusual characters** that could affect analysis.

### 🧠 Initial Observations

- There are **at least 4 relevant columns** containing all the necessary data for this a


# 🧹 Data Cleaning

### 🎯 Objective

The goal of this stage is to **refine the dataset** so it’s well-structured, consistent, and ready for accurate analysis.

---

## ✅ Expected Clean Data Format

The cleaned dataset should meet the following **criteria and constraints**:

- Only **relevant columns** are retained.  
- All **data types** are appropriate for their contents.  
- No column should contain **null or missing values**, ensuring completeness and reliability.

---

### 📏 Cleaned Dataset Constraints

| 🧩 **Property**       | 📋 **Description** |
|------------------------|--------------------|
| **Number of Rows**     | 100 |
| **Number of Columns**  | 4 |

---

## 🧠 Data Cleaning Steps

To prepare the dataset for analysis, the following steps will be performed:

1. 🗑️ **Remove unnecessary columns** — keep only the required fields for analysis.  
2. 🔡 **Extract YouTube channel names** from the first column using text parsing or formula logic.  
3. 🏷️ **Rename columns** for clarity and consistency across the dataset.  

---

After these steps, the dataset will be **structured, clean, and ready** for visualization in Power BI.

# 📊 Visualization

### 🧾 Results

#### 💻 Dashboard Overview

Below is the Power BI dashboard created for this project:

---

### 🖼️ Dashboard Preview

**GIF of Power BI Dashboard:**  
*(Insert your GIF or image link here)*  
> Example:  
> `![Power BI Dashboard](path-to-your-dashboard.gif)`

---

### 📈 Description

This dashboard showcases the **Top UK YouTubers in 2024**, highlighting key metrics such as:

- 👥 **Subscribers**
- 👀 **Total Views**
- 🎥 **Number of Videos**
- 💬 **Engagement Metrics**

It provides a **clear visual summary** of YouTube performance, helping the marketing team identify the most influential creators to collaborate with.
