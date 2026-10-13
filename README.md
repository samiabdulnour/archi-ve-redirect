# archi-ve.app → archipic.app

Archipic's website moved to **https://archipic.app** (source: the `docs/`
folder of [samiabdulnour/archipic](https://github.com/samiabdulnour/archipic)).

This repository only keeps the old address working. GitHub Pages serves it at
archi-ve.app, and every page forwards to the same page on archipic.app:
`support.html`, `privacy.html` and `press.html` explicitly (no JavaScript
needed, so link checkers follow them too), everything else through
`404.html`, which keeps the path.

Keep it as long as anything still links to archi-ve.app, including the App
Store listing's support and privacy URLs until they are updated.
