# jiahangwang197-ai.github.io

个人技术博客 & 主页，使用 [Jekyll](https://jekyllrb.com/) + [Minima](https://github.com/jekyll/minima) 主题构建，托管于 [GitHub Pages](https://pages.github.com/)。

## 本地运行

```bash
# 安装依赖
bundle install

# 启动本地服务器
bundle exec jekyll serve

# 浏览器访问
# http://localhost:4000
```

## 目录结构

```text
├── _config.yml          # Jekyll 配置
├── _posts/              # 博客文章
├── _layouts/            # 布局模板（由 minima 主题提供）
├── assets/css/          # 自定义样式
├── index.md             # 首页
└── about.md             # 关于页
```

## 部署

推送到 `main` 分支，GitHub Pages 会自动构建并部署。

## 许可

MIT License
