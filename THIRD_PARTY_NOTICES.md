# Third-party notices

## DejaVu Sans (subset) - `package/res/statcollector_data/symbols.ttf`

Used only by the opt-in "Шрифт для символов" experiment of the in-game dashboard (`gf_font.js`, off by default).

- What it is: `symbols.ttf` is a subset of **DejaVu Sans 2.37** (16 symbol glyphs: U+2212, U+22EE, U+22EF, U+2501, U+2502, U+2504,
  U+250A, U+25AE, U+25B2, U+25B6, U+25BC, U+25C9, U+25CF, U+2605, U+2606, U+2715), made with `tools/make_symbols_font.py`. The glyph outlines are
  unchanged; hinting and every other glyph were dropped and the family was renamed to `SCSym`, as the licence requires for a modified font.
- Source: https://github.com/dejavu-fonts/dejavu-fonts (release `version_2_37`, `dejavu-fonts-ttf-2.37.zip`, `ttf/DejaVuSans.ttf`).
- Licence: the **Bitstream Vera Fonts licence** (Copyright (c) 2003 Bitstream, Inc.) together with the **Arev Fonts licence**
  (Copyright (c) 2006 Tavmjong Bah); the changes made by the DejaVu project are in the public domain. Free to use, copy, modify and
  redistribute (also as part of a larger package, but not sold by itself); the copyright and permission notice must stay with every copy;
  a modified font must not be named "Bitstream", "Vera", "Arev" or "Tavmjong Bah".
- The full licence text is shipped with the mod as `package/res/licenses/DejaVu-LICENSE.txt` and the notice is also kept inside the
  font file (name table ids 0, 13 and 14).

## Gameface library (OpenWG)

See `package/res/licenses/openwg-gameface.txt` (MIT).
