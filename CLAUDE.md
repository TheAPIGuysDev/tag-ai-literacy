# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**tag-ai-literacy** is a WordPress plugin that creates an educational resource using MkDocs. The plugin provides a set of markdown files (starting with glossary.md) to help clarify, educate, and elucidate AI terminology, benefits, risks, and strategies. This is an AI literacy resource aimed at making AI concepts accessible and understandable.

**Current Status**: Early-stage project. The MkDocs documentation framework is in place with initial structure - plugin source code to integrate this into WordPress is not yet implemented.

**Repository**: https://github.com/TheAPIGuysDev/tag-ai-literacy

## Development Environment

This plugin is being developed in a Local by Flywheel WordPress environment at:
```
/Users/pbair19/Documents/Local/pressable-ms/app/public/wp-content/plugins/tag-ai-literacy
```

The project uses standard WordPress gitignore patterns to exclude WordPress core files and uploads.

## Documentation System

Project planning and documentation is managed using **MkDocs** in the `claude/` directory.

### Working with Documentation

**Start the documentation server**:
```bash
cd claude
mkdocs serve
```
Then visit http://127.0.0.1:8000

**Build static documentation**:
```bash
cd claude
mkdocs build
```

**Install MkDocs** (if needed):
```bash
pip install mkdocs mkdocs-material
```

### Documentation Structure

```
claude/
├── mkdocs.yml          # MkDocs configuration
├── index.md            # Project overview and vision
├── README.md           # Documentation usage guide
└── docs/               # Planning documents
    ├── glossary.md     # Implementation planning
    └── index.md        # Documentation index
```

The documentation uses the ReadTheDocs theme with support for:
- Admonitions (notes, tips, warnings)
- Code highlighting
- Tables and task lists
- Fenced code blocks

## Future Development

When implementing the WordPress plugin:

1. **Plugin Structure**: Follow WordPress plugin best practices with a main plugin file in the root directory
2. **MkDocs Integration**: The plugin will need to integrate the MkDocs-generated content into WordPress, possibly as custom post types, shortcodes, or embedded content
3. **Content Focus**: Primary content is the AI literacy glossary and educational materials - focus on making this content accessible and navigable within WordPress
4. **Educational Resource**: Structure the plugin to serve as an educational tool for AI terminology, benefits, risks, and strategies

## Documentation Guidelines

- Keep planning documents in `claude/docs/`
- Update `claude/mkdocs.yml` nav section when adding new documentation pages
- Use MkDocs markdown extensions for better formatting (admonitions, code blocks, tables)
- Document architectural decisions as the codebase grows
