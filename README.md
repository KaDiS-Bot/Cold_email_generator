Project: Cold Email Generator for a Software Services Company

Overview: This project focuses on developing a cold email generator using Groq, Langchain, and Streamlit to streamline outreach for a software services company. The tool enables users to input the URL of a company's careers page, where it extracts job listings automatically. Based on the job descriptions, it generates personalized cold emails that include relevant portfolio links, which are sourced from a vector database.

Example Use Case: Imagine Nike is hiring a Principal Software Engineer and is allocating significant time and resources to the hiring process, onboarding, and training. A software services company like Atliq could provide a dedicated software engineer to meet Nike's needs efficiently. The tool would help a business development executive, like Mohan from Atliq, generate a targeted cold email to Nike’s HR team, offering Atliq’s services to fill the position.

Setup Instructions

  Get your API Key
  To begin, navigate to Groq Console and generate an API key. Once you have your key, open the app/.env file and update the GROQ_API_KEY field with your new API key.
  
  
  Install Dependencies
  Before running the app, install the necessary dependencies by running the following command:

    pip install -r requirements.txt

Run the Application
Launch the Streamlit app using this command:

    streamlit run app/main.py
