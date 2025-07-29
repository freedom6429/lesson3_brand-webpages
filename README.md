# lesson3_brand-webpages

第三堂-RWD 品牌形象官網

2025/7/16 初稿
2025/7/17 按照 lesson2 任務助教建議修改以下項目：

1.  設計稿大部分文字的行高為 1.5 倍、字距為 0.05em 等，也可以統一在  body  設定，讓子元素繼承父層的文字設定，少部分（例如標題）再另外設定即可
2.  導覽列的高度依設計稿為 80px，可以調整一下 padding
3.  麵包屑可以參考 Bootstrap 調整為 nav>ol>li 的結構，另外當前的頁面項通常不會設定連結
4.  圖片的部分建議使用 img 標籤呈現，對 SEO 會比較好
5.  區塊可以嘗試使用百分比設定寬度

2025/7/28

1. base.css 部分樣式搬移至 layout.css
2. page-brand-story.css 標題樣式搬移至 base.css
3. 刪除 refactor 前的 css
4. base.css 加上 img 樣式設置
5. brand-story 的 hero 刪除 width: 100%
6. body 標籤的 font-family 字型設置修正
7. 刪除多餘 lettter-spacing: 0.05em 設置
8. breadcrumb 調整為 <nav> 標籤
9. 修正 768~1320 範圍 X 軸可滾動的問題
10. 頁碼 hover 樣式，可再根據設計稿呈現來做設置唷（背景色：#F8F9FA）
11. 修正產品詳細頁產品圖片 desktop 版間距以及 mobile 版滿版樣式
12. 修正品牌故事頁 hero filter 的 padding 小數點
13. 品牌故事頁 history 事件列表以 ol 取代 ul

2025/7/30

1. img 部分都以 base.css 設定的 max-width 為主，其他頁面多餘 width 設定刪除
2. 部分 div 區塊的 width: 100%刪除
3. 移除 nav-link-item 類別，但保留.heading 的 letter-spacing:0.05 設定，因為 heading 字體大小會影響 letter-spacing 計算結果，無法直接繼承 body 設定。
4. 修改 media query typo(pax->px)
5. 產品詳細頁 mobile 主圖不使用 vw 而改為另外寫一個專用 div，螢幕切換到 mobile 版才會顯示以跳脫 container
6. 品牌介紹頁主圖因 typo 造成滿版問題修正為有水平 padding 的樣式
