# Samsung AI Search prototype

A clickable prototype of a conversational AI search experience for samsung.com, built with the site's existing components.

Open it: https://panthshah.github.io/samsung-ai-search-prototype/

- `index.html` is the whole app. Answers are generated in the browser with BM25 retrieval over `data/kb.json`, a snapshot of samsung.com product pages, FAQs and support articles crawled in October 2026. Prices are snapshots.
- `data/accessories.json` holds official cases, screen protectors and S Pens.
- `img/` holds product images.

Samsung's own fonts (SamsungOne, Samsung Sharp Sans) are licensed and not included; the page falls back to Noto Sans and Outfit from Google Fonts. If you have the Samsung fonts installed locally they are used automatically.

This is a design prototype and is not affiliated with or endorsed by Samsung.
