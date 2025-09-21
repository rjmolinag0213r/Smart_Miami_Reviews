<img width="100" height="100" alt="NLP Logo" src="https://github.com/user-attachments/assets/f3f5dfe0-b577-4a31-89b7-6429594adbbf" />

# Smart Miami Reviews
# Author : Ricardo Jose Molina Gonzalez
## [Github] [Linkedin]
[Linkedin]: https://www.linkedin.com/in/molina1312/
[Github]: https://github.com/rjmolinag0213r

---

## 📋 Abstract
**Smart Miami Reviews** is an AI-powered tool that elevates the transparency and trustworthiness of restaurant reviews in Miami, directly supporting the city's vision to become a global leader in smart city innovation. By harnessing advanced Natural Language Processing (NLP) and Google's Gemini API, the platform analyzes user reviews from sources like Google Maps, providing detailed, aspect-based sentiment evaluations on Food Quality, Environment, and Customer Service.

This initiative aligns with Miami’s smart city ambitions by:
- **Empowering Tourists:** Visitors can confidently choose the best dining experiences using reliable, AI-analyzed insights that go beyond misleading star ratings or fake reviews, making their stay in Miami more enjoyable and memorable.
- **Enhancing Urban Data Ecosystems:** The structured, trustworthy feedback generated can inform city planners and local businesses about customer sentiment, guiding improvements in hospitality standards and urban services.
- **Showcasing Miami as a Smart Travel Destination:** By offering innovative, data-driven tools that improve tourist experiences, the project positions Miami as a model for other cities seeking to integrate AI into public-facing services.

Ultimately, Smart Miami Reviews fosters a transparent, data-rich environment that benefits travelers, local businesses, and Miami’s broader smart city objectives.

## 📝 Problem Statement
Online restaurant reviews often show a significant inconsistency between the written feedback from users and the star ratings they provide. For example, a review might have positive text but a low star rating, or the other way around. This creates noise and can lead to a skewed public perception and misinformation. Tourists and residents alike may be misled, undermining trust in Miami’s digital platforms and affecting the city’s reputation as a welcoming, technologically advanced destination.

## 🗺️ Stakeholder Map
This project serves three primary groups, each linked to Miami’s smart city goals:

**Tourists & Visitors:**  
People exploring Miami, often for the first time, who rely on authentic reviews to make the most of their stay. Smart Miami Reviews gives them trustworthy, easy-to-understand summaries—helping them discover great dining spots and avoid disappointing experiences.

**City Planners & Local Government:**  
Officials and smart city strategists seeking to leverage real-time, high-quality data to guide policy, improve urban experiences, and demonstrate Miami’s leadership in digital transformation.

**Restaurant Owners & Businesses:**  
Hospitality providers whose reputation and economic success depend on accurate customer feedback. The project encourages businesses to maintain high service standards and rewards excellence with fair, AI-validated recognition.

## 🎯 SMART Goals
- **Specific:** Analyze restaurant reviews in Miami for Food Quality, Environment, and Customer Service; produce structured summaries and reveal inconsistencies between text and ratings.
- **Measurable:** Quantify the accuracy of aspect-based sentiment detection and the number of mismatches flagged between written reviews and star ratings.
- **Achievable:** Uses state-of-the-art Gemini AI and robust data pipelines for rapid deployment.
- **Relevant:** Directly supports Miami’s smart city vision by improving data reliability for residents, tourists, businesses, and city planners.
- **Time-bound:** The project will be delivered according to a set schedule with defined development, testing, and deployment phases.

## 🛠️ Tools & Technology to be Used
- **Google AI Platform (Gemini API):** Core analysis for aspect-based sentiment classification and summaries.
- **Data Gathering API:** Automated review collection from Google Maps.
- **Python Libraries:** `googlemaps`, `pandas`, `nltk`, `google-generativeai`, `gradio`, and more.

## 📊 Architecture Diagram
![NLPdia](https://github.com/user-attachments/assets/3cc6b306-6715-4bee-abe4-8b4ffb86c8cd)

## Prompt Engineering

* 📝 **Task Definition:** Multi-part prompt: classify overall sentiment and three key aspects.
* ➡️ **Strict Output Formatting:** Enforces structured, key-value output for reliable parsing.
* ❌ **Exception Handling:** Explicit instructions ensure clarity when an aspect is not mentioned.
* 🤖 **Zero-Shot Learning:** Leverages Gemini’s built-in understanding with no extra training.

## Model Pipeline

**1. Framework & Model Initialization:**  
- Uses LangChain, `langchain-google-genai`, and `google-generativeai` with Gemini-1.5-flash-latest.

**2. Execution and Integration:**  
- A custom Python function (`analyze_review_with_gemini`) analyzes each review, parses results, and enriches the dataset for further visualization and reporting.

# 📘 How to Run the Code: Quick Guide

## 🔐 Setup & API Keys (Crucial First Step)
1. **Install Dependencies:**  
   Install required Python libraries (`googlemaps`, `pandas`, `nltk`, etc.).

2. **Add API Keys:**  
   - Get API keys for Google Maps and Google Gemini.
   - In Google Colab: Use the “Secrets” tab (🔑) to add:
     - `Maps_API_KEY`
     - `GOOGLE_API_KEY`

## 🧹 Data Extraction & Cleaning
- Use the Google Maps API to collect Miami restaurant reviews.
- Clean and preprocess reviews using NLTK and pandas.

## 🤖 AI-Powered Analysis
- Run the Gemini API integration cell to analyze and assign aspect-based sentiment.
## Video Demo
[ Demo ]

[Demo]:https://www.youtube.com/watch?v=Df2sAGX3w5U

# Folder Organization 
---

### Directory Descriptions

* **`data/`**: Raw and processed data.
    * **`API KEY`**: Placeholder directory.
* **`docs/`**: Project documentation.
    * `Executive Summary NLP.pdf`: High-level summary.
    * `NLPdia.jpg`: Project architecture diagram.
    * `README.md`: Docs folder instructions.
* **`notebooks/`**: Jupyter Notebooks for analysis and model development.
    * `Review_Senti_Analisys.ipynb`: Main analysis notebook.


---
