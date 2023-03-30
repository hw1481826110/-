安装
安装好docker服务，命令行直接执行：

docker run -d -v /tmp/ql:/ql/data -p 5700:5700 --name qinglong --hostname qinglong --restart unless-stopped whyour/qinglong:2.13.3
其中/tmp/ql为本地存储青龙数据的路径，可以自行更改

等待命令执行完毕，访问 localhost:5700 根据提示完成面板的初始化

常用依赖
依赖管理-新建依赖-自动拆分选是-粘贴对应的依赖-确定

NodeJs下

crypto-js
prettytable
dotenv
jsdom
date-fns
tough-cookie
tslib
ws@7.4.3
ts-md5
jsdom -g
jieba
fs
form-data
json5
global-agent
png-js
@types/node
require
typescript
js-base64
axios
moment
Python3下

requests
canvas
ping3
jieba
PyExecJS
aiohttp
Linux下

bizCode
bizMsg
lxm
订阅地址
订阅管理-新建订阅-粘贴链接和名字-确定

以下是我从网上搜索到的一些库，不做推荐仅自用，本人对任何脚本问题概不负责。
https://github.com/6dylan6/jdpro
https://github.com/Oreomeow/checkinpanel.git

变量提取
https://bean.m.jd.com/bean/signIndex.action pt开头
