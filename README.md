## Resume 
### Hi everyone! I'm Bella. This is a free personal blog, and I'm happy to share it with you.
> Source Codes: https://github.com/fplei/fplei.github.io.git

- You can also create a brand new blog and install it via the npm command:

```
npm i hexo-theme-resume

Then delete the redundant dependency packages (important), open package.json, copy and replace all with the following:

```
{
  "name": "hexo-site",
  "private": true,
  "hexo": {
    "version": "5.2.0"
  },
  "scripts": {
    "start": "hexo server",
    "build": "node pre-deploy.js && hexo clean && hexo generate",
    "deploy": "npm run build && hexo deploy"
  },
  "engines": {
    "node": ">=8.9.0"
  },
  "dependencies": {
    "hexo": "^5.2.0",
    "hexo-autonofollow": "^1.0.1",
    "hexo-deployer-git": "^2.1.0",
    "hexo-neat": "^1.0.9",
    "hexo-renderer-ejs": "^1.0.0",
    "hexo-renderer-marked": "^3.2.0",
    "hexo-renderer-stylus": "^2.0.1",
    "hexo-server": "^1.0.0"
  }
}
```

```
Then enter npm i to install dependent packages.

> 本站源码： https://github.com/fplei/fplei.github.io.git

- 也可以创建全新的博客，通过 npm 命令安装：

```
npm i hexo-theme-resume

然后删除多余的依赖包（重要），打开 package.json 复制并全部替换为以下内容：

```
{
  "name": "hexo-site",
  "private": true,
  "hexo": {
    "version": "5.2.0"
  },
  "scripts": {
    "start": "hexo server",
    "build": "node pre-deploy.js && hexo clean && hexo generate",
    "deploy": "npm run build && hexo deploy"
  },
  "engines": {
    "node": ">=8.9.0"
  },
  "dependencies": {
    "hexo": "^5.2.0",
    "hexo-autonofollow": "^1.0.1",
    "hexo-deployer-git": "^2.1.0",
    "hexo-neat": "^1.0.9",
    "hexo-renderer-ejs": "^1.0.0",
    "hexo-renderer-marked": "^3.2.0",
    "hexo-renderer-stylus": "^2.0.1",
    "hexo-server": "^1.0.0"
  }
}
```
然后输入 npm i 安装依赖包。
