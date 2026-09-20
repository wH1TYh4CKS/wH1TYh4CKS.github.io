# wH1TYh4CKS.github.io

Personal site, served by GitHub Pages at <https://wH1TYh4CKS.github.io>.

Two files: `index.html` and `fonts.css`. No build step, no framework, and **no
external requests** — Plus Jakarta Sans and Space Mono are embedded in
`fonts.css` as data URIs, and the favicon is an inline SVG. Nothing is fetched
from a CDN.

Design system is "Lilac Terminal": violet on near-white, inverted for dark mode,
2–4px radii, mono labels on wide tracking. Colour tokens live on `:root` in
`index.html`, with a `prefers-color-scheme` block and a `[data-theme]` override.

Motion is opt-out: sections reveal on scroll through an IntersectionObserver and
the recall bar fills when it enters view, all disabled under
`prefers-reduced-motion`.

Edit `index.html`, push to `main`, done.
