# 🛡️ CISP 模擬試題 Flash Card

> 註冊信息安全專業人員 (Certified Information Security Professional) 模擬試題
> 303 條題目，分 16 個知識分類，配備 flash card 互動學習

## 🌐 線上訪問

**https://garyfunghcai.github.io/cisp-flashcard/**

## ✨ 功能

- **303 條 CISP 試題**（來源：[npcola/CISP](https://github.com/npcola/CISP/blob/main/%E8%AF%95%E9%A2%98.md)）
- **16 個知識分類**自動分類（密碼學、訪問控制、風險評估、ISMS、網絡安全、應急響應、等級保護、SSE-CMM、法律法規、人力安全、物理安全、業務連續性、IATF、軟件安全、操作系統、新興技術、供應鏈）
- **持久化進度**（localStorage v1 schema — 刷新頁面唔冇 progress）
- **書籤功能**（釘選難題，獨立 filter 翻睇）
- **錯題回顧**（自動收集錯題，可一鍵複習）
- **分類篩選**（按知識分類做專項訓練）
- **洗牌模式**（隨機順序，避免背答案位置）
- **進度匯出/匯入**（JSON 格式，方便多設備同步）
- **鍵盤快捷鍵**（1-4 揀答案 / Space 下一題 / B 書籤 / R 顯示答案）

## 🛠️ 技術

- 純 vanilla JS + HTML + CSS，**零 build step**
- 單檔部署（`index.html` 自帶所有題庫）
- localStorage 持久化
- 深色配色（藍紫漸層）+ Noto Sans TC

## 📦 本地運行

```bash
git clone https://github.com/garyfunghcai/cisp-flashcard.git
cd cisp-flashcard
python3 -m http.server 8000
# 訪問 http://localhost:8000
```

## ⚠️ 題庫聲明

- 題庫來源於 [npcola/CISP](https://github.com/npcola/CISP) 開源項目
- 本倉庫僅作學習用途
- 試題原始編號 1-314 中有 10 個跳號（源文件缺漏），實際收錄 **303 條**
- 分類由正則表達式自動標註，**僅供參考**，可能有誤判

## 📝 License

題庫內容版權歸原作者所有。本工具代碼 MIT License。
