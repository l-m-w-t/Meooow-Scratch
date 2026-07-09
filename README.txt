數位刮刮卡使用說明

請把以下檔案放在同一個資料夾：

1. index.html
2. main-visual.jpg   ← 必備，底圖／主視覺
3. silver.png        ← 可選，銀膜圖層；若沒有，程式會自動生成銀膜

使用方式：
- 直接雙擊 index.html，用 Chrome / Safari / Edge 開啟。
- 展場建議使用 Chrome 或 Edge 全螢幕模式。
- 60 秒無操作後會自動回到完整銀膜。

可調整參數：
- idleResetTime：無操作幾秒後重置，目前為 60 秒。
- brushSize：刮除半徑，目前為 75。
- #mainVisual 的 object-fit：
  - cover：滿版顯示，可能裁切。
  - contain：完整顯示，不裁切，但可能有留邊。
