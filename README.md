<p align="center">
  <img width="104" src="./images/readme-mark.svg" alt="ihopeful Blog logo" />
</p>

<h1 align="center">ihopeful Blog</h1>

<p align="center">
  记录前端工程、跨端开发、桌面工具与工程质量实践。<br />
  以可复现的步骤、明确的边界和真实代码为核心。
</p>

<p align="center">
  <a href="https://github.com/ihopefulChina/ihopefulchina.github.io/actions/workflows/pages/pages-build-deployment"><img src="https://github.com/ihopefulChina/ihopefulchina.github.io/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master" alt="GitHub Pages deployment" /></a>
  <a href="https://ihopefulchina.github.io/"><img src="https://img.shields.io/website?url=https%3A%2F%2Fihopefulchina.github.io%2F&label=blog" alt="Blog availability" /></a>
</p>

<p align="center">
  <a href="https://ihopefulchina.github.io/"><strong>阅读博客</strong></a>
  · <a href="https://ihopefulchina.github.io/archives/">文章归档</a>
  · <a href="https://ihopefulchina.github.io/tags/">主题标签</a>
  · <a href="https://ihopefulchina.github.io/post/about/">关于</a>
</p>

---

## 关于这个博客

ihopeful Blog 是一份中文技术笔记，关注真实项目中可以复用的工程方法，而不是只展示最终代码。文章通常从问题、约束和失败路径出发，再给出实现、验证方式与适用边界。

主要内容包括：

- **前端工程**：TypeScript、Vue、React，以及复杂异步状态和接口契约。
- **跨端开发**：UniApp、Taro 与微信小程序的工程实践。
- **桌面工具**：Swift、macOS 原生应用与开发者工具。
- **工程质量**：自动化验证、发布流程、安全边界和可维护性。
- **历史实践**：WordPress、PHP 与旧项目的迁移和复盘。

## 从这里开始

- [不只是防抖：复杂前端异步竞态的四层治理](https://ihopefulchina.github.io/post/async-race-governance/)
- [契约优先的前端开发：从 Java OpenAPI 到生成客户端](https://ihopefulchina.github.io/post/contract-first-openapi-client/)
- [Pro Components Vue2：为存量后台补齐现代工程能力](https://ihopefulchina.github.io/post/pro-components-vue2/)
- [在 Mac 上，像用访达一样用阿里云 OSS](https://ihopefulchina.github.io/post/ossuno-macos-oss-client/)

完整文章请查看[归档](https://ihopefulchina.github.io/archives/)或按[标签](https://ihopefulchina.github.io/tags/)浏览。

## 仓库说明

这个仓库是博客的 **GitHub Pages 发布产物**。HTML、样式、搜索索引、站点地图和文章页面由 Gridea Pro 从写作工作区生成；直接修改生成文件会在下一次发布时被覆盖。

```text
master
├── index.html       # 首页
├── post/            # 文章页面
├── archives/        # 归档页
├── tags/            # 标签页
├── styles/          # 生成样式
├── scripts/         # 站点交互与搜索
└── sitemap.xml      # 搜索引擎站点地图
```

## 本地预览

静态站点不需要安装运行时依赖。克隆仓库后启动任意静态文件服务器即可：

```bash
git clone https://github.com/ihopefulChina/ihopefulchina.github.io.git
cd ihopefulchina.github.io
python3 -m http.server 4173
```

然后访问 `http://127.0.0.1:4173/`。这只验证已生成页面；文章源文件和生成配置不在本仓库中。

## 反馈

如果文章中的示例无法复现、链接失效或表述有误，请提交 [Issue](https://github.com/ihopefulChina/ihopefulchina.github.io/issues/new)，并附上文章链接、运行环境和可复现信息。
