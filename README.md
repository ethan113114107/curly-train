# 慈濟經管系網｜學術深紅整合版
版本 tcu-academic-final-20261015。學生個人系網提案，非校方官方網站。

## 使用
完整解壓縮後開啟 index.html；三個 HTML、404.html、graph/ 保持同一層。
CSS/JS 內嵌各 HTML，沒有 CDN、字型檔、登入、追蹤、資料庫或收件表單。
index.html：系所介紹、學習特色、成果、官方資源與聯絡。
studentworks.html：三筆公開成果、篩選、搜尋、介紹視窗、攝影版位、概念影片。
ai-collaboration.html：九則實際 Prompt、後補筆記、設計參考與評分對照。

## 維護
兩個主頁的 window.STUDENT_WORKS 是作品資料，修改時同步更新題名、分類、摘要、原始公告與 graph/圖片路徑。
共用樣式位於各頁 style；修改請同步所有 HTML。
攝影區 photography 保留三個版位。照片放進 graph，修改 src、alt、拍攝者、日期、活動、圖說並移除待補實拍註記。
影片更新 source、poster、片長與文字稿；不得將示意素材當成自行拍攝成果。
「嶼食織心」不列為網站作品，只在歷史刪除指令出現。

## 上線
根目錄含 index.html、studentworks.html、graph；Public、main / root，非直接上傳 ZIP。
實際狀態見 PUBLISH-STATUS.json。保留既有 metro_control_center.html，不覆寫其他課程作業。
給分由老師決定，公開部署與本機檔案驗收分開確認。
