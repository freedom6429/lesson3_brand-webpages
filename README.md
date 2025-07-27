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
