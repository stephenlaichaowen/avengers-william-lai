
# 一個很棒的圖像網格

![](https://cdn.glitch.com/e2d0de36-c372-4b42-8f8f-5dea2faa4285%2Fpic-1.png?1556420236684)

## 開始

最近 ***復仇者聯盟 4*** 正如火如荼地上映中, 各種周邊相關的應用也順勢而出, 有一個網站叫做 **[AVENGTHEM](https://avengethem.com/)** 提供了很酷炫的 AI 換臉功能, 總共有 17 個畫面, 我們只需上傳一張清楚的正面照, 網站就會自動的進行圖像融合並轉檔成 GIF 格式. 這個網頁 UI 的特色是圖片的寬度皆相同, 但是高度不同, 圖片的排列呈現無縫接軌 (如上圖所示), 這用 CSS Grid, Flexbox, 或是 Bootstrap 做不到, 必須使用其他的辦法. 上網搜尋關鍵字 "css image gallery with different sizes", 找到了解法, 這種排版叫做 "seamless responsive photo grid" ~ 無縫響應照片網格.

## 程式說明

要製作一個 "無縫響應照片網格", 其實非常容易, 在容器內設定 `column-count`, `column-gap`, `line-height` 這 3 個指令就可以辦到. 再透過 media query 設定不同斷點應該顯示的欄位數即可. 

- 取消行高 : `line-height: 0`

- 設定欄位數 : `column-count: 4`

- 取消欄位與欄位的間距 : `column-gap: 0`

<br>

## [程式碼 & DEMO]

- [程式碼](https://github.com/stephenlaichaowen/avengers-william-lai/blob/gh-pages/index.html)

- [DEMO](https://stephenlaichaowen.github.io/avengers-william-lai/)

## [學習資源 & 參考資料]

- [AVENGETHEM](https://avengethem.com/)

- [Seamless Responsive Photo Grid](https://css-tricks.com/seamless-responsive-photo-grid/)
