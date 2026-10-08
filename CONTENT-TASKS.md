# Content Update Tasks

A checklist of written-content updates needed to replace the placeholder (lorem ipsum) text throughout the site. Config files, images, videos, and HTML/CSS/JS are out of scope.

## Homepage — `src/content/homepage/-index.md`
- [x] **Banner**: Replace lorem-ipsum `content` paragraph with real intro copy; review `title` ("Let us solve your critical website development challenges") and button label.
- [x] **Feature section**: Rewrite title ("Something You Need To Know") and the six lorem-ipsum feature descriptions (Clean Code, Object Oriented, 24h Service, Value for Money, Faster Response, Cloud Support); rename features if they don't match the actual offering.
- [x] **Services section**: Replace the four service titles (currently generic "digital marketing / cyber security" boilerplate), their lorem-ipsum bodies, and CTA button labels ("Check it out").
- [x] **Workflow section**: Review title ("Experience the best workflow with us") and fill in the empty `description`; add step-by-step workflow copy if supported.
- [x] **Call to Action**: Replace lorem-ipsum body under "Ready to get started?" and confirm button label/link text.
- [x] Set a proper SEO meta description for the homepage front matter (if present).

## Blog — `src/content/blog/`
- [x] **Index (`-index.md`)**: Replace "this is meta description"; consider a better heading than "Latest news".
- [x] **blog-1.md** ("What you need to know about Photography"): Write a real article or repurpose/remove; fix lorem-ipsum body and placeholder description.
- [x] **blog-2.md** ("How to make toys from old Olarpaper"): Same as above — real content or delete.
- [x] **blog-3.md**: Duplicate title of blog-1 — needs a unique title and real content.
- [x] **blog-4.md**: Duplicate title of blog-2 — needs a unique title and real content.
- [x] **blog-5.md** ("Adversus is a web-based dialer…"): Placeholder post — rewrite or remove.
- [x] For every retained post: write a real meta `description`, accurate `date`, relevant tags/categories (if used), and meaningful section headings instead of "Creative Design" filler.
- [x] Add genuine articles for the site's actual topics.

## Pricing — `src/content/pricing/-index.md`
- [x] Replace meta description ("meta description").
- [x] **Plans**: Rewrite plan names/subtitles (Basic / Professional / Business), confirm prices ($49/$69/$99) and billing type, and replace generic feature lists ("Express Service", "Customs Clearance"…) with real per-plan features.
- [x] **Plan buttons**: Update labels ("Get started for free", etc.) and links if checkout URLs exist.
- [x] **Call to action**: Replace lorem-ipsum body under "Need a larger plan?".

## Contact — `src/content/contact/-index.md`
- [x] Replace meta description.
- [x] Rewrite "Why you should contact us!" description (currently lorem ipsum).
- [x] Update contact details: phone (+88 125 256 452), email (info@bigspring.com), address (360 Main rd, Rio, Brazil) with real business info.
- [x] Review form field labels/validation messages (text strings only).

## FAQ — `src/content/faq/-index.md`
- [x] Replace meta description.
- [x] Rewrite all six lorem-ipsum answers (free updates, student/non-profit discounts, custom work, documentation/support, refunds, product key) with accurate policy information.
- [x] Review questions — keep/add/remove so they reflect real customer questions.
- [x] Replace dummy `https://www.example.com` links inside answers with real destinations (or remove).

## Static Pages — `src/content/pages/`
- [x] **privacy-policy.md**: Replace all lorem-ipsum sections (Responsibility of Contributors, Gathering of Personal Information, Protection of Personal Information, etc.) with a real privacy policy; set proper title/meta description.
- [x] **terms-conditions.md**: Same treatment — real terms text, proper meta fields.
- [x] **elements.mdx**: Component showcase page — either update its sample prose or mark it as dev-only/remove before launch.

## Global / Cross-content
- [x] Search all content files for remaining "Lorem ipsum" and "example.com" occurrences and clear them (`grep -ri "lorem ipsum" src/content`).
- [x] Ensure every page/post has a unique, meaningful meta `description` (no "this is meta description"/"meta description" placeholders).
- [x] Verify internal links referenced in content (e.g., `/contact`) point to pages that will exist with final content.
- [x] Proofread tone/voice consistency across homepage, pricing, FAQ, and legal pages.
