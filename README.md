# meta 对应的值
### http-equiv
> x-dns-prefetch-control dns预解析 \<meta http-equiv="x-dns-prefetch-control" content="on" \/\>

> viewport 设置页面视口宽度 \<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no"\/\>

> apple-mobile-web-app-status-bar-style 控制苹果状态栏 \<meta name="apple-mobile-web-app-status-bar-style" content="black"\/\>

> 不把数字转化为拨号链接; 不识别邮箱; 不识别日期; 不跳转地图
  \<meta name="format-detection" content="telephone=no, email=no, adress=no, date=no"\/\>
  
> 页面关键词，用于搜索引擎收录\<meta name="keywords" content="页面的关键词"\/\>

> 页面描述 \<meta name="description" content="页面的描述"\/\>

### link \-\> 资源加载
> subresource在Chrome下，我们可以用 link标签声明特定文件的预加载 \<link rel="subresource" href="./a.js" \/\>

> 在 Firefox 中或用 meta 标签声明 \<meta http-equiv="Link" content="<critical.js>; rel=prefetch"\/\>

> 添加到桌面的图标
* \<link rel="apple-touch-icon-precomposed" sizes="57x57" href="xxx57.png" \/\>
* \<link rel="apple-touch-icon-precomposed" sizes="72x72" href="xxx72.png" \/\>
* \<link rel="apple-touch-icon-precomposed" sizes="114x114" href="xxx114.png" \/\>
* \<link rel="apple-touch-icon-precomposed" sizes="144x144" href="xxx144.png" \/\>

> 告知搜索引擎还有其它语言的网站版本
* \<link rel="alternate" hreflang="zh-CN" href="http://cn.xxx.com"\/\>
* \<link rel="alternate" hreflang="zh" href="http://cn.xxx.com"\/\>
* \<link rel="alternate" hreflang="en" href="http://en.xxx.com"\/\>
* \<link rel="alternate" hreflang="zh-TW" href="http://cn.tw.xxx.com"\/\>

> 告知搜索主站
* \<link rel="canonical" href="http://m.iqiyi.com"\/\>
