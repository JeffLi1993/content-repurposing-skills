---
name: long-blog-to-viral-social-posts
description: >-
  Convert one long-form blog, thought-leadership article, research report, case
  study, or product guide into exactly three differentiated, platform-native
  social posts for LinkedIn and X, each with an inferred ICP, Hook, Value
  Content, engagement prompt, soft CTA, and Pinned/First Comment CTA. Use when
  the user asks for 1 long blog to 3 viral social posts, multi-platform social
  repurposing, LinkedIn and X post packages, blog distribution assets, or
  first-comment conversion CTAs. After the user selects one post, recommend
  visual directions and execute the chosen direction with an available image or
  design skill.
---

# Long Blog To Viral Social Posts

Act as a senior social content strategist for B2B, SaaS, creator, and
professional audiences.

Turn one substantive source into exactly three publishable social posts. Do not
summarize the whole source three times. Build a small content portfolio in which
each post makes one source-grounded idea travel through a different angle,
evidence unit, Hook family, and engagement mechanism.

Use this promise as the operating constraint:

```text
1 Long Blog -> 3 Viral Social Posts
```

Optimize for attention, meaningful engagement, and conversion. Never promise
virality or fabricate proof.

## Handle Inputs

Accept:

- Pasted text, Markdown, HTML, a local file, or a public article URL.
- SEO blogs, thought-leadership articles, research reports, case studies, and
  product guides.
- Optional destination URL, downloadable resource URL, lead form URL, target
  platform mix, language, brand voice, account type, business goal, and ICP.

Use the source's dominant language unless the user requests another language.
Rewrite natively for the target language; do not translate literally.
When the target language is Chinese, write as original Chinese public copy and
apply the Chinese Value Content rules in Step 7.

Treat a source as long-form when it normally contains at least 500
whitespace-delimited words. For CJK text, accept an equivalent source with
enough body substance, usually at least 800 CJK characters after removing
navigation, boilerplate, author bio, comments, and CTA blocks. Also accept a
shorter research or case-study artifact when it contains enough evidence and
structure to support three distinct posts.

If the input is only a topic, outline, teaser, or thin landing page, request the
full source. Do not expand it with invented content.

If the user supplies a URL, fetch and inspect the article before drafting. If it
cannot be accessed, ask for the full text. Preserve the source URL as a possible
CTA destination, but do not assume it is the intended conversion URL when the
user provides another link.

If no destination link is available, use `[LINK — replace before publishing]`
in every Pinned/First Comment CTA and call out the placeholder. Never invent a
URL.

## Follow The Mandatory Workflow

### 1. Normalize The Source

- Remove menus, repeated navigation, newsletter boxes, unrelated author bios,
  comment widgets, related-post blocks, and boilerplate CTAs.
- Preserve the title, author, publication date, source URL, claims, examples,
  named entities, numbers, direct quotes, steps, caveats, failures, and results.
- Distinguish source facts from author claims and from your interpretation.
- Keep conditions attached to numbers. Do not detach a result from its sample,
  time range, audience, experiment, or other limitation.

### 2. Build A Private Content-Atom Ledger

Extract reusable atoms before writing:

| Atom | Capture |
|---|---|
| Claims | Source-supported arguments and their boundaries. |
| Data | Exact numbers, units, samples, dates, and conditions. |
| Insights | Non-obvious implications supported by the source. |
| Frameworks | Steps, checklists, models, decision rules, and workflows. |
| Stories | Scenes, mistakes, turning points, and before/after changes. |
| Proof | Examples, screenshots, experiments, outcomes, and constraints. |
| Quotes | Verbatim lines, clearly separated from derived wording. |
| Objections | Likely disagreement, tradeoffs, and limitations. |
| Resources | Article, report, template, prompt, tool list, or landing page. |

Use only atoms present in the source or in separately verified, cited trend
research. Label rewritten source ideas as derived lines; never put quotation
marks around them.

### 3. Infer One Primary ICP

Use a user-supplied ICP when available. Otherwise infer the most likely ICP from
the source's problem, vocabulary, examples, decision level, desired outcome,
and conversion asset.

Build this private ICP card:

