# Food Delivery Platform Crawler

* [繁體中文 README.md(Traditional Chinese README.md)](https://github.com/DysonMa/Food-Delivery-Platform-Crawler/blob/master/README-zh-TW.md)
* Using pyquery, requests, selenium to build a crawler to crawl Foodpandas and UberEats.

## About

Foodpanda and UberEats are the most frequently used food delivery platform in Taiwan.

![Foodpanda](/images/foodpandas.png)

![UberEats](/images/ubereats.png)

### Built With
* python
* pyquery
* requests
* selenium

## Getting Started
### Installation
Clone the repo
```
git clone https://github.com/DysonMa/Food-Delivery-Platform-Crawler.git
```
## Usage
1. Input the address for crawling, and selenium will open the website.
```
輸入外送地址(OO市OO區OO路OO號): 
```
2. Execute crawling and process datas.
3. Input the category you want to eat.
```
============================ 以下是目前有開放訂購的餐廳 =====================

輸入想吃的食物種類(EX:美式、日式、義式...):
```

![category](/images/category.png)

4. Input the restaurant you want to place an order.
```
輸入想外送的餐廳名稱:
```
5. List the restaurants open to order(rate by their star counts).
![opened](/images/opened.png)
6. List the restaurants open to order(rate by their shipping cost).
![cost](/images/cost.png)
7. Choose the designated restaurant and list the detail information.
```
輸入確定訂購的餐廳名稱: 
```
![order](/images/order.png)
8. Save as csv file.

## License
Distributed under the MIT License.

## Contact
Dyson Ma - madihsiang@gmail.com
Project Link: https://github.com/DysonMa/Food-Delivery-Platform-Crawler
