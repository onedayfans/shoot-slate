# 短影音 場記表 · Script Supervisor's Log

**三機同拍的短片拍攝場記表網頁 — 排程、現場分工、Take 記錄、剪輯清單,一頁搞定。**
**A phone-first, single-file web app for planning and logging a 3-camera short-video shoot: schedule, on-set roles, take log, and an edit list.**

👉 **Live / 線上使用:https://onedayfans.github.io/shoot-slate/**

⭐ 覺得有用請給個星 / If this helps you, please star the repo!

## 功能 Features

| 分頁 Tab | 中文 | English |
|---|---|---|
| 排程 Plan | 依「輪」(一次表演、最多 3 台同時錄)排好整天時間表,自動插入午休,可調拍攝日期、開工時間、快慢節奏 | Day schedule built by *run* (one performance, up to 3 cameras rolling), auto lunch break, adjustable date / call time / pace |
| 現場 On set | 選 Cam1/2/3 或場記,只看自己的任務:畫面大小(附白話解釋)、鏡頭 mm、構圖、演員動作 | Pick Cam1/2/3 or Script Supervisor and see only your job: shot size (plain-language), lens, framing, action |
| 場記 Log | 每鏡記 Take、OK / 備用 / NG、各機檔案號、連戲、備註 | Per-shot take number, OK / backup / NG, file number per camera, continuity notes |
| 剪輯 Edit | 自動整理哪些畫面可用,可複製剪輯清單給剪輯師 | Auto-summary of usable footage, copyable edit list for the editor |

- 每個鏡頭有「儲存這一條」按鈕,存成一筆紀錄(時間/結果/次數/檔案號/備註),可單筆刪除;另有「全部清空」 / Per-shot **Save** button keeps a timestamped entry you can delete individually, plus a **Clear all** button
- 可填 Cam1/2/3 的機型(如 FX3、A7S3),全頁自動帶入,隨時修改整批更新 / Enter each camera's model (e.g. FX3, A7S3); it propagates everywhere and can be changed any time
- 內建名詞說明(Take、NG、連戲、越軸…)給不懂場記的人 / Built-in glossary for crew new to set terms
- 純靜態、無需後端;記錄存在瀏覽器 localStorage(同一支手機使用) / Static, no backend; logs live in your browser's localStorage (use the same phone on set)
- 支援淺色 / 深色模式 / Light & dark theme

## 資料 Data
目前內建兩支 40 秒短片的鏡頭資料(共 51 鏡)。想換成自己的片,修改 `index.html` 內的 `V1`、`V2`、`BEATS` 資料陣列即可。
Ships with shot data for two 40-second shorts (51 shots). To use your own project, edit the `V1`, `V2` and `BEATS` arrays in `index.html`.

## 授權 License
程式碼 Code: MIT。
Code is MIT licensed.
