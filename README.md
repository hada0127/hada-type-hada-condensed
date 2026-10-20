# 하다 콘덴스드 · Hada Condensed — Hada Type

하다 콘덴스드 무료 한글 폰트 — 미리보기·다운로드: https://hada-type.com/hada-condensed

Hada Condensed, a free Korean font by Hada Type — previews and downloads: https://hada-type.com/hada-condensed

This repository holds the published webfont files of Hada Condensed only.
The source build repository is private; load these files through
jsDelivr's GitHub CDN endpoint and keep the version pinned.

## CDN

Whole files — one WOFF2 per weight/style:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type-hada-condensed@v2026.10.21/css/hada-condensed.css">
```

Sliced — the same faces cut into unicode-range pieces, so the browser
downloads only the pieces the page's text uses:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type-hada-condensed@v2026.10.21/css/hada-condensed-subset.css">
```

Without the `@v2026.10.21` tag the URL follows the latest release
(`https://cdn.jsdelivr.net/gh/hada0127/hada-type-hada-condensed/css/hada-condensed.css`). Pin the tag in production.

Direct WOFF2 example:

```css
@font-face {
  font-family: "Hada Condensed";
  src: url("https://cdn.jsdelivr.net/gh/hada0127/hada-type-hada-condensed@v2026.10.21/woff2/HadaCondensed-Light.woff2") format("woff2");
  font-weight: 300;
  font-style: normal;
  font-display: swap;
}
```

## Files

- `css/hada-condensed.css` — whole-file stylesheet (`woff2/`)
- `css/hada-condensed-subset.css` — sliced stylesheet (`woff2-subset/`)
- `woff2-subset/manifest.json` — slice list with codepoints and SHA-256

## Packages

TTF, OTF, WOFF2 and sliced WOFF2 ZIPs are attached to the GitHub release:

[HadaCondensed-TTF.zip](https://github.com/hada0127/hada-type-hada-condensed/releases/download/v2026.10.21/HadaCondensed-TTF.zip) · [HadaCondensed-OTF.zip](https://github.com/hada0127/hada-type-hada-condensed/releases/download/v2026.10.21/HadaCondensed-OTF.zip) · [HadaCondensed-WOFF2.zip](https://github.com/hada0127/hada-type-hada-condensed/releases/download/v2026.10.21/HadaCondensed-WOFF2.zip) · [HadaCondensed-WOFF2-Subset.zip](https://github.com/hada0127/hada-type-hada-condensed/releases/download/v2026.10.21/HadaCondensed-WOFF2-Subset.zip)

Each ZIP includes `WEBFONT-USAGE.txt`, `LICENSE.txt` and `COPYRIGHT.txt`.
The WOFF2 ZIP also includes `WEBFONT.css` for self-hosted use; the sliced
ZIP carries `woff2-subset/` with `WEBFONT-SUBSET.css` (relative URLs).

## Other Hada Type families

- 하다 산스 · Hada Sans — https://github.com/hada0127/hada-type-hada-sans
- 하다 바탕 · Hada Batang — https://github.com/hada0127/hada-type-hada-batang
- 하다 모노 · Hada Mono — https://github.com/hada0127/hada-type-hada-mono
- 하다 라운드 · Hada Round — https://github.com/hada0127/hada-type-hada-round
- 춤추는사람들 · Dancing Peoples — https://github.com/hada0127/hada-type-dancing-peoples
- 춤추는사람들 고정폭 · Dancing Peoples Mono — https://github.com/hada0127/hada-type-dancing-peoples-mono
- 레벨업 · LevelUp — https://github.com/hada0127/hada-type-levelup

## License

The fonts are distributed under the SIL Open Font License 1.1.
