# LLM Cold Email Generator

Overview
This project is designed to automate the process of scraping job listings, extracting relevant information from the scraped content, and generating personalized cold emails for outreach using LangChain. The pipeline uses a machine learning model, ChatGroq, and document loaders from LangChain to achieve these objectives.

# Requirements
- Python 3.7+
- OpenAI API key
- Required Python packages:
  openai
  python-dotenv
  ipywidgets

# Installation
Clone this repository:
  git clone https://github.com/Shyam-45/AI-PoweredJob-Application-Assistant

Install the required packages:
  pip install openai python-dotenv ipywidgets


Create a .env file in the project root and add your OpenAI API key:
  OPENAI_API_KEY=your_api_key_here

# Usage
- Open the llm_code_email_generator.ipynb notebook in Jupyter Lab or Jupyter Notebook.
- Run all cells in the notebook.
- Use the provided input fields to enter company and recipient information.
- Click the "Generate Email" button to create a personalized cold email.
- The generated email will be displayed below the input fields.
