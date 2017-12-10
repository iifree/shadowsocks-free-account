### ShadowSockets 爬虫

爬取 <https://free-ss.site/> 网站上更新的免费 SS 账号，将其中评分为 100 分的抓取出来写进 ss 配置文件中，然后通过 ss 客户端导入配置文件  

> 在线下载地址：<http://47.93.48.236:3001>

### 使用

需要 nodejs 环境，node 版本大于等于 v7.0.0, 步骤如下

* clone 项目

``` git
git clone https://github.com/phobal/ShadowSocksSpider.git
```

* 下载依赖

``` bash
npm i
```

* 运行

``` bash
node app.js
```

* 安装 SS 客户端

[shadowsocks下载地址](https://github.com/shadowsocks/ShadowsocksX-NG)

* 导入配置文件

![](./1.jpg)

选择通过上一步执行成功生成的 ss.json 文件并导入  
done!
接下来就可以愉快的玩耍了

> 部分账号大概每隔6小时变1次，重新输入最新的账号即可。另外部分账号的IP已经被墙，发现不能使用请换其他账号
