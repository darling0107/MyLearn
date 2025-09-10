---
title: 个人博客
outline: deep
---

<div class="blog-hero">
  <img class="avatar" src="https://avatars.githubusercontent.com/u/9919?s=200&v=4" alt="avatar" />
  <h1>你好，我是 <span class="name">Your Name</span></h1>
  <p class="subtitle">记录所学、所思与所做 | 前端 · 笔记 · 生活</p>
  <div class="cta">
    <a class="btn primary" href="#posts">最新文章</a>
    <a class="btn" href="#about">关于我</a>
    <a class="btn" href="#contact">联系我</a>
  </div>
</div>

## 关于我 {#about}

热爱构建优雅、可维护的应用与知识体系。在这里我会分享：

- Web 与工程效率实践
- 学习心得与读书笔记
- 日常折腾与灵感片段

> Keep it simple. Make it useful. Make it delightful.

## 精选文章 {#posts}

<div class="card-grid">
  <a class="card" href="/">
    <h3>从这里开始 →</h3>
    <p>站点总览与快速导航。</p>
    <span class="meta">文档 · 首页</span>
  </a>
  <a class="card" href="/markdown-examples.html">
    <h3>Markdown 写作进阶</h3>
    <p>VitePress 下的 Markdown 能力演示与常用范式。</p>
    <span class="meta">技巧 · 写作</span>
  </a>
  <a class="card" href="/api-examples.html">
    <h3>组件与 API 例子</h3>
    <p>常用交互与组件 API 的简明示例。</p>
    <span class="meta">代码 · 示例</span>
  </a>
</div>

## 最近更新

- 2025-09-10：搭建个人博客主页与样式优化
- 2025-09-08：整理 Markdown 示例与常用片段

## 标签

`前端` `工程化` `写作` `随笔`

## 联系我 {#contact}

- 邮箱：your.name@example.com
- GitHub：`https://github.com/yourname`
- 微信：请备注“博客”

<style>
.blog-hero {
  text-align: center;
  padding: 28px 0 8px;
}
.blog-hero .avatar {
  width: 88px;
  height: 88px;
  border-radius: 50%;
  box-shadow: 0 8px 24px rgba(0,0,0,0.08);
}
.blog-hero .name { color: var(--vp-c-brand-1); }
.blog-hero .subtitle {
  color: var(--vp-c-text-2);
  margin-top: 6px;
}
.cta { margin-top: 14px; display: inline-flex; gap: 10px; }
.btn {
  display: inline-block;
  padding: 8px 14px;
  border-radius: 10px;
  border: 1px solid var(--vp-c-divider);
  color: var(--vp-c-text-1);
  text-decoration: none;
  transition: all .2s ease;
}
.btn:hover { transform: translateY(-1px); box-shadow: 0 6px 16px rgba(0,0,0,0.06); }
.btn.primary { background: var(--vp-c-brand-1); color: white; border-color: var(--vp-c-brand-1); }

.card-grid {
  margin: 8px 0 2px;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 14px;
}
.card {
  display: block;
  padding: 14px;
  border-radius: 12px;
  border: 1px solid var(--vp-c-divider);
  background: var(--vp-c-bg);
  text-decoration: none;
  color: inherit;
  transition: box-shadow .2s ease, transform .2s ease;
}
.card:hover { transform: translateY(-2px); box-shadow: 0 10px 24px rgba(0,0,0,0.08); }
.card h3 { margin: 0 0 6px; }
.card p { margin: 0 0 8px; color: var(--vp-c-text-2); }
.card .meta { font-size: 12px; color: var(--vp-c-text-3); }

@media (min-width: 768px) {
  .blog-hero { padding-top: 36px; }
  .blog-hero .avatar { width: 96px; height: 96px; }
}
</style>


