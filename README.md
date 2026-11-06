# A2O 知識問答（Knowledge QA Chatbot）

單頁 HTML 聊天機器人，根據「A2O（虛構）精密零組件廠」的知識庫回答客戶問題。
由 **Groq** 的 LLM 驅動，前端做輕量檢索（RAG 簡化版），只依知識庫內容回答，避免編造。

## 功能
- 單一 `index.html`，瀏覽器開啟即可使用，無需安裝。
- 輸入 **Groq API key** 才能啟用（可於 [console.groq.com](https://console.groq.com) 免費申請）。
- 內建知識庫：WH-12 產品母稿（規格／保固／認證／適用場景）、新人須知 2026（客戶詢問、客訴、報價權限、對外承諾）、報價流程、退換貨辦法、窗口。
- 訊息介面：含建議問題 chips、引用出處顯示。

## 使用
1. 開啟 `index.html`。
2. 在上方輸入你的 Groq API key，按「儲存並啟用」。
3. 輸入或點選建議問題。

## 模型
- `openai/gpt-oss-120b`（Groq 上的 GPT-OSS 模型）

## 知識庫來源
- A2O 課程練習包（虛構公司與假資料），僅為練習用途。

## License
本專案僅供學習與練習使用。
