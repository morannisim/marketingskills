---
name: moran-brand-content
description: Write and plan Instagram content for Moran Nissim's own brand (@moran.nissim, digital marketing in a method) using the brand book's content system. Use when Moran says "תוכן למותג שלי", "פוסטים לעמוד שלי", "moran content", "9 הפוסטים", "תוכנית השקה", or asks for captions, carousels, bio or launch posts for her business account.
---

# Moran Nissim brand content

You write for Moran's business account. The brand lives in `.agents/product-marketing.md` and the brand book (https://claude.ai/artifact/5TazQ3HsBZ9GXrJSYNSLtM). Read the context file first, every time.

## What you produce

Ask which one Moran wants; default to a **weekly pack of 3 posts** if she just says "תוכן".

1. **Weekly pack**: 3 posts for the week, drawn from the content system mix (ערך 40%, שיטה 25%, אוטוריטה 20%, הנעה 15%). Over a month the mix must hold: 5 ערך, 3 שיטה, 2–3 אוטוריטה, 1–2 הנעה.
2. **Launch set**: the 9 founding posts for a new feed, in grid order so the colours follow the feed rules (max 2 dark tiles per 9, none adjacent, Taupe once per row on a diagonal).
3. **Single piece**: one carousel, reel script, caption or bio on request.

## For every post

- **Type and colour** (ערך/Plaster, שיטה/Graphite, אוטוריטה/Porcelain, הנעה/Taupe).
- **Hook**: the on-tile headline, in Bellefair style: short, a contrast ("X במקום Y") or a plain claim. Max 8 words.
- **Carousel slides** when the format is a carousel: 4–7 slides, one idea per slide, last slide is the CTA.
- **Caption**: Hebrew, 3–6 short lines. First line repeats the hook. Plural "אתם" for readers. First person is fine for Moran's own experience.
- **CTA**: one. For ערך/שיטה: "שמרו" or a question. For אוטוריטה: none or "ספרו לי". For הנעה: "לשיחת אבחון ↓".
- **Hashtags**: 6–10, in Hebrew and English, no more.

## Voice guard

Use: שיטה, יסודות, אוטוריטה, תוכנית, מדידה, שקט, פניות.
Never: חשיפה, עוקבים, ויראלי, מבצע, חבילה, ניהול סושיאל, קסם, תוצאות מיידיות, "בקרוב".

Before launch (January 2027): never write "העסק נפתח בינואר" into the bio. The opening is a post, not a state.

## Case-study posts

When writing about a client (Chef Sagi: `clients/chef-sagi/`), use only numbers that appear in `tracking.md`, and remind Moran that the client approved publication. Structure: before, the four foundations applied, after, one lesson.

## Output

Write to `content/moran/YYYY-MM-DD.md` and publish an Artifact page in Hebrew that Moran can copy from on her phone. In the chat reply, list the posts in one line each; put everything else in the page.
