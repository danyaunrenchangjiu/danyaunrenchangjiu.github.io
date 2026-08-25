# 博士生活与科研工具箱

这是一个基于 Hexo + Butterfly 的个人博客，用来记录博士生活、科研技巧、实验复盘、论文阅读和代码笔记。

## 常用命令

```bash
pnpm install
pnpm run server
pnpm run build
pnpm run clean
```

本地预览地址默认是 <http://localhost:4000>。

## 写新文章

```bash
pnpm exec hexo new post "文章标题"
```

文章会生成在 `source/_posts/`。建议每篇文章都写清楚 `categories`、`tags`、`description` 和 `cover`。

## 需要你后续替换的内容

- `_config.yml` 里的 `author` 和正式部署后的 `url`。
- `_config.butterfly.yml` 里的邮箱、头像、社交链接和公告。
- 如果要部署到 GitHub Pages，可以再配置仓库地址和自动部署流程。

## 当前已启用

- Butterfly 主题
- 中文导航
- 文章目录
- 代码复制、语言显示、代码块高度限制
- 站内搜索
- 字数统计与阅读时间
- Mermaid 图表
- 分类页、标签页、关于页
