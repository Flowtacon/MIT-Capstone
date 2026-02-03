# MIT-Capstone
# Real-Time Retail Feedback Intelligence 🛍️ 🤖

An automated customer feedback analysis pipeline powered by Generative AI. This project leverages Large Language Models (LLMs) to transform unstructured customer reviews into actionable business intelligence, enabling real-time decision-making for retail strategy.

## 📌 Business Context
**The Challenge:** "ChicStyle", a fast-growing fashion retailer, faced scalability issues with manual customer feedback analysis. Valuable insights regarding sizing defects and fabric quality were buried in thousands of text rows, leading to slow reaction times and increased return rates.

**The Solution:** A scalable GenAI pipeline that automatically:
* Decomposes complex reviews using **Chain-of-Thought** reasoning.
* Identifies sentiment and specific product flaws (e.g., "runs small", "poor stitching").
* Outputs structured data (JSON) ready for BI dashboards.

## 🚀 Key Features
* **Exploratory Data Analysis (EDA):** Deep dive into 23,486 reviews to analyze age distribution, ratings, and department performance.
* **Sentiment Analysis:** Classification of customer feedback using LLMs.
* **Automated Tagging:** Extraction of key themes from unstructured text.
* **Visualization:** Data storytelling using Seaborn and Plotly.

## 🛠️ Tech Stack
* **Language:** Python 3.12+
* **AI/LLM:** OpenAI API (GPT-4o-mini, GPT-5-mini), Prompt Engineering
* **Data Manipulation:** Pandas, NumPy, Scikit-learn
* **Visualization:** Matplotlib, Seaborn, Plotly, WordCloud

## 📊 Dataset
Used the **Women's E-Commerce Clothing Reviews** dataset containing:
* 23,486 Customer Reviews
* Features: Review Text, Rating (1-5), Recommended IND, Age, Division/Department.

## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone [https://github.com/your-username/retail-feedback-intelligence.git](https://github.com/your-username/retail-feedback-intelligence.git)
