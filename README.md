This is for SA docker Reading group

預計以線上的方式
* 雙週一次, 平日晚上, 目前可能是 21:00 ~ 22:00 或是 20:00 ~ 21:00 , 看大家時間的集成.
* chat on slack
* 檔案放 GitHub

書 Mastering Docker - 2nd edition ( 2018年讀書會 )

https://www.tenlong.com.tw/products/9781787280243


書 Oreilly - docker cookbook ( 2017年讀書會 )

http://techbus.safaribooksonline.com/book/software-engineering-and-development/9781491919705


心智圖軟體 freemind 下載
http://freemind.sourceforge.net/wiki/index.php/Download


應用想法


-------------------------------------------------

目錄結構

* books/ - 跟書有關的檔案
* books/docbook-master - 書中的範例
* books/讀書心得 - 可以將各章節讀書心得共同編輯
* mindmap/ - 心智圖存放
* other_materials/ - 存放一些相關文件/ Tips
* Dockerfile/ - Dockerfile 分享


-------------------------------------------------

##2018年讀書會

* Member: Netman, Daniel, 翔二, 阿哲, Matt, sakana

-------------------------------------------------

2018/3/21

* 進度: Chapter 3 p67

* Layer and Docker ID 討論, 

* 下次讀書會 2018/4/11

-------------------------------------------------

2018/3/7

* 進度: Chapter 3 ~ Chapter 3 p67

* Todo: 大家都要嘗試 autobuild with Github

* 下次讀書會 2018/3/21

-------------------------------------------------

2018/2/21

* 進度 Chapter 2 p41 ~ Chapter 2 結束

* 討論小記: Dockerfile 裡面的 ARG 可以在 docker build 的時候 使用 docker build --build-arg 的方式導入變數, 相對 ENV 有彈性多, 但是同時存在 ARG 與 ENV 時候, 看起來會以 ENV 為主

* 下次讀書會 2018/3/7

-------------------------------------------------

2018/2/7

* 進度 Chapter 2 ~ Chapter 2 p.40
	* 確認大家都要 docker build 第2章的 docker file example image
* 翔二的資料: https://github.com/sakanamax/SA_dockerReading/tree/master/other_materials/dearjack
* sakana 補充: https://github.com/sakanamax/SA_dockerReading/tree/master/other_materials/Max_Huang/Mastering_Docker_2nd_edition
* 下次讀書會 2018/2/21


-------------------------------------------------

2018/1/24

* 進度: Chapter 1 ~ Chapter 1 結束
	* 確認大家安裝 docker 與 docker-compose
* 讀書心得討論 https://github.com/sakanamax/SA_dockerReading/blob/master/books/%E8%AE%80%E6%9B%B8%E5%BF%83%E5%BE%97/2018-Mastering-Docker/ch1.txt
* 下次讀書會 2018/2/7

-------------------------------------------------


Fist online Meet up 2018/1/10

* 使用 Google hangout
* 分享視窗的方式討論(webpage, 書) + 語音 + google doc
* 下次讀書會 2018/1/24


-------------------------------------------------

##2017年讀書會

Fist online Meet up 2016/4/11

* 使用 Google hangout
* 分享視窗的方式討論(webpage, 終端機) + 語音 + google doc
* 主要放在 Chapter 1 - Chapter 5, Chatper 6 之後可以討論各自的案例分享
* Cluster 的部份採用 Docker swarm
* 考慮網路的關係, docker 版本可能用 1.10.x
* 第一次讀書會是 2016/4/25 21:30, 時間為一個小時
* 建立 Dockerfile 資料夾分享彼此的 Dockerfile
 * 使用功能分類（by folder）

-------------------------------------------------

第一次讀書會 2016/4/25 21:30

範圍: Chapter 1

目的: 有自己的docker 環境

-------------------------------------------------

2016/4/25

進度: Chapter 1 - Chapter 1.13

* 確認大家有 docker 環境, docker  network ls 可以看得到


讀書心得討論 https://github.com/sakanamax/SA_dockerReading/blob/master/books/%E8%AE%80%E6%9B%B8%E5%BF%83%E5%BE%97/ch1.txt

下次讀書會 2016/5/9 21:30

從 1.14 開始

-------------------------------------------------

2016/5/9

進度: Chapter 1.14 - Chapter 1.19

* 主要練習 volume 使用以及掛載


讀書心得討論 https://github.com/sakanamax/SA_dockerReading/blob/master/books/%E8%AE%80%E6%9B%B8%E5%BF%83%E5%BE%97/ch1.txt

下次讀書會 2016/5/23 21:30

從 1.20 開始


-------------------------------------------------

20160523

進度: Chapter 1.20 - 2.5

下次讀書會 6/13

-------------------------------------------------

20160613

進度: 近況分享 

下次讀書會 6/27

-------------------------------------------------


20160627

進度: 近況分享 

下次讀書會 7/4

-------------------------------------------------

20160704

進度: 2.6 - 2.9 

下次讀書會 7/18

-------------------------------------------------

20160718

進度: 近況分享 

下次讀書會 8/15

-------------------------------------------------


20160816

進度: docker swarm mode 討論 

下次讀書會 8/29

-------------------------------------------------


