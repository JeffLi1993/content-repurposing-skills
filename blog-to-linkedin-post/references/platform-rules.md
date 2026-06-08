# LinkedIn Platform Rules Reference

Last manually checked: 2026-06-08.

This file is a baseline. When running the skill with web access, refresh official
LinkedIn sources because limits, product behavior, and media guidance can
change.

## Official Sources To Refresh

- LinkedIn Help, "Post and share updates": https://www.linkedin.com/help/linkedin/answer/a528176/
- LinkedIn Help, "Differences between posting updates and publishing articles": https://www.linkedin.com/help/linkedin/answer/a522483/differences-between-posting-updates-and-publishing?lang=en
- LinkedIn Help, "Difference between posts, articles, reposts, and newsletters": https://www.linkedin.com/help/linkedin/answer/a519819
- LinkedIn Help, "Share photos on LinkedIn": https://www.linkedin.com/help/linkedin/answer/a527229
- LinkedIn Help, "Make your website shareable on LinkedIn": https://www.linkedin.com/help/linkedin/answer/a521928
- LinkedIn Sharing Guide PDF: https://content.linkedin.com/content/dam/help/linkedin/en-us/LinkedIn-Sharing-Guide.pdf

## Current Baseline

- LinkedIn posts have a 3000-character limit.
- If a post exceeds the post limit, use a LinkedIn article instead. LinkedIn
  articles can be much longer, but this skill defaults to posts, not articles.
- Posts are feed content. Articles are long-form publishing content.
  Newsletters are recurring article-based publications. Reposts share another
  member's content.
- Uploaded photos have a 5 MB upload size limit, should be at least 552 x 276 px,
  and LinkedIn recommends 1080 px width for stronger display quality.
- Organic photo aspect ratio can range from 3:1 to 4:5. Larger ratios may be
  centered and cropped.
- Multi-photo posts can include up to 20 images. The first image strongly affects
  layout and visual emphasis.
- LinkedIn Help says a post can share either a URL link or an image, but not both
  as the same attached media format. If a URL is shared, LinkedIn creates a
  preview image from the site.
- Link preview images should use a 1.91:1 ratio, commonly 1200 x 627 px, with a
  5 MB max file size.
- Official LinkedIn sharing guidance encourages a point of view, relevant
  hashtags, timely/trending topics, quality insights, questions that start
  conversation, mentions when relevant, and rich media.

## Practical Writing Constraints

- Default to 800-1600 characters for professional readability unless the source
  needs a longer explanation.
- Open with a clear point of view or professional conflict.
- Use short paragraphs. Dense walls of text are harder to scan in the feed.
- Use 0-3 hashtags. Avoid generic hashtag stuffing.
- Use mentions only when the person/company is relevant and the user approves or
  the source makes it appropriate.
- Use either a native uploaded image strategy or a URL preview strategy. Do not
  promise both as simultaneous primary media.
- Preserve source limitations and conditions around data.
- Do not convert a weak article into fake thought leadership by inventing
  personal experience.
- End with a discussion prompt, decision question, or practical CTA.

## Trend Adaptation Rules

- Search the last 30 days at runtime.
- Use a trend only when it directly strengthens the article's professional
  argument.
- Do not force a popular topic onto an unrelated article.
- Cite the sources used for trend adaptation.
- Prefer durable industry shifts, product launches, research reports,
  regulatory changes, company updates, and professional debates over broad viral
  chatter.
