# The Whistle: homepage mockup

A proposed homepage for [thewhistle.news](https://www.thewhistle.news), built for 4 to about 10 stories. It is a mockup for review, not the live site.

**See it:** https://muimran.github.io/whistle-homepage-mockup/

The top (the menu and the big logo block) and the bottom (the "তথ্য দিন" box and the footer) are the site's own, unchanged. Only the part between them is new.

## What changes

1. **One lead story, shown big.** It is the newest story by default, and editors can pin a different story there instead.
2. **Video gets its own dark band** straight after the lead, so new stories never push it down. With more videos: one big, the rest in a small row.
3. **Every other story is the same small card:** picture, label, headline, one-line summary, date. Three per row on desktop (two today, because there are only two), a compact list on phones.
4. **Labels in the red from the logo.** Headlines keep the live site's grey (#939393).

Past about 10 stories, the grid stops at 9 cards and a "সব প্রতিবেদন" link goes to an archive page.

## Files

- `index.html`: the whole page. The new part's CSS is in its `<style>` block, and every class starts with `hp-`, so it won't clash with the site's CSS.
- `images/`: the site's own pictures, resized for the web.
