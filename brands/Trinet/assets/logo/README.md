# Logo assets

All files here are raster (PNG/GIF) exports from the current brand kit — **there is no SVG source in this set**. Treat these as the working files until vector masters are sourced; see "Gaps" below before using any of these at large scale.

## Files

| File | Size | What it is |
|---|---|---|
| `JMS_logo_cropped.png` | 1000×1001, transparent | The mark ("JM" in black + splash-gradient "S"), tight-cropped, near-square canvas. **Use this as the default mark file.** |
| `JMS_logo_splatter.png` | 1651×1275, transparent | Same mark, larger canvas with more surrounding whitespace/splash spread. Use when you need extra breathing room baked into the file itself (e.g. dropping straight into a layout without building clearspace yourself). |
| `JMS_logo_splatter_cropped.png` | 582×416, transparent | Same mark again, small and tightly cropped. Lowest resolution of the three — don't scale this one up. |
| `JMS_wordmark_Black.png` | 1153×112, transparent | "John McNeil Studio" wordmark, black text — for light backgrounds. |
| `JMS_wordmark_White.png` | 1153×112, transparent | Same wordmark, white text — for dark/midnight backgrounds (the default use case per `brand-elements.md`). |
| `JMS_Signature_Look10_GIF_Signature.gif` | 450×310, transparent, 22 frames | Animated build-on of the mark — the splash assembles itself onto the black "JM" lockup. For video/motion or web-hero use. |

## What's NOT here (gaps to flag before this kit is treated as complete)

- **No monochrome mark.** The mark only exists in its full-color gradient form. If you need the mark in solid white or solid black (e.g. single-color print, embossing, watermark use), it doesn't exist yet and needs to be produced.
- **No combined lockup file.** Mark and wordmark are separate assets — there's no single file with both pre-composed at a fixed relationship. If mark+wordmark need to appear together, that spacing is being built by hand each time rather than pulled from a locked asset, which is a real inconsistency risk.
- **No vector (SVG/EPS) source.** Everything here is raster, and the largest version (`JMS_logo_splatter.png`) tops out at 1651px wide. Fine for web and slides; too low-res for large-format print (banners, environmental, step-and-repeat) — get the vector master from whoever holds the original files before any print use beyond letter/A4 scale.
- **No favicon-specific export.** Nothing here is optimized/simplified for a 16–32px favicon context — `JMS_logo_cropped.png` will likely need a simplified redraw at that size, not just a scale-down.

## Usage rules

Clearspace, minimum size, and when to use mark vs. wordmark live in `../../brand/brand-elements.md` §5 — this file just documents what's physically in the folder.
