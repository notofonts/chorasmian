## FontBakery report

fontbakery version: 0.10.4

<details><summary><b>[1] Experimental checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| br_Latn (Breton) | Some base glyphs were missing: CʼH, cʼh |
|  ^  | Shaper produced a .notdef |
| haw_Latn (Hawaiian) | Some base glyphs were missing: ʻ |
|  ^  | Shaper produced a .notdef |
| mh_Latn (Marshallese) | Some base glyphs were missing: Ḷ, ḷ, Ṃ, ṃ, Ṇ, ṇ, Ọ, ọ |
|  ^  | Some mark glyphs were missing: ◌̣ |
|  ^  | Shaper produced a .notdef |
| qu_Latn (Quechua) | Some base glyphs were missing: CHʼ, Kʼ, Pʼ, Qʼ, Tʼ, chʼ, kʼ, pʼ, qʼ, tʼ |
|  ^  | Shaper produced a .notdef |
| scn_Latn (Sicilian) | Some base glyphs were missing: Ḍ, ḍ |
|  ^  | Shaper produced a .notdef |
| teo_Latn (Teso) | Some base glyphs were missing: Ɔ, Ɛ, Ɨ, Ʉ, ɔ, ɛ, ɨ, ʉ, ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ |
|  ^  | Shaper produced a .notdef |

 [code: failed-language-shaping]
* ⚠ **WARN** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| lg_Latn (Ganda) | No variant glyphs were found for Eng |
| dyo_Latn (Jola-Fonyi) | No variant glyphs were found for Eng |
| ny_Latn (Nyanja) | No variant glyphs were found for Eng |
| wo_Latn (Wolof) | No variant glyphs were found for Eng |

 [code: warning-language-shaping]
</div></details><br></div></details><details><summary><b>[15] NotoSansChorasmian-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.0030059814453125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Glyph "Aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Dcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Tcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acutecomb" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0306" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030C" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0327" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0302" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0308" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0307" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gravecomb" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030B" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0328" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030A" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "tildecomb" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** No dotted circle glyph present and font uses a complex shaper [code: missing-dotted-circle-complex]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, syriac, tai-le, canadian-aboriginal, math, old-permic, tifinagh, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: psalter-pahlavi, tai-le, thaana, duployan, chakma, pahawh-hmong, kayah-li, gurmukhi, hanifi-rohingya, limbu, balinese, new-tai-lue, siddham, sundanese, tai-tham, grantha, tai-viet, yi, telugu, khudawadi, sharada, buhid, lepcha, malayalam, tagbanwa, mahajani, thai, hatran, mandaic, khmer, bengali, gujarati, phags-pa, buginese, cham, brahmi, manichaean, avestan, oriya, sogdian, tagalog, tibetan, gunjala-gondi, devanagari, saurashtra, syloti-nagri, hanunoo, meetei-mayek, modi, mongolian, newa, syriac, dogra, myanmar, khojki, takri, tirhuta, tamil, rejang, batak, kharoshthi, nko, sinhala, kannada, tifinagh, javanese, warang-citi, kaithi

