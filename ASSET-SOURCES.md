# 素材來源與輸出記錄

## 本輪範圍

2026-09-11 補齊使用者指定的 Logo PNG、一般網站圖示 PNG、CRM／Panel 專用圖示、404 插圖，以及管理畫面中英文／深淺色截圖。全部新增於 public 根目錄，不製作龍蝦合成圖，不刪除既有素材。

## 品牌圖形

- 依據根目錄正式 v2.5 SVG 與 README 色票。
- 一般 PNG 由同名 SVG 以原尺寸四倍輸出；保留透明背景與原始比例。
- CRM／Panel 的 SVG 內嵌原 favicon 圖形，只做整體等比例縮放與移動，另加人物／方格徽章；沒有改動標誌內部路徑、配色或間距。
- 深色背景：左臂與圓點 #22EE88，右臂 #098658。淺色背景：左臂與圓點 #005e58，右臂 #15B97C。
- PNG 輸出使用 Sharp；未使用生成式工具重新繪製 Logo。
- 正式 favicon PNG 為固定色版；沒有將自動切色 SVG 的單次輸出誤稱成自動切色 PNG。

## 管理畫面截圖

- 來源：[新版管理頁示範模式](https://7eu-demo-00.realvco.com/v2/?demo=1#/today)。
- 擷取日期：2026-09-11；頁尾顯示 Admin Panel v26.0820.001。
- 使用已載入的示範模式頁面，透過頁面既有語言與配色按鈕取得四個版本。
- 完整頁面截圖均為 1898 × 1288；PNG 截圖轉為無損 WebP，逐像素比對相同。
- 未修改頁面 DOM、標誌、工作名稱、資料或產品程式。英文介面的示範工作名稱仍保留中文。
- 擷取結束恢復原本的繁體中文、深色顯示。
- 這批為新版「今天」總覽，並非替舊版主機儀表板截圖換皮。

## 404 插圖

- 使用內建 imagegen 生成；原始生成圖保留，倉庫提供 PNG 與 WebP。
- WebP 為網頁使用版本，PNG 為生成原圖。
- 目視確認：404 文字正確、無龍蝦、無新品牌標誌或浮水印。
- 生成提示詞如下（原文）：

```text
Use case: stylized-concept
Asset type: production website 404 error illustration for realvco.
Create one polished square 1536x1536 illustration. A small elegant helpful AI robot in a quiet futuristic wayfinding space looks thoughtfully at a floating broken navigation path that ends in a softly glowing question-mark shape. Above the robot, clearly legible large geometric digits "404". Visual style: refined editorial 3D illustration, smooth matte surfaces, subtle dimensional lighting, restrained composition with generous negative space, mature and friendly, suitable for an AI partner company. Background deep near-black teal #001111, primary highlights emerald #22EE88, secondary facets #098658, warm white #F2F6F5. The robot should be simple and abstract, no human face and no new brand emblem. Keep contrast clean. Typography must read exactly "404"; no other words, no logos. Avoid lobsters, red mascot characters, lime yellow-green, cluttered matrix code, server-wreck scenes, busy textures, watermarks, gradients behind any brand logo. Render crisp final image, opaque background.
```

## 檢查與限制

- 檢查輸出尺寸、透明度、全部圖片可正常解碼、兩個既有分享圖位置內容一致、截圖無損轉檔與 Git 差異格式。
- 本次沒有產品執行程式碼變動，未改動外部網站或郵件的素材引用。
- Figma 原稿未取得連結，未驗證或修改 Figma 文件。
