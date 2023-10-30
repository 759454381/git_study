---
typora-root-url: ./
---

# Typora + Picgo  + Github + Git 管理搭建图床 解决 csdn 导入MakeDown中图片转存失败的问题——外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传（保姆教程）--【已修改】

![image-20231030084436473](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229965.png)



### 步骤分析：

>第一步：首先下载 PicGo 图床上床工具
>
>第二步：在 Github 中拿到私钥，添加到 PicGo中
>
>第三步：设置 Typora 中图像上传的服务为 PicGo



### 1. PicGo 下载安装和设置

>##### 1.打开 Typora 如下：


![image-20231029183642602](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229966.png)

> ##### 2.
---

![image-20231029184259343](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229968.png)



> ##### 3
---



![image-20231029184500913](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229969.png)



> ##### 4
---



![image-20231029184932632](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229970.png)




> ##### 5
---



![image-20231029185204864](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229971.png)




> ##### 6
---





![image-20231029185546796](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229972.png)



### 2. 在 Github 创建仓库 并且生成 令牌，用PicGo 绑定令牌

> ##### 1
---
![image-20231029185935623](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229973.png)


> ##### 2
---



![image-20231029190831942](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229974.png)


> ##### 3
---

![image-20231029191747934](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229975.png)


> ##### 4
---

![image-20231029200526845](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229976.png)

> ##### 5
---



![image-20231029200618341](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229977.png)



> ##### 6 当前token【令牌】只生成一次 所以生成后要保存  如果不记得 后续删除重新保存 修改 token
---

![image-20231029191747934](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229975.png)

### 3.设置 PicGO
> ##### 1  安装插件
> 
---
![image-20231029202411497](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229978.png)

> ##### 2  CDN(内容分发网络) 代理加速  客户端 ——>CDN反向代理 ——> Github 服务器
>
> 1.cdn 这里是选填 可以不填

```
https://cdn.jsdelivr.net/gh/github用户名/仓库名
```

![image-20231029215728015](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229979.png)



### 4.设置 Typora 

> ##### 1  设置 Typora 上传服务 PicGO 的安装路径
---



![image-20231029224429372](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229980.png)



### 5. 以上完成以后



![image-20231029225547931](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229981.png)



![image-20231029232300289](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229982.png)





![image-20231029232441647](https://cdn.jsdelivr.net/gh/759454381/image/csdn/202310301229983.png)



# 2.最后注意！：写完文档一定要备份一个，在再做其他操作。
