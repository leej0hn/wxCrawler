# wxCrawler
微信文章爬虫思路
微信公众号文章采集思路  
一、通过android客户端获取到微信用户登录信息（即小号）。  
二、提供微信公众号信息(biz)  
三、通过http协议分析文章接口，写微信爬虫程序，需要用到上面两种资源，即小号越多，爬取速度越快。
    微信爬虫引擎为分布式，可多实例部署工作。  
	
最后实现的效果为：
android客户端程序定时获取微信用户登录信息，保存到数据库中。数据库中保存大量的公众号信息，  
爬虫引擎工作时，去数据库获取要爬取公众号的信息与微信小号的身份信息。  
![image](https://note.youdao.com/yws/public/resource/fd1336f198c1b2181971eb5555fe14f9/xmlnote/2C5A8A71ACBC46FAB46C86A23B2BFDD6/22272)  
PS:有兴趣可加群讨论：878224604  
