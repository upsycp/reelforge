# ReelForge pitch deck

A self-contained animated deck: one `index.html`, local fonts, no build step and no external requests.

## Deploy to Vercel

**Easiest (no terminal):**
1. Go to vercel.com/new and choose to deploy without Git, or drag this whole folder onto the Vercel dashboard.
2. Framework preset: **Other**. Leave the build command and output directory empty.
3. Deploy. You get a `*.vercel.app` link you can share.

**With the CLI:**
```
npm i -g vercel
cd reelforge-site
vercel --prod
```

**From GitHub:** push this folder to a repo, import it at vercel.com/new, preset **Other**, deploy. Every push redeploys.

## Presenting

- Arrow keys, space, click, scroll or swipe to move between slides.
- The corner button goes full screen.
- Link straight to a slide with `#4` (slide 4) on the end of the URL.

## Editing

All copy lives in `index.html`. Search for the placeholder boxes (`class="ph"`) to fill in:
- Slide 5: TVF stats
- Slide 11: pilot numbers (and sample clips)
- Slide 12: work email and phone

`og-image.png` is the preview image shown when the link is shared.
