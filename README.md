<p align="center"> 
  <a href="https://github.com/yuting1214/LineBot-FastAPI"> 
    <img src="https://raw.githubusercontent.com/yuting1214/logo-store/refs/heads/main/assets/line-icon.svg" height="50"> 
  </a> 
</p>
<h1 align="center"> 
  <a href="https://github.com/yuting1214/LineBot-FastAPI">LineBot-FastAPI</a> 
</h1>

<p align="center">
  <span>
    <a href="https://railway.app/template/yNppuu?referralCode=jk_FgY"> 
      <img src="https://railway.app/button.svg" alt="Deploy on Railway" height="30"> 
    </a> 
    <a href="https://zeabur.com/templates/W6RZMT"> 
      <img src="https://zeabur.com/button.svg" alt="Deploy on Zeabur" height="30"> 
    </a>
  </span>
</p>

[![English](https://img.shields.io/badge/lang-English-blue.svg)](README.md)
[![中文 (繁體)](https://img.shields.io/badge/lang-中文(繁體)-red.svg)](README.zh-TW.md)

LineBot-FastAPI is a comprehensive and modular template for developing LINE bots using FastAPI. It integrates seamlessly with various APIs and provides a robust structure for handling complex interactions and processing.


## Key Features and Integrations 🎉
Key features:

* 🤖 LINE Bot Integration: Easily create and manage LINE bots with built-in event handling and messaging capabilities.
* ⚡ FastAPI API Documentation and Authentication: Leverage FastAPI's powerful documentation tools and secure authentication mechanisms.
* 🧠 LLM Integration (OpenAI): Implement advanced chatbot logic using Large Language Models, with support for text, image, and audio modalities.

## Why This Template ? 🚀
* 📝 API-Driven Logging: This template uses API calls to log data, ensuring better modularity and flexibility.
* ⚙️ Async Non-Blocking Operations: Designed to handle multiple user inputs simultaneously, making the bot responsive and efficient even under heavy load.
* 🌐 LLM Omniversal Integration: Supports various input modalities (text, image, audio) for a more versatile and interactive chatbot experience.

## Setting Up API Key and Credentials 🔑

To enable full functionality, you'll need to set up your LINE API credentials and configure the environment variables.

### 1. Register on LINE Developer Console

1. **Log in to LINE Developer Console**: [LINE Developer Console](https://developers.line.biz/)
2. **Set up LINE Authentication**:
   - Click **"Create a new Channel"**.
   - Choose **Message API** as the type of channel.
3. **Retrieve Important Keys and Tokens**:
   - Go to **Basic Settings** and copy the **Channel Secret**.
   - Go to **Messaging API** and copy the **Channel Access Token** (click **Issue** if setting up for the first time).
   
### 2. Set up Webhook

1. **Obtain Public Domain**: Once you have deployed your app and obtained a public domain (e.g., `https://line.app`), ensure you use this URL in the Webhook settings.
2. **Configure Webhook URL**: In **Messaging API** settings, set the **Webhook URL** as:
```
   https://your-public-domain/webhooks/line
```
   Replace `your-public-domain` with your actual domain and add the `/webhooks/line` suffix for correct routing.

3. **Enable Webhook**: Ensure that the **Use Webhook** option is enabled so your bot can start receiving messages from LINE users.

By following these steps, your LINE bot will be ready to handle events and interact with users!

## Contributing 🤝
We welcome contributions from the community! Whether it's bug fixes, feature enhancements, or documentation improvements, feel free to open a pull request.

---

Designed with :heart: by [Mark Chen](https://github.com/yuting1214)
