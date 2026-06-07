# Content Repurposing Skills

Reusable Agent skills for turning long-form blog content into social posts with
platform-specific copy, visual direction, and current trend adaptation.

This repository currently ships two skills:

- `blog-to-twitter-post`: convert a blog article into Twitter/X-ready short posts
  with a primary visual concept.
- `blog-to-linkedin-post`: convert a blog article into LinkedIn-ready professional
  posts with a primary visual concept.

Both skills require a real blog/article input of at least 500 words, or an
equivalent long-form CJK article, before drafting. They are designed for content
repurposing, not generic summarization.

## Structure

```text
content-repurposing-skills/
├── blog-to-twitter-post/
│   ├── SKILL.md
│   └── references/
│       └── platform-rules.md
├── blog-to-linkedin-post/
│   ├── SKILL.md
│   └── references/
│       └── platform-rules.md
├── README.md
└── README.zh.md
```

## Usage

Ask Agent to use one of the skills with a full blog article:

```text
Use $blog-to-twitter-post.
Target language: English
Style: Founder
Audience: Indie Hacker

<paste a blog article with at least 500 words>
```

```text
Use $blog-to-linkedin-post.
Target language: Chinese
Style: Growth Expert
Audience: SaaS Team

<paste a blog article with at least 500 words>
```

## Installation

Install each skill directory separately:

```bash
npx skills add /Users/jeff/JeffPage/creations/code-skill/content-repurposing-skills/blog-to-twitter-post
npx skills add /Users/jeff/JeffPage/creations/code-skill/content-repurposing-skills/blog-to-linkedin-post
```

Restart Agent after installing or updating a skill.

## Design Notes

Each skill follows the same high-level workflow:

1. Validate the input length and extract the article spine.
2. Identify the article's strongest quote, judgment, or transferable insight.
3. Refresh current platform limits and recommendation guidance from official
   sources when possible.
4. Scan the last 30 days of relevant trends and use only trends with a real
   semantic bridge to the article.
5. Draft platform-native post variants.
6. Design a visual concept or generate the primary image when an image tool is
   available.
7. Run final quality gates for source fidelity, platform fit, and exposure
   potential.

The trend step is intentionally runtime-based because social platform rules and
topics change quickly.
