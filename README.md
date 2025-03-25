"""
README for ManekTech AI-powered Chatbot

This document provides an overview of the ManekTech AI-powered Chatbot, its features,
architecture, and instructions for running the application.
"""

# ManekTech AI-powered Chatbot

## Overview

The ManekTech AI-powered Chatbot is an interactive conversational system that uses multiple AI agents to provide information about ManekTech's services, handle hiring queries, and schedule meetings. The chatbot features animated characters with lip movement and text-to-speech capabilities for a realistic conversation experience.

## Features

### Multiple AI Agents
- **Data Extraction Agent**: Extracts and provides company details from ManekTech data
- **Client Interaction Agent**: Mimics human responses for client interactions
- **Hiring Query Agent**: Handles hiring queries with positive responses about the company
- **Meeting Scheduler Agent**: Schedules meetings with ManekTech representatives

### Interactive User Interface
- Three animated characters representing different agents
- Character lip movement when responding
- Interactive chat interface
- Agent selection buttons

### Audio Capabilities
- Text-to-speech functionality
- Different voices for different characters
- Audio toggle option

## Technical Architecture

### Backend
- **Data Extraction**: Ultra-lightweight keyword-based approach for extracting company information
- **Client Interaction**: Conversational agent with natural language processing
- **Hiring Queries**: Specialized agent for handling career-related questions
- **Meeting Scheduling**: State-based conversation flow for scheduling meetings

### Frontend
- **Streamlit**: Web-based user interface
- **Character Animation**: CSS-based lip movement animation
- **Text-to-Speech**: pyttsx3 for generating audio responses

## Requirements

- Python 3.10+
- Streamlit
- pyttsx3
- Other dependencies listed in requirements.txt

## Installation

1. Clone the repository:
```
git clone https://github.com/your-username/manektech-chatbot.git
cd manektech-chatbot
```

2. Install the required packages:
```
pip install -r requirements.txt
```

## Running the Application

Run the main application script:
```
python main.py
```

This will start the Streamlit server and open the chatbot in your default web browser.

Alternatively, you can run the Streamlit app directly:
```
streamlit run frontend/app_with_tts.py
```

## Project Structure

```
manektech_chatbot/
├── backend/
│   ├── ultra_lightweight_extraction_agent.py
│   ├── client_interaction_agent.py
│   ├── hiring_query_agent.py
│   ├── meeting_scheduler_agent.py
│   └── test_*.py (test scripts for each agent)
├── data/
│   └── manektech_info.md (company information)
├── frontend/
│   ├── app.py (basic frontend)
│   ├── app_with_tts.py (frontend with text-to-speech)
│   └── text_to_speech.py (TTS functionality)
├── main.py (main application script)
├── requirements.txt
└── README.md
```

## Usage Examples

### Client Services
- "What services does ManekTech offer?"
- "Tell me about your company"
- "What technologies do you work with?"
- "Can you show me some of your projects?"

### Hiring Information
- "Are you hiring?"
- "What's the work culture like at ManekTech?"
- "What skills do you look for in developers?"
- "What benefits do you offer to employees?"

### Meeting Scheduling
- "I'd like to schedule a meeting"
- "Can I book a call with your team?"
- "I want to discuss a project with your team"

## Future Enhancements

- Integration with ManekTech's calendar system for real-time availability
- More sophisticated animations for characters
- Support for additional languages
- Voice input capabilities

## License

[Specify the license here]

## Contact

For questions or support, please contact [your contact information].
"# chatbot" 
"# chatbot" 
