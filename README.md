# 自定义hosts以访问服务器

**若还没有配置hosts, 请先前往[hosts配置](#2-hosts-配置), 自定义hosts以访问下列服务器内容**

>  暂时没时间，简陋点，等有空了改个好看点的门户网站

# 1. 以下是引导内容

---

`https://sayurinana.github.io/hosts/`

# <a href="http://blog.wuuuu.115b.net:2233" target="_blank">柒柒的小破站</a>


# <a href="http://115b.net:8008/" target="_blank">媒体服务器</a>

> 有两个公共账户:
>
> 1. 
>
>    用户名：
>
>    resource
>
>    密码：
>
>    123
>
> 2. 
>
>    用户名：
>
>    a
>
>    密码：
>
>    a

![image-20230315142000757](./assets/image-20230315142000757.png)

# <a href="http://115b.net:9001" target="_blank">OSS 对象存储服务</a>

# <a href="http://115b.net:7777/" target="_blank">柒柒の窝</a>

![image-20230315142023956](./assets/image-20230315142023956.png)

# 2. hosts 配置 

## 2.1. Android 配置

配合 [virtual-hosts](https://github.com/x-falcon/Virtual-Hosts) 使用 ,

供 virtual-hosts 使用的远程hosts文件 :

[https://sayurinana.github.io/hosts/](https://sayurinana.github.io/hosts/)


## 2.2. Windows 配置

编辑添加[hosts内容](#3-hosts-内容)

`C:\Windows\System32\drivers\etc\hosts`

## 2.3. Linux/Unix/类Unix 配置

编辑添加[hosts内容](#3-hosts-内容)

`/etc/hosts`

## 2.4. MacOS/iOS 配置

> 别看,不知道

---

# 3. hosts 内容

更新时间: 

当前的hosts内容

```
172.20.32.11 115b.net
172.20.32.11 blog.wuuuu.115b.net
172.20.32.11 minio.server.115b.net
```

---
