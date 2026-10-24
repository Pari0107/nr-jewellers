# N R Jewellers — design rules

Keep any future edit inside these rules.

- Colours come from Pari's NR logo: wine `#3a0914` (deep `#22040b`, soft `#5c1427`), gold `#b0812f`, light gold `#e2b65e`, shine `#fbe6b0`, ivory `#f8f2e8`. The only gradients are the moving wine silk behind the hero and the gold shimmer on the headline.
- Fonts: Cinzel (500/600) for the brand, h1 and h2; Cormorant Garamond (italic for taglines, 600 for item names); Jost (300/400) for body. Never Inter or system UI.
- No icons, emoji, star ratings or location eyebrow labels (Pari finds these look AI-made). Ornaments: twinkling four-point sparkles, small floating diamond photos (images/diamond.png) in the collections and story sections only, never the hero (the hero gets a necklace photo), and the scrolling gold collections band.
- Motion: staggered rise-in of the hero, scroll reveals (.rv), hover zoom plus a gold frame on tiles, and a sweep fill on buttons. All of it is off under prefers-reduced-motion.
- No shadows, rounded cards, glassmorphism or hover lifts. Use square corners and 1px gold hairlines.
- Buttons are square, either a solid navy or gold fill or a 1px outline, with uppercase text letter-spaced at .16em.
- Keep it to three sections below the header: hero (animated logo + "NR Jewellers" + necklace photo), collections band, collections, story + visit (wine). Each collection tile opens a modal gallery of 10-15 designs.
- Images are 1:1 for collections and 4:5 for the hero. Placeholders are flat tinted blocks with a caption.
- Copy comes from the shop: no "crafted with passion" filler, and no invented claims.

- Logo: images/logo/*.png are gold layers cut from the logo artwork. They are revealed in the order of the logo video (crown, ring, NR, ELEGANCE/STYLE, leaves, SINCE 2005), then glow softly.