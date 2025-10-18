# My Blog

A simple blog built with Jekyll and hosted on GitHub Pages.

## 🚀 Quick Start

This blog uses Jekyll, which is built into GitHub Pages. You don't need to install anything locally to get started!

### Setting Up GitHub Pages

1. Push this repository to GitHub
2. Go to your repository settings
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select the branch you want to deploy (usually `main`)
5. Click "Save"
6. Your site will be published at `https://[your-username].github.io/[repository-name]/`

## ✍️ Adding New Blog Posts

Adding new posts is super easy! Just create a new Markdown file in the `_posts` directory.

### Steps to Add a Post:

1. Create a new file in the `_posts` folder
2. Name it following this format: `YYYY-MM-DD-title-of-post.md`
   - Example: `2025-10-18-my-awesome-post.md`
3. Add front matter at the top of the file:

```markdown
---
layout: post
title: "Your Post Title"
date: 2025-10-18 10:00:00 -0000
author: Your Name
---

Your content goes here...
```

4. Write your content in Markdown below the front matter
5. Commit and push to GitHub
6. GitHub Pages will automatically build and publish your new post!

## 📝 Writing in Markdown

Markdown is simple and intuitive. Here are some common elements:

- **Headings**: Use `#` for headings (`#` for h1, `##` for h2, etc.)
- **Bold**: `**bold text**`
- **Italic**: `*italic text*`
- **Links**: `[link text](url)`
- **Images**: `![alt text](image-url)`
- **Code**: Use backticks for inline code or triple backticks for code blocks
- **Lists**: Use `-` or `*` for bullets, or `1.` for numbered lists

## 🎨 Customization

### Update Site Information

Edit `_config.yml` to change:

- Site title
- Description
- Author name
- Email

### Modify Design

Edit `assets/css/style.css` to customize:

- Colors
- Fonts
- Layout
- Spacing

### Add New Pages

Create a new Markdown or HTML file in the root directory with front matter:

```markdown
---
layout: default
title: Page Title
permalink: /page-url/
---

Your content here...
```

Then add a link to the navigation in `_layouts/default.html`.

## 📁 Project Structure

```
.
├── _config.yml           # Site configuration
├── _layouts/             # Page templates
│   ├── default.html      # Main layout with header/footer
│   └── post.html         # Blog post layout
├── _posts/               # Your blog posts (Markdown files)
│   ├── 2025-10-18-welcome-to-my-blog.md
│   └── 2025-10-17-getting-started-with-markdown.md
├── assets/
│   └── css/
│       └── style.css     # Styling
├── index.html            # Home page (lists posts)
├── about.md              # About page
├── archive.html          # Archive page (all posts)
└── README.md             # This file
```

## 🧪 Testing Locally (Optional)

If you want to preview your site locally before pushing:

1. Install Ruby and Bundler
2. Create a `Gemfile` with:

```ruby
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
```

3. Run `bundle install`
4. Run `bundle exec jekyll serve`
5. Visit `http://localhost:4000`

## 📚 Resources

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)

## 💡 Tips

- Commit and push regularly to keep your blog updated
- Use descriptive post titles and filenames
- Add images to an `assets/images/` folder and reference them in posts
- Check your site after publishing to make sure everything looks right

Happy blogging! 🎉
