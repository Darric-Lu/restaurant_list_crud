# restaurant_list_crud

使用 Node.js + Express 打造的餐廳美食網站

---

## Features ⚡️ 產品功能

- 使用者可以在首頁看到所有餐廳與它們的簡單資料

  - 餐廳照片
  - 餐廳名稱
  - 餐廳分類
  - 餐廳評分

- 使用者可以再點進去看餐廳的詳細資訊

  - 類別
  - 地址
  - 電話
  - 描述
  - 圖片

- 新增、修改與刪除餐廳
  - 使用者可以新增一家餐廳
  - 使用者可以瀏覽一家餐廳的詳細資訊
  - 使用者可以瀏覽全部所有餐廳
  - 使用者可以修改一家餐廳的資訊
  - 使用者可以刪除一家餐廳

---

## Getting Started 🚀 環境需求

```
node v12.18.0 or higher
npm v6.14.7 or higher
mongoDB v4.2.9 or higher
```

---

## How To Use 🔧 如何使用

Open MongoDB in (another) terminal

```
$ cd ~/[YOUR PATH]/mongodb/bin/
$ ./mongod --dbpath ~/[YOUR PATH]/mongodb-data

```

Clone this repository

```
$ git clone https://github.com/tingchun0113/restaurant_list_crud.git
```

Go into the repository

```
$ cd "restaurant_list_crud"
```

Install the dependencies using NPM

```
$ npm install
```

Run seeds

```
$ npm run seed
```

After seeing `mongodb connected!` and `done`, press `ctrl + c` to exit

```
mongodb connected!
done
```

Run the app

```
$ npm run dev
```
