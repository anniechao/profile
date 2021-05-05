# 製作特色化的個人履歷
- 姓名: 趙晨安
- 系級: 外文四
- 學號: B06102029

## 履歷網址
Annie's Profile : [https://anniechao.github.io/profile/profile.html](https://anniechao.github.io/profile/profile.html)

## 作業說明
參考 pinterest 上的網站履歷範本圖，並自行設計本次作業。主要使用 `html`、`scss`、`bootstrap`，並且使用了 `aos` (`jquery`的套件) 進行coding。主要是自己刻模板，搭配部分套件完成整個網頁

### Design
1. 設計靈感來源參照 pinterest: [https://www.pinterest.com/pin/450148925245942022/](https://www.pinterest.com/pin/450148925245942022/)
2. 使用 Figma 簡易繪製履歷版面: [https://www.figma.com/file/pVtxDE03kp936fWZOFgg3B/Untitled?node-id=0%3A1](https://www.figma.com/file/pVtxDE03kp936fWZOFgg3B/Untitled?node-id=0%3A1)
3. 配色靈感參考 Coolors 網站:
   - [Palette 1](https://coolors.co/cb997e-eddcd2-fff1e6-f0efeb-ddbea9-a5a58d-b7b7a4)
   - [Palette 2](https://coolors.co/b98b73-cb997e-ddbea9-ffe8d6-d4c7b0-b7b7a4-a5a58d-6b705c-3f4238)
4. 使用 Font Awesome 提供的 Icon 於履歷中: [https://fontawesome.com/](https://fontawesome.com/)

### Bootstrap
1. 製作漢堡選單: [https://getbootstrap.com/docs/5.0/components/navbar/#nav](https://getbootstrap.com/docs/5.0/components/navbar/#nav)
2. 於 Skills 欄位使用 card 模組: [https://getbootstrap.com/docs/5.0/components/card/#titles-text-and-links](https://getbootstrap.com/docs/5.0/components/card/#titles-text-and-links)
3. 其他技巧: 
   - 使用 `row` & `col` 製作響應式版面
   - 於 Banner 與 Activities 欄位使用 `g-0` (no gutters) 去除 column 間的間距 
### HTML & SCSS & CSS
1. 使用 `scss` 做 coding
2. 於 Banner 欄位使用定位技巧 (`position relative/absolute`) 於 banner 欄位
3. 於 Projects 欄位使用 image hover overlay 技巧: [https://www.w3schools.com/howto/howto_css_image_overlay.asp](https://www.w3schools.com/howto/howto_css_image_overlay.asp)
4. 其他技巧:
   -  在欄位下 id 標籤，使用 navi 時可快速跳至特定區塊
   -  使用 flex 技巧製作響應式版面
   -  在 header 和 footer 的名字使用 `hover:{text-decoration:none;}` 於 a 標籤上
 
### AOS
- 使用 `AOS`(`jQuery`套件) 呈現捲動時的動畫效果: [https://michalsnik.github.io/aos/](https://michalsnik.github.io/aos/), [https://github.com/michalsnik/aos/blob/next/README.md](https://github.com/michalsnik/aos/blob/next/README.md)
- 包含以下幾種樣式(實際應用有調整一些參數):
  - fade-up/ fade-right/ fade-left
  - zoom-in 
  - 
  ```
  <div data-aos="fade-right"
     data-aos-offset="300"
     data-aos-easing="ease-in-sine">
  </div>
  ```
  - 
  ```
  <div data-aos="fade-up"
     data-aos-duration="3000">
  </div>
  ```
