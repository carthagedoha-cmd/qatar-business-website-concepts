# Qatar Business Website Concepts

Independent, unsolicited concept websites for three Qatar businesses. Not official company sites. No use of the iVoices repository.

## Live preview URLs (once GitHub Pages deployment completes)
- https://carthagedoha-cmd.github.io/qatar-business-website-concepts/panda-food-centre/
- https://carthagedoha-cmd.github.io/qatar-business-website-concepts/trim-time-salon/
- https://carthagedoha-cmd.github.io/qatar-business-website-concepts/concept-garage/

Each business has five standalone pages: Home, Services, More (Offers / Lookbook / Process), About, Contact.

## Secure admin editing — no programming
1. Open https://app.pagescms.org/ and **Sign in with GitHub**.
2. Install the Pages CMS GitHub App, selecting ONLY repository `carthagedoha-cmd/qatar-business-website-concepts`.
3. In Pages CMS, select this repository.
4. Choose one of the three business entries and change text in English/Arabic, photos, service descriptions, opening details, logo-style branding colours, telephone, or Google Maps link.
5. **Save / Commit**. GitHub Pages republishes changed content automatically from the main branch; public-site updates may take a few minutes. The CMS's save action commits to GitHub. The public demo does not contain a username/password form.
6. Your admin shortcut is `https://carthagedoha-cmd.github.io/qatar-business-website-concepts/admin/`.

Important: Pages CMS needs the account owner to authorize the app once. This cannot be done via a generated password. Store only public business data in this public repository.

Major design layout changes may require updating `assets/site.js` or `assets/style.css`; these are shared across all concepts, so validate the three sites before publishing structural changes.

All photography currently uses illustrative third-party stock image URLs, not owner photos. Replace with store-approved images once available. All displayed business data, products, offers and services require owner verification before official use. No fake offers or confirmed booking system.

Price to offer each business for ownership: **QAR 5,000** one time. Hosting, custom domain and ongoing maintenance are outside that fee unless separately agreed. Contact for owners: website.business.qatar@gmail.com / +974 3332 4228.

## Hosting
GitHub Pages, source branch `main`, source `/`. This repo contains only static demonstration websites. They do not collect payments or visitor information.

## Individual files
- `content/*.json`: editable business content and images, managed by Pages CMS.
- `.pages.yml`: CMS fields and media storage.
- `assets/site.js`: shared front-end renderer.
- `assets/style.css`: responsive styles.
- `*/index.html` and companion pages: business page entrypoints.
