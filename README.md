# hosts
在国内网络环境下，很多没有被屏蔽的国外网站想访问也十分艰难，其中有一部分的艰难就来自于国内DNS服务器由于各种问题而缺失或错误的DNS记录。

而通过修改本地DNS映射表文件——hosts，将这些网站的正确IP地址定死，即可绕过DNS查询过程直接访问正确IP，这样做可以有效提升访问速率和防止DNS故障。

LJM12914的hosts文件目前包括了一些LJM12914常去的网站。如有任何建议欢迎提issue，PR就算了。

国内备份：[Gitee](https://gitee.com/ljm12914/hosts/raw/master/hosts)　短链：Gitee`ljm.im/hosts`　Github`ljm.im/host`

## Windows
`C:\Windows\System32\drivers\etc\hosts`

## 移动端
1. root设备：直接修改`/system/etc/hosts`
2. 无root设备：https://github.com/x-falcon/Virtual-Hosts/releases 或其他代理软件。

## 注意
DNS问题只是访问国外网站诸多问题中的一个，修改hosts文件并不能保证该网站一定可访问或访问速度加快。

## 授权许可
MIT
