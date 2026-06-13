# JS → Node.js 銜接教學

給新手的互動式自學網站：**先把 JavaScript 觀念弄懂 → 再看它怎麼延伸到 Node.js**。
搭配六角學院 Node.js 直播班使用。

## 內容

7 課打通從 JS 銜接到 Node.js 的地基，每課固定三段：

1. **PART 1 ── 先把 JS 觀念弄懂**（生活比喻 + 程式碼 + 重點）
2. **PART 2 ── 延伸到 Node.js**（同一個觀念在 Node 變成什麼）
3. **換你試試**（點選即時對錯）

| 課 | JS 觀念 | 之後在 Node 變成 |
|---|---|---|
| 1 | 物件 | `req.url`、`data.title`、`module.exports` |
| 2 | 解構賦值 | `const { x } = require(...)` |
| 3 | 函式 + 箭頭 + callback | `createServer((req,res)=>{})`、`req.on("data", ...)` |
| 4 | 條件判斷 if / === / && | API 路由判斷 |
| 5 | 字串 ↔ JSON 互轉 | `JSON.parse` / `JSON.stringify` |
| 6 | 陣列 push / filter / map | `todos.push()`、整理資料 |
| 7 | 非同步 Promise / async / await | 讀檔、打 API、之後幾乎全部 |

## 使用方式

- 本地：直接用瀏覽器打開 `index.html`。
- 線上：本專案為純靜態網站，可直接用 Vercel 部署（零設定，根目錄的 `index.html` 即首頁）。

學習進度會自動存在瀏覽器的 localStorage。