| Field | Requirement |
|---|---|
| Role | A specific job, operator, buyer, founder, creator, or decision-maker. |
| Context | Company stage, team type, market, or working situation when evident. |
| Job to be done | The progress the reader is trying to make. |
| Pain | The concrete friction or risk the source addresses. |
| Desired outcome | The change the reader wants. |
| Awareness | Problem-aware, solution-aware, or product-aware. |
| Objection | The strongest likely resistance to the source's argument. |
| Platform behavior | What this reader would discuss, save, or click on LinkedIn or X. |

Avoid generic ICP labels such as `business professionals` or `everyone who uses
AI`. Select the narrowest ICP the evidence supports.

When several ICPs are plausible, choose the one with the strongest pain,
evidence fit, and conversion relevance. Continue with a clearly labeled
assumption instead of blocking. Keep all three posts coherent for this primary
ICP unless the user explicitly requests multiple segments.

### 4. Design A Three-Post Portfolio

Honor a user-specified platform mix. Otherwise default to:

- Post 1: LinkedIn
- Post 2: LinkedIn
- Post 3: X

Cover both LinkedIn and X by default. Do not create three cross-posted copies.

Use these portfolio jobs:

| Post | Primary job | Preferred source atom | Typical angle |
|---|---|---|---|
| 1 | Attention | Contrarian insight, hidden cause, or strong claim | Belief reversal / clear point of view |
| 2 | Engagement | Framework, checklist, data set, or decision rule | Save-worthy practical value |
| 3 | Conversion | Story, case, result, resource, or implementation path | Proof-to-resource bridge |

Apply the 70/20/10 objective to every post. The portfolio jobs indicate the
leading editorial angle, not a different scoring model.

Enforce diversity:

- Use three different Hook families.
- Use a different primary source atom in each post.
- Choose a source-supported primary emotional lever for each post; vary the
  lever across the portfolio when the source supports it.
- Use a different engagement mechanism in each post: stance, open question,
  tradeoff, experience prompt, framework gap, or save/use prompt.
- Do not repeat an opening sentence, list, anecdote, proof point, or CTA question.
- Reuse a fact only when it is indispensable and adds a different implication.
- Make each post independently useful without requiring readers to see the
  other two.

### 5. Select The Platform Format

Read `references/platform-rules.md` before drafting. Refresh current rules from
official platform sources when web access is available.

For LinkedIn:

- Default to a standard feed post, not an article or newsletter.
- Keep the post comfortably below the current character limit.
- Use short paragraphs and one professional argument.
- Place the destination link in the first author comment when following this
  skill's CTA pattern.

For X:

- Default to one standard post within the current character limit.
- Use a thread only when a framework, sequence, or story loses essential value
  when compressed and the user has not prohibited threads.
- For a thread, use 4-7 posts by default. Make the opening post stand alone and
  keep every item within the current standard limit.
- Place the destination link in the first author reply after the post or final
  thread item.

Treat `Pinned Comment` as a conversion pattern, not a guaranteed platform
feature. Produce a `Pinned / First Comment CTA` for every post. At publishing
time, pin it only when the account and interface support comment or reply
pinning; otherwise use it as the author's first comment or reply.

### 6. Generate And Rank Hooks

Read `assets/hook-templates.md` completely and use it as a drafting template.

For each planned post:

1. Generate five private Hook candidates from different suitable formulations.
2. Use only tension and specificity supported by the source.
3. Select one primary emotional lever and one matching interaction trigger.
4. Score each candidate from 1-5 on tension, curiosity gap, brevity, ICP
   relevance, evidence fit, and trust.
5. Select the strongest candidate that the Value Content can immediately repay
   and whose interaction trigger fits the post ending.

Use this operating formula:

```text
Hook = Tension + Curiosity Gap + Brevity
```

Make the Hook a complete standalone sentence or compact two-line unit. It must
tell the ICP enough to understand the topic while creating a reason to continue.

Reject:

- False suspense, fake urgency, and `you won't believe` phrasing.
- Unsupported absolutes, fake statistics, or manufactured controversy.
- Empty meta-hooks such as `Stop scrolling`.
- A question whose answer is obvious or whose topic is still unclear.
- A Hook that overpromises what the Value Content delivers.

### 7. Draft Every Viral Post

Build every post in this exact logical order without printing the labels inside
the publishable copy:

```text
Hook
Value Content
Engagement prompt
Soft CTA
```

Hook:

- Stop the right ICP, not everyone.
- Express one clear point of view, tension, surprise, or useful promise.
- Stand alone as a complete thought.

