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

LineBot-FastAPI 是一個使用 FastAPI 開發 LINE 機器人的完整模組化範本。

## 主要功能與整合 🎉

主要功能：

* 🤖 **LINE Bot 整合**：輕鬆建立並管理 LINE 機器人，具有內建的事件處理與訊息功能。
* ⚡ **FastAPI 文件化與認證**：利用 FastAPI 強大的文件生成工具與安全認證機制。
* 🧠 **LLM 整合 (OpenAI)**：使用大型語言模型實現先進的聊天機器人邏輯，支援文本、圖片和音頻模態。

## 為什麼選擇這個範本？ 🚀

* 📝 **API 驅動的日誌紀錄**：此範本使用 API 呼叫來紀錄數據，確保更高的模組化與靈活性。
* ⚙️ **非阻塞的非同步操作**：設計用於同時處理多個使用者輸入，使機器人在高負載下仍保持響應快速且高效。
* 🌐 **LLM 全方位整合**：支援各種輸入模態（文本、圖片、音頻），提供更全面和互動式的聊天機器人體驗。

## 設定 API 金鑰與憑證 🔑

為了啟用全部功能，您需要設置 LINE API 的憑證並配置環境變數。

### 1. 在 LINE 開發者控制台註冊

1. **登入 LINE 開發者控制台**：[LINE Developer Console](https://developers.line.biz/)
2. **設定 LINE 認證**：
   - 點擊 **「建立新頻道」**。
   - 選擇 **訊息 API** 作為頻道類型。
3. **取得重要的金鑰與憑證**：
   - 進入 **基本設定** 並複製 **Channel Secret**。
   - 進入 **Messaging API** 並複製 **Channel Access Token**（如果是首次設定，請點擊 **發行**）。

### 2. 設定 Webhook

1. **取得公共域名**：當您部署應用程式並獲得公共域名（例如 `https://line.app`）後，請確保在 Webhook 設定中使用此 URL。
2. **配置 Webhook URL**：在 **Messaging API** 設定中，將 **Webhook URL** 設為：
   ```
   https://your-public-domain/webhooks/line
   ```
   請將 `your-public-domain` 替換為您的實際域名，並加上 `/webhooks/line` 後綴以正確路由。

3. **啟用 Webhook**：確保啟用 **使用 Webhook** 選項，以便機器人可以開始接收來自 LINE 使用者的訊息。

完成這些步驟後，您的 LINE 機器人將準備好處理事件並與使用者互動！

## 貢獻 🤝

我們歡迎社群的貢獻！無論是修正錯誤、增強功能，還是改進文件，查看我們的[問題頁面](https://github.com/yuting1214/LineBot/issues)來尋找需要幫助的地方。

---

由 [Mark Chen](https://github.com/yuting1214) 精心設計 :heart:
