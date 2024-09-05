## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansDevanagari[wdth,wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 944, but got 896 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[12] NotoSansDevanagari[wdth,wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- acutecomb

- ayMatradeva

- candraBelowvedic

- dotBelowvedic

- doubleRingAbovevedic

- doubleSvaritavedic

- gravecomb

- invertedCandrabindudeva

- kathakaAnudattavedic

- ringAbovevedic

- threeDotsBelowvedic

- tildecomb

- tiryakvedic

- tripleSvaritavedic

- twoDotsBelowvedic

- uni0302

- uni0304

- uni0306

- uni0307

- uni0308

- uni030A

- uni030B

- uni030C

- uni0326

- uni0327

- uni0328

- uni0901

- uni0902

- uni093A

- uni093C

- uni0941

- uni0942

- uni0943

- uni0944

- uni0945

- uni0946

- uni0947

- uni0948

- uni094D

- uni0951

- uni0952

- uni0955

- uni0956

- uni0957

- uni0962

- uni0963

- yajurvedicAggravatedIndependentSvaritavedic

- yajurvedicIndependentSvaritavedic

- yajurvedicKathakaSvaritaSchroedervedic

- yajurvedicKathakaSvaritavedic
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
reversedVisargaAnudattavedic (U+1CE6), reversedVisargaUdattavedic (U+1CE4), visargaAnudattaTailvedic (U+1CE8), visargaAnudattavedic (U+1CE5), visargaUdattaTailvedic (U+1CE7) and visargaUdattavedic (U+1CE3)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
rigvedicKashmiriIndependentSvaritavedic (U+1CE0)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+A8FA</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- NULL

- eshortvowelsignrephanusvarade

- karshanavedic.UI

- prenkhavedic.UI

- sharavedic.UI

- uni091B094D094D0930093C

- uni091D094D094D0930.NEP

- uni091D094D094D0930093C.NEP

- uni20F0.UI
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
atharvavedicIndependentSvaritavedic, atharvavedicIndependentSvaritavedic.alt, rigvedicKashmiriIndependentSvaritavedic, yajurvedicAggravatedIndependentSvaritavedic, yajurvedicAggravatedIndependentSvaritavedic.alt01, yajurvedicIndependentSvaritavedic, yajurvedicIndependentSvaritavedic.alt01, yajurvedicKathakaSvaritaSchroedervedic, yajurvedicKathakaSvaritaSchroedervedic.alt01 and yajurvedicKathakaSvaritavedic.alt01</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansDevanagari/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, tifinagh, canadian-aboriginal, old-permic, malayalam, coptic, tai-le, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+2010 HYPHEN: try adding one of: kaithi, sora-sompeng, armenian, kharoshthi, syloti-nagri, arabic, sundanese, yi, lisu, hebrew, cham, coptic, kayah-li</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>devanagari</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į⃰ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦⃰ į̧̀ į̧́</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ekpeye (Latn, 226,000 speakers), Aghem (Latn, 38,843 speakers), Zapotec (Latn, 490,000 speakers), Makaa (Latn, 221,000 speakers), Ejagham (Latn, 120,000 speakers), Mundani (Latn, 34,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kom (Latn, 360,685 speakers), Igbo (Latn, 27,823,640 speakers), Lugbara (Latn, 2,200,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Nateni (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), Mango (Latn, 77,000 speakers), Cicipu (Latn, 44,000 speakers), Dii (Latn, 71,000 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Ebira (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Ngbaka (Latn, 1,020,000 speakers), Bete-Bendi (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 10 | 94 | 7 | 137 | 0 | 
| 0% | 0% | 1% | 4% | 37% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
