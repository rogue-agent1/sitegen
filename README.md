# sitegen

Minimal static site generator from Markdown. Zero dependencies.

## Usage

```bash
sitegen init                              # Create sample content/
sitegen build --name "My Blog"            # Build to public/
sitegen build --src pages --out dist      # Custom paths
```

## Features

- Markdown → HTML with built-in converter
- YAML frontmatter (title, date)
- Auto-generated index page
- Clean, responsive CSS
- No dependencies, no config files

## Content Format

```markdown
---
title: My Post
date: 2026-01-01
---

# Hello

Write **Markdown** here.
```

## Requirements

- Python 3.6+ (stdlib only)
