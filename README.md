STL 3D 模型查看器

📌 介紹

這是一個基於 Vue 3 和 Three.js 的 STL 3D 模型查看器。使用者可以上傳 STL 文件，並透過 TrackballControls 進行無限制旋轉。此外，還支援相機切換與動態顏色變更。

✨ 功能

✅ 上傳 STL 檔案 - 透過 <input type="file"> 選擇並載入 .stl 3D 模型。
✅ 無限制旋轉 - 使用 TrackballControls，允許 3D 模型自由旋轉、縮放和平移。
✅ 動態更改顏色 - 使用 <input type="color"> 即時變更 3D 模型顏色。
✅ 相機切換 - 透視相機 (PerspectiveCamera) 與正交相機 (OrthographicCamera) 之間切換。
✅ 環境光與點光源 - 提供基本光照，提升 3D 模型的可視化效果。

📦 依賴

本專案使用以下 JavaScript 函式庫：

Vue 3

Three.js

TrackballControls

STLLoader

🚀 使用方法

打開網頁：直接在瀏覽器中打開 index.html。

上傳 STL 文件：點擊「選擇檔案」按鈕，上傳 .stl 格式的 3D 模型。

旋轉、縮放與平移模型：

滑鼠 左鍵 拖曳 → 旋轉

滑鼠 滾輪 滾動 → 縮放

滑鼠 右鍵 拖曳 → 平移

變更顏色：使用色彩選擇器 (<input type="color">) 即時更改模型外觀。

切換相機：點擊 透視相機 / 無透視相機 按鈕切換相機模式。
