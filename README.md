<p align="center">
  <img width="420" src="https://cdn.jsdelivr.net/gh/baimingxuan/media-store/images/logo-r-md.png">
</p>
<p align="center">
  <a href="https://github.com/facebook/react">
    <img src="https://img.shields.io/badge/react-18.2.0-brightgreen.svg" alt="react">
  </a>
  <a href="https://github.com/remix-run/react-router">
    <img src="https://img.shields.io/badge/react_router-6.19.0-brightgreen.svg" alt="react-router">
  </a>
  <a href="https://github.com/reduxjs/redux-toolkit">
    <img src="https://img.shields.io/badge/react_redux-8.1.3-brightgreen.svg" alt="redux-toolkit">
  </a>
  <a href="https://github.com/vitejs/vite">
    <img src="https://img.shields.io/badge/vite-4.5.0-brightgreen.svg" alt="vite">
  </a>
  <a href="https://github.com/ant-design/ant-design">
    <img src="https://img.shields.io/badge/antd-5.11.2-brightgreen.svg" alt="antd">
  </a>
 <a href="https://github.com/microsoft/TypeScript">
    <img src="https://img.shields.io/badge/typescript-5.2.2-brightgreen.svg" alt="typescript">
  </a>
  <a href="https://github.com/less">
    <img src="https://img.shields.io/badge/less-4.2.0-brightgreen.svg" alt="less">
  </a>
</p>  


## 简介

#### react-admin-design是一个后台管理系统，它使用了最新的前端技术栈，并且提供了丰富的功能组件模块，可以帮助你快速搭建企业级中后台的前端架构。

##

- **技术栈**：使用 React18、Vite4、TSX 、ant-design5 等前端前沿技术开发
- **主题**：可配置的主题色
- **国际化**：内置完善的国际化方案
- **Mock 数据** 内置 Mock 数据方案

- **docker 环境开发部署**：docker 容器运行 开发环境 和 打包后的部署环境


![](https://cdn.jsdelivr.net/gh/baimingxuan/media-store/images/home-vue3.png)

## 本地开发

```bash
// 克隆项目
git clone https://github.com/r70kg/ract-admin-design.git

// 安装依赖
pnpm install

// 开发
pnpm run dev
```

## 构建

```bash
// 构建
pnpm run build
```

## 浏览器支持

本地开发推荐使用`Chrome 80+` 浏览器

支持现代浏览器, 不支持 IE

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt=" Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt=" Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|                         not support                          |                       last 2 versions                        |                       last 2 versions                        |                       last 2 versions                        |                       last 2 versions                        |

## Git 贡献提交规范

- `feat` 增加新功能
- `fix` 修复问题/BUG
- `style` 代码风格相关无影响运行结果的
- `perf` 优化/性能提升
- `refactor` 重构
- `revert` 撤销修改
- `test` 测试相关
- `docs` 文档/注释
- `chore` 依赖更新/脚手架配置修改等


## docker 容器中开发配置 此配置为 本地开发环境 和 部署环境】

本地开发配置 见 [Dockerfile-dev](./Dockerfile-dev)

本地部署配置 见 [Dokcerfile-prod](./Dockerfile-prod)

docker-compose 配置文件 见 [docker-compose.yml](./docker-compose.yml)

### 启动

```
docker-compose up -d
```

### 停止

```
docker-compose down
```

### 访问

本地开发 loaclhost:8201
本地部署 loaclhost:8202

