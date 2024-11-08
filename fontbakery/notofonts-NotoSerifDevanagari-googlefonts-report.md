## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSerifDevanagari[wdth,wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 931, but got 930 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[9] NotoSerifDevanagari[wdth,wght].ttf</summary>
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
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni1CE0 (U+1CE0), uni1CE2 (U+1CE2), uni1CE3 (U+1CE3), uni1CE4 (U+1CE4), uni1CE5 (U+1CE5), uni1CE6 (U+1CE6), uni1CE7 (U+1CE7) and uni1CE8 (U+1CE8)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 48 in glyph 'two' has a kink between location wght=900,wdth=100 and location wght=100,wdth=62

- Contour order differs in glyph 'zhdeva': [0, 1, 2, 3, 4] in wght=900,wdth=100, [0, 1, 3, 4, 2] in wght=100,wdth=62.

- Contour order differs in glyph 'zhdeva': [0, 1, 2, 3, 4] in wght=100,wdth=62, [0, 1, 4, 2, 3] in wght=900,wdth=62.
</code></pre>
 [code: interpolation-issues]



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
<pre><code>- awMatra_rephCandrabindudeva

- awMatra_rephanusvaradeva

- ayMatra_rephCandrabindudeva

- ayMatra_rephanusvaradeva

- eCandraMatra_candrabindudeva

- ghh_nukadeva

- oeMatra_candrabindudeva

- oeMatra_rephanusvaradeva

- oeMatra_rephcandrabindudeva

- two_karshana

- uni00310930.1

- uni00310967.1

- uni00320909.1

- uni00320930.1

- uni0032093D.1

- uni00330915.1

- uni00330930.1

- uni00340930.1

- uni00350930.1

- uni0901.alt

- uni0915094D0924094D092F

- uni0915094D0924094D0935

- uni0918093C

- uni0919093C

- uni0919093C094D

- uni0919093C094D0930

- uni0919093C094D0930094D

- uni0919094D

- uni0919094D0930

- uni0919094D0930094D

- uni091A093C

- uni091B093C

- uni091B093C094D0930

- uni091B094D0930

- uni091B094D094D0930093C

- uni091D093C

- uni091D093C.NEP

- uni091D093C.alt

- uni091D094D094D0930.NEP

- uni091D094D094D0930093C.NEP

- uni091E093C

- uni091F093C

- uni091F093C094D

- uni091F093C094D0930

- uni091F093C094D0930094D

- uni091F094D

- uni091F094D0930

- uni091F094D0930094D

- uni0920093C

- uni0920093C094D

- uni0920093C094D0930

- uni0920093C094D0930094D

- uni0920094D

- uni0920094D0930

- uni0920094D0930094D

- uni0921094D

- uni0921094D0930

- uni0921094D0930094D

- uni0922094D

- uni0922094D0930

- uni0922094D0930094D

- uni0923093C

- uni0924093C

- uni0924093C.alt

- uni0925093C

- uni0926093C

- uni0926093C0941

- uni0926093C0942

- uni0926093C0943

- uni0926093C094D

- uni0926093C094D0930094D

- uni0926094D

- uni0926094D0930094D

- uni0927093C

- uni092A093C

- uni092C093C

- uni092D093C

- uni092E093C

- uni0930094D0930

- uni0930094D094D0930094D

- uni0931094D0930

- uni0931094D0930094D

- uni0932093C.MAR

- uni093293C

- uni0933094D0930

- uni0933094D0930093C

- uni0935093C

- uni0936093C

- uni0936093C.MAR

- uni0937093C

- uni0938093C

- uni0939093C

- uni0939093C0943

- uni0939093C0944

- uni0939093C094D0930094D

- uni0939094D0930094D

- uni093C0941.01

- uni093C0942.01

- uni0941.01.1

- uni0941.short.1

- uni0942.short.1

- uni094D0930093C.1

- uni094F0930094D

