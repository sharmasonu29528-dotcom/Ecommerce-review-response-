# Customer Review Analysis & AI-Powered Response Generator

## 📌 Project Overview

This project analyzes an e-commerce customer review dataset by performing data cleaning, exploratory analysis, and AI-powered customer support response generation using **LangChain** and **Groq LLM (Llama 3.3 70B Versatile)**.

The notebook identifies critical customer reviews, extracts customer feedback, and generates professional support responses using an LLM.

---

## 🚀 Features

- Load and preprocess e-commerce review data
- Handle missing values
- Remove duplicate records
- Clean email addresses
- Detect and cap outliers
- Categorize customer ratings
- Identify the most common complaint keywords
- Visualize complaint frequencies
- Extract customer reviews by Customer ID
- Generate AI-powered customer support responses using Groq

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- LangChain
- Groq API
- Llama 3.3 70B Versatile

---

## 📂 Dataset

The project uses an e-commerce review dataset containing information such as:

- Customer ID
- Review ID
- Product
- Price
- Rating
- Review
- Email

---

## 📊 Data Preprocessing

The following preprocessing steps are performed:

- Remove duplicate records
- Handle missing values
- Clean email usernames
- Convert rating data types
- Detect numerical outliers
- Cap outlier values using percentile thresholds
- Create a new **Rating_Type** column

Rating categories:

- **Critical** → Ratings 1–2
- **Moderate or Good** → Ratings 3–5

---

## 📈 Exploratory Data Analysis

The notebook includes:

- Missing value analysis
- Data type inspection
- Rating distribution
- Critical review extraction
- Most common complaint keywords
- Complaint frequency visualization

---

## 🤖 AI Customer Support Assistant

The project integrates **LangChain** with **Groq** to generate personalized customer support responses.

### Model

- **Provider:** Groq
- **Model:** `llama-3.3-70b-versatile`

### Workflow

1. Extract customer review using Customer ID.
2. Send the review to the LLM.
3. Generate a professional and empathetic response.

---

## 📦 Installation

Install the required packages:

```bash
pip install pandas numpy plotly langchain langchain-core langchain-groq
```

---

## 🔑 Environment Variable

Set your Groq API key before running the notebook.

Linux/macOS:

```bash
export GROQ_API_KEY=your_api_key
```

Windows:

```cmd
set GROQ_API_KEY=your_api_key
```

Or using Python:

```python
import os

os.environ["GROQ_API_KEY"] = "your_api_key"
```

> **Important:** Never hardcode or commit your API key to a public repository.

---

## ▶️ Running the Project

1. Install dependencies.
2. Configure the Groq API key.
3. Open the Jupyter Notebook.
4. Run all cells sequentially.

---

## 📁 Project Structure

```
├── Customer_Review_Analysis.ipynb
├── ecommerce_reviews_simple_dirty_with_email.csv
├── README.md
```

---

## 📌 Future Improvements

- Sentiment Analysis
- Complaint Classification
- Product Recommendation
- Dashboard using Streamlit
- Multi-language customer support
- RAG-based knowledge retrieval

---

## 👨‍💻 Author

Developed as a Customer Review Analytics and AI Customer Support project using LangChain and Groq.# Ecommerce-review-response-
