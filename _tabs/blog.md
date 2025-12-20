---
layout: page
icon: fas fa-blog
order: 4
title: Blog
---

This page lists blog posts (if any) in your site.

<ul class="post-list">
  {% for post in site.posts %}
    <li class="post-item">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <div class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</div>
      <p class="post-excerpt">{{ post.excerpt | strip_html | truncate: 240 }}</p>
    </li>
  {% endfor %}
</ul>

<style>
  .post-list { list-style: none; padding: 0; margin: 1rem 0; }
  .post-item { padding: 1rem; border: 1px solid var(--border-color); background: var(--card-bg); border-radius: 8px; margin-bottom: 1rem; }
  .post-item a { font-weight: 600; color: inherit; text-decoration: none; }
  .post-meta { color: var(--text-secondary); font-size: 0.9rem; margin-top: 0.25rem; }
  .post-excerpt { margin-top: 0.75rem; color: var(--text-secondary); }
</style>
