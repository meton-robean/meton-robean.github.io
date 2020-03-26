## v2ray使用配置教程      

v2ray据说比shadowsock要稳定. windows有直接的软件安装.下面是linux环境配置方法,采用脚本安装(虽然github上有一些v2ray UI for linux, 但是我试过还有bugs)：     

系统环境最好是centos7、 ubuntu16以上.    

1.使用以下v2ray官方给的命令安装v2ray，出现下图界面就是安装中了，稍等片刻，即可安装完成(centos可能需要sudo权限):    
```
bash <(curl -L -s https://install.direct/go.sh)
```  
2.关闭防火墙,下面三组命令一组成功即可：     
```
systemctl stop firewalld
systemctl disable firewalld
 
servcie iptables stop
chkconfig iptables off
 
ufw disable
``` 

3.v2ray配置：     
打开v2ray配置文件路径：/etc/v2ray/config.json，清空原有内容.    
将你购买的vpn服务中v2ray的相关配置，一般是json格式的配置文件内容复制带config.json.中，保存关闭

4.v2ray启动与管理(可能需要sudo)：     
```
service v2ray start
service v2ray status
service v2ray stop 
```  

5.配合bbr加速工具更好, bbr安装参考：https://blog.sprov.xyz/2019/02/04/bbr-tcp-faster/     

6.谷歌浏览器访问外网还需要设置代理端口后启动:     
chrome 启动， 默认采用sock5， 默认127.0.0.1:1080, 实际请查看v2ray配置文件. v2ray配置文件路径：/etc/v2ray/config.json
#启动前确认关闭原来的chrome..."
```
google-chrome --proxy-server=socks5://127.0.0.1:1080
```