# maechanfarmstay.com

Private idea-sharing site for Farmstay MaeChan. Hosted on Cloudflare Pages, deployed from this repo on every commit.

- `public/` is the website (Cloudflare build output directory, no build command).
- The front page is intentionally blank. Pages live at random paths and are shared by link only.
- Every response carries `X-Robots-Tag: noindex` and `Referrer-Policy: no-referrer` (`public/_headers`), so search engines don't list it and shared links don't leak the path to other sites.
- Libraries are self-hosted in `public/lib/` (three.js r128, OrbitControls, JSZip 3.10.1).

| Page | Path |
| --- | --- |
| Guest building 3D model (view only: no variables panel, no model download) | `/zi41p7hovs/` |
| Brandon's Montreal apartment 3D model (family viewing) | `/v1tihck703/` |
