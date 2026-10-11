# 個人作業：分段實作建議（對應程式碼內 STEP 註解）

> 這份專案是可以用來參考與測試的範例版本。上課作業請依老師的 AI 使用規範，自己理解與修改程式，不應將 AI 直接製作的程式當作完全由自己獨立完成。Commit 時紀錄你實際做過的事，不要人為製造虛假的開發歷史。

| 階段 | 實作 | 自己檢查的重點 |
|---|---|---|
| STEP 01 | HTML 基本架構 | 標題、首頁／測驗、日文介面 |
| STEP 02 | CSS 黑白排版 | 手機版不水平超出、字能讀 |
| STEP 03 | 37 字資料表 | 21 聲母、13 韻母、3 介音，加上例詞 |
| STEP 04 | JavaScript 自動生成卡片 | 左注音、右例詞，數量 37 |
| STEP 05 | 37 個教育部 WAV 檔播放 | `audio/F1.WAV` 到 `audio/F37.WAV` |
| STEP 06 | 中文例詞 TTS | `zh-TW` 語音設定與無語音環境提示 |
| STEP 07 | 五聲調練習 | ㄅㄚ、ㄅㄚˊ、ㄅㄚˇ、ㄅㄚˋ、˙ㄅㄚ（八、拔、把、爸、吧） |
| STEP 08 | 隨機四選一測驗 | 10 題不重複、答案判定、總分、重來 |
| STEP 09 | 授權、部署與完成檢查 | CC BY 4.0 標示、手機版、Chrome、GitHub Pages |

**聲調音源注意：** 教育部 37 個 WAV 只涵蓋單一注音發音；五聲調練習使用瀏覽器 TTS。請用台灣華語音源及真人發音比較，不能保證 TTS 的聲調一定正確。

**GitHub 獨立 Repo 建議名稱：** `bopomofo`。在 GitHub 新增 Repo 時勾選「Add a README file」以建立 main 分支（不要額外選 License，專案已含音檔授權聲明），將此壓縮檔**內的檔案**放到 Repo 根目錄。上傳後到 Settings → Pages → Deploy from a branch → `main` / `(root)` → Save。正式網站網址預計為 `https://kuanyu-10.github.io/bopomofo/`，必須等 Pages 發布成功後才能視為可用。