# Chat with a Website from URL - LangChain Chatbot with Streamlit GUI
Chat with a Website from URL

# Features
1. Website Interaction: The chatbot uses the latest version of LangChain to interact with and extract information from various websites.
2. Large Language Model Integration: Compatibility with models like GPT-4, Mistral, Llama2, and ollama. In this code I am using GPT-4, but you can change it to any other model.
3. Streamlit GUI: A clean and intuitive user interface built with Streamlit, making it accessible for users with varying levels of technical expertise.
4. Python-based: Entirely coded in Python.
   
# Brief explanation of how RAG works
A RAG bot is short for Retrieval-Augmented Generation. This means that we are going to "augment" the knowledge of our LLM with new information that we are going to pass in our prompt. We first vectorize all the text that we want to use as "augmented knowledge" and then look through the vectorized text to find the most similar text to our prompt. We then pass this text to our LLM as a prefix.

# Installation

Ensure you have Python installed on your system. Then clone this repository:

git clone [repository-link]
cd [repository-directory]

Install the required packages:

pip install -r requirements.txt

Create your own .env file with the following variables:

OPENAI_API_KEY=[your-openai-api-key]


# Usage

To run the Streamlit app:

streamlit run app.py
