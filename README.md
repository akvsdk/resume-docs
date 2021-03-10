# 快速搭建Hexo风格简历

## 搭建Node环境  

1. 安装nvm

[sh安装](https://github.com/nvm-sh/nvm#install--update-script)

[scoop安装](https://www.jianshu.com/p/50993df76b1c)

2. nvm 设置镜像源

```
nvm node_mirror https://npm.taobao.org/mirrors/node/
nvm npm_mirror https://npm.taobao.org/mirrors/npm/
```

3. 安装

   ```
   nvm ls   // 查看目前已经安装的版本
   nvm install 12.18.3  // 安装指定的版本的nodejs
   nvm use 12.18.3  // 使用指定版本的nodejs
   ```

   ## 全局安装Hexo

   ```
   npm install hexo-cli -g
   ```

   ## 搭建

1. 下载源码

```
git clone https://github.com/akvsdk/resume-docs.git
```

2. 运行依赖

```
npm i
```

3. 本地测试效果

```
npm start
```

4. 生成静态文件

```
hexo g
```

5. 部署到git仓库

```
hexo d
```
