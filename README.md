React + ES6 + webpack 多页面项目框架
---
### 准备工作

1. 克隆到本地

> git clone

2. 安装依赖

> npm i

3. 运行查看

> npm run dev

在浏览器打开 localhost:3040 请查看首页

### 简要说明
```
src/views        站点入口目录，放置的是入口的js；
src/components   React 组件目录，包含所有的业务逻辑和样式；
src/assets       放置图片资源的目录
```

### 开发约定

当新创建一个页面时，如一个详情页 detail，需要做以下几件事情：

1. 在 `views` 目录新建 `detail` 目录，并在目录下 创建 `detail.jsx`。 结果： `/views/detail/detail.jsx`
2. 拷贝一份 `index.jsx` 的内容粘贴至 `detail.jsx`。
3. 运行 `npm run dev` 后，打开浏览器 输入 `localhost:3040/detail` ,便可以看到内容。


### 部署

> 运行 `npm run build` 把生成的 dist 目录传到服务器上便可
