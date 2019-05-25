# 校园综合服务平台小程序后台客户端

#### 安装教程

1.安装依赖并启动

```
npm install
npm run dev
```
2.登录初始密码
```
qwe123123
```

访问[http://localhost:3336](http://localhost:3336)

#### 线上部署
1.打开文件 src/assets/js/yzy.js
```
const yzy = {
  ...
  NODE_API: "https://api.demo.com/api/",  //改成自己服务器地址
  ...
}
```
2.打包导出
```
npm run build
```
导出的文件在dist目录下<br>
3.进入dist目录有两个文件 dist和index.html,将index.html拖到dist中。<br>
4.讲dist目录下的dist拖到服务端public目录下<br>
