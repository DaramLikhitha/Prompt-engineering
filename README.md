# Event Planning Chatbot

## Overview
This project is an event planning chatbot built using Streamlit and OpenAI's GPT-3.5 (Chat 3.5 Turbo) model. The chatbot assists users in planning various events by providing recommendations, scheduling assistance, and other relevant information.

## Features
- **Natural Language Understanding:** Utilizes OpenAI's GPT-3.5 (Chat 3.5 Turbo) model for natural language processing, enabling the chatbot to understand user queries and provide accurate responses.
- **Interactive Interface:** Built with Streamlit, providing a user-friendly interface for interacting with the chatbot.
- **Event Recommendations:** Offers suggestions for event venues, catering services, entertainment options, and more based on user preferences.
- **Scheduling Assistance:** Helps users schedule event dates and send invitations.
- **Customizable:** Easily customizable to accommodate different types of events and user preferences.

## Setup
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/DaramLikhitha/Event-planning-bot.git
    ```
2. **Install Dependencies:**
    ```bash
    cd event-planning-chatbot
    pip install -r requirements.txt
    ```
3. **Get OpenAI API Key:**
    - Sign up for the OpenAI API and obtain your API key.
    - Add your API key to the `.env` file.
4. **Run the Application:**
    ```bash
    streamlit run app.py
    ```
5. **Access the Chatbot:**
    Open your web browser and navigate to the URL provided by Streamlit (usually http://localhost:8501).

## Usage
- Upon launching the application, users are greeted with a chat interface where they can type their event planning queries.
- Users can ask questions or provide details about the event they are planning, such as the type of event, preferred date and time, number of attendees, budget, etc.
- The chatbot will process the input using OpenAI's GPT-3.5 model and provide relevant recommendations and assistance.
- Users can interact with the chatbot to refine their event plans, ask follow-up questions, or make changes to their preferences.

## Contributing
Contributions are welcome! If you have any ideas for improving the chatbot or adding new features, feel free to submit a pull request or open an issue.
