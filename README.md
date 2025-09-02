# Millennium × WICC Coinbase Sentiment Analysis Project

This repository contains my contributions to the **Coinbase Sentiment Analysis** project, conducted in collaboration with Millennium engineers through Women in Computing at Cornell (WICC).  
The work was presented to Millennium’s engineering team as part of our final showcase.

---

## 📖 Project Overview
The goal of this project was to analyze sentiment around Coinbase by processing Reddit data, performing sentiment scoring, and visualizing trends over time.

I followed an **iterative development process** documented across three Jupyter notebooks:

1. **`Millennium_Reddit_1st_Iteration.ipynb`** — *Initial Simulation*:  
   - Objective: Test pipeline for scraping Reddit data and running basic sentiment analysis.  
   - Issue: Data cleaning and sentiment scoring produced unreliable results due to noise in raw data.  
   - Outcome: Identified the need for more targeted data collection and preprocessing.

2. **`Millennium_Reddit_2nd_Iteration.ipynb`** — *Refined Data Pipeline*:  
   - Objective: Narrow subreddit scope, improve tokenization, and re-run analysis.  
   - Issue: Model still produced inconsistent sentiment scores due to stopword handling and preprocessing gaps.  
   - Outcome: Led to a complete overhaul of the preprocessing logic.

3. **`Millennium_Reddit_3rd_Iteration.ipynb`** — *Final Working Version*:  
   - Objective: Implement improved preprocessing, apply sentiment lexicons, and produce visualizations for trends.  
   - Outcome: Generated consistent sentiment metrics and clear visualizations, forming the basis for the final presentation.

---

## 📊 Tech Stack
- **Languages:** Python (Pandas, NLTK, Matplotlib)
- **Tools:** Jupyter Notebook
- **Data Source:** Reddit API

---

## 🎯 My Role
- Designed and implemented data preprocessing logic for Reddit posts
- Developed sentiment scoring pipeline using NLTK’s VADER lexicon
- Created visualizations for sentiment trends over time
- Presented project results to Millennium engineers

---

## 📂 Repository Structure

Millennium_Reddit_1st_Iteration.ipynb # Initial simulation attempt
Millennium_Reddit_2nd_Iteration.ipynb # Refined data pipeline attempt
Millennium_Reddit_3rd_Iteration.ipynb # Final working version

---

## 📑 Final Presentation
**View slides:** [Click here](https://www.canva.com/design/DAGj3wCmVQE/smQCYSZuUzARpc_h28xFIg/view?utm_content=DAGj3wCmVQE&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h48a9c7d6a9)  
*(See slides 14–17 for work directly related to these notebooks)*
