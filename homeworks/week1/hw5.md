## 請解釋後端與前端的差異。


<<<<<<< HEAD
基本上網頁上看得到的部分就是前端，而看不到的地方發生的事就是後端。

基本上當你的瀏覽器 (Client) 造訪一個網頁時，你首先要輸入網址接著你的瀏覽器會先發需求給域名系統 (DNS)，請他幫忙根據域名 (Domain) 解碼一下真正的 IP 地址，域名系統於是告訴你網址精確的 IP 地址為何。你的瀏覽器才能進一步透過這個 IP 位置找到對應的伺服器 (Server，我理解就是遠方的電腦)，然後發 request 給這個 Server，接著 Server 會根據你的需求從資料庫 (database) 中取出一些資料並且回應 (response) 給你的瀏覽器 (Client)。

>如果用餐廳來比喻的話

基本上當你（瀏覽器）進入到一網頁時就像是來到一間餐廳，你會點各種菜或者跟店員做各種互動，這時候招待你的是前台，像是這間店的裝潢，以及店內菜單的設計等，這些工作對比到網頁上就是「前端」工程師負責的事。

而當你進到店裡你點了一道菜，這時候就前台就要發出一個需求（request）給餐廳的內場，而餐廳的後台人員就要根據這需求去調閱餐廳的食材庫（database）並且取出適當的食材加工後送回（response）給餐廳的前場，而餐廳後場從食材庫取出食材並且加工的一系列工作，這些工作對比到網頁上就是「後端」工程師要負責的事。




## 假設我今天去 Google 首頁搜尋框打上：JavaScri[t 並且按下 Enter，請說出從這一刻開始到我看到搜尋結果為止發生在背後的事情。
=======
## 假設我今天去 Google 首頁搜尋框打上：JavaScript 並且按下 Enter，請說出從這一刻開始到我看到搜尋結果為止發生在背後的事情。
>>>>>>> 57ada911fa480bef8821cd1620d8e68855647d53

我的瀏覽器 (Client) ，先詢問 DNS 得到 Google 的 IP 8.8.8.8，接著發 request 到 8.8.8.8到 Google 的 Server ，Server 於是查詢了它的 Database 後回應 (response) 給我的瀏覽器一系列的查詢結果。

前兩題好讀版：https://tripxbook.com/100days-learn-to-do/frontend-developer-day7/


## 請列舉出 3 個「課程沒有提到」的 command line 指令並且說明功用


sudo  -s        mac終端切換使用者到root
history         列出所有曾經打過的指令
find            找尋檔案
(ex:  ~/Desktop -name "*.jpg" )