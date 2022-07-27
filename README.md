# 爬虫工程师常用的 Chrome 插件

>做多了爬虫都知道，写一个爬虫大部分时间不是在代码上，而是在分析网页上，所有有一套好用的工具可以极大节省劳动力，这里把平时积累的一些 Chrome 插件分享出来，均来自本人和同事推荐，并不定时更新，欢迎点赞和收藏。

>下面大标题指向的是谷歌应用商店，访问需要特殊方法，也可以进入本仓库的 `extensions` 目录中下载。

## [XPath Helper](https://chrome.google.com/webstore/detail/xpath-helper/hgimnogjllphhhkhlmebbmlgjoejdpjl)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190729094906.png-slim" width="80%"> </p>

相比较 Chrome 自身的 html 搜索，这款插件好用之处是可以显示匹配结果，在插件里写出正确的 XPath 语句后再复制到代码里即可。

## [Toggle JavaScript](https://chrome.google.com/webstore/detail/toggle-javascript/cidlcjdalomndpeagkjpnefhljffbnlo)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190729094907.png-slim" width="80%"> </p>

一键拦截网页所有的 JS，可以快速区分出哪些是异步加载的数据，绝对是爬虫必备神器。

## [FeHelper](https://chrome.google.com/webstore/detail/web%E5%89%8D%E7%AB%AF%E5%8A%A9%E6%89%8Bfehelper/pkgccpejnmalmdinmhkkfafefagiiiad)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190729094903.png-slim" width="80%"> </p>

这款插件的强大之处不想多说，看上面的截图就行了，其中一些数据转换的功能，在分析请求时会经常用到。

## [JSON-Handle](https://chrome.google.com/webstore/detail/json-handle/iahnhfdhidomcpggpaimmmahffihkfnj)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190729095522.png-slim" width="80%"> </p>

虽然上面推荐的已经带有 JSON 功能，但这款插件带有局部选取、对象类型、数组长度等小功能，适合有额外需求的时候。并且相较于其他 JSON 插件，这款的性能更强，在处理巨量字符串时不容易卡死。

## [User-Agent Switcher](https://chrome.google.com/webstore/detail/user-agent-switcher-for-c/djflhoibgkdhkhhcedjiklpkjnoahfmg)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190729094904.png-slim" width="80%"> </p>

快速修改 `UserAgent` 的插件，当需要请求移动端页面时，或者需要传特殊的 UA 时，不要忘记它。

## [X-Forwarded-For Header](https://chrome.google.com/webstore/detail/x-forwarded-for-header/hkghghbnihliadkabmlcmcgmffllglin)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190729094902.png-slim" width="80%"> </p>

有时候网站过滤 IP 是通过请求 Headers 中的 `X-Forwarded-For` 字段，通过这个插件就可以修改此字段，用来快速进行判断。

## [SwitchyOmega](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190729094908.png-slim" width="80%"> </p>

快速切换 HTTP / Socks 代理的插件，还能根据匹配地址自动切换。另一个技巧是配合 Charles、Burp Suite 这类抓包工具，这些工具使用时需要设置本地代理，可以提前设置好用时就切换。

## [Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190811175102.png-slim" width="80%"> </p>

可以解析当前前端页面所使用的框架及服务支持，这样可以针对 Web 框架使用特殊的爬取方式。

## [Web Scraper](https://chrome.google.com/webstore/detail/web-scraper/jnhgnonknehpejjnehehllkliplmbmhn)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190811175103.png-slim" width="80%"> </p>

又一个神器，如果只是简单的爬取数据，不需要部署和更复杂的操作，可以使用这款插件，内置在 Chrome 控制台，直接操作 Chrome 浏览器进行爬取，不需要写一行代码，支持多种导出格式。

## [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg)

<p align="center"> <img src="http://static.zkqiang.cn/images/20190831161529.png-slim" width="80%"> </p>

爬虫遇到权限页面时，难免要对 Cookie 反复调试，这款插件可以对当前站点进行 Cookie 编辑，支持增删改查、导入导出、一键清空、搜索等功能。

* * *

## 免责声明

Chrome 插件虽然绝大部分经过谷歌严格审查，但存在曝光过有恶意代码的情况。

本人承诺以上所有 Chrome 插件的链接以及仓库中的 crx 均来自[谷歌官方商店](https://chrome.google.com/webstore/category/extensions)，如插件内存在恶意代码均与本人无关，相关损失请自行承担。

如不放心可以亲自审计插件代码，在 `Chrome/Default/Extension` 目录下可以找到 JS 代码及相关文件。

* * *
