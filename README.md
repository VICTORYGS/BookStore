# BookStore
用爬虫实现的一个微信图书商城 
本来这个项目用的是豆瓣的接口实现的,但是接口后来被豆瓣给禁了...  
所以匆忙改用了爬虫(所以数据可能会响应较慢),获取的是亚马逊上的数据(有个别一些图书的数据可能会爬取失败,大多数图书都是ok的).  
小程序是使用uni-app编译编译出来的(和支付相关的功能暂时还没写),用户认证使用的是jwt的方式.  
后端用的golang,web框架用的Gin,爬虫方面的工具用了goquery、chromedp,  
数据库用的mysql 用到的几张表的sql代码 我存在了sql文件夹中,  
默认跑在3000端口 要改具体的配置 可以到conf下的配置文件中进行修改  



![image](https://github.com/VICTORYGS/BookStore/blob/master/1.png?raw=true)
![image](https://github.com/VICTORYGS/BookStore/blob/master/11.png?raw=true)
![image](https://github.com/VICTORYGS/BookStore/blob/master/12.png?raw=true)
![image](https://github.com/VICTORYGS/BookStore/blob/master/2.png?raw=true)
![image](https://github.com/VICTORYGS/BookStore/blob/master/3.png?raw=true)
![image](https://github.com/VICTORYGS/BookStore/blob/master/4.png?raw=true)
