# Qatar Business Website Concepts

Three independent, unsolicited website concepts for Qatar local businesses. This is a separate repository from iVoices. These are NOT the businesses' official sites.

## Live GitHub Pages links
- Panda Food Centre — https://carthagedoha-cmd.github.io/qatar-business-website-concepts/panda-food-centre/
- Trim Time Salon — https://carthagedoha-cmd.github.io/qatar-business-website-concepts/trim-time-salon/
- Concept Garage — https://carthagedoha-cmd.github.io/qatar-business-website-concepts/concept-garage/

Each has five pages: Home, Services, More (Offers / Lookbook / Process), About, Contact. English/Arabic switching is built in. Images are illustrative examples rather than actual store interiors, employees or completed projects.

## Design system (2026 update)
- Panda: fresh editorial retail, oversized serif typography, vibrant produce photography, asymmetric category cards, warm natural colour, animated moving keywords.
- Trim Time: cinematic dark barber aesthetic, muted bronze and warm tones, large editorial headings, image focus, restrained transitions.
- Concept Garage: industrial charcoal and orange, compressed display typography, dynamic workshop imagery, geometric CTAs and technical details.
- Interactions: composited entrance animations, scroll-reveal, image hover scaling, progress indicator and navigation microinteractions. All respect reduced-motion settings; no autoplay video, WebGL or paid animation libraries.
- Static site and contact links remain the priority; no fabricated operating hours, prices, promotions or online booking.

## Buyer-only administration — sale and handover policy
**There is NO buyer sign-in on any preview site.** The demo repository intentionally has no live Pages CMS configuration. Buyers must NOT be invited as collaborators to this shared repository: it contains three independent prospect websites.

Once a specific buyer accepts the QAR 5,000 ownership offer:
1. Confirm exactly which website has been purchased and agree payment, scope, delivery and support terms.
2. Package ONLY the purchased site's folder, its corresponding JSON content file, the shared static site assets, and the site-specific CMS configuration template. Do not copy other clients' content.
3. Create a new **individual** repository under the buyer's own GitHub account, or explicitly transfer the newly isolated repository to the buyer. The buyer must approve or accept control of their own account.
4. Configure Pages CMS using ONLY `.pages.yml` for that buyer, derived from the corresponding file in `handover/<site>.pages.yml`. The buyer authorizes Pages CMS GitHub App for **that repository only**; the preview site needs no CMS login.
5. Buyer signs in to https://app.pagescms.org/ using their own GitHub account and can edit text, photographs, services, offers and business information. Commits trigger publishing when the hosting source has been configured.
6. Transfer/verify buyer-only repository ownership, and remove seller access after acceptance. The seller does not keep an admin account or shared password.
7. Configure hosting and a buyer-controlled domain separately according to the agreed contract. GitHub Pages may be appropriate as a demo; confirm production hosting and terms for a commercial site.

No step requires the seller to sign into Pages CMS now. No buyer can receive exclusive administrative rights while their site remains in the current shared demo repository.

**For major redesigns:** the editor manages content, images and colours; changes to structural templates require modifying shared site code (or its isolated copy after sale).

## Commercial offer
One-time website ownership price: **QAR 5,000 per business**. Domain, hosting and future maintenance are separate unless expressly agreed. Contact: website.business.qatar@gmail.com · +974 3332 4228.

All prices, stock, business details, promotions, service scopes, photographs and hours must be approved by the business before official launch. The preview is not affiliated with or endorsed by the listed businesses. Do not use photos of staff, inventory or property without permission.

## Technical layout
- `content/*.json` — structured editable content for preview sites
- `assets/site.js` — shared client renderer, keyboard menu, language switching and motion enhancements
- `assets/style.css` — responsive themes and animations
- `<business>/index.html`, `services.html`, `features.html`, `about.html`, `contact.html` — static entrypoints
- `handover/<business>.pages.yml` — buyer-specific Pages CMS configuration templates; not enabled on previews
- `admin/index.html` — handover policy information, NOT an active login page

Hosted for public demonstration through GitHub Pages, source `main` branch, path `/`. The sites are static and do not collect payment information or send form submissions. The seller may continue to use these previews for sales until each business agrees on the final handover.


## Apple-inspired visual standard (23 November 2026)
All three live concept sites use a shared premium design language informed by Apple's current public website: system UI typography (no redistributed Apple fonts), generous neutral surfaces, 16:9 cinematic imagery on desktop and portrait crops on mobile, minimal rounded blue CTAs, restrained scroll reveals, and dark/light full-width sections. Business identity and text remain independent, not Apple-affiliated. Never use Apple's name, logo, photography, fonts or site code in client sites. The JavaScript renderer supports optional owner-licensed `hero_video` and `feature_video` MP4 URLs per individual JSON file with muted inline playback, a pause button and reduced-motion/data-saver fallback. The preview sites use clearly labelled illustrative Pexels video clips from the specific sources documented in each content JSON. These clips are NOT footage of the listed businesses; replace with buyer-approved original footage before official launch. They are hosted by Pexels rather than packaged into the GitHub repository, so playback depends on Pexels availability; the page shows a still poster if the stream cannot load. Respect reduced-motion and data-saver settings. Buyer-only administrative rights and future standalone-repository handover are unchanged.
