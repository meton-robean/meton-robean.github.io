## git下载国外项目加速的方法    

git clone 国外一些项目时候有时候速度非常慢.有一些提速方法.    

1.将github项目通过码云复制一份镜像,在码云主页选择新建仓库时候可以从github项目导入, 之后通过码云来git clone项目就快很多.     
可以参考：https://blog.csdn.net/kcx64/article/details/83866633    


2.在有科学上网服务的条件下，可以给git设置代理:      
    
git config --global http.proxy 'socks5://127.0.0.1:1080'  
git config --global https.proxy 'socks5://127.0.0.1:1080'
    
    