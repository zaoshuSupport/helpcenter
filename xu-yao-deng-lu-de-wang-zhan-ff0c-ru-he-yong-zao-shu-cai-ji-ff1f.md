## **如何采集需要登录的页面的数据？**

需要登录的页面数据采集，一定要保证使用合法或被授权的的账户来登录。

![](/assets/cookie1.png)

造数目前支持GET和POST两种方法，登录网站进行数据采集。

（教程浏览器为Chrome，不同浏览器方法不同）



**1、如何使用GET方法**

点击“切换为高级姿势”，看到需要输入URL、Headers和Cookies。URL就是网址的链接，我们需要获得Headers和Cookies。



下面介绍如何使用造数爬取豆瓣首页内容。

在已经登录豆瓣的情况下，单击鼠标右键——检查（或者F12）——选择Network——刷新页面



![](/assets/豆瓣·12)

![](/assets/豆瓣212)





选中ALL下面的第一个链接www.douban.com，可以看到如下内容

![](/assets/imp123213213ort.png)

&lt;

**Request Method是GET，Requests Headers内容就是Headers，我们把Requests Headers所有内容复制到造数的输入框。**

![](/assets/imp432413123ort.png)



点击创建爬虫，可以看到现在已经是登录状态了，就可以开始选择数据了。

![](/assets/impor大幅度t.png)

需要注意的是，某些网站需要额外的输入Cookies，Cookies也在Requests Headers中，有需要直接复制即可。

![](/assets/im2port.png)

**2、如何使用POST方法**

![](/assets/impor常常t.png)



相比GET，POST方法多了一个Body参数，例如在中国证券监督管理委员会搜索“市场”来到www.csrc.gov.cn/wcm/websearch/zjh\_simp\_list.jsp

然后和

GET

方法一样，单击鼠标右键——检查（或者

F12

）——选择

Network

——刷新页面，选择

ALL

下面的第一个链接。

![](/assets/impoccvrt.png)

![](/assets/imposadfrt.png)



Body要填的内容就是Form Data，但是需要先点击view source，再复制内容，Body是

schword=%E5%B8%82%E5%9C%BA&searchword=pub%2Fnewsite%2F&channelid=3858&whereId=

回到输入框，依次输入URL、Headers、Body，即可创建爬虫。

![](/assets/imposadfart.png)



需要注意的是，某些网站需要额外的输入Cookies，Cookies在**Requests Headers中。**





以上是需要登录的网站如何采集数据的指导说明。

