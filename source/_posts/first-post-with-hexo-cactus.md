---
title: 我的第一篇博客：开始使用 Hexo 和 Cactus 主题
date: 2025-04-25 17:04:17
tags: 
  - Hexo
  - Cactus
  - 博客
categories:
  - 技术
---

## 欢迎来到我的博客

在 Copilot 的大力帮助下，终于使用 Hexo 框架和 Cactus 主题搭建了自己的博客站点。

## 为什么选择 Hexo + Cactus

[Hexo](https://hexo.io/) 是一个快速、简洁且高效的博客框架，使用 Markdown 写作，能够快速生成静态网站。Hexo 具有以下优点：

- 简单易用，安装方便
- 部署迅速，生成静态文件
- 支持 Markdown，专注写作体验
- 丰富的插件和主题

而 [Cactus](https://github.com/probberechts/hexo-theme-cactus) 主题则是一个简约、优雅的主题，它的设计理念是：

- 简洁的视觉体验
- 响应式布局，适配各种设备
- 良好的代码高亮支持
- 支持自定义

## 安装与配置过程

其实下面这些事情，Copilot 都帮我完成了。。。

### 1. 安装 Hexo

```bash
npm install -g hexo-cli
```

### 2. 初始化项目

```bash
hexo init blog
cd blog
```

### 3. 安装 Cactus 主题

```bash
git clone https://github.com/probberechts/hexo-theme-cactus.git themes/cactus
```

### 4. 配置主题

编辑 `_config.yml` 文件，将主题设置为 Cactus：

```yaml
theme: cactus
```

## 结语

Copilot真是太强了，上面这些事情都帮我做了。。。
