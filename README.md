# 🌺 Okinawa Solo Trip 2025 PWA

一個精美的旅遊行程規劃 Progressive Web App，專為 2025 沖繩單人旅行設計。

## ✨ 功能特色

### 📅 行程頁面
- 以時間軸方式展示 4 天行程
- 可展開/收合每日活動詳情
- 重要事項特別標示

### ✅ 必做清單
- 互動式勾選功能
- 進度條顯示完成度
- 資料自動儲存於本地端

### 📖 攻略頁面
- 折疊式選單設計
- 包含交通、美食、購物、演唱會資訊
- 緊急聯絡資訊

## 🛠️ 技術堆疊

- **React 18** - UI 框架
- **Tailwind CSS** - 樣式系統
- **Lucide React** - 圖示庫
- **PWA** - 可安裝至手機主畫面

## 📱 如何安裝到手機

### iOS (Safari)
1. 用 Safari 開啟此網頁
2. 點擊底部「分享」按鈕 (方形+箭頭圖示)
3. 選擇「加入主畫面」
4. 點擊「新增」

### Android (Chrome)
1. 用 Chrome 開啟此網頁
2. 點擊右上角選單 (三個點)
3. 選擇「安裝應用程式」或「加入主畫面」
4. 點擊「安裝」

## 🚀 本地開發

```bash
# 使用任何靜態伺服器即可
# 例如 Python:
python -m http.server 8000

# 或 Node.js:
npx serve .

# 然後開啟瀏覽器訪問 http://localhost:8000
```

## 📁 檔案結構

```
okinawa-trip/
├── index.html      # 主要應用程式
├── manifest.json   # PWA 配置檔
├── sw.js          # Service Worker (離線功能)
├── icon.svg       # App 圖示
└── README.md      # 說明文件
```

## 🎨 設計理念

採用 Apple 風格的極簡設計：
- 純白背景搭配柔和灰色
- 圓角卡片與微妙陰影
- 流暢的動畫與過渡效果
- 清晰的資訊層級

## 📝 自訂行程

如需修改行程內容，請編輯 `index.html` 中的以下資料：

- `itineraryData` - 每日行程
- `todoData` - 必做清單項目
- `guideData` - 攻略內容

## 📄 License

MIT License - 歡迎自由使用與修改

---

祝你沖繩旅途愉快！🌴☀️🍜
