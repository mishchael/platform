# Deprecated 
## 近日会以vue组件重写

### A Survey Platform
### 一个前端问卷调查框架


##### 主要用到的东西：
* vue.js

## [Demo](https://www.ycwalker.com/platform)  内置账号 ycwalker 密码 111

##### 本地测试
需要node环境，确保已经安装node.js与npm

1.克隆远程库
``` bash
git clone https://github.com/ycwalker/platform.git
```
2.移动到plateform目录下 

``` bash
cd plateform
```

3.安装依赖
``` bash
npm install
```

4.webpack打包生成
``` bash
npm run generate
```

5.等上一部编译完成，开启webpack server服务器
``` bash
npm run start
```
6.如果一切正常，打开localhost:8080，即可进入登陆页面

默认内置账户 ycwalker , 密码 111

数据库采用前端模拟，存储在localStore里,如果需要重置，打开F12，清空localStore的三个键值对并重新登陆


