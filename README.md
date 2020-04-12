### 环境准备

- vue-cli
- nodejs
- mongodb

### 后台管理系统

- 新增分类
- 分类列表(增删改查)

- 新增文章
- 文章列表(增删改查)

- 文章评论列表

- 新增友链
- 友链列表(增删改查)

- 留言列表

- 留言用户列表

- Markdown 编辑器集成
- 图片上传功能

- 新增用户
- 用户列表(增删改查)

- 通用增删改查接口实现(中间件 resourceMiddleware)

- 登录功能
- 登出功能
- 添加 jwt 校验（1. 用户名查找 2. 密码校验 3. 返回 token）
- 添加 http 拦截器（request、response)

### 博客系统

- 博客首页 UI
- 博客首页接口实现
- 博客归档页面 UI
- 博客归档页面接口实现
- 博客文章页面 UI
- 博客文章页面接口实现
- 博客友链页面 UI
- 博客友链页面接口实现
- 博客留言页面 UI
- 博客留言页面接口实现

### 项目打包部署

- 项目打包
- 域名购买
- 域名解析
- linux 云服务器购买
- git 安装, ssh key 添加
- pm2 部署
- ngnix 配置
- mongodb 配置
- mongodb 数据导入

### 博客后台管理系统

![](./screenshot/admin.gif)

### 博客系统

![](./screenshot/web.gif)

### To Do List

- 性能优化，图片需要压缩处理，预加载处理
- 给博文页面加上 tag 标签页以及搜索功能
- 浏览器兼容问题，移动端适配。只用了自己电脑的谷歌 chrome 浏览器开发和手机适配效果，其他种种都没试，不过不建议移动端使用，电脑登陆效果更佳
- 解决 vue 的 seo 问题及刷新渲染页面抖动问题。先暂时做 vue 预渲染，不排除以后会做 vue 服务端渲染或 nuxt.js 服务端渲染
- 整理代码，拆分出组件。让结构更清晰，代码量更少
- 利用 typescript 重构整个项目
- 想到有意思的功能也会慢慢加上，持续开发中...
