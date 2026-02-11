# Documentation

This directory contains project planning and documentation for the TAG Pressable Multisite plugin, formatted for [MkDocs](https://www.mkdocs.org/).

## 📚 Viewing the Documentation

### Option 1: Local Development Server

1. **Install MkDocs** (if not already installed):
   ```bash
   pip install mkdocs mkdocs-material
   ```

2. **Navigate to this directory**:
   ```bash
   cd /Users/pbrocks/Documents/Local/pressable-ms/app/public/wp-content/plugins/tag-pressable-multisite/claude
   ```

3. **Start the development server**:
   ```bash
   mkdocs serve
   ```

4. **Open in browser**:
   - Visit: `http://127.0.0.1:8000`
   - The site will auto-reload when you edit markdown files!

### Option 2: Build Static Site

Generate static HTML files:

```bash
mkdocs build
```

The built site will be in the `site/` directory.

### Option 3: Read Markdown Directly

All documentation is in plain markdown and can be read directly:

- **[Home](index.md)** - Project overview
- **[WaaS Architecture](docs/multisite-paying.md)** - Full planning document
- **[Storefront Integration](docs/multisite-storefront.md)** - Integration analysis

## 🎨 Theme & Features

This documentation uses the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme with:

- ✅ **Dark/Light mode** - Automatically switches based on system preference
- ✅ **Code highlighting** - Syntax highlighting for PHP, bash, etc.
- ✅ **Search** - Full-text search across all pages
- ✅ **Mobile responsive** - Looks great on all devices
- ✅ **Admonitions** - Info boxes, warnings, tips, etc.
- ✅ **Emoji support** - Native emoji rendering

## 📝 Editing Documentation

### File Structure

```
claude/
├── mkdocs.yml          # MkDocs configuration
├── index.md            # Home page
├── README.md           # This file
└── docs/               # Documentation pages
    ├── multisite-paying.md
    └── multisite-storefront.md
```

### Adding New Pages

1. Create a new `.md` file in `docs/`
2. Add it to the `nav` section in `mkdocs.yml`:

```yaml
nav:
  - Home: index.md
  - Planning:
    - WaaS Architecture: docs/multisite-paying.md
    - Storefront Integration: docs/multisite-storefront.md
    - Your New Page: docs/your-new-page.md  # Add here
```

### Markdown Extensions

The following markdown features are enabled:

#### Admonitions

```markdown
!!! note "Optional Title"
    This is a note box

!!! tip
    This is a tip

!!! warning
    This is a warning

!!! danger
    This is a danger notice
```

#### Code Blocks

````markdown
```php
function hello_world() {
    echo "Hello, World!";
}
```
````

#### Tables

```markdown
| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
```

#### Task Lists

```markdown
- [x] Completed task
- [ ] Incomplete task
```

## 🚀 Deployment

### GitHub Pages

To deploy to GitHub Pages:

1. Uncomment `site_url` in `mkdocs.yml`
2. Run:
   ```bash
   mkdocs gh-deploy
   ```

This will build the site and push it to the `gh-pages` branch.

## 🛠️ Troubleshooting

### "mkdocs: command not found"

Install MkDocs:
```bash
pip install mkdocs mkdocs-material
```

Or using pip3:
```bash
pip3 install mkdocs mkdocs-material
```

### Port 8000 already in use

Use a different port:
```bash
mkdocs serve -a 127.0.0.1:8001
```

### Material theme not found

Install the Material theme:
```bash
pip install mkdocs-material
```

## 📖 Resources

- **MkDocs**: https://www.mkdocs.org/
- **Material for MkDocs**: https://squidfunk.github.io/mkdocs-material/
- **Markdown Guide**: https://www.markdownguide.org/

---

**Happy documenting! 📝**
