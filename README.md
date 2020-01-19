# vue-cli-demo

> Vue  命令, 安装配置 及页面框架案例

## 开发环境

### 1. 安装编辑器

- [VS Code](https://code.visualstudio.com/) - 编辑器

### 2. 配置编辑器

```jsonc
{
  "editor.rulers": [100],
  "editor.formatOnSave": true,
}
```

将以上配置放到 vscode 的用户配置中。

### 3. 安装配置

```bash

# node & fw
> npm install vue-cli -g
> vue init webpack vue-cli-demo
> cd vue-cli-demo
> npm run dev

// fw

vue-cli-demo
  │
  ├─build                    // 项目构建 (webpack) 相关代码
  ├─config                   // 配置目录，包括端口号等
  │
  ├─src  // 源码目录
  │  │  App.vue  // 项目入口
  │  │  main.js  // 项目入口-项目核心文件
  │  │
  │  ├─assets      // 资源目录
  │  │
  │  ├─components  // 组件目录
  │  │
  │  └─router      // 路由配置目录
  │
  └─static         // 静态资源目录，如图片、字体等。

//
  │  .babelrc
  │  .editorconfig
  │  .eslintignore      // eslint 配置
  │  .eslintrc.js       // eslint 配置
  │  .gitignore
  │  .postcssrc.js
  │  index.html          // 首页入口模板文件
  │  package-lock.json
  │  package.json
  └─ README.md

```