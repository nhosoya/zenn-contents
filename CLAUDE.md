# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a Zenn content repository for publishing technical articles.

## Repository Structure

- `articles/` - Markdown articles with YAML frontmatter
- `books/` - Book content
- `images/{article-id}/` - Images for each article

## Common Commands

```bash
npx zenn-cli preview    # Local preview at http://localhost:8000
npx zenn-cli new:article # Create new article
npx zenn-cli new:book    # Create new book
```

For full Zenn CLI documentation: https://zenn.dev/zenn/articles/zenn-cli-guide

## Article Frontmatter

```yaml
---
title: "Article title"
emoji: "🆔"
type: "tech" # or "idea"
topics: ["topic1", "topic2"] # lowercase, max 5
published: true # or false
---
```

## Notes

- Repository auto-syncs with Zenn platform on push to GitHub