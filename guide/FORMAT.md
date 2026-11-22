# File formats (the website depends on these, so don't change them)

## Blog post: `posts/YYYY-MM-DD-slug.md`

```markdown
---
title: "How much edge tape does a cabinet shop really waste?"
description: "One-sentence summary under 155 characters for Google."
date: 2026-11-24
slug: how-much-edge-tape-does-a-cabinet-shop-waste
category: Edgebanding and materials
tags: [edge tape, waste, inventory]
faq:
  - q: "Question?"
    a: "Short answer."
---

Post body in Markdown…
```

- `slug` must match the file name without the date. Use lowercase with hyphens.
- `date` is the date the post goes live.

## Social captions: `social/YYYY-MM-DD-slug.md`

```markdown
# Social: <post title>

## Instagram
Caption (hook in the first line, under 150 words, 5–8 hashtags at the end)

## Facebook
Caption (conversational, 60–120 words, ends with the blog link)

## Image idea
What to photograph or film in the workshop, or which existing footage to use.

## Ad angle (optional)
One-line hook and audience if this post would work as a paid ad.
```
