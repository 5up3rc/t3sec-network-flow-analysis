N-EM-00002
---
黑客从外网对公司的博客系统进行了渗透活动，拿下了外网博客服务器后以此为跳板又对内网中的其他主机进行了漏洞利用，好在公司开启了流量抓取的设备，黑客攻击的这段流量和公司内部上网的流量全被全部抓取了下来，尝试从中分析出黑客的具体活动
1. 攻击者爆破了网站的后台，请查出joomla的后台用户名和密码（格式 user/password）
```
admin/apple
```
2. 攻击者修改了哪一个模板的哪一个文件（格式 模板名/文件名 例如 template/config.php）
```
beez3/index.php
```
3. joomla主机网络适配器1的IP地址
```
192.168.28.130
```
4. 攻击者扫描的IP地址范围（格式用英文,连接 IP1,ip2 如两个IP为 10.1.1.1,10.1.1.20 ）
```
192.168.28.120,192.168.28.135
```
5. joomla网站的数据库用户名密码是多少（格式 用户名/密码 例如 user/passwd）
```
root/mysqlpasswd
```
6. 黑客执行命令添加用户的用户名密码是什么（格式 用户名/密码 例如 user/passwd）
```
hacker/hacker
```
7. 内网web服务器的IP地址是多少？
```
192.168.28.129
```
8. 攻击者登陆内网web应用后台所使用的用户名是什么？
```
simple
```
9. 攻击者利用了内网web服务器上的哪一个php页面的漏洞修改了文件？
```
tpl_manage.php
```
10. 内网web服务器上数据库的用户名密码是什么？(格式 用户/密码 例 user/password)
```
root/123456
```
11. 内网web服务器上第一次被添加的webshell密码是什么？
```
Bshell
```
12. 内网web服务器上被攻击者添加的用户名密码是什么？（格式 用户名/密码 例如 user/passwd）
```
bluehacker/redhacker1@3
```
13. 内网web服务器中第二次被添加的webshell的密码是多少？
```
cmd_shell
```
14. 内网web服务器中第二次被添加的webshell的绝对路径是什么？
```
C:\phpstudy\WWW\bluecms\data\foot.php
```
15. ftp服务的banner信息
```
Microsoft FTP Service
```
16. 处于内网的ftp服务器的账号密码分别是多少？（格式 用户名/密码  例如 user/passwd）
```
ftpadmin/ftppasswd
```