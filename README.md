# Classic Snake｜最原始貪吃蛇

這是一款使用 HTML、CSS、JavaScript 製作的最原始貪吃蛇小遊戲。

## 遊戲玩法

- 使用 WASD 或方向鍵控制蛇移動
- 吃到紅色食物會加分並變長
- 撞到牆壁會遊戲結束
- 撞到自己會遊戲結束
- 支援手機方向鍵按鈕
- 最高分會儲存在瀏覽器中

## 專案結構

```text
classic-snake-game/
├── index.html
├── style.css
├── script.js
├── README.md
└── .nojekyll
```

## 如何遊玩

直接用瀏覽器打開 `index.html` 即可遊玩。

## GitHub Pages 上傳方式

1. 建立新的 GitHub repository。
2. 將本資料夾內的檔案上傳到 repository 根目錄。
3. 確認 `index.html` 在根目錄。
4. 到 Settings。
5. 進入 Pages。
6. Source 選 `Deploy from a branch`。
7. Branch 選 `main`，資料夾選 `/root`。
8. 儲存後等待部署完成。

## 技術

- HTML
- CSS
- JavaScript


## WASD 修復

此版本改用 `event.code` 判斷鍵盤輸入，支援：

- W：向上
- A：向左
- S：向下
- D：向右
- 方向鍵：上下左右
- 空白鍵：開始遊戲

若上傳 GitHub Pages 後仍看到舊版本，請清除快取或使用 Ctrl + F5 強制重新整理。


## 分數無上限

此版本已修正棋盤填滿後可能卡住的問題。  
蛇長到棋盤容量上限後，繼續吃食物仍會加分，但不再繼續變長，因此分數可以持續累積。
