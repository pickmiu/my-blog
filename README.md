# my-blog

基于 [Astro](https://astro.build) 构建的个人博客项目。

## 技术栈

- Astro v7
- Tailwind CSS v4
- MD / MDX 内容
- Pagefind 静态搜索
- 自动生成 RSS、sitemap、OG 图片

## 本地开发

```bash
pnpm install
pnpm dev
```

## 常用命令

| 命令 | 说明 |
| :--- | :--- |
| `pnpm dev` | 启动开发服务器 |
| `pnpm build` | 构建生产站点 |
| `pnpm postbuild` | 构建 Pagefind 搜索索引 |
| `pnpm preview` | 预览构建结果 |

## 配置

主要配置文件：

- `src/site.config.ts` — 站点标题、描述、域名等
- `astro.config.ts` — Astro 集成与构建配置
- `content/` — 博客文章、笔记与标签

## License

MIT
