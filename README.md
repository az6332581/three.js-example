STL 3D 模型查看器

介紹

這是一個基於 Vue 3 和 Three.js 的 STL 3D 模型查看器。使用者可以上傳 STL 文件，並透過 TrackballControls 進行無限制旋轉。還可以切換透視相機與正交相機，以及動態更改模型顏色。

功能

上傳 STL 檔案：透過 <input type="file"> 選擇並載入 STL 3D 模型。

無限制旋轉：使用 TrackballControls，允許 3D 模型自由旋轉、縮放和平移。

動態更改顏色：使用 <input type="color"> 可即時變更模型顏色。

相機切換：可在透視相機與正交相機之間切換。

環境光與點光源：提供基本光照，讓 3D 模型更具立體感。

依賴

Vue 3

Three.js

TrackballControls

STLLoader

使用方法

打開網頁：直接在瀏覽器中打開 index.html。

上傳 STL 文件：點擊「選擇檔案」按鈕，上傳 .stl 格式的 3D 模型。

旋轉、縮放與平移模型：使用滑鼠左鍵拖曳旋轉，滾輪縮放，右鍵拖曳移動。

變更顏色：選擇顏色以即時更新 3D 模型外觀。

切換相機：點擊「透視相機 / 無透視相機」按鈕切換相機模式。
