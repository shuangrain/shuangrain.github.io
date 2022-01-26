---
title: "Hello World"
slug: "hello-world"
date: 2022-01-22T21:02:38+08:00
draft: false
---


先前在寫部落格時使用過許多不同的方案:
1. Wordpress + Self-Hosting
2. Wordpress + Cloud-Hosting
3. Hexo + Github Page
4. Hugo + Github Page

上述這幾種方案換來換去許多次，每種方案其實都有自己的優缺點。舉例來說 Wordpress 的功能最齊全豐富且自訂性也非常高，但它的缺點就是非常肥還必須有 PHP 與 MySQL 環境。若使用 Self-Hosting 則有不少維運成本，而若選用 Cloud-Hosting 會讓錢錢不能換成其它喜歡的東西。

![image](https://user-images.githubusercontent.com/7093550/151207577-1e1e31d6-2d55-4d77-b52b-96f87be37523.png)

而 Hexo 或 Hugo 這種產生靜態網站的方案則會遇到每次異動都需「編譯」再將檔案「部屬」至伺服器，其優點是靜態檔案所以瀏覽的流暢度快到無話可說，不像動態編譯語言可能會受到伺服器當前的負載而影響速度。

因為工作繁忙~~偷懶~~原先的部落格也閒置了許久都沒有更新，之前我是購買 Sugarhosts 的 Web Hosting 服務，但想著自己的使用需求降低後似乎可以把續約的費用省下來做其他事情 ~~買更多酷東西~~。且最近又開始手癢想找事情來過過手癮，正好藉著這個機會來玩最近很紅的 Github Actions，這次的方案就決定用: Hugo + Github Page + Github Actions。會選擇 Hugo 單純是因為工作上有用到 Golang 所以想說如果到時候真的功能不足需要客製化可以下海改 XD
