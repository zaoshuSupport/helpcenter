Webhook（也称为Web回调或HTTP推送API）是应用程序向其他应用程序提供实时信息的一种方式。一个webhook会将数据发送到其他应用程序，这意味着您立即获取数据。与典型的API不同，您需要经常轮询数据以便实时获取数据。这使得webhooks对于提供商和消费者来说都更有效率。

设置webhook

个人设置页面打开，开发者功能后，返回到我的爬虫，点击左上角爬虫实例后，在页面的最下方可以设置webhook

造数webhook返回的数据结构：

下面是造数发送的webhook例子:

```
POST /payload HTTP/1.1
Host: localhost:12138
User-Agent: zaoshu-Hookshot
Content-Type: application/json
Content-Length: 6877
X-zaoshu-Event: default

{
  "taskId": "de9d0c7496c247e2ba27f34cafeb052c",
  "title": "抓数据去造数！！！",
  "UUID" : "aaaaf632-0d4b-42bc-b71f-669ee0d6f9aa",
  "createdAt" : 690177600,
}
```



