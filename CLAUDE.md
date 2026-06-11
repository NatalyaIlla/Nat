# Claude Instructions

## Blog Post & Page Optimization Workflow

Apply this checklist every time you work on a blog post or page — including any SEO, content, or optimization tasks.

---

### H1 Tag

- Every post/page must have exactly ONE H1 tag
- If the title (post/page title) already acts as the H1, do NOT add another H1
- Never duplicate H1

---

### Content Rules

- Do NOT delete or change existing content
- Do NOT add or write additional content unless there is a significant grammatical error
- NEVER use dashes (em dash, en dash, hyphen in written prose) — signals AI-written text
- Never use any other signals that it was AI written
- Always use only one space between words

---

### Headings

- All main section titles should be H2 tags
- Remove dots/periods from the end of any headings (H1, H2, H3, etc.)

---

### Readability & Formatting

- Use lots of bullet points or numbered lists
- Break content into lots of short paragraphs for easy reading and flow

---

### Table of Contents

- Add a Table of Contents near the top of every post
- Link each item to its corresponding H2 section using anchor IDs
- Helps Google understand structure and can earn sitelinks in search results

---

### E-E-A-T Signals (Trust & Expertise)

- Add an author byline at the top of every post (name + credentials/experience)
- Add an author bio block at the bottom of every post
- Mention the business name, location, and relevant experience within the content
- These signals directly affect how Google rates content quality and trustworthiness

---

### Links

- Add internal links pointing to existing blogs or pages on the same site
- Bold all internal links with `<strong>` — body text only, never inside headings
- Add external links to authoritative sources
- Bold all external links with `<strong>` — body text only, never inside headings
- All external links must open in a new tab — use `target="_blank" rel="noopener noreferrer"`
- Verify every external link returns 200 before adding (no 4xx/5xx)
- After publishing, add internal links TO the new post from 2 to 3 existing older posts

---

### Media

- Add images from the site media library (never external URLs)
- Add proper alt text to all images (include keyword where natural)
- Do NOT add captions — use plain `<img>` tags only, no `<figure>` or `<figcaption>` wrappers
- Content image width: 600px max for blog posts with sidebars — always set `width="600"` and `style="height:auto;max-width:100%;"`
- Never add an image without a width attribute — renders at full natural size
- Add video embeds (YouTube embedded code) where relevant — if unsure which video to use, suggest the best options to the user
- Set a featured image for every post (used in schema, social sharing, and Google Discover)

---

### Post Settings

- Set a clean, keyword-rich slug (e.g. `/countertop-cost-charleston-sc/` not `/how-much-do-countertops-cost-in-charleston/`)
- Fill in the excerpt field — this is used as the schema description
- Close comments (disable discussion)

---

### Sitemap

- Update the sitemap on the site so Google picks it up faster on its next crawl

---

### WordPress SEO & Schema

#### Schema Markup (High Priority)

Schema is critical for ranking on Google, ChatGPT, Perplexity, Gemini, Copilot, and all AI platforms.

**FAQPage Schema (Mandatory on Every Post)**

- Add FAQPage schema to every post — this is the #1 signal AI platforms use for Q&A content
- Use existing FAQ sections, Q&A sections, or "questions to ask" sections in the post
- FAQPage drives Google featured snippets, voice search, and AI platform pickup
- Never publish a post without FAQPage schema

**BlogPosting Schema**

- Include: headline, datePublished, dateModified, author, image, description, publisher
- If a WP SEO Structured Data Schema plugin is available: enable it and fill in all BlogPosting fields
- If the plugin is NOT available: add BlogPosting schema as a script tag in the post content

**LocalBusiness Schema**

- Add LocalBusiness schema on every post for local SEO signal
- Include: business name, address, phone, geo coordinates, URL

**BreadcrumbList Schema**

- Add BreadcrumbList schema to help Google understand site structure
- Do NOT add BreadcrumbList if Yoast SEO is active and already generates it (causes duplicate critical error)

**WP SEO Structured Data Schema Plugin**

- If the plugin is available: enable it and fill in all necessary fields
- Look for the Blog Posting option and complete all fields
- If the plugin is NOT available: suggest the best schema markup to rank the blog for both search engines and AI platforms

#### Yoast SEO

- Set Focus Keyphrase — primary target keyword for the post
- Set SEO Title — keyword-optimized, under 60 characters
- Set Meta Description — 120 to 156 characters, includes primary keyword, no phone number
- Enable Cornerstone Content toggle (should be ON for important posts)
- Under Discussion: uncheck "Allow Comments"

#### Categories & Tags

- Choose proper, relevant categories and tags for each post

---

### AI Platform Optimization

- FAQPage schema is the #1 signal AI platforms (ChatGPT, Perplexity, Gemini, Copilot) use for Q&A content
- Write clear, definitive answers — AI platforms prefer direct answers over vague content
- Mention the business entity consistently throughout the post (name, location, services)
- Use structured H2/H3 headings so AI can parse the content clearly

---

### After Publishing Checklist

1. Submit the specific post URL to Google Search Console (do not just ping the sitemap)
2. Submit the sitemap to Bing Webmaster Tools — critical for ChatGPT, Copilot, and Perplexity visibility
3. Create a Google Business Profile post for every new blog post published
4. Clear the site cache (WP Rocket or equivalent)
5. Add internal links TO the new post from 2 to 3 existing older posts on the same site

---

### SEO Optimization (Priority)

- Optimizing for search engine rankings is the primary goal for every post/page
- Apply all on-page SEO best practices
- Make any additional suggestions needed to help the site rank as well as possible

---

### Code Style

- No trailing whitespace on any line
- Use consistent 2-space indentation in JSON and HTML

---

### End of Workflow

After completing the checklist, summarize:

1. What was done
2. Any issues found
3. Additional recommendations to improve rankings
