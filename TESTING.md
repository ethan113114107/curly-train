# 本版驗收與限制
版本 tcu-academic-final-20261015；日期 2026-10-15。

## 已執行
四個HTML的doctype、單一h1、不重複ID、內嵌CSS/JS、所有本機連結與片段、graph素材路徑。
兩主頁沒有被要求刪除的專案名稱；AI紀錄保留完整九則。
各段JavaScript以Node --check驗證語法。
以Python本機HTTP伺服器逐一GET 15項原始檔案，HTTP200且bytes一致。
Chromium三頁 × 1440、1024、820、768、390、320像素，共18組，沒有水平溢出或可見圖片缺漏。
實際操作平板／手機選單、Escape、分類、搜尋、無結果、重設、作品視窗、Prompt展開收合及複製。
H.264 MP4成功播放、duration16、currentTime增加、video.error為null。捕捉到的pageerror為0。
詳細機器輸出：TEST-RESULTS.json。

## 方法與限制
瀏覽器直接網路／file導覽受到本執行環境限制，視覺／互動以set_content孤立DOM驗證。
只在測試記憶體將媒體改成data URI；交付HTML保留graph/相對路徑，未嵌入媒體。
本機HTTP200及DOM測試不等於公開網址端到端驗收；發布結果單獨見PUBLISH-STATUS.json。
未做實機iPhone Safari或完整WCAG／螢幕閱讀器認證。
未聲稱學生親自執行AI工具完成的測試，未承諾外部官網永久不變。
