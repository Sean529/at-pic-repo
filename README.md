## 场景描述

很多时候自己的博客或者是网站项目都会涉及到一些静态文件的访问，如图片、js 文件，css 文件。如果全放在自己的服务器上，将会产生不必要的费用，并且访问的速度也不能得到保证。这个时候就需要一个方式能够提供免费高效稳定的方式来存放及访问我们的静态文件。

## 在 github 上创建一个图床仓库

![image.png](https://cdn.jsdelivr.net/gh/barryzpc/pic-repo/my-blog/img/image-c1eaf3b5.png)

- PS：一定要选 Public 不然无法访问到资源

## 将项目克隆到本地

```shell
 git clone git@github.com:barryzpc/pic-repo.git
```

## 创建自己的项目

#### 在 pic-repo 项目中创建自己的项目，比如我有个博客的项目那么我就建立一个 my-blog 的文件夹，并在在文件夹下面分别创建 img,js 等目录：

![image.png](https://cdn.jsdelivr.net/gh/barryzpc/pic-repo/my-blog/img/image-589b7be6.png)

## 添加静态文件到对应的目录中

#### 比如，我添加一张图片到我的 img 目录下

![image.png](https://cdn.jsdelivr.net/gh/barryzpc/pic-repo/my-blog/img/image-7f90875c.png)

## 提交到 github

```
git add .
git commit -m "add pic"
git push
```

这时图片的已经提交到 github 上

- PS: 如果包含有大量的图片，可以选择用 **[PicGo](https://github.com/Molunerfinn/PicGo)** 这个工具来上传

## 如何访问到静态文件

#### 访问的连接如何获取呢？这里就不得不提到一个厉害的 CDN 加速服务 [jsDelivr](https://www.jsdelivr.com/ "jsDelivr")

- `jsDelivr` 为开发者提供免费公共 CDN 加速服务
- 在中国大陆唯一有 license 的公有 CDN，而且使用中的访问速度也很快
- 并且`JSDelivr` 能够集成 Github、NPM、WordPress 资源，只需要通过符合 JSDelivr 规则的 URL 引用，即可直接使用他们中资源。

#### 获取直链

###### 找到刚才上传图片的链接

在线将 github 图片转换成 jsdeliver 图片地址
https://www.jsdelivr.com/github

## 博客地址

#### **[http://myblog.zhengpc.com/articles/2020/03/11/1583919217986.html](http://myblog.zhengpc.com/articles/2020/03/11/1583919217986.html)**