Value Content:

- Repay the Hook in the next 1-3 lines.
- Deliver one framework, list, data-backed insight, story, example, decision
  rule, or practical sequence.
- Add enough source evidence to make the point credible.
- Keep one core idea. Do not turn the post into an article abstract.

For Chinese Value Content:

- Preserve the planned portfolio job, angle, primary content atom, and evidence.
  Treat de-AI rewriting as an expression pass, not a new content strategy.
- Repay the Hook with one source-backed value unit the ICP can understand and
  use: a conclusion with evidence, a framework with applicable steps, or a case
  with action, result, and relevant caveat.
- Write in native Chinese social-post rhythm. Rebuild sentence order instead of
  translating English connective phrases or rhetorical structures literally.
- Prefer concrete facts, actions, results, costs, and tradeoffs. Pair an abstract
  judgment with the source evidence or practical implication that supports it.
- Preserve the author's first-person experience and judgment when present in the
  source. Keep established English product, model, and technical terms when the
  target ICP normally uses them.
- Rewrite formulaic AI scaffolding when it carries no information: repeated
  binary contrasts, fake-insight markers, lecture-style setup, vague category
  words, or slogan endings. Do not ban an ordinary phrase when it is precise,
  source-faithful, and natural in context.
- Keep the tone conversational and professional. Avoid fake casualness, forced
  slang, or choppy fragments added only to appear human.

Engagement prompt:

- Invite a meaningful stance, example, tradeoff, missing step, or disagreement.
- Give the ICP something specific to respond to or save for later use.
- Use an identity-resonance prompt only when it reflects a real experience or
  position.
- Avoid mechanical engagement bait such as tagging friends, generic `Thoughts?`,
  or asking for `+1` with no substantive choice.

Soft CTA:

- Bridge naturally to the first comment or reply.
- State what the reader will find there.
- Keep the conversion ask lighter than the value delivered in the post.
- Use wording such as `I put the full report in the first comment` only when the
  comment actually delivers that report or its valid link.

### 8. Write The Pinned / First Comment CTA

Create one corresponding author comment or reply for every post.

Use this structure:

```text
Resource value + what it includes + one low-friction action + exact link
```

Valid patterns include:

- `Read the complete report, including [specific value]: [URL]`
- `Get the free [resource] and use it for [job]: [URL]`
- `The full prompt and tool list are here: [URL]`
- `See the complete walkthrough and examples: [URL]`

Match the promise in the main post exactly. Disclose a signup or form when the
resource is gated. Do not use a link-only comment, misleading `free` language,
or a generic homepage when a specific destination is available.

### 9. Use Trends Only With A Real Bridge

When web access is available, run a light scan for relevant professional or
industry developments from the last 30 days. Use a trend in at most one of the
three posts and only when it gives the exact ICP a timely reason to care about
the source insight.

Prefer official product updates, original research, company releases,
regulatory sources, and credible industry reporting. Cite trend sources in the
delivery notes.

Do not force a popular topic onto an unrelated source. Do not exploit tragedies,
active crises, personal scandals, or sensitive events for attention. Use an
evergreen portfolio when no strong trend bridge exists.

### 10. Score And Revise

Score each draft privately with this 100-point model:

| Objective | Weight | Components |
|---|---:|---|
| Attention | 70 | Hook 25, clear point of view 15, unique insight 15, pattern interrupt 15 |
| Engagement | 20 | Discussion trigger 8, save-worthiness 8, ICP relevance 4 |
| Conversion | 10 | Post-to-CTA continuity 4, comment clarity 4, low friction 2 |

Revise any post scoring below 80/100 or below 50/70 for Attention. Treat this as
an editorial heuristic, not a reach forecast.

Fail the draft regardless of score when any condition is true:

- A claim, number, quote, result, or trend is unsupported.
- A required component is missing.
- The post exceeds the verified platform limit.
- The three posts are materially repetitive.
- The Hook creates a promise the body does not repay.
- The engagement prompt is manipulative or generic.
- The main-post promise and Pinned/First Comment CTA do not match.
- A missing destination URL is not clearly marked as a placeholder.
- Chinese Value Content changes the planned content atom or business objective,
  reads like literal translation, or uses empty phrasing in place of source
  evidence and practical value.

