Cookie 是由服务器端生成，发送给 User-Agent（一般是浏览器），浏览器会将 Cookie 的 key/value 保存到某个目录下的文本文件内，下次请求同一网站时就发送该 Cookie 给服务器（前提是浏览器设置为启用 cookie）。Cookie 名称和值可以由服务器端开发自己定义，对于 JSP 而言也可以直接写入 jsessionid，这样服务器可以知道该用户是否合法用户以及是否需要重新登录等。

造数的 cookie 功能可以帮助您方便采集需要登录的网站数据，请一定保证使用自己的或者他人授权的账号采集数据。

需要登录的网站的具体采集方式，详见 FAQ 中的[《需要登陆的网站，如何用造数采集》](https://zaoshu.gitbooks.io/helpcenter/content/xu-yao-deng-lu-de-wang-zhan-ff0c-ru-he-yong-zao-shu-cai-ji-ff1f.html)。