- uni0951.alt

- uni0951.alt1

- uni0951.alt2

- uni0951.alt3

- uni0951.ii

- uni0951.iicandra

- uni0951.iireph

- uni0951.iirephc

- uni0952.alt

- uni0952.alt1

- uni0952.alt2

- uni0952.alt3

- uni095C094D

- uni095C094D0930

- uni095C094D0930094D

- uni095D094D

- uni095D094D0930

- uni095D094D0930094D

- uni097E094D

- uni097E094D0930

- uni097E094D0930094D

- uni1CD5.alt

- uni1CD5.alt1

- uni1CD5.alt2

- uni1CD5.alt3

- uni1CD6.alt

- uni1CD6.alt1

- uni1CD6.alt2

- uni1CD6.alt3

- uni1CD7.alt

- uni1CD7.alt1

- uni1CD7.alt2

- uni1CD7.alt3

- uni1CD8.alt

- uni1CD8.alt1

- uni1CD8.alt2

- uni1CD8.alt3

- uni1CD9.alt

- uni1CD9.alt1

- uni1CD9.alt2

- uni1CD9.alt3

- uni1CDA.alt

- uni1CDA.alt1

- uni1CDA.alt2

- uni1CDA.alt3

- uni1CDA.ii

- uni1CDA.iicandra

- uni1CDA.iireph

- uni1CDA.iirephc

- uni1CDC.alt

- uni1CDC.alt1

- uni1CDC.alt2

- uni1CDC.alt3

- uni1CDD.alt

- uni1CDD.alt1

- uni1CDD.alt2

- uni1CDD.alt3

- uni1CDE.alt

- uni1CDE.alt1

- uni1CDE.alt2

- uni1CDE.alt3

- uni1CDF.alt

- uni1CDF.alt1

- uni1CDF.alt2

- uni1CDF.alt3

- uni1CED.alt

- uni1CED.alt1

- uni1CED.alt2

- uni1CED.alt3

- uni1CF8.alt

- uni1CF8.alt1

- uni1CF8.alt2

- uni1CF8.alt3

- uni1CF8.ii

- uni1CF8.iicandra

- uni1CF8.iireph

- uni1CF8.iirephc

- uni1CF9.alt

- uni1CF9.alt1

- uni1CF9.alt2

- uni1CF9.alt3

- uni1CF9.ii

- uni1CF9.iicandra

- uni1CF9.iireph

- uni1CF9.iirephc

- vi_radeva.1
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifDevanagari/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, malayalam, math, hebrew, canadian-aboriginal, duployan, todhri, tifinagh, syriac, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+2010 HYPHEN: try adding one of: cham, kayah-li, kaithi, lisu, hebrew, sora-sompeng, armenian, syloti-nagri, sundanese, kharoshthi, yi, coptic, arabic</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Han (Latn, 6 speakers), Kaska (Latn, 125 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ijo, Southeast (Latn, 2,471,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Bafut (Latn, 158,146 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Avokaya (Latn, 100,000 speakers), Zapotec (Latn, 490,000 speakers), Vute (Latn, 21,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kom (Latn, 360,685 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Dan (Latn, 1,099,244 speakers), Aghem (Latn, 38,843 speakers), Heiltsuk (Latn, 300 speakers), Gulay (Latn, 250,478 speakers), Nzakara (Latn, 50,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ngbaka (Latn, 1,020,000 speakers), Fur (Latn, 1,230,163 speakers), Mfumte (Latn, 79,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Yala (Latn, 200,000 speakers), Cicipu (Latn, 44,000 speakers), Southern Kisi (Latn, 360,000 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Igbo (Latn, 27,823,640 speakers), Mango (Latn, 77,000 speakers), Nateni (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers).</p>
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
| 0 | 0 | 2 | 8 | 94 | 7 | 140 | 0 | 
| 0% | 0% | 1% | 3% | 37% | 3% | 56% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
