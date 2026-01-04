# My Obsidian Notes

Personal knowledge base and blog source.

## Publishing to Blog

To publish a note to your blog:

1. Add front matter to your markdown file:

```yaml
---
title: "Your Post Title"
date: 2024-01-01
share: true
tags: ["tag1", "tag2"]
categories: ["category"]
---
```

2. Commit and push to GitHub
3. GitHub Actions will automatically sync to your Hugo blog: https://github.com/ColeNoice/blog2

## Front Matter Fields

- `title`: Post title (required)
- `date`: Publication date (auto-generated if not provided)
- `share`: Set to `true` to publish (required for publishing)
- `tags`: Array of tags (optional)
- `categories`: Array of categories (optional)
- `draft`: Set to `true` to mark as draft (optional)

## Note

Only notes with `share: true` will be published to the blog. All other notes remain private in this repository.
