# THSR 高鐵自動訂票機器人 🚄

一個基於 Python 和 Playwright 的台灣高鐵網路訂票自動化工具。

## ✨ 功能特色

- 🔄 **自動填寫表單** - 自動填入起訖站、日期、時間等資訊
- 🔍 **驗證碼辨識** - 使用 ddddocr 自動辨識驗證碼
- ⏰ **優先時段選擇** - 設定偏好時段，自動選擇最適合的班次
- 🔁 **智慧重試機制** - 找不到符合時段時自動重新搜尋
- 🧪 **測試模式** - 可在不實際送出訂位的情況下測試流程

## 📋 系統需求

- Python 3.9 或以上
- 作業系統：Windows / macOS / Linux

## 🚀 安裝方式

### 方法一：從原始碼執行 (推薦)

```bash
# 1. 複製專案
git clone https://github.com/YOUR_USERNAME/THSR-Ticket.git
cd THSR-Ticket

# 2. 安裝依賴
pip install -r requirements.txt

# 3. 安裝 Playwright 瀏覽器
playwright install chromium

# 5. 執行程式
python main.py
```


## 🛠️ 開發者指南

### 專案結構

```
THSR-Ticket/
├── main.py           # 主程式 (GUI 入口)
├── bot.py            # 訂票邏輯核心
├── requirements.txt  # 依賴清單
├── README.md         # 說明文件

```
## ⚠️ 注意事項

- 本工具僅供學習和個人使用
- 請遵守台灣高鐵網站的使用條款
- 驗證碼辨識不保證 100% 正確，
## 🤝 貢獻

歡迎提交 Issue 和 Pull Request！

## 免責聲明

本專案僅供教育和學習目的。使用者應自行承擔使用本工具的風險和責任。開發者不對任何因使用本工具而導致的損失負責。
