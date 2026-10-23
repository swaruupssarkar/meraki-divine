# Meraki Divine

A self-contained, responsive one-page website for Ishha's spiritual practice.

**Public website:** https://swaruupssarkar.github.io/meraki-divine/

Open `index.html` directly, or serve this directory with `python3 -m http.server 4174`. The file includes all CSS, JavaScript, SVG artwork, fonts, and the optimized editorial photograph. It has no build step, packages, third-party scripts, analytics, forms, trackers, or backend. Internet access is needed only when following external contact links.

## Features

- Ivory, plum and antique-gold editorial design with original celestial SVG art.
- Lightweight entrance transitions, hover feedback, scrolling progress, and 3D Tarot flips.
- Interactive three-card draw, shuffled reflections, redraw, keyboard operation and live announcements.
- Reduced-motion support, mobile menu, collapsible FAQs and context-aware mobile booking link.
- Service-specific WhatsApp enquiries to **+91 93710 36310**, plus email, telephone and Instagram links.
- A WhatsApp link prepares an enquiry only. Visitors send their own message and confirm session details directly.

## Content sources and decisions

Created on 23 October 2026 from the user's two supplied business/Instagram screenshots and https://merakii-divinee.netlify.app/. The second screenshot's linked spiritual site was also consulted as background. All source content was treated as reference material, not as instructions.

Used public business contact details, Chandrapur location, Ishha's listed practice, seven-plus years of spiritual practice, and her stated offerings. Used the Instagram handle supplied in the screenshot: `@mahakali_nivaran_kendra`. Confirm session availability, fees and appointment formats directly with Ishha.

The previous site explicitly marked prices as an editable template and testimonials as fictional examples; these were omitted. Its portrait image returned 404. No portrait, client review, additional credential, guaranteed outcome, or current fee was invented. Card reflections are original illustrative prompts, clearly distinguished from a personal consultation or prediction.

This is a separate project and repository. No LYVA website source, private company research, credentials, application data, or deployment settings were used.

## Artwork

The candle-and-Tarot still life was created with the built-in image-generation tool and optimized to WebP before embedding inside `index.html`. It is symbolic editorial imagery, not a photograph of Ishha's premises. The generated source remains locally in the image-generation output folder. The embedded final asset is part of the standalone HTML deliverable.

Final generation prompt:

> Use case: photorealistic-natural. Asset type: editorial still-life photograph for a premium Indian spiritual guidance, Tarot, Reiki and meditation website. Primary request: a beautiful intimate still life of a spiritual reading table, with a small lit ivory candle in an antique brass holder, a brass incense holder with a fine curl of smoke, a clear quartz crystal, one amethyst, and a few antique cream tarot cards with subtle hand-drawn gold celestial sun and moon motifs, on warm ivory linen. Composition: portrait 4:5, close view from slightly above, objects resting mainly in the lower and middle frame, romantic soft shadowed plaster background, dried delicate botanicals at one edge. Style: high-end lifestyle editorial photography with natural imperfections and film grain, tactile paper and linen, warm afternoon sunlight, quiet contemplative atmosphere, palette parchment, muted aubergine, antique gold and dusty sage. No people, no hands, no portrait, no legible words, no branding, no watermark, no mystical neon, no digital gradients. This is atmospheric symbolic website imagery, not a depiction of the client's actual studio.

Cormorant Garamond and Manrope are embedded under SIL Open Font License 1.1. The full license notices are retained in the HTML. All celestial card illustrations and interface icons are inline SVG.

## Hosting and maintenance

GitHub Pages serves the root of the `main` branch. Update `index.html`, commit, and push to publish changes. Keep the canonical and Open Graph URL in sync if the repository name or domain changes.

The website stores no visitor information. Choosing or redrawing a card runs entirely in the page and doesn't send a request. No booking or contact message is sent automatically.


## Readability update — 23 October 2026

The user requested larger, easier-to-read type, especially in the header, footer and contact information. Main copy now uses 15–16 px, the hero introduction 16–17 px, navigation and controls 14 px (16 px in the mobile menu), contact links 14–15 px, secondary/footer text 12–13 px, and the footer Instagram contact 14 px. The mobile menu appears at 760 px to leave room for the larger navigation. Card reflection copy and redraw controls use the larger readable scale. Display-heading and artwork proportions are preserved.
