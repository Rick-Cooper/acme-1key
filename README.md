# Acme.sh 域名证书一键申请脚本

此脚本可以帮助你使用acme.sh脚本申请域名的ssl证书，并且可以保存到你想要的位置

## 提示

~~本脚本请在关闭warp之后使用，否则无法申请证书。~~ （更新脚本，检测WARP状态，如为打开则自动关闭） 在纯v6环境下会自动设置dns64服务器以确保正常执行acme.sh脚本

对于双栈VPS，默认检测IPV4地址优先

对于国内VPS，可能遇到脚本不可用的问题

## 使用方法

```shell
wget -N https://cdn.jsdelivr.net/gh/Misaka-blog/acme-1key@master/acme1key.sh && chmod -R 777 acme1key.sh && bash acme1key.sh
```

快捷方式 `bash acme1key.sh`

说明文档：https://owo.misaka.rest/acme-1key/

## 赞助我们

![afdian-MisakaNo.jpg](https://s2.loli.net/2021/12/25/SimocqwhVg89NQJ.jpg)

## 交流群
[Telegram](https://t.me/misakanetcn)

## 感谢列表

感谢他们的贡献，让脚本得到进一步完善

Acme.sh https://github.com/acmesh-official/acme.sh
