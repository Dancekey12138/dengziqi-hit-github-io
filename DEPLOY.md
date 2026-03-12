# Hexo Blog Deployment Guide

## ✅ Migration Complete!

Your blog has been successfully migrated from Jekyll to Hexo with hexo-theme-keep theme.

## 🌐 Live Site

**URL:** https://dancekey12138.github.io/dengziqi-hit-github-io/

## 📁 Project Structure

```
hexo-blog/
├── source/
│   ├── _posts/          # Blog posts
│   ├── resume/          # Resume page
│   └── about/           # About page (optional)
├── themes/
│   └── keep/            # hexo-theme-keep
├── _config.yml          # Site configuration
└── themes/keep/_config.yml  # Theme configuration
```

## 🚀 Quick Commands

```bash
# Create new post
hexo new post "Your Post Title"

# Generate static files
hexo generate  # or: hexo g

# Local preview
hexo server    # or: hexo s
# Visit: http://localhost:4000

# Deploy to GitHub Pages
hexo generate && git push
```

## 📝 Configuration

### Site Info (`_config.yml`)
- Title: Ziqi Deng | Personal Portfolio
- Author: Ziqi Deng
- URL: https://dengziqi.hit.github.io

### Theme Settings (`themes/keep/_config.yml`)
- Menu: Home, Archives, Resume
- Primary Color: #0066cc
- Enable social links in configuration

## ✏️ Adding Content

### Blog Posts
```bash
hexo new post "Post Title"
# Edit: source/_posts/Post-Title.md
```

### Pages
```bash
hexo new page "page-name"
# Edit: source/page-name/index.md
```

## 🎨 Theme Customization

See: https://keep-docs.xpoet.cn

Key options:
- `base_info`: Site title, author, avatar
- `menu`: Navigation menu
- `first_screen`: Hero section
- `social_contact`: Social links
- `footer`: Footer content

## 📊 Current Content

- ✅ Resume page: `/resume`
- ✅ Welcome post: `/2024/03/13/Hello-World/`
- ✅ Archives page: `/archives`

## 🔧 Troubleshooting

### Build fails
```bash
hexo clean
hexo generate
```

### Theme not loading
```bash
# Make sure theme is in correct location
ls themes/keep/_config.yml
```

### GitHub Pages not updating
- Wait 1-2 minutes after push
- Check Actions tab for build errors
- Force refresh: Ctrl+Shift+R

---

**Last Updated:** March 13, 2024
**Author:** Ziqi Deng