Or you can add the above codepoints to one of the subsets supported by the font: `chorasmian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- tawchor.left + alephchor.left.cv01

	- alephchor.left.cv01 + kaphchor

	- kaphchor + reshchor

	- tawchor.middle + alephchor.left.cv01 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
tawchor.left_alephchor.left.cv01.liga and tawchor.middle_alephchor.left.cv01.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- sevenchor
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* three (U+0033): X=137.0,Y=-1.5 (should be at baseline 0?)

	* six (U+0036): X=470.0,Y=715.0 (should be at cap-height 714?)

	* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

	* G (U+0047): X=537.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=544.5,Y=713.0 (should be at cap-height 714?)

	* S (U+0053): X=136.0,Y=-1.0 (should be at baseline 0?)

	* S (U+0053): X=396.0,Y=713.0 (should be at cap-height 714?)

	* e (U+0065): X=408.0,Y=-1.5 (should be at baseline 0?)

	* s (U+0073): X=123.5,Y=-1.0 (should be at baseline 0?)

	* w (U+0077): X=258.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=158.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=626.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=523.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=217.0,Y=-2.0 (should be at baseline 0?)

	* braceleft (U+007B): X=150.0,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=488.5,Y=713.0 (should be at cap-height 714?)

	* germandbls (U+00DF): X=317.0,Y=-1.0 (should be at baseline 0?)

	* aring (U+00E5): X=171.0,Y=712.0 (should be at cap-height 714?)

	* aring (U+00E5): X=391.0,Y=713.0 (should be at cap-height 714?)

	* aring (U+00E5): X=336.0,Y=712.0 (should be at cap-height 714?)

	* aring (U+00E5): X=224.0,Y=712.0 (should be at cap-height 714?)

	* ae (U+00E6): X=710.5,Y=-1.5 (should be at baseline 0?)

	* egrave (U+00E8): X=408.0,Y=-1.5 (should be at baseline 0?)

	* eacute (U+00E9): X=408.0,Y=-1.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=408.0,Y=-1.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=408.0,Y=-1.5 (should be at baseline 0?)

	* yacute (U+00FD): X=217.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=217.0,Y=-2.0 (should be at baseline 0?)

	* emacron (U+0113): X=408.0,Y=-1.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=408.0,Y=-1.5 (should be at baseline 0?)

	* ecaron (U+011B): X=408.0,Y=-1.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=537.0,Y=-1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=544.5,Y=713.0 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=537.0,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=544.5,Y=713.0 (should be at cap-height 714?)

	* uni0122 (U+0122): X=537.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=544.5,Y=713.0 (should be at cap-height 714?)

	* uni0123 (U+0123): X=279.5,Y=715.5 (should be at cap-height 714?)

	* oe (U+0153): X=791.0,Y=-1.5 (should be at baseline 0?)

	* Sacute (U+015A): X=136.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=396.0,Y=713.0 (should be at cap-height 714?)

	* sacute (U+015B): X=123.5,Y=-1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=136.0,Y=-1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=396.0,Y=713.0 (should be at cap-height 714?)

	* scedilla (U+015F): X=123.5,Y=-1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=136.0,Y=-1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=396.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=123.5,Y=-1.0 (should be at baseline 0?)

	* uring (U+016F): X=199.0,Y=712.0 (should be at cap-height 714?)

	* uring (U+016F): X=419.0,Y=713.0 (should be at cap-height 714?)

	* uring (U+016F): X=364.0,Y=712.0 (should be at cap-height 714?)

	* uring (U+016F): X=252.0,Y=712.0 (should be at cap-height 714?)

	* Uogonek (U+0172): X=447.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=258.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=158.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=626.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=523.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=217.0,Y=-2.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=136.0,Y=-1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=396.0,Y=713.0 (should be at cap-height 714?)

	* uni0219 (U+0219): X=123.5,Y=-1.0 (should be at baseline 0?)

	* ring (U+02DA): X=40.0,Y=712.0 (should be at cap-height 714?)

	* ring (U+02DA): X=260.0,Y=713.0 (should be at cap-height 714?)

	* ring (U+02DA): X=205.0,Y=712.0 (should be at cap-height 714?)

	* ring (U+02DA): X=93.0,Y=712.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=-108.0,Y=712.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=112.0,Y=713.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=57.0,Y=712.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=-55.0,Y=712.0 (should be at cap-height 714?)

	* wgrave (U+1E81): X=258.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=158.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=626.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=523.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=258.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=158.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=626.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=523.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=258.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=158.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=626.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=523.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=326.5,Y=-1.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=217.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=177.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=90.0,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=439.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=352.0,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=700.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=613.0,Y=2.0 (should be at baseline 0?)

	* Euro (U+20AC): X=474.0,Y=712.0 (should be at cap-height 714?)

	* Euro (U+20AC): X=468.5,Y=-0.5 (should be at baseline 0?)

	* shinchor (U+10FC3): X=417.5,Y=0.5 (should be at baseline 0?)

	* twentychor (U+10FCA): X=471.0,Y=1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* a (U+0061) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* d (U+0064) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* m (U+006D) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* n (U+006E) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* p (U+0070) contains a short segment L<<169.0,463.0>--<173.0,463.0>>

	* r (U+0072) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* u (U+0075) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Ntilde (U+00D1) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ntilde (U+00D1) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* germandbls (U+00DF) contains a short segment B<<382.0,412.0>-<382.0,399.0>-<388.5,388.0>>

	* agrave (U+00E0) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aacute (U+00E1) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* acircumflex (U+00E2) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* atilde (U+00E3) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* adieresis (U+00E4) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aring (U+00E5) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* ntilde (U+00F1) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* ugrave (U+00F9) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uacute (U+00FA) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ucircumflex (U+00FB) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* udieresis (U+00FC) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* amacron (U+0101) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* abreve (U+0103) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aogonek (U+0105) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* dcaron (U+010F) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* dcroat (U+0111) contains a short segment L<<445.0,72.0>--<441.0,72.0>>

	* Nacute (U+0143) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Nacute (U+0143) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* nacute (U+0144) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* uni0145 (U+0145) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* uni0145 (U+0145) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* uni0146 (U+0146) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Ncaron (U+0147) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ncaron (U+0147) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* ncaron (U+0148) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Eng (U+014A) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Eng (U+014A) contains a short segment L<<582.0,142.0>--<586.0,142.0>>

	* eng (U+014B) contains a short segment L<<170.0,463.0>--<175.0,463.0>>

	* racute (U+0155) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* uni0157 (U+0157) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* rcaron (U+0159) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* umacron (U+016B) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ubreve (U+016D) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uring (U+016F) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Uogonek (U+0172) contains a short segment B<<539.5,-158.5>-<551.0,-156.0>-<559.0,-155.0>>

	* uogonek (U+0173) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Wcircumflex (U+0174) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wgrave (U+1E80) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wacute (U+1E82) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wdieresis (U+1E84) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Euro (U+20AC) contains a short segment B<<184.0,390.0>-<183.0,380.0>-<183.0,371.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,371.0>-<183.0,362.0>-<183.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,352.0>-<183.0,343.0>-<183.0,332.5>>

	* Euro (U+20AC) contains a short segment B<<183.0,332.5>-<183.0,322.0>-<184.0,311.0>>

	* Euro (U+20AC) contains a short segment B<<95.0,311.0>-<94.0,323.0>-<94.0,331.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,331.0>-<94.0,339.0>-<94.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,352.0>-<94.0,363.0>-<94.5,373.5>>

	* Euro (U+20AC) contains a short segment B<<94.5,373.5>-<95.0,384.0>-<95.0,390.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Sar (Latn, 500,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Gulay (Latn, 250,478 speakers), Mango (Latn, 77,000 speakers), Basaa (Latn, 332,940 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 5 | 11 | 119 | 7 | 113 | 0 |
| 0% | 2% | 4% | 47% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
