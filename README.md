# demo

> A Vue.js project


##具体流程
``` bash
1、vue-cli初始化一个项目，并集成webpack工具
vue init webpack demo

2、安装glob模块 ，并加入依赖
npm install glob --save-dev;

3.继续安装依赖 
npm install

4、改造项目文件，index.html，main.js，App.vue修改放入index文件夹，继续添加其他模块


5、配置webpack，改造成了多入口，webpack.base.conf.js    webpack.dev.conf.js   webpack.prod.conf.js

6、运行项目
npm run dev

7、打包项目
npm run build

```