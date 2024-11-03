# AI Chatbot with Gemini API

This project is a web application featuring an AI chatbot that provides real-time responses to user queries. Leveraging the Gemini API through Google's `google-generativeai` module, the chatbot uses generative AI to enable engaging, natural conversations with users. The frontend is built with HTML, CSS, JavaScript, and Bootstrap, while the backend is powered by Python's Flask framework.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Overview
The AI Chatbot project aims to create an interactive chatbot web application from scratch. Users can chat in real-time with the bot, which uses the Gemini large language model (LLM) to generate intelligent responses. 

## Features
- Real-time conversational AI
- Clean and responsive user interface
- Flask-based backend for handling requests and API communication
- Google Generative AI module for seamless interaction with the Gemini LLM

## Technologies Used
### Frontend
- **HTML** - Structure of the web pages
- **CSS** - Styling for a visually appealing interface
- **JavaScript** - Adds interactivity to the chatbot
- **Bootstrap** - Provides a responsive, user-friendly UI design

### Backend
- **Python (Flask)** - Serves as the backend framework, managing requests and responses

### Generative AI
- **Google Generative AI Module (`google-generativeai`)** - Used to interact with the Gemini API for AI-powered responses

## Installation

### Prerequisites
- **Python 3.x**
- **Google Cloud Account** with access to Gemini API and API Key
- **Flask** and **google-generativeai** Python libraries

### Steps
1. **Clone the Repository**
   ```bash
    git clone https://github.com/160121/Chatbot.git
2. **Navigate to the project directory**
   ```bash
    cd Chatbot
3. **Install the required packages**
   ```bash
    pip install Flask google-generativeai
4. **Configure API key**: Set up your Google Gemini API key in your environment. Create a .env file in the project root directory and add
   ```bash
    GOOGLE_API_KEY=your_google_api_key
5. **Run the Application**
   ```bash
    python app.py
  Open a browser and go to http://127.0.0.1:5000 to access the chatbot.
   
### Usage
- Open the web application in a browser.
- Type your queries in the chatbot window, and the AI will respond in real-time using Gemini's generative AI capabilities.
  
### Contributing
Contributions are welcome! Please follow these steps:

- Fork the project
- Create your feature branch (git checkout -b feature/YourFeature)
- Commit your changes (git commit -m 'Add YourFeature')
- Push to the branch (git push origin feature/YourFeature)
- Open a Pull Request
