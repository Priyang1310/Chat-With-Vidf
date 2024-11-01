
# Chat with Video/PDF Conversational Bot

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Technologies Used](#technologies-used)
4. [Features](#features)
5. [System Architecture](#system-architecture)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Future Enhancements](#future-enhancements)

---

## Introduction

This project provides a conversational bot interface allowing users to upload videos or PDFs, which the bot analyzes to generate contextual responses and dynamic, personalized interactions. Built to enhance user engagement, the bot answers questions based on uploaded content and supports character customization.

## Project Overview

The conversational bot leverages the Gemini 1.5 Flash API to understand and answer questions based on video and PDF content. Key features include secure login via Auth0, a responsive UI, and efficient state management through React Context, offering a smooth, personalized user experience.

## Technologies Used

- **Frontend**: React, React Context
- **Backend**: Flask, Python
- **Database**: MongoDB
- **Authentication**: Auth0
- **ML & Conversational API**: Gemini 1.5 Flash API

## Features

- **Dynamic Question Answering**: Contextual responses based on uploaded video and PDF content.
- **User Authentication**: Secure login and profile management using Auth0.
- **Character Customization**: Personalize bot responses with adjustable character attributes.
- **Content Analysis**: Contextual understanding of videos/PDFs to provide relevant answers.

## System Architecture

The project is divided into client and server sections:

- **Client**: Built with React to provide a responsive interface, manage user interactions, and handle data flow via React Context.
- **Server**: Flask serves as the backend, handling API requests and integrating with MongoDB for data storage.
- **Database**: MongoDB stores user data, content uploads, and character attributes.
- **Authentication**: Auth0 secures the authentication process.
- **Gemini 1.5 Flash API**: Powers the bot's question-answering and contextual analysis.

## Installation

### Prerequisites
- Node.js
- Python
- MongoDB

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/chat-with-vidf-full-stack.git
   cd chat-with-vidf-full-stack
   ```

2. **Install client dependencies**:
   ```bash
   cd client
   npm install
   ```

3. **Install server dependencies**:
   ```bash
   cd ../server
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables**: Set up `.env` files for both client and server with your MongoDB URI, Auth0 credentials, and Gemini API keys.

5. **Run the application**:
   - Start MongoDB.
   - Start the client:
     ```bash
     cd client
     npm start
     ```
   - Start the server:
     ```bash
     cd ../server
     python app.py
     ```

## Usage

1. **Sign up/Login**: Access the bot through secure authentication.
2. **Upload Content**: Add videos or PDFs for contextual analysis.
3. **Interact with the Bot**: Ask questions related to the uploaded content.
4. **Customize Responses**: Adjust character settings to personalize interactions.

## Future Enhancements

- **Expanded Language Support**: Implement multilingual capabilities.
- **Voice Interface**: Add voice input and responses.
- **Enhanced Analytics**: Track user interactions for deeper insights.

## Screenshots

### Landing Page
(./client/public/assets/screenshots/landing.png)

### Login Page
(./client/public/assets/screenshots/Auth0.png)

### Chat Interface
(./client/public/assets/screenshots/Chatbot.png)

### Casual Conversation
(./client/public/assets/screenshots/conversation.png)

### Adding File (Pdf/Video)
(./client/public/assets/screenshots/addFile.png)

### Adding Character
(./client/public/assets/screenshots/characters.png)

### Asking doubt and expecting answer in the tone of added character
(./client/public/assets/screenshots/asking.png)

### Voice Support
(./client/public/assets/screenshots/voice.png)

### Multilingual Support (currently three languages supported: English, Hindi, Gujarati)
(./client/public/assets/screenshots/multilingual.png)




---
