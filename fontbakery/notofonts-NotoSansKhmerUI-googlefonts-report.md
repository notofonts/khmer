## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[12] NotoSansKhmerUI[wdth,wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead</p>
 [code: descent]



</div>
</details>

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
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2016-2022 Google Inc. All Rights Reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
uni17B4 (U+17B4) and uni17B5 (U+17B5)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+17BE</p>
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
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansKhmerUI/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, canadian-aboriginal, tai-le, malayalam, syriac, coptic, tifinagh, hebrew, duployan, math, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+2010 HYPHEN: try adding one of: yi, lisu, kaithi, cham, arabic, sundanese, armenian, coptic, hebrew, kayah-li, syloti-nagri, kharoshthi, sora-sompeng</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>khmer</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ma’di (Latn, 584,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Dii (Latn, 71,000 speakers), Mfumte (Latn, 79,000 speakers), Heiltsuk (Latn, 300 speakers), Vute (Latn, 21,000 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nzakara (Latn, 50,000 speakers), Mango (Latn, 77,000 speakers), South Central Banda (Latn, 244,000 speakers), Igbo (Latn, 27,823,640 speakers), Ngbaka (Latn, 1,020,000 speakers), Southern Kisi (Latn, 360,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Kaska (Latn, 125 speakers), Belarusian (Cyrl, 10,064,517 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Cicipu (Latn, 44,000 speakers), Zapotec (Latn, 490,000 speakers), Basaa (Latn, 332,940 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Gulay (Latn, 250,478 speakers), Kom (Latn, 360,685 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Navajo (Latn, 166,319 speakers), Han (Latn, 6 speakers), Nateni (Latn, 100,000 speakers), Yala (Latn, 200,000 speakers), Ekpeye (Latn, 226,000 speakers), Makaa (Latn, 221,000 speakers), Bafut (Latn, 158,146 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- uni1780 + uni17B6

- uni1780 + uni17C5.right

- uni1781 + uni17B6

- uni1781 + uni17C5.right

- uni1782 + uni17B6

- uni1782 + uni17C5.right

- uni1783 + uni17B6

- uni1783 + uni17C5.right

- uni1784 + uni17B6

- uni1784 + uni17C5.right

- uni1785 + uni17B6

- uni1785 + uni17C5.right

- uni1786 + uni17B6

- uni1786 + uni17C5.right

- uni1787 + uni17B6

- uni1787 + uni17C5.right

- uni1788 + uni17B6

- uni1788 + uni17C5.right

- uni1789 + uni17B6

- uni1789 + uni17C5.right

- uni1789.a + uni17B6

- uni1789.a + uni17C5.right

- uni178A + uni17B6

- uni178A + uni17C5.right

- uni178B + uni17B6

- uni178B + uni17C5.right

- uni178C + uni17B6

- uni178C + uni17C5.right

- uni178D + uni17B6

- uni178D + uni17C5.right

- uni178E + uni17B6

- uni178E + uni17C5.right

- uni178F + uni17B6

- uni178F + uni17C5.right

- uni1790 + uni17B6

- uni1790 + uni17C5.right

- uni1791 + uni17B6

- uni1791 + uni17C5.right

- uni1792 + uni17B6

- uni1792 + uni17C5.right

- uni1793 + uni17B6

- uni1793 + uni17C5.right

- uni1794.a + uni17B6

- uni1794.a + uni17C5.right

- uni1794.a2 + uni17B6

- uni1794.a2 + uni17C5.right

- uni1795 + uni17B6

- uni1795 + uni17C5.right

- uni1796 + uni17B6

- uni1796 + uni17C5.right

- uni1797 + uni17B6

- uni1797 + uni17C5.right

- uni1798 + uni17B6

- uni1798 + uni17C5.right

- uni1799 + uni17B6

- uni1799 + uni17C5.right

- uni179A + uni17B6

- uni179A + uni17C5.right

- uni179B + uni17B6

- uni179B + uni17C5.right

- uni179C + uni17B6

- uni179C + uni17C5.right

- uni179D + uni17B6

- uni179D + uni17C5.right

- uni179E + uni17B6

- uni179E + uni17C5.right

- uni179F + uni17B6

- uni179F + uni17C5.right

- uni17A0 + uni17B6

- uni17A0 + uni17C5.right

- uni17A1 + uni17B6

- uni17A1 + uni17C5.right

- uni17A2 + uni17B6

- uni17A2 + uni17C5.right

- uni17D21783 + uni17B6

- uni17D21783 + uni17C5.right

- uni17D21783.low + uni17B6

- uni17D21783.low + uni17C5.right

- uni17D21788 + uni17B6

- uni17D21788 + uni17C5.right

- uni17D21788.low + uni17B6

- uni17D21788.low + uni17C5.right

- uni17D2178D + uni17B6

- uni17D2178D + uni17C5.right

- uni17D2178D.low + uni17B6

- uni17D2178D.low + uni17C5.right

- uni17D21794 + uni17B6

- uni17D21794 + uni17C5.right

- uni17D21794.low + uni17B6

- uni17D21794.low + uni17C5.right

- uni17D21799 + uni17B6

- uni17D21799 + uni17C5.right

- uni17D21799.low + uni17B6

- uni17D21799.low + uni17C5.right

- uni17D2179E + uni17B6

- uni17D2179E + uni17C5.right

- uni17D2179E.low + uni17B6

- uni17D2179E.low + uni17C5.right

- uni17D2179F + uni17B6

- uni17D2179F + uni17C5.right

- uni17D2179F.low + uni17B6

- uni17D2179F.low + uni17C5.right
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



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

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 4 | 9 | 93 | 7 | 138 | 0 | 
| 0% | 0% | 2% | 4% | 37% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
