## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[8] NotoSansDevanagari[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, math, old-permic, tai-le, coptic, tifinagh, canadian-aboriginal, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kharoshthi, sundanese, yi, cham, lisu, coptic, syloti-nagri, kayah-li, kaithi, sora-sompeng
 * U+20F0 COMBINING ASTERISK ABOVE: try adding grantha

Or you can add the above codepoints to one of the subsets supported by the font: `devanagari`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- chanuktaprehalfdevaNEP

	- chanuktaraprehalfUIdevaNEP

	- chanuktaraprehalfdevaNEP

	- chaprehalfdevaNEP

	- charaprehalfUIdevaNEP

	- charaprehalfdevaNEP

	- danuktaraprehalfdeva

	- daraprehalfdeva

	- ddanuktaraprehalfUIdeva

	- ddhanuktaraprehalfUIdeva

	- haraueUIdeva

	- harauueUIdeva

	- haueUIdeva

	- hauueUIdeva

	- llvocalicvowelsignnuktaUIdeva

	- lvocalicvowelsignnuktaUIdeva

	- nganuktaraprehalfUIdeva

	- question

	- rrvocalicvowelsignnuktaUIdeva

	- ttanuktaraprehalfUIdeva

	- tthanuktaraprehalfUIdeva

	- uni1CD0.UI

	- uni1CD1.UI

	- uni1CD2.UI

	- uni20F0.UI

	- uniA8F0.UI

	- uniA8F1.UI

	- vattuuevoweldeva

	- vattuuuevoweldeva
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni0903 (U+0903), uni1CE3 (U+1CE3), uni1CE4 (U+1CE4), uni1CE5 (U+1CE5), uni1CE6 (U+1CE6), uni1CE7 (U+1CE7) and uni1CE8 (U+1CE8) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni1CE0 (U+1CE0) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0903 and U+A8FA [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: i⃰ i̦⃰ i̧⃰ j⃰ j̦⃰ j̧⃰ j̨⃰ į̆ į̇ į̈ į̊ į̋ į̒ į⃰ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆

Your font fully covers the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Nateni (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 7 | 97 | 8 | 136 | 0 |
| 0% | 0% | 3% | 39% | 3% | 55% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