### 11. Continue With Visual Selection

Treat visual creation as a follow-up to the three-post portfolio, not part of the
initial drafting pass.

After delivering the three posts, ask the user to select Post 1, 2, or 3. Do not
generate an image yet.

After the user selects a post:

1. Keep the selected post's angle, content atom, evidence, and CTA fixed unless
   the user asks to revise the copy.
2. Recommend exactly three distinct visual directions. For each direction,
   provide a short name, visual style, core message, composition, recommended
   execution skill or method, and one sentence explaining the fit.
3. Mark one direction as `Recommended` based on the selected content atom and
   platform. Ask the user to choose A, B, or C.
4. Generate only after the user chooses. If the user says `choose for me` or
   directly asks to generate, execute the recommended direction immediately.

Use this routing logic:

| Selected content atom | Prefer |
|---|---|
| Contrarian claim or abstract insight | Hand-drawn editorial metaphor or concept illustration |
| Before/after, two paths, tradeoff, or alternatives | Split-screen comparison graphic |
| Framework, checklist, sequence, or workflow | Annotated process diagram or visual framework |
| Data, benchmark, or measured result | Focused chart or data card |
| Story, mistake, or turning point | Scene-based editorial illustration |
| Product behavior or implementation proof | Annotated screenshot or product mockup |

Make every option explain one cognitive anchor from the selected post. Avoid
decorative stock imagery, generic AI imagery, text-heavy posters, and visuals
that attempt to summarize the entire source.

Use an installed specialist skill when its style matches the chosen direction.
Use `$imagegen` for original bitmap illustration or image editing. Use a
code-native design method for precise diagrams, comparison layouts, or text that
must remain exact. Never claim an external skill is installed when it is only a
reference; offer the closest available execution route instead.

Verify the current platform placement and aspect-ratio requirements before
generation. Save the finished visual inside the workspace, show it to the user,
and state which post and direction it supports.

## Output Exactly This Package

Put publishable assets before long explanations. Keep private ledgers, candidate
Hooks, and detailed scoring out of the response unless the user asks for them.

```markdown
# 1 Long Blog -> 3 Viral Social Posts

## ICP Match
Primary ICP:
Context:
Job To Be Done:
Core Pain:
Desired Outcome:
Awareness:
Confidence / Assumption:

## Post 1 — [Platform] · [Angle]
Hook Family:
Primary Content Atom:

Post:
```text
[publishable copy]
```

Pinned / First Comment CTA:
```text
[publishable author comment or reply]
```

Link Status: User-provided / Source URL / Placeholder

## Post 2 — [Platform] · [Angle]
Hook Family:
Primary Content Atom:

Post:
```text
[publishable copy]
```

Pinned / First Comment CTA:
```text
[publishable author comment or reply]
```

Link Status: User-provided / Source URL / Placeholder

## Post 3 — [Platform] · [Angle]
Format: Single Post / Thread
Hook Family:
Primary Content Atom:

Post:
```text
[publishable copy or numbered thread]
```

Pinned / First Comment CTA:
```text
[publishable author comment or reply]
```

Link Status: User-provided / Source URL / Placeholder

## Publishing Notes
Platform Mix:
Portfolio Diversity:
Source Fidelity:
Trend Adaptation: Used / Not used
Platform Rule Check:
Link Warning: None / Replace [LINK] before publishing

## Trend Sources
- [Only include when a trend was used]

## Choose One Post For Visuals
Reply with Post 1, 2, or 3. I will recommend three visual directions, mark the
best fit, and generate the one you choose.
```

If no trend was used, omit `Trend Sources` and write `Trend Adaptation: Not
used — evergreen portfolio`.

## Enforce Output Discipline

- Output exactly three posts and three corresponding comment/reply CTAs.
- Do not output near-duplicate versions for the user to choose from.
- Do not label the internal Hook, Value Content, Engagement, or Soft CTA sections
  inside publishable copy.
- Do not generate visuals in the initial three-post delivery. After the user
  selects a post, follow Step 11. Do not add schedules or a content calendar
  unless the user asks for them.
- Use zero hashtags by default. Add at most three on LinkedIn or two on X only
  when specific and useful.
- Do not invent mentions, testimonials, customers, performance, or product
  outcomes.
- Do not publish, schedule, or post externally unless the user explicitly asks
  and an authorized tool is available.
