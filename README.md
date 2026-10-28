# hifzquran.org, forwarding to quranpages.org

Quran Pages moved its website to **quranpages.org** on 28 October 2026. This
tiny GitHub Pages site holds the old domain, hifzquran.org, and sends every
page to the same page there: the path, the query and the anchor are kept.

- `404.html` answers any address GitHub has no file for, so every old link
  lands on its page (hifzquran.org/privacy.html goes to
  quranpages.org/privacy.html).
- `index.html`, `privacy.html`, `support.html` and `terms.html` do the same,
  and also carry a refresh for browsers with no script, since the apps and
  the stores link to them.
- `CNAME` is hifzquran.org. The site itself lives in `hifzquran-site`, whose
  `CNAME` is quranpages.org.

The iOS and Android apps up to 4.0 link to hifzquran.org/privacy.html and put
hifzquran.org in the share message, so keep the domain renewed and this repo
in place for good.
