# Health Management App

This project is a **Health Management Application** that integrates **Google's Gemini Pro Vision API** to provide AI-driven health insights. The application is built using **Streamlit** for a simple and interactive web interface, and it supports image analysis and text-based health predictions.

## Features:
- Utilizes Google Gemini Pro Vision API for AI-based image and text analysis.
- Streamlit interface for easy user interaction.
- Secure API key management using environment variables.
- Supports multiple input types: text and images.

## Requirements:
To run this application, you need to have the following installed:
- Python 3.x
- Streamlit
- dotenv
- google-generativeai
- PIL (Python Imaging Library)


## Setup Instructions:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/health-management-app.git
   cd health-management-app

2. Install Dependencies:

       pip install -r requirements.txt

3. Add your Google API Key in a .env file:

       GOOGLE_API_KEY=<your-google-api-key>

4. Run the Application:

       streamlit run health.py


# How to Use:
Upload a health-related image and provide text input to get AI-generated insights using the Google Gemini Pro Vision API.

# Acknowledgments:
Google Gemini Pro Vision API for the AI insights.
Streamlit for the web framework.



