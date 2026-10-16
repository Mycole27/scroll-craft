# JAG Metal Studios: website

A one-page, scroll-driven site built with the scroll-craft engine. There is no
build step. It's plain HTML, CSS and JS.

## View it locally

```bash
node ../../plugins/nateherk-design/skills/scroll-craft/scripts/serve.mjs --root . --port 4500
# open http://localhost:4500
```

## Drop in real assets (no code changes needed)

| What | Where | Effect |
|---|---|---|
| Logo | `assets/brand/logo.svg` | Replaces the typeset "JAG Metal Studios" wordmark in the nav |
| Project photos | `assets/work/02.jpg` … `04.jpg` | Each finished photo wipes in over its sketch in **Selected work** |

Photo order: 02 gate, 03 balcony, 04 railing. (The staircase is told by the scroll film.) Use landscape
photos, about 2400px wide. To change the order or the captions, edit the four
`<figure class="frame">` blocks in `index.html`.

## The scroll film

`assets/film/drawing-to-stair.mp4` (desktop) and `-m.mp4` (phone) play forward
as the visitor scrolls, from drawing to finished staircase. They are encoded with
dense keyframes for smooth scrubbing. To replace the film, re-encode the new
clip with the skill's `scripts/encode.sh` and keep the same file names. The two
`.webp` files are the first and last frames: the first shows while the video
loads, and the last is used for visitors with reduced motion turned on.

## Placeholders to replace in `index.html`

- `hello@jagmetalstudios.com`: the contact link and `TO` in the form script.
- Phone number and city: add them in the `<address>` block.
- Project captions ("Project name · …").
- Brand name: the client said *JAG Metal Studios*, but the reference PDF says
  *JAG Ironworks*. Confirm which is right.

The form has no backend yet. It opens the visitor's email app with the inquiry
filled in. To collect submissions directly, point it at Formspree, Netlify
Forms or similar.

## Deploy

Upload the folder as-is to any static host (Netlify, Vercel, Cloudflare Pages,
GitHub Pages). `BRIEF.md` and `README.md` don't need to be uploaded.
