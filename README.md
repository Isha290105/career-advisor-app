# Skill-Based Career Advisor Chatbot

This project is an AI-powered career advisor that suggests suitable career paths based on user skills and interests. It uses Retrieval-Augmented Generation (RAG) with Google Gemini, FAISS, and SentenceTransformer embeddings.


## Features

* User-friendly interface with Streamlit
* Accepts natural language skill descriptions
* Retrieves top 5 relevant careers from CSV data
* Generates tailored recommendations with Gemini
* Shows confidence scores and pie chart visualization


## Requirements

* Python 3.8+
* Google Gemini API Key


## Setup

1. Clone or unzip the project:


2. Install dependencies:

   pip install -r requirements.txt

3. Add your Gemini API Key in `app.py`:

   genai.configure(api_key="YOUR_API_KEY")


4. Ensure `skills_career.csv` is in the project folder.


## Running the App

Start the Streamlit app locally:

streamlit run app.py

Open the link shown in your terminal to use the chatbot in your browser.


## Deployment

You can deploy for free on:

* [Streamlit Community Cloud]
* [Hugging Face Spaces]


## Example Input

> "I'm good at Python and data analysis but don't like front-end design."

**Example Output**:

* ✅ Data Analyst (92%)
* ✅ Data Scientist (87%)
* ✅ ML Engineer (80%)

With recommended resources and a pie chart of confidence scores.

