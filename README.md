# Tech Interview Assistant: Zinga

## Overview
Zinga is a friendly chatbot designed to assist users in preparing for technical interviews. Whether you're exploring algorithms, data structures, database management system, machine learning, or system design, Zinga is here to provide personalized guidance and answer your questions.

## Prerequisites
Before getting started, ensure you have the following prerequisites installed:

- Node.js (version >= 18)
```bash
  node --version # Should be >= 18
```
- Install the Google Generative AI package
```bash
npm install @google/generative-ai
```

## Usage
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/VivekSai07/Zinga-Interview-Companion.git
   ```
2. Navigate to the project directory:
   ```bash
   cd zinga-tech-interview-assistant
   ```
3. Create .env file and add your API key as: 
   ```bash
   API_KEY="Paste API Key here"
   ```
4. Run the server:
   ```bash
   node server.js
   ```
5. Open your web browser and go to http://localhost:3000 to access the chatbot interface.

## Chatbot Interaction
- Type your messages in the input field.
- Click the "Send" button to interact with Zinga.
- Zinga will respond based on the provided chat history and your input.

Feel free to ask Zinga about algorithms, data structures, machine learning, and more. Happy interviewing!
