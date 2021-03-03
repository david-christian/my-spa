# Cake Garden 蛋糕交流  

## 專案說明  

前端： React Hooks  
後端： JSON server  

此專案以 SPA架構實作，前後端 API 採 RESTFUL 風格  
專案：https://david-christian.github.io/my-spa/  

![](https://i.imgur.com/GAkkAYx.png)  

---  

## 主要功能  

### 會員系統  

有註冊、登入等相關功能，用 JWT 做驗證  
  
![](https://i.imgur.com/A3ahwdk.png)  
  
### 瀏覽文章  

以小區塊展示使用者的發送的文章，最新的文章會最前面  
有分頁功能，一頁最多五篇文章  

![](https://i.imgur.com/vEEjtp6.png)  
  
### 單篇文章
  
點擊首頁的小區塊文章，即可瀏覽單篇文章  

![](https://i.imgur.com/A2krjYY.png)  

### 管理文章  

發佈該文章的使用者有權編輯、刪除，admin有權刪除所有文章  

![](https://i.imgur.com/S93v2cM.png)  

### 發佈文章  

發佈介面可以預覽圖片，如果使用者發佈文章時沒有圖片
會自動預設一張圖片當作封面  

![](https://i.imgur.com/XxjW6t7.png)  

---  

## 專案技術  

### 前端  

框架： React Hooks  

Library：
 * react-router-dom：建立路由，以完成 SPA 架構
 * styled-components：在 JSX 中撰寫 CSS code，用props 值來動態改變 css 樣式
 * Prettier：使 Code 撰寫風格一致  
 * Eslint：檢查 Code ，維持 Code 品質
 * react-spinners：loading 樣式相關套件

### 後端  

Json server  

專案repo：https://github.com/david-christian/spa-jsonserver  

以 Json server 作為專案後端，並做一些功能上的微改寫完成需求，做為專案資料來源  
前後端 API 以 RESTFUL 風格實作，並部署在 Heroku  

Library：
  * jsonwebtoken：完成登錄功能的驗證





