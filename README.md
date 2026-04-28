# Idea Forge 🚀  
AI-Powered Business Idea Generator for Tamil Nadu

## Overview
Idea Forge is an interactive web application built with Streamlit that generates personalized business ideas based on a user’s interests, qualifications, budget, and district within Tamil Nadu.

Using the Gemini API, the platform analyzes user inputs and suggests locally relevant business opportunities tailored to regional market conditions. The application also provides budget planning, entrepreneurial guidance through an AI assistant, and downloadable reports for users.

## Features
- 💡 Personalized business idea generation using Gemini API  
- 📍 District-specific recommendations tailored to Tamil Nadu markets  
- 💰 Budget distribution planning for startup allocation  
- 🤖 AI-powered business development assistant chatbot  
- 📄 Export generated business plans as Word documents  
- 🎯 User-friendly interactive interface built with Streamlit  

## Tech Stack
- Python
- Streamlit
- Gemini API (Google Generative AI)
- Python-dotenv
- python-docx

## How It Works
Users provide:
- Name
- District
- Qualifications
- Startup Budget
- Interests

The application then:
1. Generates 3 personalized business ideas
2. Suggests required resources and growth potential
3. Provides marketing strategies and actionable startup steps
4. Calculates an estimated budget allocation
5. Allows users to download results as a Word report
6. Offers additional entrepreneurial guidance through an AI assistant

## Project Structure
```bash
idea_forge.py        # Main Streamlit application
.env                 # API key configuration (not included in repo)
requirements.txt     # Dependencies
```

## Installation

### Clone the repository
```bash
git clone https://github.com/your-username/idea-forge.git
cd idea-forge
```

### Create virtual environment (Optional but recommended)
```bash
python -m venv venv
source venv/bin/activate      # On Mac/Linux
venv\Scripts\activate         # On Windows
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Add Gemini API Key
Create a `.env` file in the root directory:

```env
GEMINI_API_KEY=your_api_key_here
```

## Run the Application
```bash
streamlit run idea_forge.py
```

## Example Use Cases
- Aspiring entrepreneurs looking for startup ideas
- Students exploring business opportunities
- Localized market opportunity discovery
- Small business planning and idea validation

## Future Improvements
- Support for all Indian states
- Market trend analysis integration
- Business feasibility scoring
- Multi-language support
- Investor/funding recommendation module


