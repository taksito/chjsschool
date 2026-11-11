# 新北市立忠孝國中 3D 校園

用 Blender 依「第五次變更建築工程竣工圖」建模的 3D 迷你校園，網頁用 three.js 顯示。

- `index.html`：網頁（three.js 由 jsDelivr CDN 載入）
- `campus_all.glb`：校園模型（含可行走面 `NAV_walkable`，網頁用來判斷樓梯與各樓層高度）
- `student_girl.glb`：主角女孩（含走路動畫）
- `buildings.json`：A～E 各棟樓層教室與處室資料

## 操作
- WASD／方向鍵移動，走樓梯可上 2～4F
- 點地面或走廊讓主角走過去
- 點大樓或下方 A～E 按鈕查看樓層資訊
- **F1**（或 V 鍵、畫面上的「視角」按鈕）切換視角：環繞 → 跟隨 → 第一人稱。跟隨與第一人稱用 W/S 前進後退、A/D 轉向，爬樓梯時鏡頭不會被樓板擋住

## 開啟方式
在 GitHub 的 Settings → Pages 選 `main` 分支、`/ (root)`，約 1 分鐘後可由
https://taksito.github.io/chjsschool/ 開啟。直接用檔案總管雙擊 index.html 會讀不到模型。
