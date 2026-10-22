# 雲端拾荒者

靜態 three.js 方塊探索遊戲。用任意靜態檔案伺服器提供此資料夾，或直接開啟 `index.html`（瀏覽器若封鎖 ES modules 的 `file://` 載入，請使用靜態檔案伺服器）。遊戲從 CDN 載入 three.js；方塊、快捷欄圖示與裂痕素材取自 `sky-island-assets/`。

## 操作

- WASD 移動、滑鼠轉向、空白鍵跳躍、Esc 釋放滑鼠。
- 按住左鍵挖掘、走近收集；右鍵放置選中的方塊。
- 數字鍵 1–8 或滾輪選擇快捷欄；按 R 開始/結束流星雨。

## 專案檔案

- `BRIEF.md`：遊戲目標與限制
- `VERIFY.md`：兩批驗收清單
- `PLANS.v1.md`：原始計畫草稿
- `PLANS.md`：執行追蹤
- `AGENTS.md`：後續代理開發規則
- `src/logic.test.js`：邏輯測試；`src/logic.js`：可獨立驗證的遊戲規則
