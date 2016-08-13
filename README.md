# mmf-blog-vue2

demo: [http://www.mmxiaowu.com](http://www.mmxiaowu.com)

react: [https://github.com/lincenying/mmf-blog-react](https://github.com/lincenying/mmf-blog-react)

vue1: [https://github.com/lincenying/mmf-blog-vue](https://github.com/lincenying/mmf-blog-vue)

vue2: [https://github.com/lincenying/mmf-blog-vue2](https://github.com/lincenying/mmf-blog-vue2)

vue2 服务端渲染: [https://github.com/lincenying/mmf-blog-vue2-ssr](https://github.com/lincenying/mmf-blog-vue2-ssr) // 未完成

安装nodejs, MongoDB, 并启动
```
// 安装依赖
npm install

// 第一次生成静态文件, 以免api服务器找不到模版文件
npm run build

// 启动 api 服务器
npm run server

// 启动 开发模式
npm run dev
```
#### 使用api服务器访问:

添加管理员
http://localhost:3000/admin

登录
http://localhost:3000/login

#### 使用开发模式访问:
首页
http://localhost:8080

登录
http://localhost:8080/login.html
