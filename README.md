# OpenAI API 學習筆記與實作

本專案記錄我學習 OpenAI API 的過程與練習成果，包含文字生成、圖片辨識、對話記憶、串流輸出以及結構化資料擷取等功能。

---

##  學習內容

### 1. OpenAI API 基本調用

* 建立 OpenAI Client
* 發送 Prompt
* 取得 AI 回覆
* 使用 Instructions 控制回答風格

### 2. 串流輸出（Streaming）

* 即時接收模型回覆
* 處理 Event 與 Delta
* 模擬 ChatGPT 打字效果

### 3. 對話記憶

* 使用 `previous_response_id`
* 維持上下文對話
* 建立簡易聊天機器人

### 4. 圖片辨識（Vision）

* 圖片轉 Base64
* 上傳圖片給 OpenAI 模型
* 擷取圖片中的資訊

### 5. Structured Output（結構化輸出）

* JSON Schema
* Pydantic Model
* 指定 AI 回傳固定格式資料

### 6. 圖片資訊擷取實作

從圖片中擷取：

* 商品名稱
* 商品數量
* 商品價格

並透過 Pydantic 轉換成結構化資料。

---

##  使用技術

* Python
* OpenAI API
* Pydantic
* Base64
* JSON Schema
