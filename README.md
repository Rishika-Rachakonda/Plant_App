# Plant App: Terrace Gardening

A comprehensive app designed for terrace gardening enthusiasts and beginners alike, providing detailed guidance on growing plants.

The app categorizes plants into three types: Vegetables, Fruits, and Flowers. It also features an integrated ChatGPT bot for instant help and a Weather API to assist with informed gardening decisions.

## Features:
- **Plant Categories**: Divided into Vegetables, Fruits, and Flowers with detailed growth instructions for each type.
- **ChatGPT Bot**: Integrated for instant guidance on gardening queries.
- **Weather API**: Provides real-time weather information to help users make informed gardening decisions.

## How to Run the Application

This application is built with frontend technologies and integrates third-party APIs (ChatGPT and Weather API).

### Prerequisites:
Before starting, ensure you have the following installed:
- **Node.js**: Ensure you have Node.js installed on your local machine. You can download it from [nodejs.org](https://nodejs.org/).
- **Code Editor**: A code editor like **VS Code** is recommended for better development experience.

### Steps to Run the App:

1. **Clone the Repository**  
   Clone the project repository to your local device. You can do this by running the following command in your terminal:
   ```bash
   git clone <repository-url>
2. **Open the Project in VS Code**
Open the cloned project folder in VS Code by selecting File > Open Folder....

3. **Install Dependencies**
Open the terminal in VS Code and navigate to the project directory. Install all required dependencies by running:
```
npm install

```
4. **Start the Application**
Once the dependencies are installed, you can start the application on your local machine by running:
```
npm start

```
This will launch the app at http://localhost:3000 in your browser.

## Setting Up the APIs

**Weather API** 

To integrate the Weather API, follow these steps:

1. Get your API key from OpenWeatherMap.

2. In the src/components/bot/bot.js file, update the API key URL with your key.

**ChatGPT API**

To access the ChatGPT API:

1. Get your API key from OpenAI.

2. In the server.js file, enter your API key where indicated.