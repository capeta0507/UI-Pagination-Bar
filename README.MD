# Pagination bar (分頁) UI
###### tags: `UI` `Pagination`

搜尋關鍵字：web pagination design。
當API取得資料之後，如何表達資料、如何翻頁、分頁，是前端 UI 介面所要學習的。

下圖為搜尋設計：
![](https://i.imgur.com/AkKNmzD.png)


下圖為分頁按鈕設計：
![](https://i.imgur.com/iPTYROl.png)

我們將會用 [Unsplash](https://unsplash.com/) 圖檔的網站，提供圖片搜尋的 API 來取得資料之後，進行資料顯示的分頁練習。

### Unsplash API 教學
1. [Photo Search Using the Unsplash API](https://www.youtube.com/watch?v=Rvv8xheoINc)
2. [How to make a flat design search box | HTML & CSS](https://www.youtube.com/watch?v=csY6KW7cIUM)
3. [Pagination UI Design Using Html CSS and jQuery | next() Prev()](https://www.youtube.com/watch?v=nRUbvKTiq8Y)

### Unsplash 註冊申請
1. 到 Unsplash 去註冊一個帳號
用 FB 註冊，填入以下資料
1. 註冊資料
First name : David
Last name : Chan
Email address : davidtpe@seed.net.tw
Username : davidtpe
Password : david4255
1. 到 your apps 去註冊開發API申請
Application name : Photo_Search
Description : Unsplash_Search (Test)
Access Key : z2lKI1fv5HipWjpXTi6YFxymvT6Fg1z5mIDBIYK3RqA
Secret key : 6wK882suToEl_XLY43SPgpV2qv28VNel6zNfaes0Jck
1. 閱讀 [API Documenation](https://unsplash.com/documentation)
2. API Search photos 參數 [Search photos](https://unsplash.com/documentation#search-photos)

### postman API Test
用 postman get 呼叫 https://api.unsplash.com/search/photos/?query=sky&client_id=z2lKI1fv5HipWjpXTi6YFxymvT6Fg1z5mIDBIYK3RqA

可以得到 json response
![](https://i.imgur.com/qyk2vRY.png)
