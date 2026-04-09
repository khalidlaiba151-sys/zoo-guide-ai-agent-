# Zoo Tour Guide AI Agent

Zoo Tour Guide is a smart multi-agent AI project built with Google ADK.  
It researches animal-related questions using integrated tools and structured agent workflows.  
Fast, friendly, and informative — designed to turn curiosity into engaging answers.

## Description
...A multi-agent Zoo Tour Guide built with Google ADK that researches animal-related queries using Wikipedia and returns friendly, well-formatted responses.

## Features
- Built with Google ADK
- Sequential multi-agent workflow
- User prompt state management
- Wikipedia integration using LangChain
- Friendly formatted responses

## Tech Stack
- Python
- Google ADK
- LangChain
- Wikipedia API Wrapper
- dotenv
- Google Cloud Logging

## How It Works
1. The user enters a query
2. The prompt is saved in agent state
3. The researcher agent gathers information
4. The formatter agent creates a readable response
   Install dependencies:
   pip install -r requirements.txt
Environment Variables
MODEL=your_model_name
Run the Project
python agent.py
File Structure:
.
├── agent.py
├── .env
├── requirements.txt
└── README.md
Screenshot:
<img width="931" height="437" alt="image" src="https://github.com/user-attachments/assets/da6b9171-5757-4f0e-8807-47fa06d56f45" />
git clone https://github.com/khalidlaiba151-sys/zoo-guide-ai-agent-.git
cd zoo-guide-ai-agent-



- Add more external tools
