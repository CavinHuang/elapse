# Elapse
> 流水衷曲，韶华飞逝

前后端分离 + 服务端渲染的博客系统。其中：

  - 接口服务使用Koa2 + mongodb + mongoose
  - 后端管理使用Vue开发
  - 前端页面使用React服务端渲染框架`nextjs`


此外，为了更好的体验效果，可以点击访问<a href="http://193.112.102.204" target="_blank">后端管理系统</a>，在注册用户后，即可登录体验，同时也可以发布文章，然后在<a href="http://193.112.102.204:4000/p" target="_blank">前端页面</a>就可以看到发布的文章。(目前（2018-02-28）未备案，就简单通过ip访问即可)

## 1. 效果预览
### 1.1 后端管理页面
后端管理页面使用了vue、vuex、sass以及axios，其中模仿ElementUI的样式开发了`dialog`、`loading`、`confirm`、`notofication`、`messgae`等等组件，（感觉自己对vue组件的开发姿势又稍微深入了一点点，毕竟学无止境）。以下为部分页面截图：

<ul>
  <li>
    <p>登录预览</p>
    <img src="http://ownsprds9.bkt.clouddn.com/be-login.JPG" />
  </li>
  <li>
    <p>个人中心</p>
    <img src="http://ownsprds9.bkt.clouddn.com/be-ownspace.JPG" />
  </li>
  <li>
    <p>文章管理</p>
    <img src="http://ownsprds9.bkt.clouddn.com/be-articlelist.JPG" />
  </li>
  <li>
    <p>ECharts结合</p>
    <img src="http://ownsprds9.bkt.clouddn.com/be-echarts.JPG" />
  </li>
</ul>

  
### 1.2 前端页面渲染
借此机会想学习一下`React`，于是前端页面使用了React服务端渲染框架`nextjs`，并使用了`Redux`、`axios`以及`koa`(自定义服务所用)。前端页面目前比较简单，主要就是文章的读取和渲染。以下为截图：

 
<ul>
  <li>
    <p>前端首页</p>
    <img src="http://ownsprds9.bkt.clouddn.com/fe-home.JPG" />
  </li>
  <li>
    <p>文章详情</p>
    <img src="http://ownsprds9.bkt.clouddn.com/fe-article.JPG" />
  </li>
</ul>

## 2. 笔记总结
### 2.1 Vue.js 篇

  - [Vue组件开发总结](https://github.com/mvpzx/elapse/blob/master/be/src/docs/Vue%E7%BB%84%E4%BB%B6%E5%BC%80%E5%8F%91%E5%A7%BF%E5%8A%BF%E6%80%BB%E7%BB%93.md)
  
  - [上传组件开发以及上传到七牛云](https://github.com/mvpzx/elapse/blob/master/be/src/docs/%E4%B8%8A%E4%BC%A0%E7%BB%84%E4%BB%B6.md)

## 3. 模块文档
- [后端管理系统开发](https://github.com/mvpzx/elapse/tree/master/be)
- [服务端API接口开发](https://github.com/mvpzx/elapse/tree/master/server)
- [页面部署与接口服务](https://github.com/mvpzx/elapse/tree/master/server/docs/页面部署与接口服务.md)

文档尚未仔细整理，还在不断整理添加中......
