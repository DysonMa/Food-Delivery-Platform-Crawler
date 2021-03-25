# Food Delivery Platform Crawler

* [Youtube-Demo版](https://youtu.be/JUrBNYIyFic)
* [English README.md(英文版 README.md)](https://github.com/DysonMa/Food-Delivery-Platform-Crawler/blob/master/README.md)
* 這是一個利用 pyquery, requests, selenium 來建立的網頁爬蟲，用來爬取 Foodpandas和UberEats兩個外送平台

## 關於

Foodpanda 和 UberEats 是台灣最常使用的兩大外送平台。

![Foodpanda](/images/foodpandas.png)

![UberEats](/images/ubereats.png)

### 建立環境與套件
* python
* pyquery
* requests
* selenium

## 如何開始
### 安裝
遠端下載 repo
```
git clone https://github.com/DysonMa/Food-Delivery-Platform-Crawler.git
```
## 使用
1. 輸入欲搜尋的地址，selenium套件會模擬網站開啟
```
輸入外送地址(OO市OO區OO路OO號): 
```
2. 執行爬蟲並處理資料
3. 輸入您想吃的食物種類
```
============================ 以下是目前有開放訂購的餐廳 =====================

輸入想吃的食物種類(EX:美式、日式、義式...):
```

![category](/images/category.png)

4. 輸入您想下訂單的餐廳名稱
```
輸入想外送的餐廳名稱:
```
5. 列出有開放訂購的餐廳(依照星星數量排序)
![opened](/images/opened.png)
6. 列出有開放訂購的餐廳(依照運費排序)
![cost](/images/cost.png)
7. 選定某家餐廳，並列出他的訂購資訊
```
輸入確定訂購的餐廳名稱: 
```
![order](/images/order.png)
8. 存成csv檔

## 憑證
Distributed under the MIT License.

## 聯絡方式
Dyson Ma - madihsiang@gmail.com
Project Link: https://github.com/DysonMa/Food-Delivery-Platform-Crawler
