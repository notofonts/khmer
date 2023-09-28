## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[14] NotoSansKhmerUI[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/variable/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, tifinagh, syriac, canadian-aboriginal, malayalam, coptic, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: syloti-nagri, buhid, buginese, grantha, khudawadi, limbu, manichaean, pahawh-hmong, brahmi, oriya, tibetan, chakma, yi, siddham, kaithi, balinese, sinhala, thaana, avestan, javanese, mongolian, myanmar, tai-le, telugu, gujarati, meetei-mayek, warang-citi, psalter-pahlavi, syriac, sharada, thai, malayalam, hanunoo, newa, tai-tham, gunjala-gondi, kannada, gurmukhi, kayah-li, hanifi-rohingya, old-hungarian, dogra, mahajani, saurashtra, batak, tamil, nko, tagbanwa, phags-pa, rejang, new-tai-lue, sundanese, kharoshthi, khojki, tai-viet, tagalog, cham, mandaic, tifinagh, takri, duployan, modi, bengali, devanagari, lepcha, tirhuta
 * U+2010 HYPHEN: try adding one of: syloti-nagri, kayah-li, lisu, sundanese, yi, kharoshthi, coptic, sora-sompeng, kaithi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni1780 + uni17B6

	- uni17B6 + uni17C5.right

	- uni1781 + uni17B6

	- uni1782 + uni17B6

	- uni1783 + uni17B6

	- uni1784 + uni17B6

	- uni1785 + uni17B6

	- uni1786 + uni17B6

	- uni1787 + uni17B6

	- uni1788 + uni17B6

	- uni1789 + uni17B6

	- uni1789.a + uni17B6

	- uni178A + uni17B6

	- uni178B + uni17B6

	- uni178C + uni17B6

	- uni178D + uni17B6

	- uni178E + uni17B6

	- uni178F + uni17B6

	- uni1790 + uni17B6

	- uni1791 + uni17B6

	- uni1792 + uni17B6

	- uni1793 + uni17B6

	- uni1794.a + uni17B6

	- uni1794.a2 + uni17B6

	- uni1795 + uni17B6

	- uni1796 + uni17B6

	- uni1797 + uni17B6

	- uni1798 + uni17B6

	- uni1799 + uni17B6

	- uni179A + uni17B6

	- uni179B + uni17B6

	- uni179C + uni17B6

	- uni179D + uni17B6

	- uni179E + uni17B6

	- uni179F + uni17B6

	- uni17A0 + uni17B6

	- uni17A1 + uni17B6

	- uni17A2 + uni17B6

	- uni17D21783 + uni17B6

	- uni17D21783.low + uni17B6

	- uni17D21788 + uni17B6

	- uni17D21788.low + uni17B6

	- uni17D2178D + uni17B6

	- uni17D2178D.low + uni17B6

	- uni17D21794 + uni17B6

	- uni17D21794.low + uni17B6

	- uni17D21799 + uni17B6

	- uni17D21799.low + uni17B6

	- uni17D2179E + uni17B6

	- uni17D2179E.low + uni17B6

	- uni17D2179F + uni17B6

	- uni17D2179F.low + uni17B6 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ebira (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Dutch (Latn, 31,709,104 speakers), Koonzime (Latn, 40,000 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 5 | 9 | 98 | 8 | 129 | 0 |
| 0% | 2% | 4% | 39% | 3% | 52% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
