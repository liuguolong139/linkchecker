无效链接是指存在于页面中，但其指向的资源已经不存在。本漏洞属于Web应用安全常见漏洞。通过url访问  + cheerio 抓取网页数据，抓取当前项目中所有的 <a>标签、 <link>标签、 <script> 标签的href 或者src 属性，获取的链接，跟当前url拼接后输出完整路径，最后访问访问是否有效。
