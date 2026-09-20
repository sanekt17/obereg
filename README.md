# Landing page — sanekt17.github.io/obereg

Upload the CONTENTS of this folder to the root of the `obereg` GitHub Pages repo (next to the existing
privacy.html — the copy here is identical, overwriting it is fine):

    index.html      the page (RU/HE/EN switch, remembers the choice, picks the browser language first time)
    img/            icon, 9 phone screenshots (3 per language), 3 video posters   (~1 MB)
    video/          the three 60-s tour videos                                     (~25 MB — fine for GitHub Pages)
    privacy.html    unchanged

Then open https://sanekt17.github.io/obereg/ — GitHub Pages updates within a minute or two.

## Three things to fill in later (edit index.html, search for "CONFIG")

1. `PLAY_URL` — paste the Play link on production day. The grey "Coming soon" button becomes a purple
   "Get it on Google Play" button and the "closed testing" note disappears. Nothing else to change.
2. `YT` — after uploading the videos to YouTube, paste the three video IDs (the part after `v=`). The page
   then embeds YouTube instead of the local files (saves bandwidth, counts as YouTube views). Optional.
3. `FORM_ID` — the "tell me when it's out" form posts to Formspree (free, 50 submissions/month):
   formspree.io → New form → email obereg.support@gmail.com → copy the ID from the form URL
   (`https://formspree.io/f/xxxxxxxx`) and replace `FORM_ID`. Until then the button just shows a Formspree
   error page, so do this before sharing the link.

Per-channel tracking (docs/32 §D): share the page as `https://sanekt17.github.io/obereg/?src=telegram`
etc. — Formspree stores the referrer, and on launch day the Play button can carry the same `src` as a
`referrer=` UTM.
