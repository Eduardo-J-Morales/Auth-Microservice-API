# Customer Service FAQ Chatbot

A simple and interactive chatbot designed to assist customers by answering frequently asked questions. This chatbot uses natural language processing to recognize user intents and provide relevant responses. It is built with Flask for the backend, a JSON-based knowledge base for intents and responses, and a user-friendly HTML interface for interaction.

> ⚡ **Note:** There is an explanation to install this Web App below for developers, however you don't need to install anything to try this Web App!  
> An online demo is available here: [Live Web App Deployment](https://customer-service-faq.zeabur.app/)
## Features 

- **Interactive Chat Interface**: A clean and responsive chat interface for users to interact with the chatbot.
- **Intent Recognition**: Uses tokenization to match user input with predefined intents in the knowledge base.
- **Customizable Knowledge Base**: Easily update the `knowledge.json` file to add or modify intents and responses.
- **Cross-Origin Resource Sharing (CORS)**: Enabled to allow seamless communication between the frontend and backend.
- **Dockerized Deployment**: Easily deploy the chatbot using Docker.

## Technology Stack

- ![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
- ![Flask](https://img.shields.io/badge/Flask-2.0.3-green?logo=flask&logoColor=white)
- ![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5&logoColor=white)
- ![CSS](https://img.shields.io/badge/CSS-3-blue?logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&logoColor=white)
- ![Docker](https://img.shields.io/badge/Docker-20.10-blue?logo=docker&logoColor=white)

## Installation

1. ### Clone the repo:
    ```sh
    git clone https://github.com/Eduardo-J-Morales/Customer-Service-FAQ-Chatbot.git
    cd Customer-Service-FAQ-Chatbot
     ```
    
2. ### Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```
    
3. ### Run the app:
    ```sh
    python app.py
    ```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
