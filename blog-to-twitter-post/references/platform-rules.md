# Twitter/X Platform Rules Reference

Last manually checked: 2026-06-07.

This file is a baseline. When running the skill with web access, refresh official
X sources because limits, product names, ranking surfaces, and media specs can
change.

## Official Sources To Refresh

- X Explore, "Trending": https://x.com/explore/tabs/trending
- X Help, "About different types of posts": https://help.x.com/en/using-x/types-of-posts
- X Docs, "Counting Characters": https://docs.x.com/fundamentals/counting-characters
- X Help, "Our approach to recommendations": https://help.x.com/en/rules-and-policies/recommendations
- X Business, "Creative ad specs": https://business.x.com/en/help/campaign-setup/creative-ad-specifications
- X Docs, "Media introduction": https://docs.x.com/x-api/media/introduction

## Current Baseline

- Standard X posts use a 280-character limit.
- X uses weighted character counting. CJK characters and emoji count heavier
  than Latin text. Use official character-counting guidance when exact length
  matters.
- Valid URLs are counted with platform URL handling. Treat every link as a
  significant character-budget cost.
- Longer posts can reach 25,000 characters, but they require X Premium. Do not
  use long-form posts unless the user explicitly asks for them.
- X recommendations use many signals, including the user's followed accounts and
  topics, interactions, watched media, and content popular in the user's network.
  X says no single signal is statically weighted above all others.
- Search and recommendations favor content that is relevant, credible, safe, and
  contributes meaningfully to conversation. Avoid spammy or misleading tactics.
- For image media, use PNG or JPEG. Keep generated images below 5 MB. Safe
  single-image defaults: 1200 x 1200 square or 1200 x 628 landscape.
- Useful visual ratios include 1:1, 1.91:1, 16:9, 4:5, 2:3, and 9:16, but verify
  current official specs if the output is campaign-critical.

## Practical Writing Constraints

- Default to a short, standard public post.
- Use one core idea.
- Use 0-2 hashtags only.
- Put mentions only when they add context or are explicitly requested.
- Do not start a post with a username unless the limited distribution behavior
  is intentional.
- Avoid engagement bait. Ask a useful question or invite a specific reply.
- Make the first line understandable without the blog context.
- If the blog includes data, keep the exact conditions and limits attached.
- If the blog has no data, do not create data-like claims.

## Trend Adaptation Rules

- Start with X Explore Trending at runtime, using the article topic, audience
  pain, key nouns, entities, and contrarian edge as the matching basis.
- Use a trend only when it directly strengthens the article's core insight or
  gives the exact target audience a timely reason to care.
- Do not force a popular topic onto an unrelated article.
- If X Explore is inaccessible, login-gated, too personalized to verify, or has
  no strong related trend, use evergreen copy or clearly mark external trend
  sources as secondary context.
- Cite X Explore and any sources used to verify/date the trend.
- Prefer durable industry shifts, product launches, platform changes, funding
  signals, research, regulatory changes, or audience-specific conversations over
  generic viral chatter.
