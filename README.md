# twf-anim

Motion for The Working Files (listing + article) on seedtoscale.com.

Served to the live pages over GitHub Pages so the script does not depend on any
developer machine being awake. Paste ONE tag into each page's settings, before
`</body>`, as a new block at the end — do not reorder the existing blocks.

Depends on gsap + ScrollTrigger, which the site already loads on every page, and
pulls Webflow's own SplitText build on demand. Adds no libraries.

Degrades safely: start states live in JS, never CSS, so if this file fails to load
the pages render fully visible and static rather than blank.
