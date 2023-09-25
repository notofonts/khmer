## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[16] NotoSerifKhmer-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, old-permic, syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: khojki, devanagari, mahajani, hanunoo, avestan, tirhuta, saurashtra, rejang, brahmi, psalter-pahlavi, khudawadi, chakma, old-hungarian, new-tai-lue, gujarati, grantha, lepcha, gurmukhi, modi, limbu, buhid, myanmar, hanifi-rohingya, mandaic, syriac, tibetan, warang-citi, oriya, kharoshthi, sinhala, kannada, duployan, tagalog, buginese, meetei-mayek, nko, phags-pa, manichaean, tamil, cham, bengali, balinese, thaana, kaithi, javanese, takri, tai-tham, malayalam, sundanese, syloti-nagri, tagbanwa, sharada, siddham, tai-le, tai-viet, telugu, batak, yi, dogra, gunjala-gondi, pahawh-hmong, thai, tifinagh, newa, kayah-li, mongolian
 * U+2010 HYPHEN: try adding one of: lisu, coptic, kaithi, sora-sompeng, syloti-nagri, sundanese, kharoshthi, kayah-li, yi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni178117C5
	* uni1783
	* uni178317B6
	* uni178317C5
	* uni1784
	* uni178417B6
	* uni178417C5
	* uni1785
	* uni178517B6
	* uni178517C5
	* uni1786
	* uni178617B6
	* uni178617C5
	* uni1787
	* uni178717B6
	* uni178717C5
	* uni1788
	* uni178817B6
	* uni178817C5
	* uni1789
	* uni1789.a
	* uni178917B6
	* uni178917B6.a
	* uni178917C5
	* uni178917C5.a
	* uni178A17C5
	* uni178B
	* uni178B17B6
	* uni178B17C5
	* uni178C17C5
	* uni178D
	* uni178D17B6
	* uni178D17C5
	* uni178E17C5
	* uni178F
	* uni178F17B6
	* uni178F17C5
	* uni1790
	* uni179017B6
	* uni179017C5
	* uni179117C5
	* uni1792
	* uni179217B6
	* uni179217C5
	* uni179317B6
	* uni179317C5
	* uni1794
	* uni179417B6
	* uni179417B6.high
	* uni179417C5
	* uni179417C5.high
	* uni1795
	* uni179517B6
	* uni179517C5
	* uni179617C5
	* uni179717C5
	* uni1798
	* uni179817B6
	* uni179817C5
	* uni1799
	* uni179917B6
	* uni179917C5
	* uni179A
	* uni179A17B6
	* uni179A17C5
	* uni179B
	* uni179B17C5
	* uni179C
	* uni179C17B6
	* uni179C17C5
	* uni179D
	* uni179D17B6
	* uni179D17C5
	* uni179E
	* uni179E17B6
	* uni179E17C5
	* uni179F
	* uni179F17B6
	* uni179F17C5
	* uni17A0
	* uni17A017B6
	* uni17A017C5
	* uni17A1
	* uni17A117B6
	* uni17A117C5
	* uni17A2
	* uni17A217B6
	* uni17A217C5
	* uni17A3
	* uni17A4
	* uni17A6
	* uni17AB
	* uni17AC
	* uni17B0
	* uni17B717CD
	* uni17B717CD.r
	* uni17B8
	* uni17B8.r
	* uni17BA
	* uni17BA.r
	* uni17BE
	* uni17BF
	* uni17BF.right1
	* uni17BF.right2
	* uni17BF.right3
	* uni17C0
	* uni17C0.right1
	* uni17C0.right2
	* uni17C0.right3
	* uni17C1
	* uni17C2
	* uni17C3
	* uni17C4
	* uni17C5
	* uni17D21783
	* uni17D21783.low
	* uni17D2178317B6
	* uni17D2178317B6.low
	* uni17D2178317C5
	* uni17D2178317C5.low
	* uni17D21785
	* uni17D21787
	* uni17D21788
	* uni17D21788.low
	* uni17D2178817C5
	* uni17D2178817C5.low
	* uni17D21789.a
	* uni17D2178D
	* uni17D2178D.low
	* uni17D2178D17B6
	* uni17D2178D17B6.low
	* uni17D2178D17C5
	* uni17D2178D17C5.low
	* uni17D21794
	* uni17D21794.low
	* uni17D2179417C5
	* uni17D2179417C5.low
	* uni17D21799
	* uni17D21799.low
	* uni17D2179917C5
	* uni17D2179917C5.low
	* uni17D2179D
	* uni17D2179E
	* uni17D2179E.low
	* uni17D2179E17B6
	* uni17D2179E17B6.low
	* uni17D2179E17C5
	* uni17D2179E17C5.low
	* uni17D2179F
	* uni17D2179F.low
	* uni17D2179F17B6
	* uni17D2179F17B6.low
	* uni17D2179F17C5
	* uni17D2179F17C5.low
	* uni17D217A1
	* uni17D8
	* uni17DA
	* uni17DB
	* uni17E5
	* uni19E5
	* uni19EF
	* uni19F0
	* uni19F5 and uni19FF
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 569 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=765.0,Y=-2.0 (should be at baseline 0?)

	* J (U+004A): X=117.0,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=317.0,Y=2.0 (should be at baseline 0?)

	* Q (U+0051): X=317.0,Y=-1.0 (should be at baseline 0?)

	* c (U+0063): X=431.0,Y=535.0 (should be at x-height 536?)

	* f (U+0066): X=155.0,Y=713.5 (should be at cap-height 714?)

	* p (U+0070): X=337.5,Y=1.5 (should be at baseline 0?)

	* q (U+0071): X=386.0,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=376.5,Y=535.5 (should be at x-height 536?)

	* t (U+0074): X=93.0,Y=535.5 (should be at x-height 536?)

	* t (U+0074): X=367.0,Y=1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=329.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=469.0,Y=2.0 (should be at baseline 0?)

	* questiondown (U+00BF): X=480.5,Y=-1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=281.0,Y=-1.0 (should be at baseline 0?)

	* dcaron (U+010F): X=666.5,Y=712.5 (should be at cap-height 714?)

	* lcaron (U+013E): X=376.5,Y=712.5 (should be at cap-height 714?)

	* tcaron (U+0165): X=371.0,Y=1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=378.5,Y=712.5 (should be at cap-height 714?)

	* uni021B (U+021B): X=367.0,Y=1.5 (should be at baseline 0?)

	* uni0312 (U+0312): X=98.0,Y=713.0 (should be at cap-height 714?)

	* uni1784 (U+1784): X=138.0,Y=713.0 (should be at cap-height 714?)

	* uni1784 (U+1784): X=342.0,Y=713.0 (should be at cap-height 714?)

	* uni178A (U+178A): X=305.5,Y=715.0 (should be at cap-height 714?)

	* uni17AF (U+17AF): X=193.0,Y=716.0 (should be at cap-height 714?)

	* uni17BC (U+17BC): X=-236.0,Y=-291.0 (should be at descender -293?)

	* uni17BC (U+17BC): X=-236.0,Y=-291.0 (should be at descender -293?)

	* uni17BF (U+17BF): X=1049.0,Y=1067.0 (should be at ascender 1069?)

	* uni17C7 (U+17C7): X=207.0,Y=-2.0 (should be at baseline 0?)

	* uni17C7 (U+17C7): X=207.0,Y=-2.0 (should be at baseline 0?)

	* uni17CA (U+17CA): X=-533.5,Y=1067.0 (should be at ascender 1069?)

	* uni17CA (U+17CA): X=-196.5,Y=1070.0 (should be at ascender 1069?)

	* uni17CC (U+17CC): X=-333.5,Y=1070.5 (should be at ascender 1069?)

	* uni17CF (U+17CF): X=-180.5,Y=1067.5 (should be at ascender 1069?)

	* uni17D6 (U+17D6): X=282.0,Y=-2.0 (should be at baseline 0?)

	* uni17D6 (U+17D6): X=282.0,Y=-2.0 (should be at baseline 0?)

	* uni17E9 (U+17E9): X=279.5,Y=714.5 (should be at cap-height 714?)

	* uni19E8 (U+19E8): X=427.5,Y=712.5 (should be at cap-height 714?)

	* uni19E9 (U+19E9): X=519.0,Y=713.5 (should be at cap-height 714?)

	* uni19F0 (U+19F0): X=406.5,Y=712.5 (should be at cap-height 714?)

	* uni19F3 (U+19F3): X=295.0,Y=-294.0 (should be at descender -293?)

	* uni19F3 (U+19F3): X=295.0,Y=-294.0 (should be at descender -293?)

	* uni19F4 (U+19F4): X=288.0,Y=-292.0 (should be at descender -293?)

	* uni19F4 (U+19F4): X=706.0,Y=0.5 (should be at baseline 0?)

	* uni19F5 (U+19F5): X=290.0,Y=-294.0 (should be at descender -293?)

	* uni19F5 (U+19F5): X=616.0,Y=-1.0 (should be at baseline 0?)

	* uni19F6 (U+19F6): X=379.0,Y=-292.0 (should be at descender -293?)

	* uni19F7 (U+19F7): X=295.0,Y=-294.0 (should be at descender -293?)

	* uni19F7 (U+19F7): X=295.0,Y=-294.0 (should be at descender -293?)

	* uni19F9 (U+19F9): X=454.0,Y=-295.0 (should be at descender -293?)

	* uni19F9 (U+19F9): X=543.0,Y=-291.5 (should be at descender -293?)

	* uni19FD (U+19FD): X=1000.0,Y=-294.0 (should be at descender -293?)

	* uni19FD (U+19FD): X=1000.0,Y=-294.0 (should be at descender -293?)

	* uni19FE (U+19FE): X=1005.0,Y=-292.0 (should be at descender -293?)

	* uni19FE (U+19FE): X=1423.0,Y=0.5 (should be at baseline 0?)

	* uni19FF (U+19FF): X=1003.0,Y=-294.0 (should be at descender -293?)

	* uni19FF (U+19FF): X=1329.0,Y=-1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=246.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=462.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=246.0,Y=713.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* y (U+0079): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yacute (U+00FD): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ycircumflex (U+0177): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ydieresis (U+00FF): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSerifKhmer-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, old-permic, syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: khojki, devanagari, mahajani, hanunoo, avestan, tirhuta, saurashtra, rejang, brahmi, psalter-pahlavi, khudawadi, chakma, old-hungarian, new-tai-lue, gujarati, grantha, lepcha, gurmukhi, modi, limbu, buhid, myanmar, hanifi-rohingya, mandaic, syriac, tibetan, warang-citi, oriya, kharoshthi, sinhala, kannada, duployan, tagalog, buginese, meetei-mayek, nko, phags-pa, manichaean, tamil, cham, bengali, balinese, thaana, kaithi, javanese, takri, tai-tham, malayalam, sundanese, syloti-nagri, tagbanwa, sharada, siddham, tai-le, tai-viet, telugu, batak, yi, dogra, gunjala-gondi, pahawh-hmong, thai, tifinagh, newa, kayah-li, mongolian
 * U+2010 HYPHEN: try adding one of: lisu, coptic, kaithi, sora-sompeng, syloti-nagri, sundanese, kharoshthi, kayah-li, yi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni178117C5
	* uni1783
	* uni178317B6
	* uni178317C5
	* uni1784
	* uni178417B6
	* uni178417C5
	* uni1785
	* uni178517B6
	* uni178517C5
	* uni1786
	* uni178617B6
	* uni178617C5
	* uni178717B6
	* uni178717C5
	* uni1788
	* uni178817B6
	* uni178817C5
	* uni1789
	* uni1789.a
	* uni178917B6
	* uni178917B6.a
	* uni178917C5
	* uni178917C5.a
	* uni178A17B6
	* uni178A17C5
	* uni178B
	* uni178B17B6
	* uni178B17C5
	* uni178C17C5
	* uni178D
	* uni178D17C5
	* uni178E17C5
	* uni178F
	* uni178F17B6
	* uni178F17C5
	* uni1790
	* uni179017B6
	* uni179017C5
	* uni179117C5
	* uni1792
	* uni179217B6
	* uni179217C5
	* uni179317C5
	* uni1794
	* uni179417B6
	* uni179417B6.high
	* uni179417C5
	* uni179417C5.high
	* uni1795
	* uni179517B6
	* uni179517C5
	* uni179617C5
	* uni1798
	* uni179817B6
	* uni179817C5
	* uni1799
	* uni179917B6
	* uni179917C5
	* uni179A
	* uni179A17C5
	* uni179B
	* uni179B17C5
	* uni179C
	* uni179C17B6
	* uni179C17C5
	* uni179D
	* uni179D17B6
	* uni179D17C5
	* uni179E
	* uni179E17B6
	* uni179E17C5
	* uni179F
	* uni179F17B6
	* uni179F17C5
	* uni17A0
	* uni17A017B6
	* uni17A017C5
	* uni17A1
	* uni17A117C5
	* uni17A2
	* uni17A217B6
	* uni17A217C5
	* uni17A3
	* uni17A4
	* uni17A6
	* uni17AB
	* uni17AC
	* uni17AF
	* uni17B0
	* uni17B717CD
	* uni17B717CD.r
	* uni17BA
	* uni17BA.r
	* uni17BE
	* uni17BF
	* uni17BF.right1
	* uni17C0
	* uni17C0.right1
	* uni17C1
	* uni17C2
	* uni17C3
	* uni17C4
	* uni17C5
	* uni17D21783
	* uni17D21783.low
	* uni17D2178317B6
	* uni17D2178317B6.low
	* uni17D2178317C5
	* uni17D2178317C5.low
	* uni17D21788
	* uni17D21788.low
	* uni17D21789.a
	* uni17D2178D
	* uni17D2178D.low
	* uni17D2178D17C5
	* uni17D2178D17C5.low
	* uni17D21794
	* uni17D21794.low
	* uni17D2179417C5
	* uni17D2179417C5.low
	* uni17D21799
	* uni17D21799.low
	* uni17D2179917C5
	* uni17D2179917C5.low
	* uni17D2179D
	* uni17D2179E
	* uni17D2179E.low
	* uni17D2179E17B6
	* uni17D2179E17B6.low
	* uni17D2179E17C5
	* uni17D2179E17C5.low
	* uni17D2179F
	* uni17D2179F.low
	* uni17D2179F17C5
	* uni17D2179F17C5.low
	* uni17D217A1
	* uni17D8
	* uni17DA
	* uni17DB
	* uni17E5
	* uni19E5
	* uni19EF
	* uni19F0
	* uni19F5 and uni19FF
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 565 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=122.0,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=348.0,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=339.0,Y=1.5 (should be at baseline 0?)

	* semicolon (U+003B): X=131.0,Y=-2.0 (should be at baseline 0?)

	* J (U+004A): X=282.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=264.5,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=320.0,Y=712.0 (should be at cap-height 714?)

	* p (U+0070): X=247.0,Y=1.5 (should be at baseline 0?)

	* t (U+0074): X=334.5,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=68.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=464.0,Y=2.0 (should be at baseline 0?)

	* agrave (U+00E0): X=264.5,Y=-1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=264.5,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=264.5,Y=-1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=264.5,Y=-1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=264.5,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=264.5,Y=-1.5 (should be at baseline 0?)

	* amacron (U+0101): X=264.5,Y=-1.5 (should be at baseline 0?)

	* abreve (U+0103): X=264.5,Y=-1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=264.5,Y=-1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=336.5,Y=-1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=334.5,Y=-1.0 (should be at baseline 0?)

	* uni1784 (U+1784): X=298.0,Y=712.0 (should be at cap-height 714?)

	* uni178B (U+178B): X=622.0,Y=713.5 (should be at cap-height 714?)

	* uni179C (U+179C): X=286.0,Y=713.5 (should be at cap-height 714?)

	* uni17A5 (U+17A5): X=202.0,Y=712.0 (should be at cap-height 714?)

	* uni17A6 (U+17A6): X=942.0,Y=713.5 (should be at cap-height 714?)

	* uni17AF (U+17AF): X=304.0,Y=713.5 (should be at cap-height 714?)

	* uni17B0 (U+17B0): X=461.0,Y=2.0 (should be at baseline 0?)

	* uni17B0 (U+17B0): X=482.0,Y=-1.0 (should be at baseline 0?)

	* uni17BD (U+17BD): X=-184.0,Y=-292.0 (should be at descender -293?)

	* uni17BD (U+17BD): X=-259.0,Y=-292.5 (should be at descender -293?)

	* uni17BF (U+17BF): X=794.0,Y=1070.5 (should be at ascender 1069?)

	* uni17C3 (U+17C3): X=-1.0,Y=1070.0 (should be at ascender 1069?)

	* uni17CA (U+17CA): X=-463.5,Y=1067.0 (should be at ascender 1069?)

	* uni17CA (U+17CA): X=-207.0,Y=1070.0 (should be at ascender 1069?)

	* uni17CD (U+17CD): X=-233.0,Y=1070.0 (should be at ascender 1069?)

	* uni17E9 (U+17E9): X=294.0,Y=714.5 (should be at cap-height 714?)

	* uni19E0 (U+19E0): X=499.5,Y=-292.5 (should be at descender -293?)

	* uni19E4 (U+19E4): X=113.0,Y=713.0 (should be at cap-height 714?)

	* uni19E4 (U+19E4): X=640.0,Y=713.0 (should be at cap-height 714?)

	* uni19E9 (U+19E9): X=661.0,Y=1068.0 (should be at ascender 1069?)

	* uni19E9 (U+19E9): X=513.0,Y=715.5 (should be at cap-height 714?)

	* uni19EE (U+19EE): X=830.0,Y=713.0 (should be at cap-height 714?)

	* uni19EE (U+19EE): X=1357.0,Y=713.0 (should be at cap-height 714?)

	* uni19F0 (U+19F0): X=493.0,Y=-292.5 (should be at descender -293?)

	* uni19F8 (U+19F8): X=507.5,Y=-292.5 (should be at descender -293?)

	* quotesinglbase (U+201A): X=122.0,Y=-2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=331.0,Y=-2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=122.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] NotoSerifKhmer-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, old-permic, syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: khojki, devanagari, mahajani, hanunoo, avestan, tirhuta, saurashtra, rejang, brahmi, psalter-pahlavi, khudawadi, chakma, old-hungarian, new-tai-lue, gujarati, grantha, lepcha, gurmukhi, modi, limbu, buhid, myanmar, hanifi-rohingya, mandaic, syriac, tibetan, warang-citi, oriya, kharoshthi, sinhala, kannada, duployan, tagalog, buginese, meetei-mayek, nko, phags-pa, manichaean, tamil, cham, bengali, balinese, thaana, kaithi, javanese, takri, tai-tham, malayalam, sundanese, syloti-nagri, tagbanwa, sharada, siddham, tai-le, tai-viet, telugu, batak, yi, dogra, gunjala-gondi, pahawh-hmong, thai, tifinagh, newa, kayah-li, mongolian
 * U+2010 HYPHEN: try adding one of: lisu, coptic, kaithi, sora-sompeng, syloti-nagri, sundanese, kharoshthi, kayah-li, yi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni178117C5
	* uni1783
	* uni178317B6
	* uni178317C5
	* uni1784
	* uni178417B6
	* uni178417C5
	* uni1785
	* uni178517B6
	* uni178517C5
	* uni1786
	* uni178617B6
	* uni178617C5
	* uni1787
	* uni178717B6
	* uni178717C5
	* uni1788
	* uni178817B6
	* uni178817C5
	* uni1789
	* uni1789.a
	* uni178917B6
	* uni178917B6.a
	* uni178917C5
	* uni178917C5.a
	* uni178A17B6
	* uni178A17C5
	* uni178B
	* uni178B17B6
	* uni178B17C5
	* uni178C17C5
	* uni178D
	* uni178D17C5
	* uni178E17C5
	* uni178F
	* uni178F17B6
	* uni178F17C5
	* uni1790
	* uni179017B6
	* uni179017C5
	* uni179117C5
	* uni1792
	* uni179217B6
	* uni179217C5
	* uni179317C5
	* uni1794
	* uni179417B6
	* uni179417B6.high
	* uni179417C5
	* uni179417C5.high
	* uni1795
	* uni179517B6
	* uni179517C5
	* uni179617C5
	* uni1798
	* uni179817B6
	* uni179817C5
	* uni1799
	* uni179917B6
	* uni179917C5
	* uni179A
	* uni179A17C5
	* uni179B
	* uni179B17C5
	* uni179C
	* uni179C17B6
	* uni179C17C5
	* uni179D
	* uni179D17B6
	* uni179D17C5
	* uni179E
	* uni179E17B6
	* uni179E17C5
	* uni179F
	* uni179F17B6
	* uni179F17C5
	* uni17A0
	* uni17A017B6
	* uni17A017C5
	* uni17A1
	* uni17A117B6
	* uni17A117C5
	* uni17A2
	* uni17A217B6
	* uni17A217C5
	* uni17A3
	* uni17A4
	* uni17A6
	* uni17AB
	* uni17AC
	* uni17AF
	* uni17B0
	* uni17B717CD
	* uni17B717CD.r
	* uni17B8
	* uni17B8.r
	* uni17BA
	* uni17BA.r
	* uni17BE
	* uni17BF
	* uni17BF.right1
	* uni17BF.right2
	* uni17BF.right3
	* uni17C0
	* uni17C0.right1
	* uni17C0.right2
	* uni17C0.right3
	* uni17C1
	* uni17C2
	* uni17C3
	* uni17C4
	* uni17C5
	* uni17D21783
	* uni17D21783.low
	* uni17D2178317B6
	* uni17D2178317B6.low
	* uni17D2178317C5
	* uni17D2178317C5.low
	* uni17D21785
	* uni17D21787
	* uni17D21788
	* uni17D21788.low
	* uni17D21789.a
	* uni17D2178D
	* uni17D2178D.low
	* uni17D2178D17C5
	* uni17D2178D17C5.low
	* uni17D21794
	* uni17D21794.low
	* uni17D2179417C5
	* uni17D2179417C5.low
	* uni17D21799
	* uni17D21799.low
	* uni17D2179917C5
	* uni17D2179917C5.low
	* uni17D2179D
	* uni17D2179E
	* uni17D2179E.low
	* uni17D2179E17B6
	* uni17D2179E17B6.low
	* uni17D2179E17C5
	* uni17D2179E17C5.low
	* uni17D2179F
	* uni17D2179F.low
	* uni17D2179F17B6.low
	* uni17D2179F17C5
	* uni17D2179F17C5.low
	* uni17D217A1
	* uni17D8
	* uni17DA
	* uni17DB
	* uni17E5
	* uni19E5
	* uni19EF
	* uni19F0
	* uni19F5 and uni19FF
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 567 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=354.0,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=120.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=319.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=509.0,Y=2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=274.0,Y=1.0 (should be at baseline 0?)

	* bracketright (U+005D): X=162.0,Y=1.0 (should be at baseline 0?)

	* f (U+0066): X=157.5,Y=715.0 (should be at cap-height 714?)

	* s (U+0073): X=365.5,Y=535.0 (should be at x-height 536?)

	* t (U+0074): X=86.0,Y=534.0 (should be at x-height 536?)

	* t (U+0074): X=352.5,Y=0.5 (should be at baseline 0?)

	* y (U+0079): X=353.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=467.0,Y=2.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=373.0,Y=712.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=394.0,Y=713.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=411.0,Y=713.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=395.0,Y=713.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=353.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=353.0,Y=2.0 (should be at baseline 0?)

	* dcaron (U+010F): X=651.0,Y=712.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=358.0,Y=712.0 (should be at cap-height 714?)

	* Eng (U+014A): X=693.0,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=355.5,Y=0.5 (should be at baseline 0?)

	* tcaron (U+0165): X=360.0,Y=712.0 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=353.0,Y=2.0 (should be at baseline 0?)

	* uni021B (U+021B): X=352.5,Y=0.5 (should be at baseline 0?)

	* tilde (U+02DC): X=330.0,Y=713.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-234.0,Y=713.0 (should be at cap-height 714?)

	* uni0312 (U+0312): X=95.0,Y=713.0 (should be at cap-height 714?)

	* uni1784 (U+1784): X=132.0,Y=716.0 (should be at cap-height 714?)

	* uni1784 (U+1784): X=322.0,Y=713.0 (should be at cap-height 714?)

	* uni178B (U+178B): X=633.0,Y=715.5 (should be at cap-height 714?)

	* uni179C (U+179C): X=303.5,Y=715.5 (should be at cap-height 714?)

	* uni17A6 (U+17A6): X=939.5,Y=715.5 (should be at cap-height 714?)

	* uni17A8 (U+17A8): X=324.0,Y=715.0 (should be at cap-height 714?)

	* uni17AF (U+17AF): X=334.5,Y=715.5 (should be at cap-height 714?)

	* uni17B0 (U+17B0): X=467.0,Y=-2.0 (should be at baseline 0?)

	* uni17C0 (U+17C0): X=678.0,Y=1067.0 (should be at ascender 1069?)

	* uni17C7 (U+17C7): X=204.0,Y=1.0 (should be at baseline 0?)

	* uni17C7 (U+17C7): X=204.0,Y=1.0 (should be at baseline 0?)

	* uni17CA (U+17CA): X=-530.0,Y=1067.0 (should be at ascender 1069?)

	* uni17CA (U+17CA): X=-465.5,Y=1068.0 (should be at ascender 1069?)

	* uni17CA (U+17CA): X=-201.0,Y=1070.0 (should be at ascender 1069?)

	* uni17CF (U+17CF): X=-221.0,Y=1068.0 (should be at ascender 1069?)

	* uni17D6 (U+17D6): X=282.0,Y=1.0 (should be at baseline 0?)

	* uni17D6 (U+17D6): X=282.0,Y=1.0 (should be at baseline 0?)

	* uni17E7 (U+17E7): X=644.0,Y=715.5 (should be at cap-height 714?)

	* uni17E8 (U+17E8): X=732.0,Y=715.0 (should be at cap-height 714?)

	* uni17E9 (U+17E9): X=286.0,Y=714.5 (should be at cap-height 714?)

	* uni17E9 (U+17E9): X=499.0,Y=715.0 (should be at cap-height 714?)

	* uni19E0 (U+19E0): X=498.0,Y=-294.0 (should be at descender -293?)

	* uni19E5 (U+19E5): X=410.5,Y=1070.5 (should be at ascender 1069?)

	* uni19E9 (U+19E9): X=671.0,Y=1070.0 (should be at ascender 1069?)

	* uni19E9 (U+19E9): X=516.0,Y=714.5 (should be at cap-height 714?)

	* uni19EF (U+19EF): X=1155.5,Y=1070.5 (should be at ascender 1069?)

	* uni19F0 (U+19F0): X=489.5,Y=-294.0 (should be at descender -293?)

	* uni19F1 (U+19F1): X=237.0,Y=-1.0 (should be at baseline 0?)

	* uni19F1 (U+19F1): X=74.0,Y=-1.0 (should be at baseline 0?)

	* uni19F3 (U+19F3): X=304.5,Y=-294.0 (should be at descender -293?)

	* uni19F8 (U+19F8): X=510.0,Y=-294.0 (should be at descender -293?)

	* uni19F9 (U+19F9): X=548.0,Y=-294.0 (should be at descender -293?)

	* uni19FD (U+19FD): X=984.0,Y=-295.0 (should be at descender -293?)

	* uni19FD (U+19FD): X=984.0,Y=-295.0 (should be at descender -293?)

	* ygrave (U+1EF3): X=353.0,Y=2.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=241.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=454.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=241.0,Y=713.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* y (U+0079): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* yacute (U+00FD): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ycircumflex (U+0177): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ydieresis (U+00FF): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ygrave (U+1EF3): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<444.0,335.0>--<285.0,336.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[15] NotoSerifKhmer-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, old-permic, syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: khojki, devanagari, mahajani, hanunoo, avestan, tirhuta, saurashtra, rejang, brahmi, psalter-pahlavi, khudawadi, chakma, old-hungarian, new-tai-lue, gujarati, grantha, lepcha, gurmukhi, modi, limbu, buhid, myanmar, hanifi-rohingya, mandaic, syriac, tibetan, warang-citi, oriya, kharoshthi, sinhala, kannada, duployan, tagalog, buginese, meetei-mayek, nko, phags-pa, manichaean, tamil, cham, bengali, balinese, thaana, kaithi, javanese, takri, tai-tham, malayalam, sundanese, syloti-nagri, tagbanwa, sharada, siddham, tai-le, tai-viet, telugu, batak, yi, dogra, gunjala-gondi, pahawh-hmong, thai, tifinagh, newa, kayah-li, mongolian
 * U+2010 HYPHEN: try adding one of: lisu, coptic, kaithi, sora-sompeng, syloti-nagri, sundanese, kharoshthi, kayah-li, yi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1789
	* uni1789.a
	* uni178917B6
	* uni178917B6.a
	* uni178917C5
	* uni178917C5.a
	* uni17A2
	* uni17A217B6
	* uni17A217C5
	* uni17A3 and uni17A4
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=486.5,Y=-1.0 (should be at baseline 0?)

	* W (U+0057): X=496.0,Y=713.0 (should be at cap-height 714?)

	* W (U+0057): X=533.0,Y=713.0 (should be at cap-height 714?)

	* f (U+0066): X=349.0,Y=716.0 (should be at cap-height 714?)

	* w (U+0077): X=411.0,Y=535.0 (should be at x-height 536?)

	* w (U+0077): X=452.0,Y=535.0 (should be at x-height 536?)

	* sterling (U+00A3): X=359.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=91.0,Y=2.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=486.5,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=486.5,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=486.5,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=569.0,Y=1.0 (should be at baseline 0?)

	* Wcircumflex (U+0174): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wcircumflex (U+0174): X=533.0,Y=713.0 (should be at cap-height 714?)

	* uni17A5 (U+17A5): X=203.5,Y=713.5 (should be at cap-height 714?)

	* uni17A6 (U+17A6): X=817.5,Y=-295.0 (should be at descender -293?)

	* uni17A7 (U+17A7): X=542.0,Y=2.0 (should be at baseline 0?)

	* uni17A8 (U+17A8): X=542.0,Y=2.0 (should be at baseline 0?)

	* uni17A9 (U+17A9): X=542.0,Y=2.0 (should be at baseline 0?)

	* uni17AA (U+17AA): X=542.0,Y=2.0 (should be at baseline 0?)

	* uni17B0 (U+17B0): X=458.0,Y=2.0 (should be at baseline 0?)

	* uni17B1 (U+17B1): X=516.0,Y=2.0 (should be at baseline 0?)

	* uni17B3 (U+17B3): X=542.0,Y=2.0 (should be at baseline 0?)

	* uni17CF (U+17CF): X=-197.0,Y=1071.0 (should be at ascender 1069?)

	* uni17E9 (U+17E9): X=305.5,Y=713.5 (should be at cap-height 714?)

	* uni17E9 (U+17E9): X=469.0,Y=715.0 (should be at cap-height 714?)

	* uni17F9 (U+17F9): X=341.5,Y=-1.5 (should be at baseline 0?)

	* uni19E0 (U+19E0): X=565.0,Y=-294.0 (should be at descender -293?)

	* uni19E2 (U+19E2): X=144.5,Y=1067.0 (should be at ascender 1069?)

	* uni19E5 (U+19E5): X=467.0,Y=716.0 (should be at cap-height 714?)

	* uni19E6 (U+19E6): X=275.0,Y=712.0 (should be at cap-height 714?)

	* uni19EC (U+19EC): X=828.5,Y=1067.0 (should be at ascender 1069?)

	* uni19EF (U+19EF): X=1159.0,Y=716.0 (should be at cap-height 714?)

	* uni19F0 (U+19F0): X=543.0,Y=-294.0 (should be at descender -293?)

	* uni19F5 (U+19F5): X=467.0,Y=-295.0 (should be at descender -293?)

	* uni19F8 (U+19F8): X=543.0,Y=-294.0 (should be at descender -293?)

	* uni19FA (U+19FA): X=529.0,Y=-291.0 (should be at descender -293?)

	* uni19FB (U+19FB): X=1223.0,Y=-291.0 (should be at descender -293?)

	* uni19FB (U+19FB): X=529.0,Y=-291.0 (should be at descender -293?)

	* uni19FC (U+19FC): X=529.0,Y=-291.0 (should be at descender -293?)

	* uni19FD (U+19FD): X=529.0,Y=-291.0 (should be at descender -293?)

	* uni19FE (U+19FE): X=529.0,Y=-291.0 (should be at descender -293?)

	* uni19FF (U+19FF): X=529.0,Y=-291.0 (should be at descender -293?)

	* Wgrave (U+1E80): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wgrave (U+1E80): X=533.0,Y=713.0 (should be at cap-height 714?)

	* Wacute (U+1E82): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wacute (U+1E82): X=533.0,Y=713.0 (should be at cap-height 714?)

	* Wdieresis (U+1E84): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wdieresis (U+1E84): X=533.0,Y=713.0 (should be at cap-height 714?)

	* Euro (U+20AC): X=417.0,Y=1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[15] NotoSerifKhmer-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, old-permic, syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: khojki, devanagari, mahajani, hanunoo, avestan, tirhuta, saurashtra, rejang, brahmi, psalter-pahlavi, khudawadi, chakma, old-hungarian, new-tai-lue, gujarati, grantha, lepcha, gurmukhi, modi, limbu, buhid, myanmar, hanifi-rohingya, mandaic, syriac, tibetan, warang-citi, oriya, kharoshthi, sinhala, kannada, duployan, tagalog, buginese, meetei-mayek, nko, phags-pa, manichaean, tamil, cham, bengali, balinese, thaana, kaithi, javanese, takri, tai-tham, malayalam, sundanese, syloti-nagri, tagbanwa, sharada, siddham, tai-le, tai-viet, telugu, batak, yi, dogra, gunjala-gondi, pahawh-hmong, thai, tifinagh, newa, kayah-li, mongolian
 * U+2010 HYPHEN: try adding one of: lisu, coptic, kaithi, sora-sompeng, syloti-nagri, sundanese, kharoshthi, kayah-li, yi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1783
	* uni178317B6
	* uni178317C5
	* uni1789
	* uni1789.a
	* uni178917B6
	* uni178917B6.a
	* uni178917C5
	* uni178917C5.a
	* uni178B17B6
	* uni178B17C5
	* uni179C17C5
	* uni179F17C5
	* uni17A2
	* uni17A217B6
	* uni17A217C5
	* uni17A3
	* uni17A4
	* uni17BE
	* uni17BF
	* uni17C0
	* uni17C5 and uni17DA
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* nine (U+0039): X=147.0,Y=1.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=183.5,Y=714.5 (should be at cap-height 714?)

	* bracketright (U+005D): X=145.5,Y=714.5 (should be at cap-height 714?)

	* t (U+0074): X=297.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=412.0,Y=534.0 (should be at x-height 536?)

	* w (U+0077): X=462.0,Y=534.0 (should be at x-height 536?)

	* y (U+0079): X=269.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=354.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=79.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=460.5,Y=1.0 (should be at baseline 0?)

	* paragraph (U+00B6): X=496.0,Y=715.5 (should be at cap-height 714?)

	* Oslash (U+00D8): X=446.5,Y=714.5 (should be at cap-height 714?)

	* atilde (U+00E3): X=398.0,Y=712.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=432.0,Y=712.0 (should be at cap-height 714?)

	* eth (U+00F0): X=440.0,Y=715.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=455.0,Y=712.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=489.0,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=408.0,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=442.0,Y=712.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=269.0,Y=-1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=269.0,Y=-1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=222.5,Y=713.5 (should be at cap-height 714?)

	* ccaron (U+010D): X=318.0,Y=713.5 (should be at cap-height 714?)

	* dcroat (U+0111): X=402.5,Y=716.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=219.5,Y=713.5 (should be at cap-height 714?)

	* ecaron (U+011B): X=315.0,Y=713.5 (should be at cap-height 714?)

	* lslash (U+0142): X=98.0,Y=715.5 (should be at cap-height 714?)

	* ncaron (U+0148): X=279.5,Y=713.5 (should be at cap-height 714?)

	* ncaron (U+0148): X=375.0,Y=713.5 (should be at cap-height 714?)

	* rcaron (U+0159): X=176.5,Y=713.5 (should be at cap-height 714?)

	* rcaron (U+0159): X=272.0,Y=713.5 (should be at cap-height 714?)

	* scaron (U+0161): X=173.5,Y=713.5 (should be at cap-height 714?)

	* scaron (U+0161): X=269.0,Y=713.5 (should be at cap-height 714?)

	* tcaron (U+0165): X=297.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=269.0,Y=-1.0 (should be at baseline 0?)

	* zcaron (U+017E): X=212.5,Y=713.5 (should be at cap-height 714?)

	* zcaron (U+017E): X=308.0,Y=713.5 (should be at cap-height 714?)

	* uni021B (U+021B): X=297.0,Y=1.0 (should be at baseline 0?)

	* caron (U+02C7): X=122.5,Y=713.5 (should be at cap-height 714?)

	* caron (U+02C7): X=218.0,Y=713.5 (should be at cap-height 714?)

	* tilde (U+02DC): X=339.0,Y=712.0 (should be at cap-height 714?)

	* tilde (U+02DC): X=373.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-185.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-151.0,Y=712.0 (should be at cap-height 714?)

	* uni030C (U+030C): X=-327.5,Y=713.5 (should be at cap-height 714?)

	* uni030C (U+030C): X=-232.0,Y=713.5 (should be at cap-height 714?)

	* uni0312 (U+0312): X=56.0,Y=715.0 (should be at cap-height 714?)

	* uni1787 (U+1787): X=437.5,Y=712.5 (should be at cap-height 714?)

	* uni1790 (U+1790): X=433.0,Y=712.5 (should be at cap-height 714?)

	* uni1795 (U+1795): X=435.0,Y=712.5 (should be at cap-height 714?)

	* uni17A5 (U+17A5): X=197.5,Y=713.5 (should be at cap-height 714?)

	* uni17A5 (U+17A5): X=269.5,Y=712.5 (should be at cap-height 714?)

	* uni17A6 (U+17A6): X=821.5,Y=-293.5 (should be at descender -293?)

	* uni17AA (U+17AA): X=106.0,Y=716.0 (should be at cap-height 714?)

	* uni17CC (U+17CC): X=-470.5,Y=1070.5 (should be at ascender 1069?)

	* uni17D0 (U+17D0): X=-198.0,Y=1068.0 (should be at ascender 1069?)

	* uni17E9 (U+17E9): X=474.5,Y=716.0 (should be at cap-height 714?)

	* uni19E0 (U+19E0): X=557.0,Y=-295.0 (should be at descender -293?)

	* uni19E6 (U+19E6): X=110.5,Y=1070.5 (should be at ascender 1069?)

	* uni19F0 (U+19F0): X=543.0,Y=-295.0 (should be at descender -293?)

	* uni19F1 (U+19F1): X=93.0,Y=-1.0 (should be at baseline 0?)

	* uni19F5 (U+19F5): X=262.0,Y=2.0 (should be at baseline 0?)

	* uni19F5 (U+19F5): X=463.0,Y=-295.0 (should be at descender -293?)

	* uni19F8 (U+19F8): X=543.0,Y=-295.0 (should be at descender -293?)

	* ygrave (U+1EF3): X=269.0,Y=-1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=198.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=377.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=198.0,Y=715.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* question (U+003F): L<<200.0,201.0>--<199.0,346.0>>

	* questiondown (U+00BF): L<<203.0,215.0>--<204.0,333.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] NotoSerifKhmer-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, old-permic, syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: khojki, devanagari, mahajani, hanunoo, avestan, tirhuta, saurashtra, rejang, brahmi, psalter-pahlavi, khudawadi, chakma, old-hungarian, new-tai-lue, gujarati, grantha, lepcha, gurmukhi, modi, limbu, buhid, myanmar, hanifi-rohingya, mandaic, syriac, tibetan, warang-citi, oriya, kharoshthi, sinhala, kannada, duployan, tagalog, buginese, meetei-mayek, nko, phags-pa, manichaean, tamil, cham, bengali, balinese, thaana, kaithi, javanese, takri, tai-tham, malayalam, sundanese, syloti-nagri, tagbanwa, sharada, siddham, tai-le, tai-viet, telugu, batak, yi, dogra, gunjala-gondi, pahawh-hmong, thai, tifinagh, newa, kayah-li, mongolian
 * U+2010 HYPHEN: try adding one of: lisu, coptic, kaithi, sora-sompeng, syloti-nagri, sundanese, kharoshthi, kayah-li, yi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni178117C5
	* uni1783
	* uni178317B6
	* uni178317C5
	* uni178417B6
	* uni178417C5
	* uni178517B6
	* uni178517C5
	* uni178617B6
	* uni178617C5
	* uni178717B6
	* uni178717C5
	* uni1788
	* uni178817B6
	* uni178817C5
	* uni1789
	* uni1789.a
	* uni178917B6
	* uni178917B6.a
	* uni178917C5
	* uni178917C5.a
	* uni178A17B6
	* uni178A17C5
	* uni178B
	* uni178B17B6
	* uni178B17C5
	* uni178C17C5
	* uni1790
	* uni179017B6
	* uni179017C5
	* uni179217B6
	* uni179217C5
	* uni1794
	* uni179417B6
	* uni179417B6.high
	* uni179417C5
	* uni179417C5.high
	* uni1795
	* uni179517B6
	* uni179517C5
	* uni1798
	* uni179817B6
	* uni179817C5
	* uni1799
	* uni179917C5
	* uni179C
	* uni179C17B6
	* uni179C17C5
	* uni179D
	* uni179D17B6
	* uni179D17C5
	* uni179E
	* uni179E17B6
	* uni179E17C5
	* uni179F
	* uni179F17B6
	* uni179F17C5
	* uni17A017C5
	* uni17A2
	* uni17A217B6
	* uni17A217C5
	* uni17A3
	* uni17A4
	* uni17AB
	* uni17AC
	* uni17AF
	* uni17B0
	* uni17B717CD
	* uni17B717CD.r
	* uni17BA
	* uni17BE
	* uni17BF
	* uni17BF.right1
	* uni17C0
	* uni17C0.right1
	* uni17C1
	* uni17C2
	* uni17C3
	* uni17C4
	* uni17C5
	* uni17D21783
	* uni17D21783.low
	* uni17D21789.a
	* uni17D2179E
	* uni17D2179E.low
	* uni17D2179E17B6
	* uni17D2179E17B6.low
	* uni17D2179E17C5
	* uni17D2179E17C5.low
	* uni17DA and uni17DB
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 561 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni17B0 (U+17B0): L<<583.0,-68.0>--<583.0,-68.0>> -> L<<583.0,-68.0>--<583.0,-68.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] NotoSerifKhmer-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/khmer.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSerifKhmer/googlefonts/ttf/NotoSerifKhmer-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/khmer.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ញ៉ាំញ៊ាំ</span> (fontdiff-1782-Khmer.html)</li>


<pre>Expected: uni178917B6=0+1357|uni17BB=0@-431,-333+0|uni17C6=0@191,-114+0|uni178917B6=4+1357|uni17BB=4@-431,-333+0|uni17C6=4@191,-114+0</pre>



<pre>Got     : uni178917B6=0+1357|uni17BB=0@-431,-333+0|uni17C6=0@191,-114+0|uni178917B6=4+1357|uni17CA=4@-294,-93+0|uni17C6=4@191,-114+0</pre>



<pre>                                                                                                ^^     ++  ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2714 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M195.0,1.0L103.0,1.0L103.0,470.0Q54.0,520.0 54.0,543.0Q54.0,554.0 71.5,579.0Q89.0,604.0 117.0,630.0Q140.0,651.0 165.0,667.0Q190.0,683.0 206.0,683.0Q218.0,683.0 235.0,672.0Q252.0,661.0 276.0,640.0Q294.0,624.0 306.5,613.5Q319.0,603.0 320.0,603.0Q323.0,603.0 336.5,615.5Q350.0,628.0 368.0,645.0Q387.0,662.0 401.0,672.5Q415.0,683.0 431.0,683.0Q454.0,683.0 478.5,668.5Q503.0,654.0 523.0,630.0Q552.0,657.0 596.0,670.0Q640.0,683.0 695.0,683.0Q762.0,683.0 812.5,664.0Q863.0,645.0 889.0,605.0Q948.0,648.0 984.0,665.0Q1020.0,682.0 1048.0,682.0Q1092.0,682.0 1133.0,650.0L1227.0,576.0Q1265.0,547.0 1265.0,501.0L1265.0,0.0L1173.0,0.0L1173.0,507.0L1071.0,588.0Q1061.0,596.0 1051.0,601.5Q1041.0,607.0 1033.0,607.0Q1018.0,607.0 983.5,584.5Q949.0,562.0 914.0,537.0Q915.0,526.0 915.0,513.0L915.0,1.0L823.0,1.0L823.0,513.0Q823.0,548.0 804.5,571.0Q786.0,594.0 757.0,605.0Q728.0,616.0 695.0,616.0Q662.0,616.0 633.0,605.0Q604.0,594.0 585.5,571.0Q567.0,548.0 567.0,513.0L567.0,1.0L475.0,1.0L475.0,522.0Q475.0,549.0 455.5,570.5Q436.0,592.0 417.0,592.0Q403.0,592.0 389.5,581.0Q376.0,570.0 361.5,555.5Q347.0,541.0 331.0,530.0Q315.0,519.0 297.0,519.0Q279.0,519.0 263.0,529.5Q247.0,540.0 233.0,554.0Q219.0,568.0 207.0,578.5Q195.0,589.0 184.0,589.0Q178.0,589.0 172.0,586.0Q166.0,583.0 161.0,578.0Q149.0,568.0 149.0,559.0Q149.0,551.0 161.0,535.5Q173.0,520.0 195.0,500.0L195.0,247.0Q251.0,250.0 278.5,223.5Q306.0,197.0 306.0,152.0Q306.0,134.0 298.5,110.0Q291.0,86.0 267.5,58.5Q244.0,31.0 195.0,1.0ZM195.0,182.0L195.0,90.0Q235.0,115.0 235.0,151.0Q235.0,170.0 223.5,176.0Q212.0,182.0 195.0,182.0ZM796.0,-107.0Q796.0,-81.0 811.0,-64.5Q826.0,-48.0 855.0,-48.0Q890.0,-48.0 904.5,-71.0Q919.0,-94.0 919.0,-133.0Q919.0,-188.0 894.0,-223.0Q869.0,-258.0 829.5,-275.0Q790.0,-292.0 746.0,-292.0Q701.0,-292.0 666.0,-276.5Q631.0,-261.0 597.5,-235.5Q564.0,-210.0 525.0,-181.0Q467.0,-139.0 414.0,-122.0Q361.0,-105.0 314.0,-105.0Q265.0,-105.0 219.5,-120.5Q174.0,-136.0 139.0,-164.0L119.0,-164.0Q138.0,-105.0 194.5,-76.5Q251.0,-48.0 324.0,-48.0Q395.0,-48.0 452.0,-73.0Q509.0,-98.0 574.0,-145.0Q639.0,-192.0 677.5,-209.5Q716.0,-227.0 751.0,-227.0Q790.0,-227.0 817.5,-208.5Q845.0,-190.0 845.0,-153.0Q845.0,-107.0 796.0,-107.0Z" transform="translate(0, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(926, 460)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(1548, 679)"/>
<path d="M195.0,1.0L103.0,1.0L103.0,470.0Q54.0,520.0 54.0,543.0Q54.0,554.0 71.5,579.0Q89.0,604.0 117.0,630.0Q140.0,651.0 165.0,667.0Q190.0,683.0 206.0,683.0Q218.0,683.0 235.0,672.0Q252.0,661.0 276.0,640.0Q294.0,624.0 306.5,613.5Q319.0,603.0 320.0,603.0Q323.0,603.0 336.5,615.5Q350.0,628.0 368.0,645.0Q387.0,662.0 401.0,672.5Q415.0,683.0 431.0,683.0Q454.0,683.0 478.5,668.5Q503.0,654.0 523.0,630.0Q552.0,657.0 596.0,670.0Q640.0,683.0 695.0,683.0Q762.0,683.0 812.5,664.0Q863.0,645.0 889.0,605.0Q948.0,648.0 984.0,665.0Q1020.0,682.0 1048.0,682.0Q1092.0,682.0 1133.0,650.0L1227.0,576.0Q1265.0,547.0 1265.0,501.0L1265.0,0.0L1173.0,0.0L1173.0,507.0L1071.0,588.0Q1061.0,596.0 1051.0,601.5Q1041.0,607.0 1033.0,607.0Q1018.0,607.0 983.5,584.5Q949.0,562.0 914.0,537.0Q915.0,526.0 915.0,513.0L915.0,1.0L823.0,1.0L823.0,513.0Q823.0,548.0 804.5,571.0Q786.0,594.0 757.0,605.0Q728.0,616.0 695.0,616.0Q662.0,616.0 633.0,605.0Q604.0,594.0 585.5,571.0Q567.0,548.0 567.0,513.0L567.0,1.0L475.0,1.0L475.0,522.0Q475.0,549.0 455.5,570.5Q436.0,592.0 417.0,592.0Q403.0,592.0 389.5,581.0Q376.0,570.0 361.5,555.5Q347.0,541.0 331.0,530.0Q315.0,519.0 297.0,519.0Q279.0,519.0 263.0,529.5Q247.0,540.0 233.0,554.0Q219.0,568.0 207.0,578.5Q195.0,589.0 184.0,589.0Q178.0,589.0 172.0,586.0Q166.0,583.0 161.0,578.0Q149.0,568.0 149.0,559.0Q149.0,551.0 161.0,535.5Q173.0,520.0 195.0,500.0L195.0,247.0Q251.0,250.0 278.5,223.5Q306.0,197.0 306.0,152.0Q306.0,134.0 298.5,110.0Q291.0,86.0 267.5,58.5Q244.0,31.0 195.0,1.0ZM195.0,182.0L195.0,90.0Q235.0,115.0 235.0,151.0Q235.0,170.0 223.5,176.0Q212.0,182.0 195.0,182.0ZM796.0,-107.0Q796.0,-81.0 811.0,-64.5Q826.0,-48.0 855.0,-48.0Q890.0,-48.0 904.5,-71.0Q919.0,-94.0 919.0,-133.0Q919.0,-188.0 894.0,-223.0Q869.0,-258.0 829.5,-275.0Q790.0,-292.0 746.0,-292.0Q701.0,-292.0 666.0,-276.5Q631.0,-261.0 597.5,-235.5Q564.0,-210.0 525.0,-181.0Q467.0,-139.0 414.0,-122.0Q361.0,-105.0 314.0,-105.0Q265.0,-105.0 219.5,-120.5Q174.0,-136.0 139.0,-164.0L119.0,-164.0Q138.0,-105.0 194.5,-76.5Q251.0,-48.0 324.0,-48.0Q395.0,-48.0 452.0,-73.0Q509.0,-98.0 574.0,-145.0Q639.0,-192.0 677.5,-209.5Q716.0,-227.0 751.0,-227.0Q790.0,-227.0 817.5,-208.5Q845.0,-190.0 845.0,-153.0Q845.0,-107.0 796.0,-107.0Z" transform="translate(1357, 793)"/>
<path d="M-496.0,867.0L-569.0,824.0Q-593.0,847.0 -610.5,872.0Q-628.0,897.0 -628.0,927.0Q-628.0,951.0 -612.0,975.0Q-596.0,999.0 -552.0,1037.0Q-532.0,1054.0 -514.5,1066.5Q-497.0,1079.0 -485.0,1079.0Q-474.0,1079.0 -457.5,1065.0Q-441.0,1051.0 -413.0,1025.0Q-397.0,1010.0 -384.0,1000.0Q-371.0,990.0 -361.0,990.0Q-351.0,990.0 -337.5,1000.5Q-324.0,1011.0 -305.0,1030.0Q-282.0,1051.0 -266.0,1064.0Q-250.0,1077.0 -240.0,1077.0Q-233.0,1077.0 -221.5,1069.5Q-210.0,1062.0 -190.0,1042.0L-150.0,1002.0Q-124.0,976.0 -80.0,979.0Q-90.0,939.0 -107.5,926.0Q-125.0,913.0 -142.0,913.0Q-161.0,913.0 -175.5,923.5Q-190.0,934.0 -202.0,947.5Q-214.0,961.0 -225.0,971.5Q-236.0,982.0 -249.0,982.0Q-262.0,982.0 -275.0,970.5Q-288.0,959.0 -303.0,946.0Q-342.0,913.0 -372.0,913.0Q-387.0,913.0 -402.5,923.0Q-418.0,933.0 -441.0,951.0Q-463.0,968.0 -475.0,975.5Q-487.0,983.0 -498.0,983.0Q-514.0,983.0 -528.0,967.0Q-535.0,960.0 -540.0,951.0Q-545.0,942.0 -545.0,930.0Q-545.0,914.0 -533.0,900.0Q-521.0,886.0 -496.0,867.0Z" transform="translate(2420, 700)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(2905, 679)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2714 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M195.0,1.0L103.0,1.0L103.0,470.0Q54.0,520.0 54.0,543.0Q54.0,554.0 71.5,579.0Q89.0,604.0 117.0,630.0Q140.0,651.0 165.0,667.0Q190.0,683.0 206.0,683.0Q218.0,683.0 235.0,672.0Q252.0,661.0 276.0,640.0Q294.0,624.0 306.5,613.5Q319.0,603.0 320.0,603.0Q323.0,603.0 336.5,615.5Q350.0,628.0 368.0,645.0Q387.0,662.0 401.0,672.5Q415.0,683.0 431.0,683.0Q454.0,683.0 478.5,668.5Q503.0,654.0 523.0,630.0Q552.0,657.0 596.0,670.0Q640.0,683.0 695.0,683.0Q762.0,683.0 812.5,664.0Q863.0,645.0 889.0,605.0Q948.0,648.0 984.0,665.0Q1020.0,682.0 1048.0,682.0Q1092.0,682.0 1133.0,650.0L1227.0,576.0Q1265.0,547.0 1265.0,501.0L1265.0,0.0L1173.0,0.0L1173.0,507.0L1071.0,588.0Q1061.0,596.0 1051.0,601.5Q1041.0,607.0 1033.0,607.0Q1018.0,607.0 983.5,584.5Q949.0,562.0 914.0,537.0Q915.0,526.0 915.0,513.0L915.0,1.0L823.0,1.0L823.0,513.0Q823.0,548.0 804.5,571.0Q786.0,594.0 757.0,605.0Q728.0,616.0 695.0,616.0Q662.0,616.0 633.0,605.0Q604.0,594.0 585.5,571.0Q567.0,548.0 567.0,513.0L567.0,1.0L475.0,1.0L475.0,522.0Q475.0,549.0 455.5,570.5Q436.0,592.0 417.0,592.0Q403.0,592.0 389.5,581.0Q376.0,570.0 361.5,555.5Q347.0,541.0 331.0,530.0Q315.0,519.0 297.0,519.0Q279.0,519.0 263.0,529.5Q247.0,540.0 233.0,554.0Q219.0,568.0 207.0,578.5Q195.0,589.0 184.0,589.0Q178.0,589.0 172.0,586.0Q166.0,583.0 161.0,578.0Q149.0,568.0 149.0,559.0Q149.0,551.0 161.0,535.5Q173.0,520.0 195.0,500.0L195.0,247.0Q251.0,250.0 278.5,223.5Q306.0,197.0 306.0,152.0Q306.0,134.0 298.5,110.0Q291.0,86.0 267.5,58.5Q244.0,31.0 195.0,1.0ZM195.0,182.0L195.0,90.0Q235.0,115.0 235.0,151.0Q235.0,170.0 223.5,176.0Q212.0,182.0 195.0,182.0ZM796.0,-107.0Q796.0,-81.0 811.0,-64.5Q826.0,-48.0 855.0,-48.0Q890.0,-48.0 904.5,-71.0Q919.0,-94.0 919.0,-133.0Q919.0,-188.0 894.0,-223.0Q869.0,-258.0 829.5,-275.0Q790.0,-292.0 746.0,-292.0Q701.0,-292.0 666.0,-276.5Q631.0,-261.0 597.5,-235.5Q564.0,-210.0 525.0,-181.0Q467.0,-139.0 414.0,-122.0Q361.0,-105.0 314.0,-105.0Q265.0,-105.0 219.5,-120.5Q174.0,-136.0 139.0,-164.0L119.0,-164.0Q138.0,-105.0 194.5,-76.5Q251.0,-48.0 324.0,-48.0Q395.0,-48.0 452.0,-73.0Q509.0,-98.0 574.0,-145.0Q639.0,-192.0 677.5,-209.5Q716.0,-227.0 751.0,-227.0Q790.0,-227.0 817.5,-208.5Q845.0,-190.0 845.0,-153.0Q845.0,-107.0 796.0,-107.0Z" transform="translate(0, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(926, 460)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(1548, 679)"/>
<path d="M195.0,1.0L103.0,1.0L103.0,470.0Q54.0,520.0 54.0,543.0Q54.0,554.0 71.5,579.0Q89.0,604.0 117.0,630.0Q140.0,651.0 165.0,667.0Q190.0,683.0 206.0,683.0Q218.0,683.0 235.0,672.0Q252.0,661.0 276.0,640.0Q294.0,624.0 306.5,613.5Q319.0,603.0 320.0,603.0Q323.0,603.0 336.5,615.5Q350.0,628.0 368.0,645.0Q387.0,662.0 401.0,672.5Q415.0,683.0 431.0,683.0Q454.0,683.0 478.5,668.5Q503.0,654.0 523.0,630.0Q552.0,657.0 596.0,670.0Q640.0,683.0 695.0,683.0Q762.0,683.0 812.5,664.0Q863.0,645.0 889.0,605.0Q948.0,648.0 984.0,665.0Q1020.0,682.0 1048.0,682.0Q1092.0,682.0 1133.0,650.0L1227.0,576.0Q1265.0,547.0 1265.0,501.0L1265.0,0.0L1173.0,0.0L1173.0,507.0L1071.0,588.0Q1061.0,596.0 1051.0,601.5Q1041.0,607.0 1033.0,607.0Q1018.0,607.0 983.5,584.5Q949.0,562.0 914.0,537.0Q915.0,526.0 915.0,513.0L915.0,1.0L823.0,1.0L823.0,513.0Q823.0,548.0 804.5,571.0Q786.0,594.0 757.0,605.0Q728.0,616.0 695.0,616.0Q662.0,616.0 633.0,605.0Q604.0,594.0 585.5,571.0Q567.0,548.0 567.0,513.0L567.0,1.0L475.0,1.0L475.0,522.0Q475.0,549.0 455.5,570.5Q436.0,592.0 417.0,592.0Q403.0,592.0 389.5,581.0Q376.0,570.0 361.5,555.5Q347.0,541.0 331.0,530.0Q315.0,519.0 297.0,519.0Q279.0,519.0 263.0,529.5Q247.0,540.0 233.0,554.0Q219.0,568.0 207.0,578.5Q195.0,589.0 184.0,589.0Q178.0,589.0 172.0,586.0Q166.0,583.0 161.0,578.0Q149.0,568.0 149.0,559.0Q149.0,551.0 161.0,535.5Q173.0,520.0 195.0,500.0L195.0,247.0Q251.0,250.0 278.5,223.5Q306.0,197.0 306.0,152.0Q306.0,134.0 298.5,110.0Q291.0,86.0 267.5,58.5Q244.0,31.0 195.0,1.0ZM195.0,182.0L195.0,90.0Q235.0,115.0 235.0,151.0Q235.0,170.0 223.5,176.0Q212.0,182.0 195.0,182.0ZM796.0,-107.0Q796.0,-81.0 811.0,-64.5Q826.0,-48.0 855.0,-48.0Q890.0,-48.0 904.5,-71.0Q919.0,-94.0 919.0,-133.0Q919.0,-188.0 894.0,-223.0Q869.0,-258.0 829.5,-275.0Q790.0,-292.0 746.0,-292.0Q701.0,-292.0 666.0,-276.5Q631.0,-261.0 597.5,-235.5Q564.0,-210.0 525.0,-181.0Q467.0,-139.0 414.0,-122.0Q361.0,-105.0 314.0,-105.0Q265.0,-105.0 219.5,-120.5Q174.0,-136.0 139.0,-164.0L119.0,-164.0Q138.0,-105.0 194.5,-76.5Q251.0,-48.0 324.0,-48.0Q395.0,-48.0 452.0,-73.0Q509.0,-98.0 574.0,-145.0Q639.0,-192.0 677.5,-209.5Q716.0,-227.0 751.0,-227.0Q790.0,-227.0 817.5,-208.5Q845.0,-190.0 845.0,-153.0Q845.0,-107.0 796.0,-107.0Z" transform="translate(1357, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(2283, 460)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(2905, 679)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">តាម​ការ​កំណត់​របស់​ក្បួន​ពី​មុន​នោះ​គឺ</span> (fontdiff-khm-sample-20161201.html)</li>


<pre>Expected: uni178F17B6=0+981|uni1798=2+654|space=3+0|uni178017B6=4+981|uni179A=6+377|space=7+0|uni1780=8+633|uni17C6=8@40,-126+0|uni178E=10+1327|uni178F=11+633|uni17CB=11@38,-66+0|space=13+0|uni179A=14+377|uni1794=15+654|uni179F=16+1001|uni17CB=16@20,-66+0|space=18+0|uni1780=19+633|uni17D21794=19+354|uni17BD=19@-123,-336+0|uni1793=23+652|space=24+0|uni1796=25+657|uni17B8=25@-2,-94+0|space=27+0|uni1798=28+654|uni17BB=28@-116,-16+0|uni1793=30+652|space=31+0|uni17C1=32+339|uni179317B6=32+1010|uni17C7=32+386|space=35+0|uni1782=36+633|uni17BA=36@40,-94+0</pre>



<pre>Got     : uni178F17B6=0+981|uni1798=2+654|space=3+0|uni178017B6=4+981|uni179A=6+377|space=7+0|uni1780=8+633|uni17C6=8@40,-94+0|uni178E=10+1327|uni178F=11+633|uni17CB=11@38,-66+0|space=13+0|uni179A=14+377|uni1794=15+654|uni179F=16+1001|uni17CB=16@20,-66+0|space=18+0|uni1780=19+633|uni17D21794=19+354|uni17BD=19@-123,-336+0|uni1793=23+652|space=24+0|uni1796=25+657|uni17B8=25@-2,-94+0|space=27+0|uni1798=28+654|uni17BB=28@-116,-16+0|uni1793=30+652|space=31+0|uni17C1=32+339|uni179317B6=32+1010|uni17C7=32+386|space=35+0|uni1782=36+633|uni17BA=36@40,-94+0</pre>



<pre>                                                                                                                          ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13588 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM177.0,0.0L85.0,0.0L85.0,316.0Q85.0,354.0 115.5,386.5Q146.0,419.0 196.5,439.0Q247.0,459.0 307.0,459.0Q369.0,459.0 419.5,438.5Q470.0,418.0 499.5,385.5Q529.0,353.0 529.0,316.0L529.0,0.0L437.0,0.0L437.0,316.0Q437.0,336.0 419.5,353.5Q402.0,371.0 373.0,381.5Q344.0,392.0 308.0,392.0Q252.0,392.0 214.5,368.5Q177.0,345.0 177.0,316.0L177.0,246.0Q233.0,249.0 260.5,222.5Q288.0,196.0 288.0,151.0Q288.0,133.0 280.5,109.0Q273.0,85.0 249.5,57.5Q226.0,30.0 177.0,0.0ZM177.0,181.0L177.0,89.0Q217.0,114.0 217.0,150.0Q217.0,169.0 205.5,175.0Q194.0,181.0 177.0,181.0Z" transform="translate(0, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(981, 793)"/>
<path d="" transform="translate(1635, 793)"/>
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM539.0,316.0L539.0,0.0L447.0,0.0L447.0,316.0Q447.0,336.0 429.5,353.5Q412.0,371.0 383.0,381.5Q354.0,392.0 318.0,392.0Q262.0,392.0 224.5,368.5Q187.0,345.0 187.0,316.0L187.0,0.0L95.0,0.0L95.0,316.0Q95.0,354.0 125.5,386.5Q156.0,419.0 206.5,439.0Q257.0,459.0 317.0,459.0Q379.0,459.0 429.5,438.5Q480.0,418.0 509.5,385.5Q539.0,353.0 539.0,316.0Z" transform="translate(1635, 793)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(2616, 793)"/>
<path d="" transform="translate(2993, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(2993, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(3666, 699)"/>
<path d="M128.0,515.0L194.0,463.0L194.0,246.0Q250.0,249.0 277.5,222.5Q305.0,196.0 305.0,151.0Q305.0,133.0 297.5,109.0Q290.0,85.0 266.5,57.5Q243.0,30.0 194.0,0.0L102.0,0.0L102.0,438.0Q69.0,467.0 58.5,480.5Q48.0,494.0 48.0,504.0Q48.0,514.0 56.5,526.0Q65.0,538.0 87.0,559.0Q109.0,580.0 148.0,614.0Q194.0,654.0 227.5,668.0Q261.0,682.0 297.0,682.0Q330.0,682.0 366.0,670.0Q402.0,658.0 449.0,622.0Q499.0,584.0 520.5,546.5Q542.0,509.0 542.0,463.0L542.0,91.0L669.0,196.0L797.0,91.0L797.0,438.0Q764.0,467.0 753.5,481.0Q743.0,495.0 743.0,505.0Q743.0,515.0 751.5,527.0Q760.0,539.0 782.0,559.5Q804.0,580.0 843.0,614.0Q889.0,654.0 920.5,668.0Q952.0,682.0 989.0,682.0Q1021.0,682.0 1059.0,670.0Q1097.0,658.0 1144.0,622.0Q1194.0,584.0 1215.5,546.5Q1237.0,509.0 1237.0,463.0L1237.0,0.0L1145.0,0.0L1145.0,464.0Q1145.0,489.0 1130.0,515.5Q1115.0,542.0 1091.0,564.5Q1067.0,587.0 1038.5,601.0Q1010.0,615.0 983.0,615.0Q952.0,615.0 916.5,592.0Q881.0,569.0 823.0,515.0L889.0,463.0L889.0,0.0L797.0,0.0L669.0,105.0L542.0,0.0L450.0,0.0L450.0,464.0Q450.0,489.0 435.5,515.5Q421.0,542.0 397.0,564.5Q373.0,587.0 344.5,601.0Q316.0,615.0 289.0,615.0Q258.0,615.0 222.0,592.0Q186.0,569.0 128.0,515.0ZM194.0,181.0L194.0,89.0Q234.0,114.0 234.0,150.0Q234.0,169.0 222.5,175.0Q211.0,181.0 194.0,181.0Z" transform="translate(3626, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4953, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(5624, 727)"/>
<path d="" transform="translate(5586, 793)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(5586, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(5963, 793)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(6617, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(7638, 727)"/>
<path d="" transform="translate(7618, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(7618, 793)"/>
<path d="M-196.0,-317.0L-196.0,-113.0Q-196.0,-83.0 -178.0,-66.0Q-160.0,-49.0 -127.0,-49.0Q-90.0,-49.0 -70.5,-67.5Q-51.0,-86.0 -51.0,-111.0Q-51.0,-133.0 -65.5,-151.5Q-80.0,-170.0 -104.0,-170.0L-104.0,-227.0L34.0,-131.0L162.0,-227.0L162.0,424.0Q125.0,454.0 107.0,471.0Q89.0,488.0 83.0,497.5Q77.0,507.0 77.0,514.0Q77.0,524.0 86.5,538.0Q96.0,552.0 121.0,584.0Q146.0,616.0 192.0,680.0Q224.0,659.0 245.0,647.0Q266.0,635.0 285.5,631.0Q305.0,627.0 330.0,629.0Q330.0,604.0 312.5,580.5Q295.0,557.0 266.0,557.0Q253.0,557.0 235.5,564.0Q218.0,571.0 192.0,590.0L149.0,532.0L254.0,447.0L254.0,-317.0L162.0,-317.0L34.0,-222.0L-104.0,-317.0L-196.0,-317.0Z" transform="translate(8251, 793)"/>
<path d="M-361.0,-221.0Q-361.0,-204.0 -353.5,-183.5Q-346.0,-163.0 -333.0,-138.0L-329.0,-130.0Q-349.0,-130.0 -358.5,-119.5Q-368.0,-109.0 -368.0,-93.0Q-368.0,-73.0 -353.5,-61.0Q-339.0,-49.0 -308.0,-49.0Q-281.0,-49.0 -262.0,-59.5Q-243.0,-70.0 -243.0,-97.0Q-243.0,-110.0 -249.5,-126.0Q-256.0,-142.0 -264.0,-160.0Q-273.0,-179.0 -278.5,-199.0Q-284.0,-219.0 -269.0,-219.0Q-257.0,-219.0 -238.0,-209.0Q-219.0,-199.0 -190.0,-175.0Q-181.0,-199.0 -171.5,-209.0Q-162.0,-219.0 -150.0,-219.0Q-130.0,-219.0 -116.5,-197.5Q-103.0,-176.0 -99.0,-143.0Q-96.0,-117.0 -99.0,-94.0Q-102.0,-71.0 -109.0,-49.0Q-70.0,-37.0 -46.5,-44.5Q-23.0,-52.0 -23.0,-99.0Q-23.0,-125.0 -31.0,-155.0Q-39.0,-185.0 -54.0,-212.0Q-69.0,-239.0 -90.5,-256.5Q-112.0,-274.0 -139.0,-274.0Q-161.0,-274.0 -177.0,-263.5Q-193.0,-253.0 -204.0,-240.0Q-226.0,-253.0 -248.5,-263.5Q-271.0,-274.0 -297.0,-274.0Q-325.0,-274.0 -343.0,-260.5Q-361.0,-247.0 -361.0,-221.0Z" transform="translate(8482, 457)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(8605, 793)"/>
<path d="" transform="translate(9257, 793)"/>
<path d="M149.0,558.0Q149.0,550.0 161.0,534.5Q173.0,519.0 195.0,499.0L195.0,246.0Q251.0,249.0 278.5,222.5Q306.0,196.0 306.0,151.0Q306.0,133.0 298.5,109.0Q291.0,85.0 267.5,57.5Q244.0,30.0 195.0,0.0L103.0,0.0L103.0,469.0Q54.0,519.0 54.0,542.0Q54.0,553.0 71.5,578.0Q89.0,603.0 117.0,629.0Q140.0,650.0 165.0,666.0Q190.0,682.0 206.0,682.0Q218.0,682.0 235.0,671.0Q252.0,660.0 276.0,639.0Q294.0,623.0 306.5,612.5Q319.0,602.0 320.0,602.0Q323.0,602.0 336.5,614.5Q350.0,627.0 368.0,644.0Q387.0,661.0 401.0,671.5Q415.0,682.0 431.0,682.0Q462.0,682.0 493.0,658.0Q524.0,634.0 545.5,597.0Q567.0,560.0 567.0,521.0L567.0,0.0L475.0,0.0L475.0,521.0Q475.0,548.0 455.5,569.5Q436.0,591.0 417.0,591.0Q403.0,591.0 389.5,580.0Q376.0,569.0 361.5,554.5Q347.0,540.0 331.0,529.0Q315.0,518.0 297.0,518.0Q279.0,518.0 263.0,528.5Q247.0,539.0 233.0,553.0Q219.0,567.0 207.0,577.5Q195.0,588.0 184.0,588.0Q178.0,588.0 172.0,585.0Q166.0,582.0 161.0,577.0Q149.0,567.0 149.0,558.0ZM195.0,181.0L195.0,89.0Q235.0,114.0 235.0,150.0Q235.0,169.0 223.5,175.0Q212.0,181.0 195.0,181.0Z" transform="translate(9257, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(9912, 699)"/>
<path d="" transform="translate(9914, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(9914, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(10452, 777)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(10568, 793)"/>
<path d="" transform="translate(11220, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(11220, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q403.0,682.0 457.0,659.0Q511.0,636.0 538.0,602.0Q598.0,647.0 635.0,664.5Q672.0,682.0 701.0,682.0Q745.0,682.0 786.0,650.0L880.0,576.0Q918.0,547.0 918.0,501.0L918.0,0.0L826.0,0.0L826.0,507.0L724.0,588.0Q714.0,596.0 704.0,601.5Q694.0,607.0 686.0,607.0Q676.0,607.0 656.0,596.0Q636.0,585.0 611.0,568.0Q586.0,551.0 562.0,534.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(11559, 793)"/>
<path d="M193.0,445.0Q162.0,445.0 136.5,460.5Q111.0,476.0 95.5,501.5Q80.0,527.0 80.0,558.0Q80.0,589.0 95.5,614.5Q111.0,640.0 136.5,655.5Q162.0,671.0 193.0,671.0Q224.0,671.0 249.5,655.5Q275.0,640.0 290.5,614.5Q306.0,589.0 306.0,558.0Q306.0,527.0 290.5,501.5Q275.0,476.0 249.5,460.5Q224.0,445.0 193.0,445.0ZM192.0,506.0Q214.0,506.0 229.5,521.0Q245.0,536.0 245.0,558.0Q245.0,580.0 230.0,596.0Q215.0,612.0 192.0,612.0Q170.0,612.0 155.0,596.5Q140.0,581.0 140.0,558.0Q140.0,536.0 155.5,521.0Q171.0,506.0 192.0,506.0ZM193.0,12.0Q162.0,12.0 136.5,27.5Q111.0,43.0 95.5,68.5Q80.0,94.0 80.0,125.0Q80.0,156.0 95.5,181.5Q111.0,207.0 136.5,222.5Q162.0,238.0 193.0,238.0Q224.0,238.0 249.5,222.5Q275.0,207.0 290.5,181.5Q306.0,156.0 306.0,125.0Q306.0,94.0 290.5,68.5Q275.0,43.0 249.5,27.5Q224.0,12.0 193.0,12.0ZM192.0,73.0Q214.0,73.0 229.5,88.0Q245.0,103.0 245.0,125.0Q245.0,147.0 230.0,163.0Q215.0,179.0 192.0,179.0Q170.0,179.0 155.0,163.5Q140.0,148.0 140.0,125.0Q140.0,103.0 155.5,88.0Q171.0,73.0 192.0,73.0Z" transform="translate(12569, 793)"/>
<path d="" transform="translate(12955, 793)"/>
<path d="M175.0,470.0L102.0,427.0Q78.0,450.0 60.5,475.0Q43.0,500.0 43.0,530.0Q43.0,554.0 59.0,578.0Q75.0,602.0 119.0,640.0Q139.0,657.0 156.5,669.5Q174.0,682.0 186.0,682.0Q197.0,682.0 213.5,668.0Q230.0,654.0 258.0,628.0Q274.0,613.0 287.0,603.0Q300.0,593.0 310.0,593.0Q320.0,593.0 333.5,603.5Q347.0,614.0 366.0,633.0Q389.0,654.0 405.0,667.0Q421.0,680.0 431.0,680.0Q438.0,680.0 449.5,672.5Q461.0,665.0 481.0,645.0L521.0,605.0Q547.0,579.0 591.0,582.0Q581.0,542.0 563.5,529.0Q546.0,516.0 529.0,516.0Q510.0,516.0 495.5,526.5Q481.0,537.0 469.0,550.5Q457.0,564.0 446.0,574.5Q435.0,585.0 422.0,585.0Q409.0,585.0 396.0,573.5Q383.0,562.0 368.0,549.0Q329.0,516.0 299.0,516.0Q284.0,516.0 268.5,526.0Q253.0,536.0 230.0,554.0Q208.0,571.0 196.0,578.5Q184.0,586.0 173.0,586.0Q157.0,586.0 143.0,570.0Q136.0,563.0 131.0,554.0Q126.0,545.0 126.0,533.0Q126.0,517.0 138.0,503.0Q150.0,489.0 175.0,470.0ZM186.0,316.0L186.0,146.0Q221.0,199.0 246.5,221.5Q272.0,244.0 304.0,244.0Q327.0,244.0 340.5,234.0Q354.0,224.0 354.0,203.0Q354.0,186.0 344.0,172.5Q334.0,159.0 314.0,159.0Q297.0,159.0 291.5,165.5Q286.0,172.0 276.0,172.0Q269.0,172.0 261.0,165.0Q253.0,158.0 240.0,138.0L186.0,53.0L186.0,0.0L94.0,0.0L94.0,316.0Q94.0,354.0 124.5,386.5Q155.0,419.0 205.5,439.0Q256.0,459.0 316.0,459.0Q378.0,459.0 428.5,438.5Q479.0,418.0 508.5,385.5Q538.0,353.0 538.0,316.0L538.0,0.0L446.0,0.0L446.0,316.0Q446.0,336.0 428.5,353.5Q411.0,371.0 382.0,381.5Q353.0,392.0 317.0,392.0Q261.0,392.0 223.5,368.5Q186.0,345.0 186.0,316.0Z" transform="translate(12955, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-377.0,1050.0 -332.0,1035.0L-332.0,1123.0L-256.0,1123.0L-256.0,1001.0Q-233.0,987.0 -210.0,969.0L-210.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(13628, 699)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13588 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM177.0,0.0L85.0,0.0L85.0,316.0Q85.0,354.0 115.5,386.5Q146.0,419.0 196.5,439.0Q247.0,459.0 307.0,459.0Q369.0,459.0 419.5,438.5Q470.0,418.0 499.5,385.5Q529.0,353.0 529.0,316.0L529.0,0.0L437.0,0.0L437.0,316.0Q437.0,336.0 419.5,353.5Q402.0,371.0 373.0,381.5Q344.0,392.0 308.0,392.0Q252.0,392.0 214.5,368.5Q177.0,345.0 177.0,316.0L177.0,246.0Q233.0,249.0 260.5,222.5Q288.0,196.0 288.0,151.0Q288.0,133.0 280.5,109.0Q273.0,85.0 249.5,57.5Q226.0,30.0 177.0,0.0ZM177.0,181.0L177.0,89.0Q217.0,114.0 217.0,150.0Q217.0,169.0 205.5,175.0Q194.0,181.0 177.0,181.0Z" transform="translate(0, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(981, 793)"/>
<path d="" transform="translate(1635, 793)"/>
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM539.0,316.0L539.0,0.0L447.0,0.0L447.0,316.0Q447.0,336.0 429.5,353.5Q412.0,371.0 383.0,381.5Q354.0,392.0 318.0,392.0Q262.0,392.0 224.5,368.5Q187.0,345.0 187.0,316.0L187.0,0.0L95.0,0.0L95.0,316.0Q95.0,354.0 125.5,386.5Q156.0,419.0 206.5,439.0Q257.0,459.0 317.0,459.0Q379.0,459.0 429.5,438.5Q480.0,418.0 509.5,385.5Q539.0,353.0 539.0,316.0Z" transform="translate(1635, 793)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(2616, 793)"/>
<path d="" transform="translate(2993, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(2993, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(3666, 667)"/>
<path d="M128.0,515.0L194.0,463.0L194.0,246.0Q250.0,249.0 277.5,222.5Q305.0,196.0 305.0,151.0Q305.0,133.0 297.5,109.0Q290.0,85.0 266.5,57.5Q243.0,30.0 194.0,0.0L102.0,0.0L102.0,438.0Q69.0,467.0 58.5,480.5Q48.0,494.0 48.0,504.0Q48.0,514.0 56.5,526.0Q65.0,538.0 87.0,559.0Q109.0,580.0 148.0,614.0Q194.0,654.0 227.5,668.0Q261.0,682.0 297.0,682.0Q330.0,682.0 366.0,670.0Q402.0,658.0 449.0,622.0Q499.0,584.0 520.5,546.5Q542.0,509.0 542.0,463.0L542.0,91.0L669.0,196.0L797.0,91.0L797.0,438.0Q764.0,467.0 753.5,481.0Q743.0,495.0 743.0,505.0Q743.0,515.0 751.5,527.0Q760.0,539.0 782.0,559.5Q804.0,580.0 843.0,614.0Q889.0,654.0 920.5,668.0Q952.0,682.0 989.0,682.0Q1021.0,682.0 1059.0,670.0Q1097.0,658.0 1144.0,622.0Q1194.0,584.0 1215.5,546.5Q1237.0,509.0 1237.0,463.0L1237.0,0.0L1145.0,0.0L1145.0,464.0Q1145.0,489.0 1130.0,515.5Q1115.0,542.0 1091.0,564.5Q1067.0,587.0 1038.5,601.0Q1010.0,615.0 983.0,615.0Q952.0,615.0 916.5,592.0Q881.0,569.0 823.0,515.0L889.0,463.0L889.0,0.0L797.0,0.0L669.0,105.0L542.0,0.0L450.0,0.0L450.0,464.0Q450.0,489.0 435.5,515.5Q421.0,542.0 397.0,564.5Q373.0,587.0 344.5,601.0Q316.0,615.0 289.0,615.0Q258.0,615.0 222.0,592.0Q186.0,569.0 128.0,515.0ZM194.0,181.0L194.0,89.0Q234.0,114.0 234.0,150.0Q234.0,169.0 222.5,175.0Q211.0,181.0 194.0,181.0Z" transform="translate(3626, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4953, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(5624, 727)"/>
<path d="" transform="translate(5586, 793)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(5586, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(5963, 793)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(6617, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(7638, 727)"/>
<path d="" transform="translate(7618, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(7618, 793)"/>
<path d="M-196.0,-317.0L-196.0,-113.0Q-196.0,-83.0 -178.0,-66.0Q-160.0,-49.0 -127.0,-49.0Q-90.0,-49.0 -70.5,-67.5Q-51.0,-86.0 -51.0,-111.0Q-51.0,-133.0 -65.5,-151.5Q-80.0,-170.0 -104.0,-170.0L-104.0,-227.0L34.0,-131.0L162.0,-227.0L162.0,424.0Q125.0,454.0 107.0,471.0Q89.0,488.0 83.0,497.5Q77.0,507.0 77.0,514.0Q77.0,524.0 86.5,538.0Q96.0,552.0 121.0,584.0Q146.0,616.0 192.0,680.0Q224.0,659.0 245.0,647.0Q266.0,635.0 285.5,631.0Q305.0,627.0 330.0,629.0Q330.0,604.0 312.5,580.5Q295.0,557.0 266.0,557.0Q253.0,557.0 235.5,564.0Q218.0,571.0 192.0,590.0L149.0,532.0L254.0,447.0L254.0,-317.0L162.0,-317.0L34.0,-222.0L-104.0,-317.0L-196.0,-317.0Z" transform="translate(8251, 793)"/>
<path d="M-361.0,-221.0Q-361.0,-204.0 -353.5,-183.5Q-346.0,-163.0 -333.0,-138.0L-329.0,-130.0Q-349.0,-130.0 -358.5,-119.5Q-368.0,-109.0 -368.0,-93.0Q-368.0,-73.0 -353.5,-61.0Q-339.0,-49.0 -308.0,-49.0Q-281.0,-49.0 -262.0,-59.5Q-243.0,-70.0 -243.0,-97.0Q-243.0,-110.0 -249.5,-126.0Q-256.0,-142.0 -264.0,-160.0Q-273.0,-179.0 -278.5,-199.0Q-284.0,-219.0 -269.0,-219.0Q-257.0,-219.0 -238.0,-209.0Q-219.0,-199.0 -190.0,-175.0Q-181.0,-199.0 -171.5,-209.0Q-162.0,-219.0 -150.0,-219.0Q-130.0,-219.0 -116.5,-197.5Q-103.0,-176.0 -99.0,-143.0Q-96.0,-117.0 -99.0,-94.0Q-102.0,-71.0 -109.0,-49.0Q-70.0,-37.0 -46.5,-44.5Q-23.0,-52.0 -23.0,-99.0Q-23.0,-125.0 -31.0,-155.0Q-39.0,-185.0 -54.0,-212.0Q-69.0,-239.0 -90.5,-256.5Q-112.0,-274.0 -139.0,-274.0Q-161.0,-274.0 -177.0,-263.5Q-193.0,-253.0 -204.0,-240.0Q-226.0,-253.0 -248.5,-263.5Q-271.0,-274.0 -297.0,-274.0Q-325.0,-274.0 -343.0,-260.5Q-361.0,-247.0 -361.0,-221.0Z" transform="translate(8482, 457)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(8605, 793)"/>
<path d="" transform="translate(9257, 793)"/>
<path d="M149.0,558.0Q149.0,550.0 161.0,534.5Q173.0,519.0 195.0,499.0L195.0,246.0Q251.0,249.0 278.5,222.5Q306.0,196.0 306.0,151.0Q306.0,133.0 298.5,109.0Q291.0,85.0 267.5,57.5Q244.0,30.0 195.0,0.0L103.0,0.0L103.0,469.0Q54.0,519.0 54.0,542.0Q54.0,553.0 71.5,578.0Q89.0,603.0 117.0,629.0Q140.0,650.0 165.0,666.0Q190.0,682.0 206.0,682.0Q218.0,682.0 235.0,671.0Q252.0,660.0 276.0,639.0Q294.0,623.0 306.5,612.5Q319.0,602.0 320.0,602.0Q323.0,602.0 336.5,614.5Q350.0,627.0 368.0,644.0Q387.0,661.0 401.0,671.5Q415.0,682.0 431.0,682.0Q462.0,682.0 493.0,658.0Q524.0,634.0 545.5,597.0Q567.0,560.0 567.0,521.0L567.0,0.0L475.0,0.0L475.0,521.0Q475.0,548.0 455.5,569.5Q436.0,591.0 417.0,591.0Q403.0,591.0 389.5,580.0Q376.0,569.0 361.5,554.5Q347.0,540.0 331.0,529.0Q315.0,518.0 297.0,518.0Q279.0,518.0 263.0,528.5Q247.0,539.0 233.0,553.0Q219.0,567.0 207.0,577.5Q195.0,588.0 184.0,588.0Q178.0,588.0 172.0,585.0Q166.0,582.0 161.0,577.0Q149.0,567.0 149.0,558.0ZM195.0,181.0L195.0,89.0Q235.0,114.0 235.0,150.0Q235.0,169.0 223.5,175.0Q212.0,181.0 195.0,181.0Z" transform="translate(9257, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(9912, 699)"/>
<path d="" transform="translate(9914, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(9914, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(10452, 777)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(10568, 793)"/>
<path d="" transform="translate(11220, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(11220, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q403.0,682.0 457.0,659.0Q511.0,636.0 538.0,602.0Q598.0,647.0 635.0,664.5Q672.0,682.0 701.0,682.0Q745.0,682.0 786.0,650.0L880.0,576.0Q918.0,547.0 918.0,501.0L918.0,0.0L826.0,0.0L826.0,507.0L724.0,588.0Q714.0,596.0 704.0,601.5Q694.0,607.0 686.0,607.0Q676.0,607.0 656.0,596.0Q636.0,585.0 611.0,568.0Q586.0,551.0 562.0,534.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(11559, 793)"/>
<path d="M193.0,445.0Q162.0,445.0 136.5,460.5Q111.0,476.0 95.5,501.5Q80.0,527.0 80.0,558.0Q80.0,589.0 95.5,614.5Q111.0,640.0 136.5,655.5Q162.0,671.0 193.0,671.0Q224.0,671.0 249.5,655.5Q275.0,640.0 290.5,614.5Q306.0,589.0 306.0,558.0Q306.0,527.0 290.5,501.5Q275.0,476.0 249.5,460.5Q224.0,445.0 193.0,445.0ZM192.0,506.0Q214.0,506.0 229.5,521.0Q245.0,536.0 245.0,558.0Q245.0,580.0 230.0,596.0Q215.0,612.0 192.0,612.0Q170.0,612.0 155.0,596.5Q140.0,581.0 140.0,558.0Q140.0,536.0 155.5,521.0Q171.0,506.0 192.0,506.0ZM193.0,12.0Q162.0,12.0 136.5,27.5Q111.0,43.0 95.5,68.5Q80.0,94.0 80.0,125.0Q80.0,156.0 95.5,181.5Q111.0,207.0 136.5,222.5Q162.0,238.0 193.0,238.0Q224.0,238.0 249.5,222.5Q275.0,207.0 290.5,181.5Q306.0,156.0 306.0,125.0Q306.0,94.0 290.5,68.5Q275.0,43.0 249.5,27.5Q224.0,12.0 193.0,12.0ZM192.0,73.0Q214.0,73.0 229.5,88.0Q245.0,103.0 245.0,125.0Q245.0,147.0 230.0,163.0Q215.0,179.0 192.0,179.0Q170.0,179.0 155.0,163.5Q140.0,148.0 140.0,125.0Q140.0,103.0 155.5,88.0Q171.0,73.0 192.0,73.0Z" transform="translate(12569, 793)"/>
<path d="" transform="translate(12955, 793)"/>
<path d="M175.0,470.0L102.0,427.0Q78.0,450.0 60.5,475.0Q43.0,500.0 43.0,530.0Q43.0,554.0 59.0,578.0Q75.0,602.0 119.0,640.0Q139.0,657.0 156.5,669.5Q174.0,682.0 186.0,682.0Q197.0,682.0 213.5,668.0Q230.0,654.0 258.0,628.0Q274.0,613.0 287.0,603.0Q300.0,593.0 310.0,593.0Q320.0,593.0 333.5,603.5Q347.0,614.0 366.0,633.0Q389.0,654.0 405.0,667.0Q421.0,680.0 431.0,680.0Q438.0,680.0 449.5,672.5Q461.0,665.0 481.0,645.0L521.0,605.0Q547.0,579.0 591.0,582.0Q581.0,542.0 563.5,529.0Q546.0,516.0 529.0,516.0Q510.0,516.0 495.5,526.5Q481.0,537.0 469.0,550.5Q457.0,564.0 446.0,574.5Q435.0,585.0 422.0,585.0Q409.0,585.0 396.0,573.5Q383.0,562.0 368.0,549.0Q329.0,516.0 299.0,516.0Q284.0,516.0 268.5,526.0Q253.0,536.0 230.0,554.0Q208.0,571.0 196.0,578.5Q184.0,586.0 173.0,586.0Q157.0,586.0 143.0,570.0Q136.0,563.0 131.0,554.0Q126.0,545.0 126.0,533.0Q126.0,517.0 138.0,503.0Q150.0,489.0 175.0,470.0ZM186.0,316.0L186.0,146.0Q221.0,199.0 246.5,221.5Q272.0,244.0 304.0,244.0Q327.0,244.0 340.5,234.0Q354.0,224.0 354.0,203.0Q354.0,186.0 344.0,172.5Q334.0,159.0 314.0,159.0Q297.0,159.0 291.5,165.5Q286.0,172.0 276.0,172.0Q269.0,172.0 261.0,165.0Q253.0,158.0 240.0,138.0L186.0,53.0L186.0,0.0L94.0,0.0L94.0,316.0Q94.0,354.0 124.5,386.5Q155.0,419.0 205.5,439.0Q256.0,459.0 316.0,459.0Q378.0,459.0 428.5,438.5Q479.0,418.0 508.5,385.5Q538.0,353.0 538.0,316.0L538.0,0.0L446.0,0.0L446.0,316.0Q446.0,336.0 428.5,353.5Q411.0,371.0 382.0,381.5Q353.0,392.0 317.0,392.0Q261.0,392.0 223.5,368.5Q186.0,345.0 186.0,316.0Z" transform="translate(12955, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-377.0,1050.0 -332.0,1035.0L-332.0,1123.0L-256.0,1123.0L-256.0,1001.0Q-233.0,987.0 -210.0,969.0L-210.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(13628, 699)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ាំ</span> (fontdiff-khm-sample-20161201.html)</li>


<pre>Expected: uni25CC=0+635|uni17B6=0+306|uni17C6=0+0</pre>



<pre>Got     : uni25CC=0+635|uni17B6=0+306|uni17C6=0@85,-114+0</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 941 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M316.0,462.0Q306.0,462.0 299.0,469.0Q292.0,476.0 292.0,486.0Q292.0,496.0 299.0,503.0Q306.0,510.0 316.0,510.0Q326.0,510.0 333.0,503.0Q340.0,496.0 340.0,486.0Q340.0,476.0 333.0,469.0Q326.0,462.0 316.0,462.0ZM219.0,438.0Q209.0,438.0 202.0,445.0Q195.0,452.0 195.0,462.0Q195.0,472.0 202.0,479.0Q209.0,486.0 219.0,486.0Q229.0,486.0 236.0,479.0Q243.0,472.0 243.0,462.0Q243.0,452.0 236.0,445.0Q229.0,438.0 219.0,438.0ZM413.0,438.0Q403.0,438.0 396.0,445.0Q389.0,452.0 389.0,462.0Q389.0,472.0 396.0,479.0Q403.0,486.0 413.0,486.0Q423.0,486.0 430.0,479.0Q437.0,472.0 437.0,462.0Q437.0,452.0 430.0,445.0Q423.0,438.0 413.0,438.0ZM148.0,368.0Q138.0,368.0 131.0,375.0Q124.0,382.0 124.0,392.0Q124.0,402.0 131.0,409.0Q138.0,416.0 148.0,416.0Q158.0,416.0 165.0,409.0Q172.0,402.0 172.0,392.0Q172.0,382.0 165.0,375.0Q158.0,368.0 148.0,368.0ZM483.0,366.0Q473.0,366.0 466.0,373.0Q459.0,380.0 459.0,390.0Q459.0,400.0 466.0,407.0Q473.0,414.0 483.0,414.0Q493.0,414.0 500.0,407.0Q507.0,400.0 507.0,390.0Q507.0,380.0 500.0,373.0Q493.0,366.0 483.0,366.0ZM122.0,267.0Q112.0,267.0 105.0,274.0Q98.0,281.0 98.0,291.0Q98.0,301.0 105.0,308.0Q112.0,315.0 122.0,315.0Q132.0,315.0 139.0,308.0Q146.0,301.0 146.0,291.0Q146.0,281.0 139.0,274.0Q132.0,267.0 122.0,267.0ZM513.0,267.0Q503.0,267.0 496.0,274.0Q489.0,281.0 489.0,291.0Q489.0,301.0 496.0,308.0Q503.0,315.0 513.0,315.0Q523.0,315.0 530.0,308.0Q537.0,301.0 537.0,291.0Q537.0,281.0 530.0,274.0Q523.0,267.0 513.0,267.0ZM485.0,173.0Q475.0,173.0 468.0,180.0Q461.0,187.0 461.0,197.0Q461.0,207.0 468.0,214.0Q475.0,221.0 485.0,221.0Q495.0,221.0 502.0,214.0Q509.0,207.0 509.0,197.0Q509.0,187.0 502.0,180.0Q495.0,173.0 485.0,173.0ZM146.0,172.0Q136.0,172.0 129.0,179.0Q122.0,186.0 122.0,196.0Q122.0,206.0 129.0,213.0Q136.0,220.0 146.0,220.0Q156.0,220.0 163.0,213.0Q170.0,206.0 170.0,196.0Q170.0,186.0 163.0,179.0Q156.0,172.0 146.0,172.0ZM414.0,101.0Q404.0,101.0 397.0,108.0Q390.0,115.0 390.0,125.0Q390.0,135.0 397.0,142.0Q404.0,149.0 414.0,149.0Q424.0,149.0 431.0,142.0Q438.0,135.0 438.0,125.0Q438.0,115.0 431.0,108.0Q424.0,101.0 414.0,101.0ZM219.0,100.0Q209.0,100.0 202.0,107.0Q195.0,114.0 195.0,124.0Q195.0,134.0 202.0,141.0Q209.0,148.0 219.0,148.0Q229.0,148.0 236.0,141.0Q243.0,134.0 243.0,124.0Q243.0,114.0 236.0,107.0Q229.0,100.0 219.0,100.0ZM316.0,73.0Q306.0,73.0 299.0,80.0Q292.0,87.0 292.0,97.0Q292.0,107.0 299.0,114.0Q306.0,121.0 316.0,121.0Q326.0,121.0 333.0,114.0Q340.0,107.0 340.0,97.0Q340.0,87.0 333.0,80.0Q326.0,73.0 316.0,73.0Z" transform="translate(0, 793)"/>
<path d="M-98.0,562.0Q-112.0,571.0 -118.5,583.5Q-125.0,596.0 -125.0,607.0Q-125.0,630.0 -94.0,651.0Q-73.0,665.0 -49.0,673.5Q-25.0,682.0 -3.0,682.0Q41.0,682.0 82.0,650.0L176.0,576.0Q214.0,547.0 214.0,501.0L214.0,0.0L122.0,0.0L122.0,507.0L23.0,586.0Q-2.0,607.0 -20.0,607.0Q-30.0,607.0 -45.5,598.5Q-61.0,590.0 -98.0,562.0Z" transform="translate(635, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(1026, 679)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 941 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M316.0,462.0Q306.0,462.0 299.0,469.0Q292.0,476.0 292.0,486.0Q292.0,496.0 299.0,503.0Q306.0,510.0 316.0,510.0Q326.0,510.0 333.0,503.0Q340.0,496.0 340.0,486.0Q340.0,476.0 333.0,469.0Q326.0,462.0 316.0,462.0ZM219.0,438.0Q209.0,438.0 202.0,445.0Q195.0,452.0 195.0,462.0Q195.0,472.0 202.0,479.0Q209.0,486.0 219.0,486.0Q229.0,486.0 236.0,479.0Q243.0,472.0 243.0,462.0Q243.0,452.0 236.0,445.0Q229.0,438.0 219.0,438.0ZM413.0,438.0Q403.0,438.0 396.0,445.0Q389.0,452.0 389.0,462.0Q389.0,472.0 396.0,479.0Q403.0,486.0 413.0,486.0Q423.0,486.0 430.0,479.0Q437.0,472.0 437.0,462.0Q437.0,452.0 430.0,445.0Q423.0,438.0 413.0,438.0ZM148.0,368.0Q138.0,368.0 131.0,375.0Q124.0,382.0 124.0,392.0Q124.0,402.0 131.0,409.0Q138.0,416.0 148.0,416.0Q158.0,416.0 165.0,409.0Q172.0,402.0 172.0,392.0Q172.0,382.0 165.0,375.0Q158.0,368.0 148.0,368.0ZM483.0,366.0Q473.0,366.0 466.0,373.0Q459.0,380.0 459.0,390.0Q459.0,400.0 466.0,407.0Q473.0,414.0 483.0,414.0Q493.0,414.0 500.0,407.0Q507.0,400.0 507.0,390.0Q507.0,380.0 500.0,373.0Q493.0,366.0 483.0,366.0ZM122.0,267.0Q112.0,267.0 105.0,274.0Q98.0,281.0 98.0,291.0Q98.0,301.0 105.0,308.0Q112.0,315.0 122.0,315.0Q132.0,315.0 139.0,308.0Q146.0,301.0 146.0,291.0Q146.0,281.0 139.0,274.0Q132.0,267.0 122.0,267.0ZM513.0,267.0Q503.0,267.0 496.0,274.0Q489.0,281.0 489.0,291.0Q489.0,301.0 496.0,308.0Q503.0,315.0 513.0,315.0Q523.0,315.0 530.0,308.0Q537.0,301.0 537.0,291.0Q537.0,281.0 530.0,274.0Q523.0,267.0 513.0,267.0ZM485.0,173.0Q475.0,173.0 468.0,180.0Q461.0,187.0 461.0,197.0Q461.0,207.0 468.0,214.0Q475.0,221.0 485.0,221.0Q495.0,221.0 502.0,214.0Q509.0,207.0 509.0,197.0Q509.0,187.0 502.0,180.0Q495.0,173.0 485.0,173.0ZM146.0,172.0Q136.0,172.0 129.0,179.0Q122.0,186.0 122.0,196.0Q122.0,206.0 129.0,213.0Q136.0,220.0 146.0,220.0Q156.0,220.0 163.0,213.0Q170.0,206.0 170.0,196.0Q170.0,186.0 163.0,179.0Q156.0,172.0 146.0,172.0ZM414.0,101.0Q404.0,101.0 397.0,108.0Q390.0,115.0 390.0,125.0Q390.0,135.0 397.0,142.0Q404.0,149.0 414.0,149.0Q424.0,149.0 431.0,142.0Q438.0,135.0 438.0,125.0Q438.0,115.0 431.0,108.0Q424.0,101.0 414.0,101.0ZM219.0,100.0Q209.0,100.0 202.0,107.0Q195.0,114.0 195.0,124.0Q195.0,134.0 202.0,141.0Q209.0,148.0 219.0,148.0Q229.0,148.0 236.0,141.0Q243.0,134.0 243.0,124.0Q243.0,114.0 236.0,107.0Q229.0,100.0 219.0,100.0ZM316.0,73.0Q306.0,73.0 299.0,80.0Q292.0,87.0 292.0,97.0Q292.0,107.0 299.0,114.0Q306.0,121.0 316.0,121.0Q326.0,121.0 333.0,114.0Q340.0,107.0 340.0,97.0Q340.0,87.0 333.0,80.0Q326.0,73.0 316.0,73.0Z" transform="translate(0, 793)"/>
<path d="M-98.0,562.0Q-112.0,571.0 -118.5,583.5Q-125.0,596.0 -125.0,607.0Q-125.0,630.0 -94.0,651.0Q-73.0,665.0 -49.0,673.5Q-25.0,682.0 -3.0,682.0Q41.0,682.0 82.0,650.0L176.0,576.0Q214.0,547.0 214.0,501.0L214.0,0.0L122.0,0.0L122.0,507.0L23.0,586.0Q-2.0,607.0 -20.0,607.0Q-30.0,607.0 -45.5,598.5Q-61.0,590.0 -98.0,562.0Z" transform="translate(635, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(941, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(២១-១)+៤</span> (fontdiff-khm-sample-20161201.html)</li>


<pre>Expected: parenleft=0+346|uni17E2=1+765|uni17E1=2+683|hyphen=3+310|uni17E1=4+683|parenright=5+346|.notdef=6+634|uni17E4=7+758</pre>



<pre>Got     : parenleft=0+346|uni17E2=1+765|uni17E1=2+683|hyphen=3+310|uni17E1=4+683|parenright=5+346|plus=6+559|uni17E4=7+758</pre>



<pre>                                                                                                  ^^^^^^^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4450 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M314.0,-128.0Q222.0,-91.0 165.5,-33.5Q109.0,24.0 83.0,110.5Q57.0,197.0 57.0,317.0Q57.0,437.0 83.0,522.5Q109.0,608.0 165.5,666.0Q222.0,724.0 314.0,760.0L314.0,715.0Q245.0,674.0 212.5,611.0Q180.0,548.0 170.5,472.5Q161.0,397.0 161.0,317.0Q161.0,238.0 170.5,162.0Q180.0,86.0 212.5,23.0Q245.0,-40.0 314.0,-82.0L314.0,-128.0Z" transform="translate(0, 793)"/>
<path d="M545.0,682.0Q556.0,682.0 575.5,670.5Q595.0,659.0 615.5,639.0Q636.0,619.0 650.5,592.5Q665.0,566.0 665.0,536.0L665.0,195.0Q665.0,140.0 634.5,95.5Q604.0,51.0 544.0,25.5Q484.0,0.0 396.0,0.0L372.0,0.0Q284.0,0.0 224.0,25.5Q164.0,51.0 133.5,95.5Q103.0,140.0 103.0,195.0L103.0,618.0Q103.0,637.0 95.0,657.0Q87.0,677.0 71.0,691.0Q55.0,705.0 30.0,705.0Q30.0,737.0 52.0,758.5Q74.0,780.0 105.0,780.0Q147.0,780.0 171.0,740.0Q195.0,700.0 195.0,638.0L195.0,195.0Q195.0,133.0 240.5,100.0Q286.0,67.0 372.0,67.0L396.0,67.0Q482.0,67.0 527.5,100.0Q573.0,133.0 573.0,195.0L573.0,536.0Q573.0,558.0 565.0,575.5Q557.0,593.0 544.0,593.0Q526.0,593.0 470.0,537.0Q441.0,566.0 425.0,579.5Q409.0,593.0 398.0,593.0Q384.0,593.0 375.0,573.0Q366.0,553.0 366.0,536.0L366.0,447.0Q422.0,447.0 449.5,420.0Q477.0,393.0 477.0,352.0Q477.0,336.0 469.5,317.0Q462.0,298.0 438.5,274.5Q415.0,251.0 366.0,221.0L274.0,221.0L274.0,536.0Q274.0,566.0 288.5,592.5Q303.0,619.0 323.0,639.0Q343.0,659.0 363.0,670.5Q383.0,682.0 393.0,682.0Q405.0,682.0 426.5,665.5Q448.0,649.0 470.0,617.0Q493.0,649.0 513.0,665.5Q533.0,682.0 545.0,682.0ZM406.0,353.0Q406.0,368.0 394.5,375.0Q383.0,382.0 366.0,382.0L366.0,310.0Q386.0,322.0 396.0,331.0Q406.0,340.0 406.0,353.0Z" transform="translate(346, 793)"/>
<path d="M583.0,389.0Q583.0,248.0 544.0,162.5Q505.0,77.0 429.0,38.5Q353.0,0.0 241.0,0.0L192.0,0.0L192.0,67.0L241.0,67.0Q335.0,67.0 389.5,97.0Q444.0,127.0 467.5,197.5Q491.0,268.0 491.0,389.0Q491.0,478.0 468.5,527.0Q446.0,576.0 408.0,595.5Q370.0,615.0 322.0,615.0Q243.0,615.0 202.5,572.0Q162.0,529.0 162.0,456.0Q162.0,402.0 183.0,366.5Q204.0,331.0 248.0,331.0Q292.0,331.0 305.0,365.0Q286.0,368.0 275.5,382.5Q265.0,397.0 265.0,416.0Q265.0,442.0 282.5,458.5Q300.0,475.0 328.0,475.0Q387.0,475.0 387.0,402.0Q387.0,365.0 371.5,333.5Q356.0,302.0 323.5,283.0Q291.0,264.0 241.0,264.0Q165.0,264.0 117.5,313.5Q70.0,363.0 70.0,447.0Q70.0,509.0 99.5,562.5Q129.0,616.0 185.5,649.0Q242.0,682.0 321.0,682.0Q400.0,682.0 458.5,651.5Q517.0,621.0 550.0,556.5Q583.0,492.0 583.0,389.0Z" transform="translate(1111, 793)"/>
<path d="M25.0,235.0L25.0,310.0L285.0,310.0L285.0,235.0L25.0,235.0Z" transform="translate(1794, 793)"/>
<path d="M583.0,389.0Q583.0,248.0 544.0,162.5Q505.0,77.0 429.0,38.5Q353.0,0.0 241.0,0.0L192.0,0.0L192.0,67.0L241.0,67.0Q335.0,67.0 389.5,97.0Q444.0,127.0 467.5,197.5Q491.0,268.0 491.0,389.0Q491.0,478.0 468.5,527.0Q446.0,576.0 408.0,595.5Q370.0,615.0 322.0,615.0Q243.0,615.0 202.5,572.0Q162.0,529.0 162.0,456.0Q162.0,402.0 183.0,366.5Q204.0,331.0 248.0,331.0Q292.0,331.0 305.0,365.0Q286.0,368.0 275.5,382.5Q265.0,397.0 265.0,416.0Q265.0,442.0 282.5,458.5Q300.0,475.0 328.0,475.0Q387.0,475.0 387.0,402.0Q387.0,365.0 371.5,333.5Q356.0,302.0 323.5,283.0Q291.0,264.0 241.0,264.0Q165.0,264.0 117.5,313.5Q70.0,363.0 70.0,447.0Q70.0,509.0 99.5,562.5Q129.0,616.0 185.5,649.0Q242.0,682.0 321.0,682.0Q400.0,682.0 458.5,651.5Q517.0,621.0 550.0,556.5Q583.0,492.0 583.0,389.0Z" transform="translate(2104, 793)"/>
<path d="M32.0,-128.0L32.0,-82.0Q101.0,-40.0 133.5,23.0Q166.0,86.0 175.5,162.0Q185.0,238.0 185.0,317.0Q185.0,397.0 175.5,472.5Q166.0,548.0 133.5,611.0Q101.0,674.0 32.0,715.0L32.0,760.0Q124.0,724.0 180.5,666.0Q237.0,608.0 263.0,522.5Q289.0,437.0 289.0,317.0Q289.0,197.0 263.0,110.5Q237.0,24.0 180.5,-33.5Q124.0,-91.0 32.0,-128.0Z" transform="translate(2787, 793)"/>
<path d="M249.0,143.0L249.0,328.0L65.0,328.0L65.0,387.0L249.0,387.0L249.0,572.0L309.0,572.0L309.0,387.0L494.0,387.0L494.0,328.0L309.0,328.0L309.0,143.0L249.0,143.0Z" transform="translate(3133, 793)"/>
<path d="M110.0,146.0L110.0,379.0Q110.0,462.0 155.0,517.0Q200.0,572.0 288.0,600.0L426.0,645.0Q531.0,680.0 531.0,722.0Q531.0,738.0 519.5,745.5Q508.0,753.0 482.0,753.0Q482.0,780.0 499.5,800.0Q517.0,820.0 551.0,820.0Q586.0,820.0 604.5,796.5Q623.0,773.0 623.0,735.0Q623.0,682.0 581.0,645.5Q539.0,609.0 456.0,583.0L307.0,536.0Q255.0,520.0 228.5,479.5Q202.0,439.0 202.0,379.0L202.0,146.0Q202.0,127.0 219.5,109.0Q237.0,91.0 266.5,79.0Q296.0,67.0 330.0,67.0L531.0,67.0Q494.0,123.0 476.0,162.0Q458.0,201.0 458.0,220.0L458.0,397.0Q458.0,438.0 483.0,463.0Q508.0,488.0 553.0,488.0Q608.0,488.0 633.0,453.5Q658.0,419.0 658.0,371.0Q658.0,333.0 642.0,308.5Q626.0,284.0 601.0,272.5Q576.0,261.0 550.0,261.0L550.0,220.0Q550.0,170.0 586.0,116.0L623.0,61.0L623.0,0.0L330.0,0.0Q265.0,0.0 215.0,23.0Q165.0,46.0 137.5,80.0Q110.0,114.0 110.0,146.0ZM550.0,322.0Q577.0,322.0 588.5,341.0Q600.0,360.0 600.0,377.0Q600.0,392.0 589.5,411.0Q579.0,430.0 550.0,436.0L550.0,322.0Z" transform="translate(3692, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4525 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M314.0,-128.0Q222.0,-91.0 165.5,-33.5Q109.0,24.0 83.0,110.5Q57.0,197.0 57.0,317.0Q57.0,437.0 83.0,522.5Q109.0,608.0 165.5,666.0Q222.0,724.0 314.0,760.0L314.0,715.0Q245.0,674.0 212.5,611.0Q180.0,548.0 170.5,472.5Q161.0,397.0 161.0,317.0Q161.0,238.0 170.5,162.0Q180.0,86.0 212.5,23.0Q245.0,-40.0 314.0,-82.0L314.0,-128.0Z" transform="translate(0, 793)"/>
<path d="M545.0,682.0Q556.0,682.0 575.5,670.5Q595.0,659.0 615.5,639.0Q636.0,619.0 650.5,592.5Q665.0,566.0 665.0,536.0L665.0,195.0Q665.0,140.0 634.5,95.5Q604.0,51.0 544.0,25.5Q484.0,0.0 396.0,0.0L372.0,0.0Q284.0,0.0 224.0,25.5Q164.0,51.0 133.5,95.5Q103.0,140.0 103.0,195.0L103.0,618.0Q103.0,637.0 95.0,657.0Q87.0,677.0 71.0,691.0Q55.0,705.0 30.0,705.0Q30.0,737.0 52.0,758.5Q74.0,780.0 105.0,780.0Q147.0,780.0 171.0,740.0Q195.0,700.0 195.0,638.0L195.0,195.0Q195.0,133.0 240.5,100.0Q286.0,67.0 372.0,67.0L396.0,67.0Q482.0,67.0 527.5,100.0Q573.0,133.0 573.0,195.0L573.0,536.0Q573.0,558.0 565.0,575.5Q557.0,593.0 544.0,593.0Q526.0,593.0 470.0,537.0Q441.0,566.0 425.0,579.5Q409.0,593.0 398.0,593.0Q384.0,593.0 375.0,573.0Q366.0,553.0 366.0,536.0L366.0,447.0Q422.0,447.0 449.5,420.0Q477.0,393.0 477.0,352.0Q477.0,336.0 469.5,317.0Q462.0,298.0 438.5,274.5Q415.0,251.0 366.0,221.0L274.0,221.0L274.0,536.0Q274.0,566.0 288.5,592.5Q303.0,619.0 323.0,639.0Q343.0,659.0 363.0,670.5Q383.0,682.0 393.0,682.0Q405.0,682.0 426.5,665.5Q448.0,649.0 470.0,617.0Q493.0,649.0 513.0,665.5Q533.0,682.0 545.0,682.0ZM406.0,353.0Q406.0,368.0 394.5,375.0Q383.0,382.0 366.0,382.0L366.0,310.0Q386.0,322.0 396.0,331.0Q406.0,340.0 406.0,353.0Z" transform="translate(346, 793)"/>
<path d="M583.0,389.0Q583.0,248.0 544.0,162.5Q505.0,77.0 429.0,38.5Q353.0,0.0 241.0,0.0L192.0,0.0L192.0,67.0L241.0,67.0Q335.0,67.0 389.5,97.0Q444.0,127.0 467.5,197.5Q491.0,268.0 491.0,389.0Q491.0,478.0 468.5,527.0Q446.0,576.0 408.0,595.5Q370.0,615.0 322.0,615.0Q243.0,615.0 202.5,572.0Q162.0,529.0 162.0,456.0Q162.0,402.0 183.0,366.5Q204.0,331.0 248.0,331.0Q292.0,331.0 305.0,365.0Q286.0,368.0 275.5,382.5Q265.0,397.0 265.0,416.0Q265.0,442.0 282.5,458.5Q300.0,475.0 328.0,475.0Q387.0,475.0 387.0,402.0Q387.0,365.0 371.5,333.5Q356.0,302.0 323.5,283.0Q291.0,264.0 241.0,264.0Q165.0,264.0 117.5,313.5Q70.0,363.0 70.0,447.0Q70.0,509.0 99.5,562.5Q129.0,616.0 185.5,649.0Q242.0,682.0 321.0,682.0Q400.0,682.0 458.5,651.5Q517.0,621.0 550.0,556.5Q583.0,492.0 583.0,389.0Z" transform="translate(1111, 793)"/>
<path d="M25.0,235.0L25.0,310.0L285.0,310.0L285.0,235.0L25.0,235.0Z" transform="translate(1794, 793)"/>
<path d="M583.0,389.0Q583.0,248.0 544.0,162.5Q505.0,77.0 429.0,38.5Q353.0,0.0 241.0,0.0L192.0,0.0L192.0,67.0L241.0,67.0Q335.0,67.0 389.5,97.0Q444.0,127.0 467.5,197.5Q491.0,268.0 491.0,389.0Q491.0,478.0 468.5,527.0Q446.0,576.0 408.0,595.5Q370.0,615.0 322.0,615.0Q243.0,615.0 202.5,572.0Q162.0,529.0 162.0,456.0Q162.0,402.0 183.0,366.5Q204.0,331.0 248.0,331.0Q292.0,331.0 305.0,365.0Q286.0,368.0 275.5,382.5Q265.0,397.0 265.0,416.0Q265.0,442.0 282.5,458.5Q300.0,475.0 328.0,475.0Q387.0,475.0 387.0,402.0Q387.0,365.0 371.5,333.5Q356.0,302.0 323.5,283.0Q291.0,264.0 241.0,264.0Q165.0,264.0 117.5,313.5Q70.0,363.0 70.0,447.0Q70.0,509.0 99.5,562.5Q129.0,616.0 185.5,649.0Q242.0,682.0 321.0,682.0Q400.0,682.0 458.5,651.5Q517.0,621.0 550.0,556.5Q583.0,492.0 583.0,389.0Z" transform="translate(2104, 793)"/>
<path d="M32.0,-128.0L32.0,-82.0Q101.0,-40.0 133.5,23.0Q166.0,86.0 175.5,162.0Q185.0,238.0 185.0,317.0Q185.0,397.0 175.5,472.5Q166.0,548.0 133.5,611.0Q101.0,674.0 32.0,715.0L32.0,760.0Q124.0,724.0 180.5,666.0Q237.0,608.0 263.0,522.5Q289.0,437.0 289.0,317.0Q289.0,197.0 263.0,110.5Q237.0,24.0 180.5,-33.5Q124.0,-91.0 32.0,-128.0Z" transform="translate(2787, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(3133, 793)"/>
<path d="M110.0,146.0L110.0,379.0Q110.0,462.0 155.0,517.0Q200.0,572.0 288.0,600.0L426.0,645.0Q531.0,680.0 531.0,722.0Q531.0,738.0 519.5,745.5Q508.0,753.0 482.0,753.0Q482.0,780.0 499.5,800.0Q517.0,820.0 551.0,820.0Q586.0,820.0 604.5,796.5Q623.0,773.0 623.0,735.0Q623.0,682.0 581.0,645.5Q539.0,609.0 456.0,583.0L307.0,536.0Q255.0,520.0 228.5,479.5Q202.0,439.0 202.0,379.0L202.0,146.0Q202.0,127.0 219.5,109.0Q237.0,91.0 266.5,79.0Q296.0,67.0 330.0,67.0L531.0,67.0Q494.0,123.0 476.0,162.0Q458.0,201.0 458.0,220.0L458.0,397.0Q458.0,438.0 483.0,463.0Q508.0,488.0 553.0,488.0Q608.0,488.0 633.0,453.5Q658.0,419.0 658.0,371.0Q658.0,333.0 642.0,308.5Q626.0,284.0 601.0,272.5Q576.0,261.0 550.0,261.0L550.0,220.0Q550.0,170.0 586.0,116.0L623.0,61.0L623.0,0.0L330.0,0.0Q265.0,0.0 215.0,23.0Q165.0,46.0 137.5,80.0Q110.0,114.0 110.0,146.0ZM550.0,322.0Q577.0,322.0 588.5,341.0Q600.0,360.0 600.0,377.0Q600.0,392.0 589.5,411.0Q579.0,430.0 550.0,436.0L550.0,322.0Z" transform="translate(3767, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">=</span> (fontdiff-khm-sample-20161201.html)</li>


<pre>Expected: .notdef=0+634</pre>



<pre>Got     : equal=0+559</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 559 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M65.0,426.0L65.0,485.0L494.0,485.0L494.0,426.0L65.0,426.0ZM65.0,229.0L65.0,288.0L494.0,288.0L494.0,229.0L65.0,229.0Z" transform="translate(0, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 634 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(0, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">Google</span> (fontdiff-km-google-app-info.html)</li>


<pre>Expected: .notdef=0+634|.notdef=1+634|.notdef=2+634|.notdef=3+634|.notdef=4+634|.notdef=5+634</pre>



<pre>Got     : G=0+714|o=1+577|o=2+577|g=3+538|l=4+310|e=5+535</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3251 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M401.0,-10.0Q285.0,-10.0 208.5,36.0Q132.0,82.0 94.5,164.5Q57.0,247.0 57.0,358.0Q57.0,466.0 96.5,548.5Q136.0,631.0 214.0,677.5Q292.0,724.0 407.0,724.0Q518.0,724.0 573.0,692.0Q628.0,660.0 628.0,612.0Q628.0,580.0 601.0,561.0Q574.0,542.0 535.0,542.0Q535.0,573.0 522.5,602.5Q510.0,632.0 481.0,651.5Q452.0,671.0 403.0,671.0Q276.0,671.0 222.0,589.5Q168.0,508.0 168.0,358.0Q168.0,208.0 224.5,127.5Q281.0,47.0 417.0,47.0Q446.0,47.0 473.0,50.0Q500.0,53.0 521.0,59.0L521.0,220.0Q521.0,264.0 496.5,276.0Q472.0,288.0 439.0,288.0L435.0,288.0L435.0,330.0L695.0,330.0L695.0,288.0L691.0,288.0Q663.0,288.0 642.5,275.5Q622.0,263.0 622.0,216.0L622.0,36.0Q572.0,13.0 519.0,1.5Q466.0,-10.0 401.0,-10.0Z" transform="translate(0, 793)"/>
<path d="M287.0,-10.0Q179.0,-10.0 117.0,59.0Q55.0,128.0 55.0,269.0Q55.0,409.0 114.5,477.5Q174.0,546.0 290.0,546.0Q398.0,546.0 460.0,477.5Q522.0,409.0 522.0,269.0Q522.0,128.0 462.5,59.0Q403.0,-10.0 287.0,-10.0ZM289.0,42.0Q364.0,42.0 394.5,99.5Q425.0,157.0 425.0,269.0Q425.0,381.0 394.0,437.0Q363.0,493.0 288.0,493.0Q213.0,493.0 182.5,437.0Q152.0,381.0 152.0,269.0Q152.0,157.0 183.0,99.5Q214.0,42.0 289.0,42.0Z" transform="translate(714, 793)"/>
<path d="M287.0,-10.0Q179.0,-10.0 117.0,59.0Q55.0,128.0 55.0,269.0Q55.0,409.0 114.5,477.5Q174.0,546.0 290.0,546.0Q398.0,546.0 460.0,477.5Q522.0,409.0 522.0,269.0Q522.0,128.0 462.5,59.0Q403.0,-10.0 287.0,-10.0ZM289.0,42.0Q364.0,42.0 394.5,99.5Q425.0,157.0 425.0,269.0Q425.0,381.0 394.0,437.0Q363.0,493.0 288.0,493.0Q213.0,493.0 182.5,437.0Q152.0,381.0 152.0,269.0Q152.0,157.0 183.0,99.5Q214.0,42.0 289.0,42.0Z" transform="translate(1291, 793)"/>
<path d="M231.0,-240.0Q127.0,-240.0 75.0,-201.5Q23.0,-163.0 23.0,-94.0Q23.0,-35.0 61.0,-5.0Q99.0,25.0 148.0,34.0Q128.0,43.0 110.5,63.5Q93.0,84.0 93.0,116.0Q93.0,146.0 108.5,168.0Q124.0,190.0 158.0,210.0Q115.0,228.0 91.5,269.5Q68.0,311.0 68.0,361.0Q68.0,447.0 115.0,496.5Q162.0,546.0 256.0,546.0Q292.0,546.0 324.0,536.0Q356.0,526.0 370.0,513.0Q384.0,529.0 409.0,548.0Q434.0,567.0 467.0,567.0Q497.0,567.0 511.5,551.5Q526.0,536.0 526.0,515.0Q526.0,494.0 513.5,478.5Q501.0,463.0 473.0,463.0Q473.0,474.0 466.5,485.5Q460.0,497.0 440.0,497.0Q417.0,497.0 397.0,485.0Q414.0,464.0 425.0,435.5Q436.0,407.0 436.0,364.0Q436.0,290.0 391.5,241.0Q347.0,192.0 256.0,192.0Q244.0,192.0 228.5,193.5Q213.0,195.0 203.0,197.0Q184.0,187.0 170.0,172.0Q156.0,157.0 156.0,134.0Q156.0,116.0 167.5,106.0Q179.0,96.0 218.0,96.0L331.0,96.0Q420.0,96.0 458.0,54.0Q496.0,12.0 496.0,-53.0Q496.0,-139.0 431.5,-189.5Q367.0,-240.0 231.0,-240.0ZM253.0,240.0Q302.0,240.0 322.0,270.0Q342.0,300.0 342.0,365.0Q342.0,433.0 321.5,465.0Q301.0,497.0 252.0,497.0Q204.0,497.0 183.0,464.0Q162.0,431.0 162.0,364.0Q162.0,300.0 183.5,270.0Q205.0,240.0 253.0,240.0ZM233.0,-191.0Q305.0,-191.0 344.0,-175.5Q383.0,-160.0 398.5,-132.5Q414.0,-105.0 414.0,-70.0Q414.0,-24.0 388.0,-8.5Q362.0,7.0 312.0,7.0L214.0,7.0Q186.0,7.0 161.0,-0.5Q136.0,-8.0 120.0,-28.0Q104.0,-48.0 104.0,-88.0Q104.0,-117.0 115.0,-140.5Q126.0,-164.0 154.0,-177.5Q182.0,-191.0 233.0,-191.0Z" transform="translate(1868, 793)"/>
<path d="M13.0,0.0L13.0,42.0L26.0,42.0Q60.0,42.0 84.0,54.5Q108.0,67.0 108.0,114.0L108.0,650.0Q108.0,694.0 83.5,706.0Q59.0,718.0 26.0,718.0L13.0,718.0L13.0,760.0L202.0,760.0L202.0,114.0Q202.0,67.0 226.0,54.5Q250.0,42.0 284.0,42.0L297.0,42.0L297.0,0.0L13.0,0.0Z" transform="translate(2406, 793)"/>
<path d="M287.0,-10.0Q178.0,-10.0 116.5,62.0Q55.0,134.0 55.0,264.0Q55.0,404.0 113.0,475.0Q171.0,546.0 277.0,546.0Q374.0,546.0 429.5,486.0Q485.0,426.0 485.0,307.0L485.0,261.0L152.0,261.0Q154.0,152.0 191.5,102.5Q229.0,53.0 301.0,53.0Q353.0,53.0 389.5,74.5Q426.0,96.0 444.0,123.0Q451.0,120.0 457.0,111.0Q463.0,102.0 463.0,89.0Q463.0,69.0 444.0,46.0Q425.0,23.0 386.0,6.5Q347.0,-10.0 287.0,-10.0ZM384.0,315.0Q384.0,395.0 359.5,443.5Q335.0,492.0 275.0,492.0Q220.0,492.0 189.5,446.5Q159.0,401.0 154.0,315.0L384.0,315.0Z" transform="translate(2716, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3804 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(0, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(634, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(1268, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(1902, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(2536, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(3170, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">រយៈពេលធ្វើដំណើរទៅមក</span> (fontdiff-km-google-app-info.html)</li>


<pre>Expected: uni179A=0+377|uni1799=1+1025|uni17C8=1+274|uni17C1=3+339|uni1796=3+657|uni179B=5+1001|uni17C1=6+339|uni1792=6+658|uni17D2179C=6@-3,-16+0|uni17B8=6@30,-94+0|uni178A=10+656|uni17C6=10@9,-84+0|uni17C1=12+339|uni178E=12+1327|uni17B8=12@-305,-94+0|uni179A=14+377|uni17C1=15+339|uni179117C5=15+1045|uni1798=17+654|uni1780=18+633</pre>



<pre>Got     : uni179A=0+377|uni1799=1+1025|uni17C8=1+274|uni17C1=3+339|uni1796=3+657|uni179B=5+1001|uni17C1=6+339|uni1792=6+658|uni17D2179C=6@-3,-16+0|uni17B8=6@30,-94+0|uni178A=10+656|uni17C6=10@29,-14+0|uni17C1=12+339|uni178E=12+1327|uni17B8=12@-305,-94+0|uni179A=14+377|uni17C1=15+339|uni179117C5=15+1045|uni1798=17+654|uni1780=18+633</pre>



<pre>                                                                                                                                                                                                   ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 10040 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(0, 793)"/>
<path d="M829.0,532.0L934.0,447.0L934.0,146.0Q934.0,114.0 906.0,80.0Q878.0,46.0 828.5,23.0Q779.0,0.0 714.0,0.0Q665.0,0.0 618.5,15.0Q572.0,30.0 540.0,62.0Q501.0,23.0 454.5,11.5Q408.0,0.0 353.0,0.0Q282.0,0.0 230.0,23.0Q178.0,46.0 150.0,80.0Q122.0,114.0 122.0,146.0L122.0,621.0Q122.0,650.0 144.0,666.0Q166.0,682.0 203.0,682.0Q262.0,682.0 294.0,644.0Q326.0,606.0 326.0,555.0Q326.0,506.0 296.5,469.0Q267.0,432.0 214.0,422.0L214.0,146.0Q214.0,124.0 233.0,106.5Q252.0,89.0 283.5,78.0Q315.0,67.0 353.0,67.0Q394.0,67.0 426.0,79.0Q458.0,91.0 476.0,109.0Q494.0,127.0 494.0,146.0L494.0,424.0Q458.0,454.0 439.5,471.0Q421.0,488.0 415.0,497.5Q409.0,507.0 409.0,514.0Q409.0,524.0 418.5,538.0Q428.0,552.0 453.0,584.0Q478.0,616.0 524.0,680.0Q556.0,659.0 577.0,647.0Q598.0,635.0 617.5,631.0Q637.0,627.0 662.0,629.0Q662.0,604.0 644.5,580.5Q627.0,557.0 598.0,557.0Q585.0,557.0 567.5,564.0Q550.0,571.0 524.0,590.0L481.0,532.0L586.0,447.0L586.0,146.0Q586.0,127.0 603.5,109.0Q621.0,91.0 650.5,79.0Q680.0,67.0 714.0,67.0Q749.0,67.0 778.0,79.0Q807.0,91.0 824.5,109.0Q842.0,127.0 842.0,146.0L842.0,424.0Q806.0,454.0 787.5,471.0Q769.0,488.0 763.0,497.5Q757.0,507.0 757.0,514.0Q757.0,524.0 766.5,538.0Q776.0,552.0 801.0,584.0Q826.0,616.0 872.0,680.0Q904.0,659.0 925.0,647.0Q946.0,635.0 965.5,631.0Q985.0,627.0 1010.0,629.0Q1010.0,604.0 992.5,580.5Q975.0,557.0 946.0,557.0Q933.0,557.0 915.5,564.0Q898.0,571.0 872.0,590.0L829.0,532.0ZM214.0,604.0L214.0,489.0Q231.0,490.0 245.0,506.5Q259.0,523.0 259.0,548.0Q259.0,569.0 247.5,584.5Q236.0,600.0 214.0,604.0Z" transform="translate(377, 793)"/>
<path d="M137.0,412.0Q115.0,412.0 101.5,428.0Q88.0,444.0 88.0,461.0Q88.0,481.0 102.0,495.5Q116.0,510.0 137.0,510.0Q157.0,510.0 171.5,495.5Q186.0,481.0 186.0,461.0Q186.0,439.0 170.0,425.5Q154.0,412.0 137.0,412.0ZM137.0,46.0Q115.0,46.0 101.5,62.0Q88.0,78.0 88.0,95.0Q88.0,115.0 102.0,129.5Q116.0,144.0 137.0,144.0Q157.0,144.0 171.5,129.5Q186.0,115.0 186.0,95.0Q186.0,73.0 170.0,59.5Q154.0,46.0 137.0,46.0Z" transform="translate(1402, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(1676, 793)"/>
<path d="M149.0,558.0Q149.0,550.0 161.0,534.5Q173.0,519.0 195.0,499.0L195.0,246.0Q251.0,249.0 278.5,222.5Q306.0,196.0 306.0,151.0Q306.0,133.0 298.5,109.0Q291.0,85.0 267.5,57.5Q244.0,30.0 195.0,0.0L103.0,0.0L103.0,469.0Q54.0,519.0 54.0,542.0Q54.0,553.0 71.5,578.0Q89.0,603.0 117.0,629.0Q140.0,650.0 165.0,666.0Q190.0,682.0 206.0,682.0Q218.0,682.0 235.0,671.0Q252.0,660.0 276.0,639.0Q294.0,623.0 306.5,612.5Q319.0,602.0 320.0,602.0Q323.0,602.0 336.5,614.5Q350.0,627.0 368.0,644.0Q387.0,661.0 401.0,671.5Q415.0,682.0 431.0,682.0Q462.0,682.0 493.0,658.0Q524.0,634.0 545.5,597.0Q567.0,560.0 567.0,521.0L567.0,0.0L475.0,0.0L475.0,521.0Q475.0,548.0 455.5,569.5Q436.0,591.0 417.0,591.0Q403.0,591.0 389.5,580.0Q376.0,569.0 361.5,554.5Q347.0,540.0 331.0,529.0Q315.0,518.0 297.0,518.0Q279.0,518.0 263.0,528.5Q247.0,539.0 233.0,553.0Q219.0,567.0 207.0,577.5Q195.0,588.0 184.0,588.0Q178.0,588.0 172.0,585.0Q166.0,582.0 161.0,577.0Q149.0,567.0 149.0,558.0ZM195.0,181.0L195.0,89.0Q235.0,114.0 235.0,150.0Q235.0,169.0 223.5,175.0Q212.0,181.0 195.0,181.0Z" transform="translate(2015, 793)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(2672, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(3673, 793)"/>
<path d="M500.0,448.0Q535.0,448.0 551.0,434.0Q567.0,420.0 567.0,395.0L567.0,0.0L475.0,0.0L335.0,115.0L195.0,0.0L103.0,0.0L103.0,443.0Q79.0,466.0 66.5,483.5Q54.0,501.0 54.0,523.0Q54.0,550.0 69.5,570.0Q85.0,590.0 108.0,612.0Q154.0,656.0 177.5,668.0Q201.0,680.0 211.0,680.0Q223.0,680.0 239.0,667.5Q255.0,655.0 283.0,628.0Q308.0,603.0 318.0,595.0Q328.0,587.0 336.0,587.0Q344.0,587.0 354.0,596.0Q364.0,605.0 387.0,628.0Q411.0,653.0 427.5,666.5Q444.0,680.0 456.0,680.0Q472.0,680.0 499.0,652.0L544.0,604.0Q557.0,590.0 575.0,584.0Q593.0,578.0 616.0,582.0Q608.0,538.0 588.0,519.0Q568.0,500.0 546.0,500.0Q526.0,500.0 513.5,511.0Q501.0,522.0 490.5,537.0Q480.0,552.0 469.0,563.0Q458.0,574.0 441.0,574.0Q427.0,574.0 413.5,563.5Q400.0,553.0 385.0,539.0Q363.0,520.0 348.5,510.0Q334.0,500.0 320.0,500.0Q304.0,500.0 285.5,511.5Q267.0,523.0 246.0,540.0Q218.0,564.0 207.0,572.0Q196.0,580.0 188.0,580.0Q174.0,580.0 159.0,567.0Q144.0,554.0 144.0,540.0Q144.0,535.0 147.0,529.0Q150.0,523.0 160.5,510.0Q171.0,497.0 195.0,471.0L195.0,91.0L335.0,207.0L475.0,91.0L475.0,228.0Q432.0,228.0 398.5,255.0Q365.0,282.0 365.0,329.0Q365.0,365.0 384.0,392.0Q403.0,419.0 433.5,433.5Q464.0,448.0 500.0,448.0ZM475.0,295.0L475.0,386.0Q459.0,386.0 444.5,373.0Q430.0,360.0 430.0,337.0Q430.0,315.0 444.5,305.0Q459.0,295.0 475.0,295.0Z" transform="translate(4012, 793)"/>
<path d="M-366.0,-302.0Q-416.0,-302.0 -450.0,-286.5Q-484.0,-271.0 -500.5,-247.5Q-517.0,-224.0 -517.0,-201.0L-517.0,-169.0Q-489.0,-168.0 -437.5,-154.5Q-386.0,-141.0 -323.5,-114.5Q-261.0,-88.0 -200.0,-48.0Q-127.0,-48.0 -127.0,-112.0Q-127.0,-146.0 -145.5,-179.5Q-164.0,-213.0 -196.5,-241.0Q-229.0,-269.0 -272.5,-285.5Q-316.0,-302.0 -366.0,-302.0ZM-439.0,-206.0Q-431.0,-221.0 -412.0,-237.0Q-393.0,-253.0 -359.0,-253.0Q-321.0,-253.0 -284.5,-231.5Q-248.0,-210.0 -224.5,-177.5Q-201.0,-145.0 -201.0,-111.0Q-238.0,-132.0 -266.0,-146.0Q-294.0,-160.0 -319.0,-170.0Q-344.0,-180.0 -372.5,-188.5Q-401.0,-197.0 -439.0,-206.0Z" transform="translate(4667, 777)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(4700, 699)"/>
<path d="M564.0,654.0Q564.0,607.0 538.5,563.5Q513.0,520.0 458.5,493.0Q404.0,466.0 318.0,466.0Q258.0,466.0 208.5,482.0Q159.0,498.0 129.5,528.5Q100.0,559.0 100.0,603.0Q100.0,643.0 127.5,674.0Q155.0,705.0 210.0,705.0Q261.0,705.0 288.5,678.0Q316.0,651.0 316.0,610.0Q316.0,589.0 308.0,573.0Q300.0,557.0 280.0,535.0Q301.0,532.0 324.0,532.0Q392.0,532.0 432.0,560.0Q472.0,588.0 472.0,633.0Q472.0,660.0 455.5,679.5Q439.0,699.0 406.0,694.0Q393.0,738.0 415.5,760.5Q438.0,783.0 470.0,783.0Q500.0,783.0 521.0,765.0Q542.0,747.0 553.0,717.5Q564.0,688.0 564.0,654.0ZM245.0,608.0Q245.0,619.0 235.5,629.0Q226.0,639.0 209.0,639.0Q193.0,639.0 182.0,630.0Q171.0,621.0 171.0,606.0Q171.0,579.0 207.0,558.0Q222.0,566.0 233.5,580.5Q245.0,595.0 245.0,608.0ZM100.0,447.0L192.0,413.0L192.0,91.0L332.0,207.0L472.0,91.0L472.0,437.0L564.0,437.0L564.0,0.0L472.0,0.0L332.0,115.0L192.0,0.0L100.0,0.0L100.0,447.0Z" transform="translate(4670, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(5355, 779)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(5326, 793)"/>
<path d="M128.0,515.0L194.0,463.0L194.0,246.0Q250.0,249.0 277.5,222.5Q305.0,196.0 305.0,151.0Q305.0,133.0 297.5,109.0Q290.0,85.0 266.5,57.5Q243.0,30.0 194.0,0.0L102.0,0.0L102.0,438.0Q69.0,467.0 58.5,480.5Q48.0,494.0 48.0,504.0Q48.0,514.0 56.5,526.0Q65.0,538.0 87.0,559.0Q109.0,580.0 148.0,614.0Q194.0,654.0 227.5,668.0Q261.0,682.0 297.0,682.0Q330.0,682.0 366.0,670.0Q402.0,658.0 449.0,622.0Q499.0,584.0 520.5,546.5Q542.0,509.0 542.0,463.0L542.0,91.0L669.0,196.0L797.0,91.0L797.0,438.0Q764.0,467.0 753.5,481.0Q743.0,495.0 743.0,505.0Q743.0,515.0 751.5,527.0Q760.0,539.0 782.0,559.5Q804.0,580.0 843.0,614.0Q889.0,654.0 920.5,668.0Q952.0,682.0 989.0,682.0Q1021.0,682.0 1059.0,670.0Q1097.0,658.0 1144.0,622.0Q1194.0,584.0 1215.5,546.5Q1237.0,509.0 1237.0,463.0L1237.0,0.0L1145.0,0.0L1145.0,464.0Q1145.0,489.0 1130.0,515.5Q1115.0,542.0 1091.0,564.5Q1067.0,587.0 1038.5,601.0Q1010.0,615.0 983.0,615.0Q952.0,615.0 916.5,592.0Q881.0,569.0 823.0,515.0L889.0,463.0L889.0,0.0L797.0,0.0L669.0,105.0L542.0,0.0L450.0,0.0L450.0,464.0Q450.0,489.0 435.5,515.5Q421.0,542.0 397.0,564.5Q373.0,587.0 344.5,601.0Q316.0,615.0 289.0,615.0Q258.0,615.0 222.0,592.0Q186.0,569.0 128.0,515.0ZM194.0,181.0L194.0,89.0Q234.0,114.0 234.0,150.0Q234.0,169.0 222.5,175.0Q211.0,181.0 194.0,181.0Z" transform="translate(5665, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(6687, 699)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(6992, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(7369, 793)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q356.0,682.0 410.0,659.5Q464.0,637.0 491.0,601.0Q551.0,647.0 588.0,664.5Q625.0,682.0 654.0,682.0Q698.0,682.0 739.0,650.0L816.0,589.0L816.0,734.0Q816.0,759.0 804.0,783.0Q792.0,807.0 767.0,819.0Q767.0,844.0 785.0,861.0Q803.0,878.0 833.0,878.0Q874.0,878.0 886.0,848.5Q898.0,819.0 898.0,770.0L898.0,604.0Q898.0,587.0 893.0,561.0Q888.0,535.0 871.0,507.0Q871.0,504.0 871.0,501.0L871.0,0.0L779.0,0.0L779.0,507.0L677.0,588.0Q667.0,596.0 657.0,601.5Q647.0,607.0 639.0,607.0Q629.0,607.0 608.5,596.0Q588.0,585.0 563.0,567.5Q538.0,550.0 514.0,533.0L514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(7708, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(8753, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(9407, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 10040 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(0, 793)"/>
<path d="M829.0,532.0L934.0,447.0L934.0,146.0Q934.0,114.0 906.0,80.0Q878.0,46.0 828.5,23.0Q779.0,0.0 714.0,0.0Q665.0,0.0 618.5,15.0Q572.0,30.0 540.0,62.0Q501.0,23.0 454.5,11.5Q408.0,0.0 353.0,0.0Q282.0,0.0 230.0,23.0Q178.0,46.0 150.0,80.0Q122.0,114.0 122.0,146.0L122.0,621.0Q122.0,650.0 144.0,666.0Q166.0,682.0 203.0,682.0Q262.0,682.0 294.0,644.0Q326.0,606.0 326.0,555.0Q326.0,506.0 296.5,469.0Q267.0,432.0 214.0,422.0L214.0,146.0Q214.0,124.0 233.0,106.5Q252.0,89.0 283.5,78.0Q315.0,67.0 353.0,67.0Q394.0,67.0 426.0,79.0Q458.0,91.0 476.0,109.0Q494.0,127.0 494.0,146.0L494.0,424.0Q458.0,454.0 439.5,471.0Q421.0,488.0 415.0,497.5Q409.0,507.0 409.0,514.0Q409.0,524.0 418.5,538.0Q428.0,552.0 453.0,584.0Q478.0,616.0 524.0,680.0Q556.0,659.0 577.0,647.0Q598.0,635.0 617.5,631.0Q637.0,627.0 662.0,629.0Q662.0,604.0 644.5,580.5Q627.0,557.0 598.0,557.0Q585.0,557.0 567.5,564.0Q550.0,571.0 524.0,590.0L481.0,532.0L586.0,447.0L586.0,146.0Q586.0,127.0 603.5,109.0Q621.0,91.0 650.5,79.0Q680.0,67.0 714.0,67.0Q749.0,67.0 778.0,79.0Q807.0,91.0 824.5,109.0Q842.0,127.0 842.0,146.0L842.0,424.0Q806.0,454.0 787.5,471.0Q769.0,488.0 763.0,497.5Q757.0,507.0 757.0,514.0Q757.0,524.0 766.5,538.0Q776.0,552.0 801.0,584.0Q826.0,616.0 872.0,680.0Q904.0,659.0 925.0,647.0Q946.0,635.0 965.5,631.0Q985.0,627.0 1010.0,629.0Q1010.0,604.0 992.5,580.5Q975.0,557.0 946.0,557.0Q933.0,557.0 915.5,564.0Q898.0,571.0 872.0,590.0L829.0,532.0ZM214.0,604.0L214.0,489.0Q231.0,490.0 245.0,506.5Q259.0,523.0 259.0,548.0Q259.0,569.0 247.5,584.5Q236.0,600.0 214.0,604.0Z" transform="translate(377, 793)"/>
<path d="M137.0,412.0Q115.0,412.0 101.5,428.0Q88.0,444.0 88.0,461.0Q88.0,481.0 102.0,495.5Q116.0,510.0 137.0,510.0Q157.0,510.0 171.5,495.5Q186.0,481.0 186.0,461.0Q186.0,439.0 170.0,425.5Q154.0,412.0 137.0,412.0ZM137.0,46.0Q115.0,46.0 101.5,62.0Q88.0,78.0 88.0,95.0Q88.0,115.0 102.0,129.5Q116.0,144.0 137.0,144.0Q157.0,144.0 171.5,129.5Q186.0,115.0 186.0,95.0Q186.0,73.0 170.0,59.5Q154.0,46.0 137.0,46.0Z" transform="translate(1402, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(1676, 793)"/>
<path d="M149.0,558.0Q149.0,550.0 161.0,534.5Q173.0,519.0 195.0,499.0L195.0,246.0Q251.0,249.0 278.5,222.5Q306.0,196.0 306.0,151.0Q306.0,133.0 298.5,109.0Q291.0,85.0 267.5,57.5Q244.0,30.0 195.0,0.0L103.0,0.0L103.0,469.0Q54.0,519.0 54.0,542.0Q54.0,553.0 71.5,578.0Q89.0,603.0 117.0,629.0Q140.0,650.0 165.0,666.0Q190.0,682.0 206.0,682.0Q218.0,682.0 235.0,671.0Q252.0,660.0 276.0,639.0Q294.0,623.0 306.5,612.5Q319.0,602.0 320.0,602.0Q323.0,602.0 336.5,614.5Q350.0,627.0 368.0,644.0Q387.0,661.0 401.0,671.5Q415.0,682.0 431.0,682.0Q462.0,682.0 493.0,658.0Q524.0,634.0 545.5,597.0Q567.0,560.0 567.0,521.0L567.0,0.0L475.0,0.0L475.0,521.0Q475.0,548.0 455.5,569.5Q436.0,591.0 417.0,591.0Q403.0,591.0 389.5,580.0Q376.0,569.0 361.5,554.5Q347.0,540.0 331.0,529.0Q315.0,518.0 297.0,518.0Q279.0,518.0 263.0,528.5Q247.0,539.0 233.0,553.0Q219.0,567.0 207.0,577.5Q195.0,588.0 184.0,588.0Q178.0,588.0 172.0,585.0Q166.0,582.0 161.0,577.0Q149.0,567.0 149.0,558.0ZM195.0,181.0L195.0,89.0Q235.0,114.0 235.0,150.0Q235.0,169.0 223.5,175.0Q212.0,181.0 195.0,181.0Z" transform="translate(2015, 793)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(2672, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(3673, 793)"/>
<path d="M500.0,448.0Q535.0,448.0 551.0,434.0Q567.0,420.0 567.0,395.0L567.0,0.0L475.0,0.0L335.0,115.0L195.0,0.0L103.0,0.0L103.0,443.0Q79.0,466.0 66.5,483.5Q54.0,501.0 54.0,523.0Q54.0,550.0 69.5,570.0Q85.0,590.0 108.0,612.0Q154.0,656.0 177.5,668.0Q201.0,680.0 211.0,680.0Q223.0,680.0 239.0,667.5Q255.0,655.0 283.0,628.0Q308.0,603.0 318.0,595.0Q328.0,587.0 336.0,587.0Q344.0,587.0 354.0,596.0Q364.0,605.0 387.0,628.0Q411.0,653.0 427.5,666.5Q444.0,680.0 456.0,680.0Q472.0,680.0 499.0,652.0L544.0,604.0Q557.0,590.0 575.0,584.0Q593.0,578.0 616.0,582.0Q608.0,538.0 588.0,519.0Q568.0,500.0 546.0,500.0Q526.0,500.0 513.5,511.0Q501.0,522.0 490.5,537.0Q480.0,552.0 469.0,563.0Q458.0,574.0 441.0,574.0Q427.0,574.0 413.5,563.5Q400.0,553.0 385.0,539.0Q363.0,520.0 348.5,510.0Q334.0,500.0 320.0,500.0Q304.0,500.0 285.5,511.5Q267.0,523.0 246.0,540.0Q218.0,564.0 207.0,572.0Q196.0,580.0 188.0,580.0Q174.0,580.0 159.0,567.0Q144.0,554.0 144.0,540.0Q144.0,535.0 147.0,529.0Q150.0,523.0 160.5,510.0Q171.0,497.0 195.0,471.0L195.0,91.0L335.0,207.0L475.0,91.0L475.0,228.0Q432.0,228.0 398.5,255.0Q365.0,282.0 365.0,329.0Q365.0,365.0 384.0,392.0Q403.0,419.0 433.5,433.5Q464.0,448.0 500.0,448.0ZM475.0,295.0L475.0,386.0Q459.0,386.0 444.5,373.0Q430.0,360.0 430.0,337.0Q430.0,315.0 444.5,305.0Q459.0,295.0 475.0,295.0Z" transform="translate(4012, 793)"/>
<path d="M-366.0,-302.0Q-416.0,-302.0 -450.0,-286.5Q-484.0,-271.0 -500.5,-247.5Q-517.0,-224.0 -517.0,-201.0L-517.0,-169.0Q-489.0,-168.0 -437.5,-154.5Q-386.0,-141.0 -323.5,-114.5Q-261.0,-88.0 -200.0,-48.0Q-127.0,-48.0 -127.0,-112.0Q-127.0,-146.0 -145.5,-179.5Q-164.0,-213.0 -196.5,-241.0Q-229.0,-269.0 -272.5,-285.5Q-316.0,-302.0 -366.0,-302.0ZM-439.0,-206.0Q-431.0,-221.0 -412.0,-237.0Q-393.0,-253.0 -359.0,-253.0Q-321.0,-253.0 -284.5,-231.5Q-248.0,-210.0 -224.5,-177.5Q-201.0,-145.0 -201.0,-111.0Q-238.0,-132.0 -266.0,-146.0Q-294.0,-160.0 -319.0,-170.0Q-344.0,-180.0 -372.5,-188.5Q-401.0,-197.0 -439.0,-206.0Z" transform="translate(4667, 777)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(4700, 699)"/>
<path d="M564.0,654.0Q564.0,607.0 538.5,563.5Q513.0,520.0 458.5,493.0Q404.0,466.0 318.0,466.0Q258.0,466.0 208.5,482.0Q159.0,498.0 129.5,528.5Q100.0,559.0 100.0,603.0Q100.0,643.0 127.5,674.0Q155.0,705.0 210.0,705.0Q261.0,705.0 288.5,678.0Q316.0,651.0 316.0,610.0Q316.0,589.0 308.0,573.0Q300.0,557.0 280.0,535.0Q301.0,532.0 324.0,532.0Q392.0,532.0 432.0,560.0Q472.0,588.0 472.0,633.0Q472.0,660.0 455.5,679.5Q439.0,699.0 406.0,694.0Q393.0,738.0 415.5,760.5Q438.0,783.0 470.0,783.0Q500.0,783.0 521.0,765.0Q542.0,747.0 553.0,717.5Q564.0,688.0 564.0,654.0ZM245.0,608.0Q245.0,619.0 235.5,629.0Q226.0,639.0 209.0,639.0Q193.0,639.0 182.0,630.0Q171.0,621.0 171.0,606.0Q171.0,579.0 207.0,558.0Q222.0,566.0 233.5,580.5Q245.0,595.0 245.0,608.0ZM100.0,447.0L192.0,413.0L192.0,91.0L332.0,207.0L472.0,91.0L472.0,437.0L564.0,437.0L564.0,0.0L472.0,0.0L332.0,115.0L192.0,0.0L100.0,0.0L100.0,447.0Z" transform="translate(4670, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(5335, 709)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(5326, 793)"/>
<path d="M128.0,515.0L194.0,463.0L194.0,246.0Q250.0,249.0 277.5,222.5Q305.0,196.0 305.0,151.0Q305.0,133.0 297.5,109.0Q290.0,85.0 266.5,57.5Q243.0,30.0 194.0,0.0L102.0,0.0L102.0,438.0Q69.0,467.0 58.5,480.5Q48.0,494.0 48.0,504.0Q48.0,514.0 56.5,526.0Q65.0,538.0 87.0,559.0Q109.0,580.0 148.0,614.0Q194.0,654.0 227.5,668.0Q261.0,682.0 297.0,682.0Q330.0,682.0 366.0,670.0Q402.0,658.0 449.0,622.0Q499.0,584.0 520.5,546.5Q542.0,509.0 542.0,463.0L542.0,91.0L669.0,196.0L797.0,91.0L797.0,438.0Q764.0,467.0 753.5,481.0Q743.0,495.0 743.0,505.0Q743.0,515.0 751.5,527.0Q760.0,539.0 782.0,559.5Q804.0,580.0 843.0,614.0Q889.0,654.0 920.5,668.0Q952.0,682.0 989.0,682.0Q1021.0,682.0 1059.0,670.0Q1097.0,658.0 1144.0,622.0Q1194.0,584.0 1215.5,546.5Q1237.0,509.0 1237.0,463.0L1237.0,0.0L1145.0,0.0L1145.0,464.0Q1145.0,489.0 1130.0,515.5Q1115.0,542.0 1091.0,564.5Q1067.0,587.0 1038.5,601.0Q1010.0,615.0 983.0,615.0Q952.0,615.0 916.5,592.0Q881.0,569.0 823.0,515.0L889.0,463.0L889.0,0.0L797.0,0.0L669.0,105.0L542.0,0.0L450.0,0.0L450.0,464.0Q450.0,489.0 435.5,515.5Q421.0,542.0 397.0,564.5Q373.0,587.0 344.5,601.0Q316.0,615.0 289.0,615.0Q258.0,615.0 222.0,592.0Q186.0,569.0 128.0,515.0ZM194.0,181.0L194.0,89.0Q234.0,114.0 234.0,150.0Q234.0,169.0 222.5,175.0Q211.0,181.0 194.0,181.0Z" transform="translate(5665, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(6687, 699)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(6992, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(7369, 793)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q356.0,682.0 410.0,659.5Q464.0,637.0 491.0,601.0Q551.0,647.0 588.0,664.5Q625.0,682.0 654.0,682.0Q698.0,682.0 739.0,650.0L816.0,589.0L816.0,734.0Q816.0,759.0 804.0,783.0Q792.0,807.0 767.0,819.0Q767.0,844.0 785.0,861.0Q803.0,878.0 833.0,878.0Q874.0,878.0 886.0,848.5Q898.0,819.0 898.0,770.0L898.0,604.0Q898.0,587.0 893.0,561.0Q888.0,535.0 871.0,507.0Q871.0,504.0 871.0,501.0L871.0,0.0L779.0,0.0L779.0,507.0L677.0,588.0Q667.0,596.0 657.0,601.5Q647.0,607.0 639.0,607.0Q629.0,607.0 608.5,596.0Q588.0,585.0 563.0,567.5Q538.0,550.0 514.0,533.0L514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(7708, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(8753, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(9407, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">A</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: .notdef=0+634</pre>



<pre>Got     : A=0+705</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 705 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M0.0,0.0L0.0,42.0L19.0,42.0Q48.0,42.0 62.5,57.0Q77.0,72.0 95.0,120.0L317.0,714.0L395.0,714.0L621.0,95.0Q632.0,64.0 647.5,53.0Q663.0,42.0 692.0,42.0L705.0,42.0L705.0,0.0L430.0,0.0L430.0,42.0L453.0,42.0Q513.0,42.0 513.0,90.0Q513.0,98.0 511.0,107.0Q509.0,116.0 505.0,127.0L465.0,239.0L202.0,239.0L164.0,134.0Q155.0,110.0 155.0,91.0Q155.0,42.0 221.0,42.0L244.0,42.0L244.0,0.0L0.0,0.0ZM221.0,289.0L447.0,289.0L385.0,464.0Q369.0,508.0 356.0,547.0Q343.0,586.0 335.0,622.0Q328.0,586.0 317.0,553.0Q306.0,520.0 289.0,473.0L221.0,289.0Z" transform="translate(0, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 634 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(0, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(III)</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: parenleft=0+346|.notdef=1+634|.notdef=2+634|.notdef=3+634|parenright=4+346</pre>



<pre>Got     : parenleft=0+346|I=1+367|I=2+367|I=3+367|parenright=4+346</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1793 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M314.0,-128.0Q222.0,-91.0 165.5,-33.5Q109.0,24.0 83.0,110.5Q57.0,197.0 57.0,317.0Q57.0,437.0 83.0,522.5Q109.0,608.0 165.5,666.0Q222.0,724.0 314.0,760.0L314.0,715.0Q245.0,674.0 212.5,611.0Q180.0,548.0 170.5,472.5Q161.0,397.0 161.0,317.0Q161.0,238.0 170.5,162.0Q180.0,86.0 212.5,23.0Q245.0,-40.0 314.0,-82.0L314.0,-128.0Z" transform="translate(0, 793)"/>
<path d="M38.0,0.0L38.0,42.0L51.0,42.0Q85.0,42.0 109.0,54.5Q133.0,67.0 133.0,114.0L133.0,600.0Q133.0,647.0 109.0,659.5Q85.0,672.0 51.0,672.0L38.0,672.0L38.0,714.0L329.0,714.0L329.0,672.0L316.0,672.0Q282.0,672.0 258.0,659.5Q234.0,647.0 234.0,600.0L234.0,114.0Q234.0,67.0 258.0,54.5Q282.0,42.0 316.0,42.0L329.0,42.0L329.0,0.0L38.0,0.0Z" transform="translate(346, 793)"/>
<path d="M38.0,0.0L38.0,42.0L51.0,42.0Q85.0,42.0 109.0,54.5Q133.0,67.0 133.0,114.0L133.0,600.0Q133.0,647.0 109.0,659.5Q85.0,672.0 51.0,672.0L38.0,672.0L38.0,714.0L329.0,714.0L329.0,672.0L316.0,672.0Q282.0,672.0 258.0,659.5Q234.0,647.0 234.0,600.0L234.0,114.0Q234.0,67.0 258.0,54.5Q282.0,42.0 316.0,42.0L329.0,42.0L329.0,0.0L38.0,0.0Z" transform="translate(713, 793)"/>
<path d="M38.0,0.0L38.0,42.0L51.0,42.0Q85.0,42.0 109.0,54.5Q133.0,67.0 133.0,114.0L133.0,600.0Q133.0,647.0 109.0,659.5Q85.0,672.0 51.0,672.0L38.0,672.0L38.0,714.0L329.0,714.0L329.0,672.0L316.0,672.0Q282.0,672.0 258.0,659.5Q234.0,647.0 234.0,600.0L234.0,114.0Q234.0,67.0 258.0,54.5Q282.0,42.0 316.0,42.0L329.0,42.0L329.0,0.0L38.0,0.0Z" transform="translate(1080, 793)"/>
<path d="M32.0,-128.0L32.0,-82.0Q101.0,-40.0 133.5,23.0Q166.0,86.0 175.5,162.0Q185.0,238.0 185.0,317.0Q185.0,397.0 175.5,472.5Q166.0,548.0 133.5,611.0Q101.0,674.0 32.0,715.0L32.0,760.0Q124.0,724.0 180.5,666.0Q237.0,608.0 263.0,522.5Q289.0,437.0 289.0,317.0Q289.0,197.0 263.0,110.5Q237.0,24.0 180.5,-33.5Q124.0,-91.0 32.0,-128.0Z" transform="translate(1447, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2594 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M314.0,-128.0Q222.0,-91.0 165.5,-33.5Q109.0,24.0 83.0,110.5Q57.0,197.0 57.0,317.0Q57.0,437.0 83.0,522.5Q109.0,608.0 165.5,666.0Q222.0,724.0 314.0,760.0L314.0,715.0Q245.0,674.0 212.5,611.0Q180.0,548.0 170.5,472.5Q161.0,397.0 161.0,317.0Q161.0,238.0 170.5,162.0Q180.0,86.0 212.5,23.0Q245.0,-40.0 314.0,-82.0L314.0,-128.0Z" transform="translate(0, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(346, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(980, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z" transform="translate(1614, 793)"/>
<path d="M32.0,-128.0L32.0,-82.0Q101.0,-40.0 133.5,23.0Q166.0,86.0 175.5,162.0Q185.0,238.0 185.0,317.0Q185.0,397.0 175.5,472.5Q166.0,548.0 133.5,611.0Q101.0,674.0 32.0,715.0L32.0,760.0Q124.0,724.0 180.5,666.0Q237.0,608.0 263.0,522.5Q289.0,437.0 289.0,317.0Q289.0,197.0 263.0,110.5Q237.0,24.0 180.5,-33.5Q124.0,-91.0 32.0,-128.0Z" transform="translate(2248, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ការទទួលស្គាល់សេចក្ដីថ្លៃថ្នូរជាប់ពីកំណើត</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: uni178017B6=0+981|uni179A=2+377|uni1791=3+587|uni1791=4+587|uni17BD=4@-121,-16+0|uni179B=6+1001|uni179F17B6=7+1348|uni17D21782=7@-338,-16+0|uni179B=11+1001|uni17CB=11@42,-66+0|uni17C1=13+339|uni179F=13+1001|uni1785=15+653|uni1780=16+633|uni17D2178A=16@4,-16+0|uni17B8=16@40,-94+0|uni17C3=20+339|uni1790=20+656|uni17D2179B=20@-3,-16+0|uni1790=24+656|uni17D21793=24@-14,-16+0|uni17BC=24@-128,-301+0|uni179A=28+377|uni178717B6=29+1005|uni1794=31+654|uni17CB=31@40,-66+0|uni1796=33+657|uni17B8=33@-2,-94+0|uni1780=35+633|uni17C6=35@40,-126+0|uni17C1=37+339|uni178E=37+1327|uni17B8=37@-305,-94+0|uni178F=39+633</pre>



<pre>Got     : uni178017B6=0+981|uni179A=2+377|uni1791=3+587|uni1791=4+587|uni17BD=4@-121,-16+0|uni179B=6+1001|uni179F17B6=7+1348|uni17D21782=7@-338,-16+0|uni179B=11+1001|uni17CB=11@42,-66+0|uni17C1=13+339|uni179F=13+1001|uni1785=15+653|uni1780=16+633|uni17D2178A=16@4,-16+0|uni17B8=16@40,-94+0|uni17C3=20+339|uni1790=20+656|uni17D2179B=20@-3,-16+0|uni1790=24+656|uni17D21793=24@-14,-16+0|uni17BC=24@-128,-301+0|uni179A=28+377|uni178717B6=29+1005|uni1794=31+654|uni17CB=31@40,-66+0|uni1796=33+657|uni17B8=33@-2,-94+0|uni1780=35+633|uni17C6=35@40,-94+0|uni17C1=37+339|uni178E=37+1327|uni17B8=37@-305,-94+0|uni178F=39+633</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15784 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM539.0,316.0L539.0,0.0L447.0,0.0L447.0,316.0Q447.0,336.0 429.5,353.5Q412.0,371.0 383.0,381.5Q354.0,392.0 318.0,392.0Q262.0,392.0 224.5,368.5Q187.0,345.0 187.0,316.0L187.0,0.0L95.0,0.0L95.0,316.0Q95.0,354.0 125.5,386.5Q156.0,419.0 206.5,439.0Q257.0,459.0 317.0,459.0Q379.0,459.0 429.5,438.5Q480.0,418.0 509.5,385.5Q539.0,353.0 539.0,316.0Z" transform="translate(0, 793)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(981, 793)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q353.0,682.0 405.0,661.5Q457.0,641.0 485.5,607.5Q514.0,574.0 514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(1358, 793)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q353.0,682.0 405.0,661.5Q457.0,641.0 485.5,607.5Q514.0,574.0 514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(1945, 793)"/>
<path d="M-361.0,-221.0Q-361.0,-204.0 -353.5,-183.5Q-346.0,-163.0 -333.0,-138.0L-329.0,-130.0Q-349.0,-130.0 -358.5,-119.5Q-368.0,-109.0 -368.0,-93.0Q-368.0,-73.0 -353.5,-61.0Q-339.0,-49.0 -308.0,-49.0Q-281.0,-49.0 -262.0,-59.5Q-243.0,-70.0 -243.0,-97.0Q-243.0,-110.0 -249.5,-126.0Q-256.0,-142.0 -264.0,-160.0Q-273.0,-179.0 -278.5,-199.0Q-284.0,-219.0 -269.0,-219.0Q-257.0,-219.0 -238.0,-209.0Q-219.0,-199.0 -190.0,-175.0Q-181.0,-199.0 -171.5,-209.0Q-162.0,-219.0 -150.0,-219.0Q-130.0,-219.0 -116.5,-197.5Q-103.0,-176.0 -99.0,-143.0Q-96.0,-117.0 -99.0,-94.0Q-102.0,-71.0 -109.0,-49.0Q-70.0,-37.0 -46.5,-44.5Q-23.0,-52.0 -23.0,-99.0Q-23.0,-125.0 -31.0,-155.0Q-39.0,-185.0 -54.0,-212.0Q-69.0,-239.0 -90.5,-256.5Q-112.0,-274.0 -139.0,-274.0Q-161.0,-274.0 -177.0,-263.5Q-193.0,-253.0 -204.0,-240.0Q-226.0,-253.0 -248.5,-263.5Q-271.0,-274.0 -297.0,-274.0Q-325.0,-274.0 -343.0,-260.5Q-361.0,-247.0 -361.0,-221.0Z" transform="translate(2411, 777)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(2532, 793)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,435.0Q777.0,466.0 765.5,480.5Q754.0,495.0 754.0,505.0Q754.0,520.0 770.0,544.5Q786.0,569.0 823.0,607.0Q855.0,640.0 886.0,661.0Q917.0,682.0 957.0,682.0Q994.0,682.0 1038.0,663.0Q1082.0,644.0 1134.0,610.0Q1183.0,579.0 1209.5,552.0Q1236.0,525.0 1246.0,497.5Q1256.0,470.0 1256.0,435.0L1256.0,0.0L1164.0,0.0L1164.0,432.0Q1164.0,467.0 1141.0,491.0Q1118.0,515.0 1083.0,540.0Q1040.0,571.0 1011.5,586.0Q983.0,601.0 953.0,601.0Q915.0,601.0 883.5,578.5Q852.0,556.0 832.0,521.0L910.0,458.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(3533, 793)"/>
<path d="M-525.0,-317.0L-525.0,-171.0Q-525.0,-128.0 -498.5,-101.5Q-472.0,-75.0 -425.5,-62.0Q-379.0,-49.0 -321.0,-49.0Q-262.0,-49.0 -216.0,-62.0Q-170.0,-75.0 -143.5,-101.5Q-117.0,-128.0 -117.0,-171.0L-117.0,-317.0L-199.0,-317.0L-199.0,-171.0Q-199.0,-132.0 -234.5,-115.0Q-270.0,-98.0 -321.0,-98.0Q-372.0,-98.0 -407.5,-115.0Q-443.0,-132.0 -443.0,-171.0L-443.0,-244.0L-407.0,-218.0Q-396.0,-210.0 -379.5,-201.0Q-363.0,-192.0 -344.0,-192.0Q-308.0,-192.0 -308.0,-224.0Q-308.0,-243.0 -322.0,-252.5Q-336.0,-262.0 -349.0,-262.0Q-362.0,-262.0 -377.0,-269.5Q-392.0,-277.0 -406.0,-288.0L-443.0,-317.0L-525.0,-317.0Z" transform="translate(4543, 777)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4881, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(5924, 727)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(5882, 793)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(6221, 793)"/>
<path d="M499.0,448.0Q534.0,448.0 550.0,434.0Q566.0,420.0 566.0,395.0L566.0,146.0Q566.0,108.0 535.5,74.5Q505.0,41.0 454.5,20.5Q404.0,0.0 344.0,0.0Q283.0,0.0 232.5,21.0Q182.0,42.0 152.0,75.5Q122.0,109.0 122.0,146.0L122.0,443.0Q98.0,466.0 85.5,483.5Q73.0,501.0 73.0,523.0Q73.0,550.0 88.5,570.0Q104.0,590.0 127.0,612.0Q173.0,656.0 196.5,668.0Q220.0,680.0 230.0,680.0Q242.0,680.0 258.0,667.5Q274.0,655.0 302.0,628.0Q327.0,603.0 337.0,595.0Q347.0,587.0 355.0,587.0Q363.0,587.0 373.0,596.0Q383.0,605.0 406.0,628.0Q430.0,653.0 446.5,666.5Q463.0,680.0 475.0,680.0Q491.0,680.0 518.0,652.0L563.0,604.0Q576.0,590.0 594.0,584.0Q612.0,578.0 635.0,582.0Q627.0,538.0 607.0,519.0Q587.0,500.0 565.0,500.0Q545.0,500.0 532.5,511.0Q520.0,522.0 509.5,537.0Q499.0,552.0 488.0,563.0Q477.0,574.0 460.0,574.0Q446.0,574.0 432.5,563.5Q419.0,553.0 404.0,539.0Q382.0,520.0 367.5,510.0Q353.0,500.0 339.0,500.0Q323.0,500.0 304.5,511.5Q286.0,523.0 265.0,540.0Q237.0,564.0 226.0,572.0Q215.0,580.0 207.0,580.0Q193.0,580.0 178.0,567.0Q163.0,554.0 163.0,540.0Q163.0,535.0 166.0,529.0Q169.0,523.0 179.5,510.0Q190.0,497.0 214.0,471.0L214.0,146.0Q214.0,126.0 232.0,108.0Q250.0,90.0 279.5,78.5Q309.0,67.0 344.0,67.0Q381.0,67.0 410.0,79.0Q439.0,91.0 456.5,109.0Q474.0,127.0 474.0,146.0L474.0,228.0Q431.0,228.0 397.5,255.0Q364.0,282.0 364.0,329.0Q364.0,365.0 383.0,392.0Q402.0,419.0 432.5,433.5Q463.0,448.0 499.0,448.0ZM474.0,295.0L474.0,386.0Q458.0,386.0 443.5,373.0Q429.0,360.0 429.0,337.0Q429.0,315.0 443.5,305.0Q458.0,295.0 474.0,295.0Z" transform="translate(7222, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(7875, 793)"/>
<path d="M-525.0,-317.0L-525.0,-171.0Q-525.0,-128.0 -498.5,-101.5Q-472.0,-75.0 -425.5,-62.0Q-379.0,-49.0 -321.0,-49.0Q-262.0,-49.0 -216.0,-62.0Q-170.0,-75.0 -143.5,-101.5Q-117.0,-128.0 -117.0,-171.0L-117.0,-317.0L-199.0,-317.0L-199.0,-171.0Q-199.0,-132.0 -234.5,-115.0Q-270.0,-98.0 -321.0,-98.0Q-372.0,-98.0 -407.5,-115.0Q-443.0,-132.0 -443.0,-171.0L-443.0,-185.0Q-409.0,-185.0 -392.0,-201.0Q-375.0,-217.0 -375.0,-243.0Q-375.0,-265.0 -388.5,-284.5Q-402.0,-304.0 -443.0,-317.0L-525.0,-317.0ZM-443.0,-223.0L-443.0,-281.0Q-429.0,-277.0 -422.5,-266.0Q-416.0,-255.0 -416.0,-245.0Q-416.0,-231.0 -424.0,-227.0Q-432.0,-223.0 -443.0,-223.0Z" transform="translate(8512, 777)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(8548, 699)"/>
<path d="M126.0,850.0Q122.0,834.0 132.0,821.0Q142.0,808.0 161.0,808.0Q178.0,808.0 188.5,821.5Q199.0,835.0 199.0,858.0Q199.0,891.0 179.5,903.5Q160.0,916.0 138.0,916.0L116.0,916.0Q79.0,916.0 70.0,926.5Q61.0,937.0 53.0,960.0Q47.0,979.0 37.5,989.0Q28.0,999.0 4.0,999.0Q4.0,1024.0 19.0,1039.0Q34.0,1054.0 62.0,1054.0Q91.0,1054.0 108.5,1035.0Q126.0,1016.0 126.0,975.0L150.0,975.0Q218.0,975.0 245.0,944.5Q272.0,914.0 272.0,872.0Q272.0,844.0 260.0,818.0Q248.0,792.0 222.0,776.0Q196.0,760.0 152.0,760.0Q111.0,760.0 82.0,776.5Q53.0,793.0 53.0,823.0Q53.0,843.0 65.5,852.5Q78.0,862.0 95.0,861.5Q112.0,861.0 126.0,850.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(8508, 793)"/>
<path d="M498.0,438.0Q533.0,438.0 549.0,424.0Q565.0,410.0 565.0,385.0L565.0,146.0Q565.0,108.0 533.5,74.5Q502.0,41.0 449.0,20.5Q396.0,0.0 333.0,0.0Q270.0,0.0 217.5,20.5Q165.0,41.0 133.0,74.5Q101.0,108.0 101.0,146.0L101.0,443.0Q77.0,466.0 64.5,485.0Q52.0,504.0 52.0,523.0Q52.0,544.0 66.5,563.0Q81.0,582.0 110.0,610.0Q138.0,637.0 165.5,659.5Q193.0,682.0 208.0,682.0Q220.0,682.0 239.0,666.5Q258.0,651.0 296.0,624.0Q334.0,597.0 363.5,582.5Q393.0,568.0 422.0,568.0Q456.0,568.0 478.0,586.0Q500.0,604.0 500.0,633.0Q500.0,660.0 481.5,678.0Q463.0,696.0 435.5,703.0Q408.0,710.0 379.0,704.0Q378.0,738.0 389.5,759.0Q401.0,780.0 433.0,780.0Q460.0,780.0 491.5,765.0Q523.0,750.0 545.0,720.5Q567.0,691.0 567.0,646.0Q567.0,606.0 548.5,572.5Q530.0,539.0 495.5,519.0Q461.0,499.0 414.0,499.0Q371.0,499.0 335.5,516.0Q300.0,533.0 265.0,556.0Q235.0,576.0 220.0,585.5Q205.0,595.0 198.0,595.0Q190.0,595.0 180.5,588.5Q171.0,582.0 163.0,574.0Q155.0,566.0 147.5,556.0Q140.0,546.0 140.0,539.0Q140.0,532.0 151.0,519.0Q162.0,506.0 193.0,471.0L193.0,146.0Q193.0,125.0 212.0,107.0Q231.0,89.0 262.5,78.0Q294.0,67.0 333.0,67.0Q372.0,67.0 404.0,78.0Q436.0,89.0 454.5,107.0Q473.0,125.0 473.0,146.0L473.0,218.0Q430.0,218.0 396.5,245.0Q363.0,272.0 363.0,319.0Q363.0,355.0 382.0,382.0Q401.0,409.0 431.5,423.5Q462.0,438.0 498.0,438.0ZM473.0,285.0L473.0,376.0Q457.0,376.0 442.5,363.0Q428.0,350.0 428.0,327.0Q428.0,305.0 442.5,295.0Q457.0,285.0 473.0,285.0Z" transform="translate(8847, 793)"/>
<path d="M-536.0,-170.0Q-536.0,-120.0 -502.5,-84.5Q-469.0,-49.0 -408.0,-49.0Q-357.0,-49.0 -330.0,-75.5Q-303.0,-102.0 -279.0,-148.0Q-261.0,-182.0 -248.5,-201.0Q-236.0,-220.0 -222.0,-220.0Q-188.0,-220.0 -182.0,-158.0Q-179.0,-126.0 -185.5,-101.0Q-192.0,-76.0 -200.0,-57.0Q-163.0,-38.0 -135.5,-42.5Q-108.0,-47.0 -108.0,-93.0Q-108.0,-106.0 -112.0,-135.0Q-116.0,-164.0 -127.5,-196.0Q-139.0,-228.0 -161.5,-250.5Q-184.0,-273.0 -221.0,-273.0Q-258.0,-273.0 -282.5,-249.0Q-307.0,-225.0 -330.0,-179.0Q-352.0,-134.0 -368.0,-116.0Q-384.0,-98.0 -406.0,-98.0Q-432.0,-98.0 -447.5,-117.5Q-463.0,-137.0 -463.0,-169.0Q-463.0,-193.0 -454.0,-208.0Q-445.0,-223.0 -431.0,-223.0Q-420.0,-223.0 -412.5,-214.5Q-405.0,-206.0 -405.0,-193.0Q-374.0,-190.0 -362.5,-200.0Q-351.0,-210.0 -351.0,-223.0Q-351.0,-242.0 -372.5,-260.0Q-394.0,-278.0 -432.0,-278.0Q-479.0,-278.0 -507.5,-247.5Q-536.0,-217.0 -536.0,-170.0Z" transform="translate(9500, 777)"/>
<path d="M498.0,438.0Q533.0,438.0 549.0,424.0Q565.0,410.0 565.0,385.0L565.0,146.0Q565.0,108.0 533.5,74.5Q502.0,41.0 449.0,20.5Q396.0,0.0 333.0,0.0Q270.0,0.0 217.5,20.5Q165.0,41.0 133.0,74.5Q101.0,108.0 101.0,146.0L101.0,443.0Q77.0,466.0 64.5,485.0Q52.0,504.0 52.0,523.0Q52.0,544.0 66.5,563.0Q81.0,582.0 110.0,610.0Q138.0,637.0 165.5,659.5Q193.0,682.0 208.0,682.0Q220.0,682.0 239.0,666.5Q258.0,651.0 296.0,624.0Q334.0,597.0 363.5,582.5Q393.0,568.0 422.0,568.0Q456.0,568.0 478.0,586.0Q500.0,604.0 500.0,633.0Q500.0,660.0 481.5,678.0Q463.0,696.0 435.5,703.0Q408.0,710.0 379.0,704.0Q378.0,738.0 389.5,759.0Q401.0,780.0 433.0,780.0Q460.0,780.0 491.5,765.0Q523.0,750.0 545.0,720.5Q567.0,691.0 567.0,646.0Q567.0,606.0 548.5,572.5Q530.0,539.0 495.5,519.0Q461.0,499.0 414.0,499.0Q371.0,499.0 335.5,516.0Q300.0,533.0 265.0,556.0Q235.0,576.0 220.0,585.5Q205.0,595.0 198.0,595.0Q190.0,595.0 180.5,588.5Q171.0,582.0 163.0,574.0Q155.0,566.0 147.5,556.0Q140.0,546.0 140.0,539.0Q140.0,532.0 151.0,519.0Q162.0,506.0 193.0,471.0L193.0,146.0Q193.0,125.0 212.0,107.0Q231.0,89.0 262.5,78.0Q294.0,67.0 333.0,67.0Q372.0,67.0 404.0,78.0Q436.0,89.0 454.5,107.0Q473.0,125.0 473.0,146.0L473.0,218.0Q430.0,218.0 396.5,245.0Q363.0,272.0 363.0,319.0Q363.0,355.0 382.0,382.0Q401.0,409.0 431.5,423.5Q462.0,438.0 498.0,438.0ZM473.0,285.0L473.0,376.0Q457.0,376.0 442.5,363.0Q428.0,350.0 428.0,327.0Q428.0,305.0 442.5,295.0Q457.0,285.0 473.0,285.0Z" transform="translate(9503, 793)"/>
<path d="M-172.0,-269.0Q-203.0,-269.0 -217.5,-253.0Q-232.0,-237.0 -234.0,-225.0L-376.0,-235.0Q-463.0,-241.0 -495.5,-221.5Q-528.0,-202.0 -528.0,-165.0Q-528.0,-122.0 -491.5,-105.0Q-455.0,-88.0 -376.0,-88.0L-234.0,-88.0L-234.0,-49.0L-152.0,-49.0L-152.0,-88.0L-89.0,-88.0L-89.0,-137.0L-152.0,-137.0L-152.0,-173.0Q-132.0,-177.0 -123.5,-189.5Q-115.0,-202.0 -115.0,-218.0Q-115.0,-239.0 -129.0,-254.0Q-143.0,-269.0 -172.0,-269.0ZM-234.0,-176.0L-234.0,-137.0L-376.0,-137.0Q-412.0,-137.0 -429.5,-140.0Q-447.0,-143.0 -447.0,-161.0Q-447.0,-170.0 -440.0,-175.5Q-433.0,-181.0 -411.5,-183.0Q-390.0,-185.0 -347.5,-183.0Q-305.0,-181.0 -234.0,-176.0Z" transform="translate(10145, 777)"/>
<path d="M-222.0,-273.0Q-263.0,-273.0 -293.5,-255.0Q-324.0,-237.0 -324.0,-203.0Q-324.0,-188.0 -319.0,-169.5Q-314.0,-151.0 -310.0,-138.0L-307.0,-130.0Q-319.0,-130.0 -327.5,-121.0Q-336.0,-112.0 -336.0,-96.0Q-336.0,-76.0 -320.5,-62.5Q-305.0,-49.0 -279.0,-49.0Q-255.0,-49.0 -241.0,-61.5Q-227.0,-74.0 -227.0,-100.0Q-227.0,-110.0 -230.0,-123.0Q-233.0,-136.0 -241.0,-160.0Q-248.0,-182.0 -242.5,-195.5Q-237.0,-209.0 -215.0,-209.0Q-188.0,-209.0 -172.5,-186.0Q-157.0,-163.0 -138.0,-117.0Q-121.0,-76.0 -110.5,-62.5Q-100.0,-49.0 -86.0,-49.0Q-75.0,-49.0 -64.0,-57.0Q-53.0,-65.0 -53.0,-85.0Q-53.0,-100.0 -60.5,-130.5Q-68.0,-161.0 -87.0,-194.0Q-106.0,-227.0 -139.0,-250.0Q-172.0,-273.0 -222.0,-273.0Z" transform="translate(10031, 492)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(10159, 793)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.0,765.0Q520.0,750.0 542.5,720.5Q565.0,691.0 565.0,647.0Q589.0,661.0 620.0,671.5Q651.0,682.0 687.0,682.0Q740.0,682.0 781.0,650.0L875.0,576.0Q913.0,547.0 913.0,501.0L913.0,0.0L821.0,0.0L821.0,501.0L722.0,580.0Q709.0,591.0 692.5,599.0Q676.0,607.0 653.0,607.0Q626.0,607.0 602.0,594.5Q578.0,582.0 555.5,564.5Q533.0,547.0 511.0,532.0Q492.0,516.0 467.0,507.5Q442.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(10536, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(11541, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(12235, 727)"/>
<path d="M149.0,558.0Q149.0,550.0 161.0,534.5Q173.0,519.0 195.0,499.0L195.0,246.0Q251.0,249.0 278.5,222.5Q306.0,196.0 306.0,151.0Q306.0,133.0 298.5,109.0Q291.0,85.0 267.5,57.5Q244.0,30.0 195.0,0.0L103.0,0.0L103.0,469.0Q54.0,519.0 54.0,542.0Q54.0,553.0 71.5,578.0Q89.0,603.0 117.0,629.0Q140.0,650.0 165.0,666.0Q190.0,682.0 206.0,682.0Q218.0,682.0 235.0,671.0Q252.0,660.0 276.0,639.0Q294.0,623.0 306.5,612.5Q319.0,602.0 320.0,602.0Q323.0,602.0 336.5,614.5Q350.0,627.0 368.0,644.0Q387.0,661.0 401.0,671.5Q415.0,682.0 431.0,682.0Q462.0,682.0 493.0,658.0Q524.0,634.0 545.5,597.0Q567.0,560.0 567.0,521.0L567.0,0.0L475.0,0.0L475.0,521.0Q475.0,548.0 455.5,569.5Q436.0,591.0 417.0,591.0Q403.0,591.0 389.5,580.0Q376.0,569.0 361.5,554.5Q347.0,540.0 331.0,529.0Q315.0,518.0 297.0,518.0Q279.0,518.0 263.0,528.5Q247.0,539.0 233.0,553.0Q219.0,567.0 207.0,577.5Q195.0,588.0 184.0,588.0Q178.0,588.0 172.0,585.0Q166.0,582.0 161.0,577.0Q149.0,567.0 149.0,558.0ZM195.0,181.0L195.0,89.0Q235.0,114.0 235.0,150.0Q235.0,169.0 223.5,175.0Q212.0,181.0 195.0,181.0Z" transform="translate(12195, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(12850, 699)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(12852, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(13525, 699)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(13485, 793)"/>
<path d="M128.0,515.0L194.0,463.0L194.0,246.0Q250.0,249.0 277.5,222.5Q305.0,196.0 305.0,151.0Q305.0,133.0 297.5,109.0Q290.0,85.0 266.5,57.5Q243.0,30.0 194.0,0.0L102.0,0.0L102.0,438.0Q69.0,467.0 58.5,480.5Q48.0,494.0 48.0,504.0Q48.0,514.0 56.5,526.0Q65.0,538.0 87.0,559.0Q109.0,580.0 148.0,614.0Q194.0,654.0 227.5,668.0Q261.0,682.0 297.0,682.0Q330.0,682.0 366.0,670.0Q402.0,658.0 449.0,622.0Q499.0,584.0 520.5,546.5Q542.0,509.0 542.0,463.0L542.0,91.0L669.0,196.0L797.0,91.0L797.0,438.0Q764.0,467.0 753.5,481.0Q743.0,495.0 743.0,505.0Q743.0,515.0 751.5,527.0Q760.0,539.0 782.0,559.5Q804.0,580.0 843.0,614.0Q889.0,654.0 920.5,668.0Q952.0,682.0 989.0,682.0Q1021.0,682.0 1059.0,670.0Q1097.0,658.0 1144.0,622.0Q1194.0,584.0 1215.5,546.5Q1237.0,509.0 1237.0,463.0L1237.0,0.0L1145.0,0.0L1145.0,464.0Q1145.0,489.0 1130.0,515.5Q1115.0,542.0 1091.0,564.5Q1067.0,587.0 1038.5,601.0Q1010.0,615.0 983.0,615.0Q952.0,615.0 916.5,592.0Q881.0,569.0 823.0,515.0L889.0,463.0L889.0,0.0L797.0,0.0L669.0,105.0L542.0,0.0L450.0,0.0L450.0,464.0Q450.0,489.0 435.5,515.5Q421.0,542.0 397.0,564.5Q373.0,587.0 344.5,601.0Q316.0,615.0 289.0,615.0Q258.0,615.0 222.0,592.0Q186.0,569.0 128.0,515.0ZM194.0,181.0L194.0,89.0Q234.0,114.0 234.0,150.0Q234.0,169.0 222.5,175.0Q211.0,181.0 194.0,181.0Z" transform="translate(13824, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(14846, 699)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(15151, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15784 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM539.0,316.0L539.0,0.0L447.0,0.0L447.0,316.0Q447.0,336.0 429.5,353.5Q412.0,371.0 383.0,381.5Q354.0,392.0 318.0,392.0Q262.0,392.0 224.5,368.5Q187.0,345.0 187.0,316.0L187.0,0.0L95.0,0.0L95.0,316.0Q95.0,354.0 125.5,386.5Q156.0,419.0 206.5,439.0Q257.0,459.0 317.0,459.0Q379.0,459.0 429.5,438.5Q480.0,418.0 509.5,385.5Q539.0,353.0 539.0,316.0Z" transform="translate(0, 793)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(981, 793)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q353.0,682.0 405.0,661.5Q457.0,641.0 485.5,607.5Q514.0,574.0 514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(1358, 793)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q353.0,682.0 405.0,661.5Q457.0,641.0 485.5,607.5Q514.0,574.0 514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(1945, 793)"/>
<path d="M-361.0,-221.0Q-361.0,-204.0 -353.5,-183.5Q-346.0,-163.0 -333.0,-138.0L-329.0,-130.0Q-349.0,-130.0 -358.5,-119.5Q-368.0,-109.0 -368.0,-93.0Q-368.0,-73.0 -353.5,-61.0Q-339.0,-49.0 -308.0,-49.0Q-281.0,-49.0 -262.0,-59.5Q-243.0,-70.0 -243.0,-97.0Q-243.0,-110.0 -249.5,-126.0Q-256.0,-142.0 -264.0,-160.0Q-273.0,-179.0 -278.5,-199.0Q-284.0,-219.0 -269.0,-219.0Q-257.0,-219.0 -238.0,-209.0Q-219.0,-199.0 -190.0,-175.0Q-181.0,-199.0 -171.5,-209.0Q-162.0,-219.0 -150.0,-219.0Q-130.0,-219.0 -116.5,-197.5Q-103.0,-176.0 -99.0,-143.0Q-96.0,-117.0 -99.0,-94.0Q-102.0,-71.0 -109.0,-49.0Q-70.0,-37.0 -46.5,-44.5Q-23.0,-52.0 -23.0,-99.0Q-23.0,-125.0 -31.0,-155.0Q-39.0,-185.0 -54.0,-212.0Q-69.0,-239.0 -90.5,-256.5Q-112.0,-274.0 -139.0,-274.0Q-161.0,-274.0 -177.0,-263.5Q-193.0,-253.0 -204.0,-240.0Q-226.0,-253.0 -248.5,-263.5Q-271.0,-274.0 -297.0,-274.0Q-325.0,-274.0 -343.0,-260.5Q-361.0,-247.0 -361.0,-221.0Z" transform="translate(2411, 777)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(2532, 793)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,435.0Q777.0,466.0 765.5,480.5Q754.0,495.0 754.0,505.0Q754.0,520.0 770.0,544.5Q786.0,569.0 823.0,607.0Q855.0,640.0 886.0,661.0Q917.0,682.0 957.0,682.0Q994.0,682.0 1038.0,663.0Q1082.0,644.0 1134.0,610.0Q1183.0,579.0 1209.5,552.0Q1236.0,525.0 1246.0,497.5Q1256.0,470.0 1256.0,435.0L1256.0,0.0L1164.0,0.0L1164.0,432.0Q1164.0,467.0 1141.0,491.0Q1118.0,515.0 1083.0,540.0Q1040.0,571.0 1011.5,586.0Q983.0,601.0 953.0,601.0Q915.0,601.0 883.5,578.5Q852.0,556.0 832.0,521.0L910.0,458.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(3533, 793)"/>
<path d="M-525.0,-317.0L-525.0,-171.0Q-525.0,-128.0 -498.5,-101.5Q-472.0,-75.0 -425.5,-62.0Q-379.0,-49.0 -321.0,-49.0Q-262.0,-49.0 -216.0,-62.0Q-170.0,-75.0 -143.5,-101.5Q-117.0,-128.0 -117.0,-171.0L-117.0,-317.0L-199.0,-317.0L-199.0,-171.0Q-199.0,-132.0 -234.5,-115.0Q-270.0,-98.0 -321.0,-98.0Q-372.0,-98.0 -407.5,-115.0Q-443.0,-132.0 -443.0,-171.0L-443.0,-244.0L-407.0,-218.0Q-396.0,-210.0 -379.5,-201.0Q-363.0,-192.0 -344.0,-192.0Q-308.0,-192.0 -308.0,-224.0Q-308.0,-243.0 -322.0,-252.5Q-336.0,-262.0 -349.0,-262.0Q-362.0,-262.0 -377.0,-269.5Q-392.0,-277.0 -406.0,-288.0L-443.0,-317.0L-525.0,-317.0Z" transform="translate(4543, 777)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4881, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(5924, 727)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(5882, 793)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(6221, 793)"/>
<path d="M499.0,448.0Q534.0,448.0 550.0,434.0Q566.0,420.0 566.0,395.0L566.0,146.0Q566.0,108.0 535.5,74.5Q505.0,41.0 454.5,20.5Q404.0,0.0 344.0,0.0Q283.0,0.0 232.5,21.0Q182.0,42.0 152.0,75.5Q122.0,109.0 122.0,146.0L122.0,443.0Q98.0,466.0 85.5,483.5Q73.0,501.0 73.0,523.0Q73.0,550.0 88.5,570.0Q104.0,590.0 127.0,612.0Q173.0,656.0 196.5,668.0Q220.0,680.0 230.0,680.0Q242.0,680.0 258.0,667.5Q274.0,655.0 302.0,628.0Q327.0,603.0 337.0,595.0Q347.0,587.0 355.0,587.0Q363.0,587.0 373.0,596.0Q383.0,605.0 406.0,628.0Q430.0,653.0 446.5,666.5Q463.0,680.0 475.0,680.0Q491.0,680.0 518.0,652.0L563.0,604.0Q576.0,590.0 594.0,584.0Q612.0,578.0 635.0,582.0Q627.0,538.0 607.0,519.0Q587.0,500.0 565.0,500.0Q545.0,500.0 532.5,511.0Q520.0,522.0 509.5,537.0Q499.0,552.0 488.0,563.0Q477.0,574.0 460.0,574.0Q446.0,574.0 432.5,563.5Q419.0,553.0 404.0,539.0Q382.0,520.0 367.5,510.0Q353.0,500.0 339.0,500.0Q323.0,500.0 304.5,511.5Q286.0,523.0 265.0,540.0Q237.0,564.0 226.0,572.0Q215.0,580.0 207.0,580.0Q193.0,580.0 178.0,567.0Q163.0,554.0 163.0,540.0Q163.0,535.0 166.0,529.0Q169.0,523.0 179.5,510.0Q190.0,497.0 214.0,471.0L214.0,146.0Q214.0,126.0 232.0,108.0Q250.0,90.0 279.5,78.5Q309.0,67.0 344.0,67.0Q381.0,67.0 410.0,79.0Q439.0,91.0 456.5,109.0Q474.0,127.0 474.0,146.0L474.0,228.0Q431.0,228.0 397.5,255.0Q364.0,282.0 364.0,329.0Q364.0,365.0 383.0,392.0Q402.0,419.0 432.5,433.5Q463.0,448.0 499.0,448.0ZM474.0,295.0L474.0,386.0Q458.0,386.0 443.5,373.0Q429.0,360.0 429.0,337.0Q429.0,315.0 443.5,305.0Q458.0,295.0 474.0,295.0Z" transform="translate(7222, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(7875, 793)"/>
<path d="M-525.0,-317.0L-525.0,-171.0Q-525.0,-128.0 -498.5,-101.5Q-472.0,-75.0 -425.5,-62.0Q-379.0,-49.0 -321.0,-49.0Q-262.0,-49.0 -216.0,-62.0Q-170.0,-75.0 -143.5,-101.5Q-117.0,-128.0 -117.0,-171.0L-117.0,-317.0L-199.0,-317.0L-199.0,-171.0Q-199.0,-132.0 -234.5,-115.0Q-270.0,-98.0 -321.0,-98.0Q-372.0,-98.0 -407.5,-115.0Q-443.0,-132.0 -443.0,-171.0L-443.0,-185.0Q-409.0,-185.0 -392.0,-201.0Q-375.0,-217.0 -375.0,-243.0Q-375.0,-265.0 -388.5,-284.5Q-402.0,-304.0 -443.0,-317.0L-525.0,-317.0ZM-443.0,-223.0L-443.0,-281.0Q-429.0,-277.0 -422.5,-266.0Q-416.0,-255.0 -416.0,-245.0Q-416.0,-231.0 -424.0,-227.0Q-432.0,-223.0 -443.0,-223.0Z" transform="translate(8512, 777)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(8548, 699)"/>
<path d="M126.0,850.0Q122.0,834.0 132.0,821.0Q142.0,808.0 161.0,808.0Q178.0,808.0 188.5,821.5Q199.0,835.0 199.0,858.0Q199.0,891.0 179.5,903.5Q160.0,916.0 138.0,916.0L116.0,916.0Q79.0,916.0 70.0,926.5Q61.0,937.0 53.0,960.0Q47.0,979.0 37.5,989.0Q28.0,999.0 4.0,999.0Q4.0,1024.0 19.0,1039.0Q34.0,1054.0 62.0,1054.0Q91.0,1054.0 108.5,1035.0Q126.0,1016.0 126.0,975.0L150.0,975.0Q218.0,975.0 245.0,944.5Q272.0,914.0 272.0,872.0Q272.0,844.0 260.0,818.0Q248.0,792.0 222.0,776.0Q196.0,760.0 152.0,760.0Q111.0,760.0 82.0,776.5Q53.0,793.0 53.0,823.0Q53.0,843.0 65.5,852.5Q78.0,862.0 95.0,861.5Q112.0,861.0 126.0,850.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(8508, 793)"/>
<path d="M498.0,438.0Q533.0,438.0 549.0,424.0Q565.0,410.0 565.0,385.0L565.0,146.0Q565.0,108.0 533.5,74.5Q502.0,41.0 449.0,20.5Q396.0,0.0 333.0,0.0Q270.0,0.0 217.5,20.5Q165.0,41.0 133.0,74.5Q101.0,108.0 101.0,146.0L101.0,443.0Q77.0,466.0 64.5,485.0Q52.0,504.0 52.0,523.0Q52.0,544.0 66.5,563.0Q81.0,582.0 110.0,610.0Q138.0,637.0 165.5,659.5Q193.0,682.0 208.0,682.0Q220.0,682.0 239.0,666.5Q258.0,651.0 296.0,624.0Q334.0,597.0 363.5,582.5Q393.0,568.0 422.0,568.0Q456.0,568.0 478.0,586.0Q500.0,604.0 500.0,633.0Q500.0,660.0 481.5,678.0Q463.0,696.0 435.5,703.0Q408.0,710.0 379.0,704.0Q378.0,738.0 389.5,759.0Q401.0,780.0 433.0,780.0Q460.0,780.0 491.5,765.0Q523.0,750.0 545.0,720.5Q567.0,691.0 567.0,646.0Q567.0,606.0 548.5,572.5Q530.0,539.0 495.5,519.0Q461.0,499.0 414.0,499.0Q371.0,499.0 335.5,516.0Q300.0,533.0 265.0,556.0Q235.0,576.0 220.0,585.5Q205.0,595.0 198.0,595.0Q190.0,595.0 180.5,588.5Q171.0,582.0 163.0,574.0Q155.0,566.0 147.5,556.0Q140.0,546.0 140.0,539.0Q140.0,532.0 151.0,519.0Q162.0,506.0 193.0,471.0L193.0,146.0Q193.0,125.0 212.0,107.0Q231.0,89.0 262.5,78.0Q294.0,67.0 333.0,67.0Q372.0,67.0 404.0,78.0Q436.0,89.0 454.5,107.0Q473.0,125.0 473.0,146.0L473.0,218.0Q430.0,218.0 396.5,245.0Q363.0,272.0 363.0,319.0Q363.0,355.0 382.0,382.0Q401.0,409.0 431.5,423.5Q462.0,438.0 498.0,438.0ZM473.0,285.0L473.0,376.0Q457.0,376.0 442.5,363.0Q428.0,350.0 428.0,327.0Q428.0,305.0 442.5,295.0Q457.0,285.0 473.0,285.0Z" transform="translate(8847, 793)"/>
<path d="M-536.0,-170.0Q-536.0,-120.0 -502.5,-84.5Q-469.0,-49.0 -408.0,-49.0Q-357.0,-49.0 -330.0,-75.5Q-303.0,-102.0 -279.0,-148.0Q-261.0,-182.0 -248.5,-201.0Q-236.0,-220.0 -222.0,-220.0Q-188.0,-220.0 -182.0,-158.0Q-179.0,-126.0 -185.5,-101.0Q-192.0,-76.0 -200.0,-57.0Q-163.0,-38.0 -135.5,-42.5Q-108.0,-47.0 -108.0,-93.0Q-108.0,-106.0 -112.0,-135.0Q-116.0,-164.0 -127.5,-196.0Q-139.0,-228.0 -161.5,-250.5Q-184.0,-273.0 -221.0,-273.0Q-258.0,-273.0 -282.5,-249.0Q-307.0,-225.0 -330.0,-179.0Q-352.0,-134.0 -368.0,-116.0Q-384.0,-98.0 -406.0,-98.0Q-432.0,-98.0 -447.5,-117.5Q-463.0,-137.0 -463.0,-169.0Q-463.0,-193.0 -454.0,-208.0Q-445.0,-223.0 -431.0,-223.0Q-420.0,-223.0 -412.5,-214.5Q-405.0,-206.0 -405.0,-193.0Q-374.0,-190.0 -362.5,-200.0Q-351.0,-210.0 -351.0,-223.0Q-351.0,-242.0 -372.5,-260.0Q-394.0,-278.0 -432.0,-278.0Q-479.0,-278.0 -507.5,-247.5Q-536.0,-217.0 -536.0,-170.0Z" transform="translate(9500, 777)"/>
<path d="M498.0,438.0Q533.0,438.0 549.0,424.0Q565.0,410.0 565.0,385.0L565.0,146.0Q565.0,108.0 533.5,74.5Q502.0,41.0 449.0,20.5Q396.0,0.0 333.0,0.0Q270.0,0.0 217.5,20.5Q165.0,41.0 133.0,74.5Q101.0,108.0 101.0,146.0L101.0,443.0Q77.0,466.0 64.5,485.0Q52.0,504.0 52.0,523.0Q52.0,544.0 66.5,563.0Q81.0,582.0 110.0,610.0Q138.0,637.0 165.5,659.5Q193.0,682.0 208.0,682.0Q220.0,682.0 239.0,666.5Q258.0,651.0 296.0,624.0Q334.0,597.0 363.5,582.5Q393.0,568.0 422.0,568.0Q456.0,568.0 478.0,586.0Q500.0,604.0 500.0,633.0Q500.0,660.0 481.5,678.0Q463.0,696.0 435.5,703.0Q408.0,710.0 379.0,704.0Q378.0,738.0 389.5,759.0Q401.0,780.0 433.0,780.0Q460.0,780.0 491.5,765.0Q523.0,750.0 545.0,720.5Q567.0,691.0 567.0,646.0Q567.0,606.0 548.5,572.5Q530.0,539.0 495.5,519.0Q461.0,499.0 414.0,499.0Q371.0,499.0 335.5,516.0Q300.0,533.0 265.0,556.0Q235.0,576.0 220.0,585.5Q205.0,595.0 198.0,595.0Q190.0,595.0 180.5,588.5Q171.0,582.0 163.0,574.0Q155.0,566.0 147.5,556.0Q140.0,546.0 140.0,539.0Q140.0,532.0 151.0,519.0Q162.0,506.0 193.0,471.0L193.0,146.0Q193.0,125.0 212.0,107.0Q231.0,89.0 262.5,78.0Q294.0,67.0 333.0,67.0Q372.0,67.0 404.0,78.0Q436.0,89.0 454.5,107.0Q473.0,125.0 473.0,146.0L473.0,218.0Q430.0,218.0 396.5,245.0Q363.0,272.0 363.0,319.0Q363.0,355.0 382.0,382.0Q401.0,409.0 431.5,423.5Q462.0,438.0 498.0,438.0ZM473.0,285.0L473.0,376.0Q457.0,376.0 442.5,363.0Q428.0,350.0 428.0,327.0Q428.0,305.0 442.5,295.0Q457.0,285.0 473.0,285.0Z" transform="translate(9503, 793)"/>
<path d="M-172.0,-269.0Q-203.0,-269.0 -217.5,-253.0Q-232.0,-237.0 -234.0,-225.0L-376.0,-235.0Q-463.0,-241.0 -495.5,-221.5Q-528.0,-202.0 -528.0,-165.0Q-528.0,-122.0 -491.5,-105.0Q-455.0,-88.0 -376.0,-88.0L-234.0,-88.0L-234.0,-49.0L-152.0,-49.0L-152.0,-88.0L-89.0,-88.0L-89.0,-137.0L-152.0,-137.0L-152.0,-173.0Q-132.0,-177.0 -123.5,-189.5Q-115.0,-202.0 -115.0,-218.0Q-115.0,-239.0 -129.0,-254.0Q-143.0,-269.0 -172.0,-269.0ZM-234.0,-176.0L-234.0,-137.0L-376.0,-137.0Q-412.0,-137.0 -429.5,-140.0Q-447.0,-143.0 -447.0,-161.0Q-447.0,-170.0 -440.0,-175.5Q-433.0,-181.0 -411.5,-183.0Q-390.0,-185.0 -347.5,-183.0Q-305.0,-181.0 -234.0,-176.0Z" transform="translate(10145, 777)"/>
<path d="M-222.0,-273.0Q-263.0,-273.0 -293.5,-255.0Q-324.0,-237.0 -324.0,-203.0Q-324.0,-188.0 -319.0,-169.5Q-314.0,-151.0 -310.0,-138.0L-307.0,-130.0Q-319.0,-130.0 -327.5,-121.0Q-336.0,-112.0 -336.0,-96.0Q-336.0,-76.0 -320.5,-62.5Q-305.0,-49.0 -279.0,-49.0Q-255.0,-49.0 -241.0,-61.5Q-227.0,-74.0 -227.0,-100.0Q-227.0,-110.0 -230.0,-123.0Q-233.0,-136.0 -241.0,-160.0Q-248.0,-182.0 -242.5,-195.5Q-237.0,-209.0 -215.0,-209.0Q-188.0,-209.0 -172.5,-186.0Q-157.0,-163.0 -138.0,-117.0Q-121.0,-76.0 -110.5,-62.5Q-100.0,-49.0 -86.0,-49.0Q-75.0,-49.0 -64.0,-57.0Q-53.0,-65.0 -53.0,-85.0Q-53.0,-100.0 -60.5,-130.5Q-68.0,-161.0 -87.0,-194.0Q-106.0,-227.0 -139.0,-250.0Q-172.0,-273.0 -222.0,-273.0Z" transform="translate(10031, 492)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(10159, 793)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.0,765.0Q520.0,750.0 542.5,720.5Q565.0,691.0 565.0,647.0Q589.0,661.0 620.0,671.5Q651.0,682.0 687.0,682.0Q740.0,682.0 781.0,650.0L875.0,576.0Q913.0,547.0 913.0,501.0L913.0,0.0L821.0,0.0L821.0,501.0L722.0,580.0Q709.0,591.0 692.5,599.0Q676.0,607.0 653.0,607.0Q626.0,607.0 602.0,594.5Q578.0,582.0 555.5,564.5Q533.0,547.0 511.0,532.0Q492.0,516.0 467.0,507.5Q442.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(10536, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(11541, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(12235, 727)"/>
<path d="M149.0,558.0Q149.0,550.0 161.0,534.5Q173.0,519.0 195.0,499.0L195.0,246.0Q251.0,249.0 278.5,222.5Q306.0,196.0 306.0,151.0Q306.0,133.0 298.5,109.0Q291.0,85.0 267.5,57.5Q244.0,30.0 195.0,0.0L103.0,0.0L103.0,469.0Q54.0,519.0 54.0,542.0Q54.0,553.0 71.5,578.0Q89.0,603.0 117.0,629.0Q140.0,650.0 165.0,666.0Q190.0,682.0 206.0,682.0Q218.0,682.0 235.0,671.0Q252.0,660.0 276.0,639.0Q294.0,623.0 306.5,612.5Q319.0,602.0 320.0,602.0Q323.0,602.0 336.5,614.5Q350.0,627.0 368.0,644.0Q387.0,661.0 401.0,671.5Q415.0,682.0 431.0,682.0Q462.0,682.0 493.0,658.0Q524.0,634.0 545.5,597.0Q567.0,560.0 567.0,521.0L567.0,0.0L475.0,0.0L475.0,521.0Q475.0,548.0 455.5,569.5Q436.0,591.0 417.0,591.0Q403.0,591.0 389.5,580.0Q376.0,569.0 361.5,554.5Q347.0,540.0 331.0,529.0Q315.0,518.0 297.0,518.0Q279.0,518.0 263.0,528.5Q247.0,539.0 233.0,553.0Q219.0,567.0 207.0,577.5Q195.0,588.0 184.0,588.0Q178.0,588.0 172.0,585.0Q166.0,582.0 161.0,577.0Q149.0,567.0 149.0,558.0ZM195.0,181.0L195.0,89.0Q235.0,114.0 235.0,150.0Q235.0,169.0 223.5,175.0Q212.0,181.0 195.0,181.0Z" transform="translate(12195, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(12850, 699)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(12852, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(13525, 667)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(13485, 793)"/>
<path d="M128.0,515.0L194.0,463.0L194.0,246.0Q250.0,249.0 277.5,222.5Q305.0,196.0 305.0,151.0Q305.0,133.0 297.5,109.0Q290.0,85.0 266.5,57.5Q243.0,30.0 194.0,0.0L102.0,0.0L102.0,438.0Q69.0,467.0 58.5,480.5Q48.0,494.0 48.0,504.0Q48.0,514.0 56.5,526.0Q65.0,538.0 87.0,559.0Q109.0,580.0 148.0,614.0Q194.0,654.0 227.5,668.0Q261.0,682.0 297.0,682.0Q330.0,682.0 366.0,670.0Q402.0,658.0 449.0,622.0Q499.0,584.0 520.5,546.5Q542.0,509.0 542.0,463.0L542.0,91.0L669.0,196.0L797.0,91.0L797.0,438.0Q764.0,467.0 753.5,481.0Q743.0,495.0 743.0,505.0Q743.0,515.0 751.5,527.0Q760.0,539.0 782.0,559.5Q804.0,580.0 843.0,614.0Q889.0,654.0 920.5,668.0Q952.0,682.0 989.0,682.0Q1021.0,682.0 1059.0,670.0Q1097.0,658.0 1144.0,622.0Q1194.0,584.0 1215.5,546.5Q1237.0,509.0 1237.0,463.0L1237.0,0.0L1145.0,0.0L1145.0,464.0Q1145.0,489.0 1130.0,515.5Q1115.0,542.0 1091.0,564.5Q1067.0,587.0 1038.5,601.0Q1010.0,615.0 983.0,615.0Q952.0,615.0 916.5,592.0Q881.0,569.0 823.0,515.0L889.0,463.0L889.0,0.0L797.0,0.0L669.0,105.0L542.0,0.0L450.0,0.0L450.0,464.0Q450.0,489.0 435.5,515.5Q421.0,542.0 397.0,564.5Q373.0,587.0 344.5,601.0Q316.0,615.0 289.0,615.0Q258.0,615.0 222.0,592.0Q186.0,569.0 128.0,515.0ZM194.0,181.0L194.0,89.0Q234.0,114.0 234.0,150.0Q234.0,169.0 222.5,175.0Q211.0,181.0 194.0,181.0Z" transform="translate(13824, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(14846, 699)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(15151, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">និងជំនឿ</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: uni1793=0+652|uni17B7=0@31,-94+0|uni1784=2+684|uni1787=3+655|uni17C6=3@29,-24+0|uni17C1=5+339|uni1793=5+652|uni17BF.right1=5+358</pre>



<pre>Got     : uni1793=0+652|uni17B7=0@31,-94+0|uni1784=2+684|uni1787=3+655|uni17C6=3@29,6+0|uni17C1=5+339|uni1793=5+652|uni17BF.right1=5+358</pre>



<pre>                                                                                    ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3340 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(0, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-300.0,1050.0 -182.0,946.0Q-156.0,924.0 -145.0,908.0Q-134.0,892.0 -134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(683, 699)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(652, 793)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.5,765.0Q521.0,750.0 543.0,720.5Q565.0,691.0 565.0,646.0Q565.0,606.0 546.5,572.5Q528.0,539.0 493.5,519.0Q459.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(1336, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(2020, 799)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(1991, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(2330, 793)"/>
<path d="M166.0,1122.0L166.0,991.0Q215.0,950.0 236.5,904.0Q258.0,858.0 258.0,810.0L258.0,-195.0Q258.0,-317.0 38.0,-317.0Q-182.0,-317.0 -182.0,-195.0L-182.0,-49.0L-90.0,-49.0L-90.0,-185.0Q-90.0,-211.0 -58.0,-230.5Q-26.0,-250.0 38.0,-250.0Q103.0,-250.0 134.5,-230.5Q166.0,-211.0 166.0,-185.0L166.0,810.0Q166.0,903.0 68.0,903.0L-115.0,903.0Q-156.0,903.0 -171.0,927.0Q-186.0,951.0 -186.0,982.0Q-186.0,1029.0 -156.5,1063.5Q-127.0,1098.0 -59.0,1098.0Q-33.0,1098.0 -9.0,1091.0L-9.0,1147.0L58.0,1147.0L58.0,1061.0Q76.0,1051.0 98.0,1037.0L98.0,1122.0L166.0,1122.0ZM-113.0,966.0L76.0,966.0Q40.0,997.0 6.0,1015.5Q-28.0,1034.0 -55.0,1034.0Q-80.0,1034.0 -96.5,1017.0Q-113.0,1000.0 -113.0,966.0Z" transform="translate(2982, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3340 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(0, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-300.0,1050.0 -182.0,946.0Q-156.0,924.0 -145.0,908.0Q-134.0,892.0 -134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(683, 699)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(652, 793)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.5,765.0Q521.0,750.0 543.0,720.5Q565.0,691.0 565.0,646.0Q565.0,606.0 546.5,572.5Q528.0,539.0 493.5,519.0Q459.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(1336, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(2020, 769)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(1991, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(2330, 793)"/>
<path d="M166.0,1122.0L166.0,991.0Q215.0,950.0 236.5,904.0Q258.0,858.0 258.0,810.0L258.0,-195.0Q258.0,-317.0 38.0,-317.0Q-182.0,-317.0 -182.0,-195.0L-182.0,-49.0L-90.0,-49.0L-90.0,-185.0Q-90.0,-211.0 -58.0,-230.5Q-26.0,-250.0 38.0,-250.0Q103.0,-250.0 134.5,-230.5Q166.0,-211.0 166.0,-185.0L166.0,810.0Q166.0,903.0 68.0,903.0L-115.0,903.0Q-156.0,903.0 -171.0,927.0Q-186.0,951.0 -186.0,982.0Q-186.0,1029.0 -156.5,1063.5Q-127.0,1098.0 -59.0,1098.0Q-33.0,1098.0 -9.0,1091.0L-9.0,1147.0L58.0,1147.0L58.0,1061.0Q76.0,1051.0 98.0,1037.0L98.0,1122.0L166.0,1122.0ZM-113.0,966.0L76.0,966.0Q40.0,997.0 6.0,1015.5Q-28.0,1034.0 -55.0,1034.0Q-80.0,1034.0 -96.5,1017.0Q-113.0,1000.0 -113.0,966.0Z" transform="translate(2982, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">វាងកុំឱ្យមនុស្សបង្ខំចិត្ដជាចុងក្រោយបង្អស់</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: uni179C17B6=0+660|uni1784=2+684|uni1780=3+633|uni17BB=3@-116,-16+0|uni17C6=3@40,-126+0|uni17B1=6+668|uni17D21799=6+350|uni1798=9+654|uni1793=10+652|uni17BB=10@-125,-16+0|uni179F=12+1001|uni17D2179F=12+389|uni1794=15+654|uni1784=16+684|uni17D21781=16@8,-16+0|uni17C6=16@-4,-14+0|uni1785=20+653|uni17B7=20@44,-94+0|uni178F=22+633|uni17D2178A=22@2,-16+0|uni178717B6=25+1005|uni1785=27+653|uni17BB=27@-112,-16+0|uni1784=29+684|uni17C1=30+339|uni17D2179A=30+371|uni178017B6=30+981|uni1799=34+1025|uni1794=35+654|uni1784=36+684|uni17D217A2=36@19,-16+0|uni179F=39+1001|uni17CB=39@20,-66+0</pre>



<pre>Got     : uni179C17B6=0+660|uni1784=2+684|uni1780=3+633|uni17BB=3@-116,-16+0|uni17C6=3@40,-94+0|uni17B1=6+668|uni17D21799=6+350|uni1798=9+654|uni1793=10+652|uni17BB=10@-125,-16+0|uni179F=12+1001|uni17D2179F=12+389|uni1794=15+654|uni1784=16+684|uni17D21781=16@8,-16+0|uni17C6=16@-4,-14+0|uni1785=20+653|uni17B7=20@44,-94+0|uni178F=22+633|uni17D2178A=22@2,-16+0|uni178717B6=25+1005|uni1785=27+653|uni17BB=27@-112,-16+0|uni1784=29+684|uni17C1=30+339|uni17D2179A=30+371|uni178017B6=30+981|uni1799=34+1025|uni1794=35+654|uni1784=36+684|uni17D217A2=36@19,-16+0|uni179F=39+1001|uni17CB=39@20,-66+0</pre>



<pre>                                                                                           ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15712 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M123.0,530.0L226.0,447.0L226.0,0.0L134.0,0.0Q87.0,34.0 63.0,60.5Q39.0,87.0 31.0,108.0Q23.0,129.0 23.0,146.0Q23.0,165.0 32.0,187.5Q41.0,210.0 65.5,226.5Q90.0,243.0 134.0,244.0L134.0,424.0Q98.0,454.0 79.5,470.5Q61.0,487.0 55.0,495.5Q49.0,504.0 49.0,511.0Q49.0,521.0 58.5,535.5Q68.0,550.0 93.0,582.5Q118.0,615.0 164.0,679.0Q184.0,661.0 196.5,653.0Q209.0,645.0 222.0,645.0Q236.0,645.0 248.0,652.5Q260.0,660.0 260.0,676.0Q260.0,694.0 241.5,708.0Q223.0,722.0 195.0,722.0Q195.0,753.0 212.0,766.0Q229.0,779.0 244.0,779.0Q260.0,779.0 277.5,767.0Q295.0,755.0 307.0,732.5Q319.0,710.0 319.0,681.0Q319.0,676.0 319.0,673.0Q334.0,677.0 350.0,677.0Q370.0,677.0 392.5,669.5Q415.0,662.0 436.0,645.0L530.0,571.0Q568.0,542.0 568.0,496.0L568.0,0.0L476.0,0.0L476.0,501.0L377.0,580.0Q364.0,591.0 350.5,596.5Q337.0,602.0 319.0,602.0Q305.0,602.0 295.5,599.0Q286.0,596.0 278.0,592.0Q253.0,570.0 220.0,570.0Q203.0,570.0 189.5,576.0Q176.0,582.0 167.0,589.0L123.0,530.0ZM134.0,84.0L134.0,176.0Q109.0,175.0 99.5,166.0Q90.0,157.0 90.0,143.0Q90.0,110.0 134.0,84.0Z" transform="translate(0, 793)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(660, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(1344, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(1861, 777)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(2017, 699)"/>
<path d="M210.0,745.0L147.0,701.0Q73.0,742.0 73.0,808.0Q73.0,856.0 107.0,890.5Q141.0,925.0 195.5,943.0Q250.0,961.0 313.0,961.0Q366.0,961.0 416.0,948.5Q466.0,936.0 505.5,913.5Q545.0,891.0 568.5,860.5Q592.0,830.0 592.0,795.0Q592.0,768.0 577.0,744.0Q562.0,720.0 531.0,710.0Q534.0,761.0 503.5,803.0Q473.0,845.0 419.5,870.5Q366.0,896.0 297.0,896.0Q236.0,896.0 194.0,874.5Q152.0,853.0 152.0,815.0Q152.0,793.0 167.0,777.5Q182.0,762.0 210.0,745.0ZM186.0,355.0Q108.0,355.0 108.0,407.0L108.0,536.0Q108.0,575.0 139.5,608.5Q171.0,642.0 223.5,662.0Q276.0,682.0 340.0,682.0Q405.0,682.0 457.5,661.5Q510.0,641.0 541.0,607.5Q572.0,574.0 572.0,536.0L572.0,463.0Q572.0,377.0 386.0,282.0L200.0,187.0L200.0,122.0Q200.0,70.0 245.0,70.0Q272.0,70.0 297.0,91.0Q352.0,137.0 393.0,166.5Q434.0,196.0 480.0,200.0L480.0,235.0L572.0,279.0L572.0,24.0Q572.0,-12.0 553.0,-30.5Q534.0,-49.0 506.0,-49.0Q481.0,-49.0 465.5,-35.0Q450.0,-21.0 450.0,-4.0Q467.0,9.0 473.5,22.5Q480.0,36.0 480.0,49.0L480.0,130.0Q469.0,130.0 452.5,123.0Q436.0,116.0 396.0,87.0Q363.0,63.0 336.5,43.5Q310.0,24.0 284.0,12.0Q258.0,0.0 224.0,0.0Q175.0,0.0 141.5,29.0Q108.0,58.0 108.0,122.0L108.0,219.0L340.0,338.0Q480.0,409.0 480.0,463.0L480.0,536.0Q480.0,557.0 461.5,575.0Q443.0,593.0 411.5,604.0Q380.0,615.0 341.0,615.0Q280.0,615.0 240.0,591.0Q200.0,567.0 200.0,536.0L200.0,509.0Q236.0,509.0 259.0,491.5Q282.0,474.0 282.0,436.0Q282.0,396.0 256.0,375.5Q230.0,355.0 186.0,355.0ZM200.0,470.0L200.0,396.0Q215.0,396.0 224.0,406.5Q233.0,417.0 233.0,435.0Q233.0,470.0 200.0,470.0Z" transform="translate(1977, 793)"/>
<path d="M145.0,532.0L250.0,447.0L250.0,-184.0Q250.0,-245.0 195.0,-280.5Q140.0,-316.0 30.0,-316.0Q-190.0,-316.0 -190.0,-192.0L-190.0,-113.0Q-190.0,-83.0 -172.0,-66.0Q-154.0,-49.0 -121.0,-49.0Q-84.0,-49.0 -64.5,-67.5Q-45.0,-86.0 -45.0,-111.0Q-45.0,-133.0 -59.5,-151.5Q-74.0,-170.0 -98.0,-170.0L-98.0,-200.0Q-98.0,-221.0 -66.0,-235.0Q-34.0,-249.0 30.0,-249.0Q95.0,-249.0 126.5,-235.0Q158.0,-221.0 158.0,-200.0L158.0,424.0Q121.0,454.0 103.0,471.0Q85.0,488.0 79.0,497.5Q73.0,507.0 73.0,514.0Q73.0,524.0 82.5,538.0Q92.0,552.0 117.0,584.0Q142.0,616.0 188.0,680.0Q220.0,659.0 241.0,647.0Q262.0,635.0 281.5,631.0Q301.0,627.0 326.0,629.0Q326.0,604.0 308.5,580.5Q291.0,557.0 262.0,557.0Q249.0,557.0 231.5,564.0Q214.0,571.0 188.0,590.0L145.0,532.0Z" transform="translate(2645, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(2995, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(3649, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(4176, 777)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4301, 793)"/>
<path d="M-173.0,-191.0L-173.0,-178.0Q-197.0,-177.0 -210.5,-159.5Q-224.0,-142.0 -224.0,-120.0Q-224.0,-89.0 -202.5,-69.0Q-181.0,-49.0 -141.0,-49.0Q-81.0,-49.0 -81.0,-98.0L-81.0,-185.0Q-81.0,-250.0 47.0,-250.0Q175.0,-250.0 175.0,-185.0L175.0,0.0L96.0,0.0L96.0,67.0L175.0,67.0L175.0,424.0Q139.0,454.0 120.5,471.0Q102.0,488.0 96.0,497.5Q90.0,507.0 90.0,514.0Q90.0,524.0 99.5,538.0Q109.0,552.0 134.0,584.0Q159.0,616.0 205.0,680.0Q237.0,659.0 258.0,647.0Q279.0,635.0 298.5,631.0Q318.0,627.0 343.0,629.0Q343.0,604.0 325.5,580.5Q308.0,557.0 279.0,557.0Q266.0,557.0 248.5,564.0Q231.0,571.0 205.0,590.0L162.0,532.0L267.0,447.0L267.0,67.0L340.0,67.0L340.0,0.0L267.0,0.0L267.0,-185.0Q267.0,-246.0 212.0,-281.5Q157.0,-317.0 47.0,-317.0Q-60.0,-317.0 -115.0,-283.5Q-170.0,-250.0 -173.0,-191.0L-173.0,-191.0Z" transform="translate(5302, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(5691, 793)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(6345, 793)"/>
<path d="M-323.0,-318.0Q-372.0,-318.0 -417.0,-310.5Q-462.0,-303.0 -490.0,-283.5Q-518.0,-264.0 -518.0,-228.0Q-518.0,-190.0 -486.0,-186.0L-332.0,-164.0Q-303.0,-160.0 -274.0,-154.0Q-245.0,-148.0 -225.5,-140.0Q-206.0,-132.0 -206.0,-122.0Q-206.0,-113.0 -218.5,-108.5Q-231.0,-104.0 -249.0,-101.5Q-267.0,-99.0 -284.5,-98.5Q-302.0,-98.0 -313.0,-98.0Q-380.0,-98.0 -407.0,-112.5Q-434.0,-127.0 -434.0,-153.0Q-471.0,-153.0 -490.0,-146.5Q-509.0,-140.0 -509.0,-120.0Q-509.0,-85.0 -455.0,-67.0Q-401.0,-49.0 -313.0,-49.0Q-286.0,-49.0 -255.0,-51.0Q-224.0,-53.0 -196.0,-59.5Q-168.0,-66.0 -150.0,-80.0Q-132.0,-94.0 -132.0,-119.0Q-132.0,-129.0 -136.5,-140.5Q-141.0,-152.0 -156.5,-164.0Q-172.0,-176.0 -205.5,-187.0Q-239.0,-198.0 -298.0,-206.0L-446.0,-227.0Q-443.0,-242.0 -423.5,-251.0Q-404.0,-260.0 -377.0,-264.5Q-350.0,-269.0 -326.0,-269.0Q-276.0,-269.0 -240.0,-254.0Q-204.0,-239.0 -204.0,-214.0Q-160.0,-214.0 -144.0,-221.5Q-128.0,-229.0 -128.0,-244.0Q-128.0,-268.0 -157.5,-284.5Q-187.0,-301.0 -231.5,-309.5Q-276.0,-318.0 -323.0,-318.0Z" transform="translate(7037, 777)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(7025, 779)"/>
<path d="M499.0,448.0Q534.0,448.0 550.0,434.0Q566.0,420.0 566.0,395.0L566.0,146.0Q566.0,108.0 535.5,74.5Q505.0,41.0 454.5,20.5Q404.0,0.0 344.0,0.0Q283.0,0.0 232.5,21.0Q182.0,42.0 152.0,75.5Q122.0,109.0 122.0,146.0L122.0,443.0Q98.0,466.0 85.5,483.5Q73.0,501.0 73.0,523.0Q73.0,550.0 88.5,570.0Q104.0,590.0 127.0,612.0Q173.0,656.0 196.5,668.0Q220.0,680.0 230.0,680.0Q242.0,680.0 258.0,667.5Q274.0,655.0 302.0,628.0Q327.0,603.0 337.0,595.0Q347.0,587.0 355.0,587.0Q363.0,587.0 373.0,596.0Q383.0,605.0 406.0,628.0Q430.0,653.0 446.5,666.5Q463.0,680.0 475.0,680.0Q491.0,680.0 518.0,652.0L563.0,604.0Q576.0,590.0 594.0,584.0Q612.0,578.0 635.0,582.0Q627.0,538.0 607.0,519.0Q587.0,500.0 565.0,500.0Q545.0,500.0 532.5,511.0Q520.0,522.0 509.5,537.0Q499.0,552.0 488.0,563.0Q477.0,574.0 460.0,574.0Q446.0,574.0 432.5,563.5Q419.0,553.0 404.0,539.0Q382.0,520.0 367.5,510.0Q353.0,500.0 339.0,500.0Q323.0,500.0 304.5,511.5Q286.0,523.0 265.0,540.0Q237.0,564.0 226.0,572.0Q215.0,580.0 207.0,580.0Q193.0,580.0 178.0,567.0Q163.0,554.0 163.0,540.0Q163.0,535.0 166.0,529.0Q169.0,523.0 179.5,510.0Q190.0,497.0 214.0,471.0L214.0,146.0Q214.0,126.0 232.0,108.0Q250.0,90.0 279.5,78.5Q309.0,67.0 344.0,67.0Q381.0,67.0 410.0,79.0Q439.0,91.0 456.5,109.0Q474.0,127.0 474.0,146.0L474.0,228.0Q431.0,228.0 397.5,255.0Q364.0,282.0 364.0,329.0Q364.0,365.0 383.0,392.0Q402.0,419.0 432.5,433.5Q463.0,448.0 499.0,448.0ZM474.0,295.0L474.0,386.0Q458.0,386.0 443.5,373.0Q429.0,360.0 429.0,337.0Q429.0,315.0 443.5,305.0Q458.0,295.0 474.0,295.0Z" transform="translate(7029, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-300.0,1050.0 -182.0,946.0Q-156.0,924.0 -145.0,908.0Q-134.0,892.0 -134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(7726, 699)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(7682, 793)"/>
<path d="M-525.0,-317.0L-525.0,-171.0Q-525.0,-128.0 -498.5,-101.5Q-472.0,-75.0 -425.5,-62.0Q-379.0,-49.0 -321.0,-49.0Q-262.0,-49.0 -216.0,-62.0Q-170.0,-75.0 -143.5,-101.5Q-117.0,-128.0 -117.0,-171.0L-117.0,-317.0L-199.0,-317.0L-199.0,-171.0Q-199.0,-132.0 -234.5,-115.0Q-270.0,-98.0 -321.0,-98.0Q-372.0,-98.0 -407.5,-115.0Q-443.0,-132.0 -443.0,-171.0L-443.0,-185.0Q-409.0,-185.0 -392.0,-201.0Q-375.0,-217.0 -375.0,-243.0Q-375.0,-265.0 -388.5,-284.5Q-402.0,-304.0 -443.0,-317.0L-525.0,-317.0ZM-443.0,-223.0L-443.0,-281.0Q-429.0,-277.0 -422.5,-266.0Q-416.0,-255.0 -416.0,-245.0Q-416.0,-231.0 -424.0,-227.0Q-432.0,-223.0 -443.0,-223.0Z" transform="translate(8317, 777)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.0,765.0Q520.0,750.0 542.5,720.5Q565.0,691.0 565.0,647.0Q589.0,661.0 620.0,671.5Q651.0,682.0 687.0,682.0Q740.0,682.0 781.0,650.0L875.0,576.0Q913.0,547.0 913.0,501.0L913.0,0.0L821.0,0.0L821.0,501.0L722.0,580.0Q709.0,591.0 692.5,599.0Q676.0,607.0 653.0,607.0Q626.0,607.0 602.0,594.5Q578.0,582.0 555.5,564.5Q533.0,547.0 511.0,532.0Q492.0,516.0 467.0,507.5Q442.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(8315, 793)"/>
<path d="M499.0,448.0Q534.0,448.0 550.0,434.0Q566.0,420.0 566.0,395.0L566.0,146.0Q566.0,108.0 535.5,74.5Q505.0,41.0 454.5,20.5Q404.0,0.0 344.0,0.0Q283.0,0.0 232.5,21.0Q182.0,42.0 152.0,75.5Q122.0,109.0 122.0,146.0L122.0,443.0Q98.0,466.0 85.5,483.5Q73.0,501.0 73.0,523.0Q73.0,550.0 88.5,570.0Q104.0,590.0 127.0,612.0Q173.0,656.0 196.5,668.0Q220.0,680.0 230.0,680.0Q242.0,680.0 258.0,667.5Q274.0,655.0 302.0,628.0Q327.0,603.0 337.0,595.0Q347.0,587.0 355.0,587.0Q363.0,587.0 373.0,596.0Q383.0,605.0 406.0,628.0Q430.0,653.0 446.5,666.5Q463.0,680.0 475.0,680.0Q491.0,680.0 518.0,652.0L563.0,604.0Q576.0,590.0 594.0,584.0Q612.0,578.0 635.0,582.0Q627.0,538.0 607.0,519.0Q587.0,500.0 565.0,500.0Q545.0,500.0 532.5,511.0Q520.0,522.0 509.5,537.0Q499.0,552.0 488.0,563.0Q477.0,574.0 460.0,574.0Q446.0,574.0 432.5,563.5Q419.0,553.0 404.0,539.0Q382.0,520.0 367.5,510.0Q353.0,500.0 339.0,500.0Q323.0,500.0 304.5,511.5Q286.0,523.0 265.0,540.0Q237.0,564.0 226.0,572.0Q215.0,580.0 207.0,580.0Q193.0,580.0 178.0,567.0Q163.0,554.0 163.0,540.0Q163.0,535.0 166.0,529.0Q169.0,523.0 179.5,510.0Q190.0,497.0 214.0,471.0L214.0,146.0Q214.0,126.0 232.0,108.0Q250.0,90.0 279.5,78.5Q309.0,67.0 344.0,67.0Q381.0,67.0 410.0,79.0Q439.0,91.0 456.5,109.0Q474.0,127.0 474.0,146.0L474.0,228.0Q431.0,228.0 397.5,255.0Q364.0,282.0 364.0,329.0Q364.0,365.0 383.0,392.0Q402.0,419.0 432.5,433.5Q463.0,448.0 499.0,448.0ZM474.0,295.0L474.0,386.0Q458.0,386.0 443.5,373.0Q429.0,360.0 429.0,337.0Q429.0,315.0 443.5,305.0Q458.0,295.0 474.0,295.0Z" transform="translate(9320, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(9861, 777)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(9973, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(10657, 793)"/>
<path d="M121.0,532.0L226.0,447.0L226.0,-193.0Q226.0,-250.0 348.0,-250.0Q469.0,-250.0 469.0,-193.0L469.0,-49.0L561.0,-49.0L561.0,-195.0Q561.0,-317.0 348.0,-317.0Q134.0,-317.0 134.0,-195.0L134.0,424.0Q98.0,454.0 79.5,471.0Q61.0,488.0 55.0,497.5Q49.0,507.0 49.0,514.0Q49.0,524.0 58.5,538.0Q68.0,552.0 93.0,584.0Q118.0,616.0 164.0,680.0Q196.0,659.0 217.0,647.0Q238.0,635.0 257.5,631.0Q277.0,627.0 302.0,629.0Q302.0,604.0 284.5,580.5Q267.0,557.0 238.0,557.0Q225.0,557.0 207.5,564.0Q190.0,571.0 164.0,590.0L121.0,532.0Z" transform="translate(10996, 793)"/>
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM539.0,316.0L539.0,0.0L447.0,0.0L447.0,316.0Q447.0,336.0 429.5,353.5Q412.0,371.0 383.0,381.5Q354.0,392.0 318.0,392.0Q262.0,392.0 224.5,368.5Q187.0,345.0 187.0,316.0L187.0,0.0L95.0,0.0L95.0,316.0Q95.0,354.0 125.5,386.5Q156.0,419.0 206.5,439.0Q257.0,459.0 317.0,459.0Q379.0,459.0 429.5,438.5Q480.0,418.0 509.5,385.5Q539.0,353.0 539.0,316.0Z" transform="translate(11367, 793)"/>
<path d="M829.0,532.0L934.0,447.0L934.0,146.0Q934.0,114.0 906.0,80.0Q878.0,46.0 828.5,23.0Q779.0,0.0 714.0,0.0Q665.0,0.0 618.5,15.0Q572.0,30.0 540.0,62.0Q501.0,23.0 454.5,11.5Q408.0,0.0 353.0,0.0Q282.0,0.0 230.0,23.0Q178.0,46.0 150.0,80.0Q122.0,114.0 122.0,146.0L122.0,621.0Q122.0,650.0 144.0,666.0Q166.0,682.0 203.0,682.0Q262.0,682.0 294.0,644.0Q326.0,606.0 326.0,555.0Q326.0,506.0 296.5,469.0Q267.0,432.0 214.0,422.0L214.0,146.0Q214.0,124.0 233.0,106.5Q252.0,89.0 283.5,78.0Q315.0,67.0 353.0,67.0Q394.0,67.0 426.0,79.0Q458.0,91.0 476.0,109.0Q494.0,127.0 494.0,146.0L494.0,424.0Q458.0,454.0 439.5,471.0Q421.0,488.0 415.0,497.5Q409.0,507.0 409.0,514.0Q409.0,524.0 418.5,538.0Q428.0,552.0 453.0,584.0Q478.0,616.0 524.0,680.0Q556.0,659.0 577.0,647.0Q598.0,635.0 617.5,631.0Q637.0,627.0 662.0,629.0Q662.0,604.0 644.5,580.5Q627.0,557.0 598.0,557.0Q585.0,557.0 567.5,564.0Q550.0,571.0 524.0,590.0L481.0,532.0L586.0,447.0L586.0,146.0Q586.0,127.0 603.5,109.0Q621.0,91.0 650.5,79.0Q680.0,67.0 714.0,67.0Q749.0,67.0 778.0,79.0Q807.0,91.0 824.5,109.0Q842.0,127.0 842.0,146.0L842.0,424.0Q806.0,454.0 787.5,471.0Q769.0,488.0 763.0,497.5Q757.0,507.0 757.0,514.0Q757.0,524.0 766.5,538.0Q776.0,552.0 801.0,584.0Q826.0,616.0 872.0,680.0Q904.0,659.0 925.0,647.0Q946.0,635.0 965.5,631.0Q985.0,627.0 1010.0,629.0Q1010.0,604.0 992.5,580.5Q975.0,557.0 946.0,557.0Q933.0,557.0 915.5,564.0Q898.0,571.0 872.0,590.0L829.0,532.0ZM214.0,604.0L214.0,489.0Q231.0,490.0 245.0,506.5Q259.0,523.0 259.0,548.0Q259.0,569.0 247.5,584.5Q236.0,600.0 214.0,604.0Z" transform="translate(12348, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(13373, 793)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(14027, 793)"/>
<path d="M-569.0,-254.0Q-569.0,-239.0 -559.0,-229.5Q-549.0,-220.0 -530.0,-220.0L-530.0,-123.0Q-530.0,-109.0 -539.0,-103.5Q-548.0,-98.0 -569.0,-98.0L-569.0,-49.0L-542.0,-49.0Q-499.0,-49.0 -473.5,-61.0Q-448.0,-73.0 -448.0,-112.0L-448.0,-142.0L-212.0,-142.0L-212.0,-123.0Q-212.0,-108.0 -221.5,-103.0Q-231.0,-98.0 -251.0,-98.0L-251.0,-49.0L-225.0,-49.0Q-181.0,-49.0 -155.5,-61.0Q-130.0,-73.0 -130.0,-112.0L-130.0,-317.0L-212.0,-317.0Q-251.0,-279.0 -251.0,-254.0Q-251.0,-239.0 -241.0,-229.5Q-231.0,-220.0 -212.0,-220.0L-212.0,-191.0L-448.0,-191.0L-448.0,-317.0L-530.0,-317.0Q-569.0,-279.0 -569.0,-254.0Z" transform="translate(14730, 777)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(14711, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(15732, 727)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15712 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M123.0,530.0L226.0,447.0L226.0,0.0L134.0,0.0Q87.0,34.0 63.0,60.5Q39.0,87.0 31.0,108.0Q23.0,129.0 23.0,146.0Q23.0,165.0 32.0,187.5Q41.0,210.0 65.5,226.5Q90.0,243.0 134.0,244.0L134.0,424.0Q98.0,454.0 79.5,470.5Q61.0,487.0 55.0,495.5Q49.0,504.0 49.0,511.0Q49.0,521.0 58.5,535.5Q68.0,550.0 93.0,582.5Q118.0,615.0 164.0,679.0Q184.0,661.0 196.5,653.0Q209.0,645.0 222.0,645.0Q236.0,645.0 248.0,652.5Q260.0,660.0 260.0,676.0Q260.0,694.0 241.5,708.0Q223.0,722.0 195.0,722.0Q195.0,753.0 212.0,766.0Q229.0,779.0 244.0,779.0Q260.0,779.0 277.5,767.0Q295.0,755.0 307.0,732.5Q319.0,710.0 319.0,681.0Q319.0,676.0 319.0,673.0Q334.0,677.0 350.0,677.0Q370.0,677.0 392.5,669.5Q415.0,662.0 436.0,645.0L530.0,571.0Q568.0,542.0 568.0,496.0L568.0,0.0L476.0,0.0L476.0,501.0L377.0,580.0Q364.0,591.0 350.5,596.5Q337.0,602.0 319.0,602.0Q305.0,602.0 295.5,599.0Q286.0,596.0 278.0,592.0Q253.0,570.0 220.0,570.0Q203.0,570.0 189.5,576.0Q176.0,582.0 167.0,589.0L123.0,530.0ZM134.0,84.0L134.0,176.0Q109.0,175.0 99.5,166.0Q90.0,157.0 90.0,143.0Q90.0,110.0 134.0,84.0Z" transform="translate(0, 793)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(660, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(1344, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(1861, 777)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(2017, 667)"/>
<path d="M210.0,745.0L147.0,701.0Q73.0,742.0 73.0,808.0Q73.0,856.0 107.0,890.5Q141.0,925.0 195.5,943.0Q250.0,961.0 313.0,961.0Q366.0,961.0 416.0,948.5Q466.0,936.0 505.5,913.5Q545.0,891.0 568.5,860.5Q592.0,830.0 592.0,795.0Q592.0,768.0 577.0,744.0Q562.0,720.0 531.0,710.0Q534.0,761.0 503.5,803.0Q473.0,845.0 419.5,870.5Q366.0,896.0 297.0,896.0Q236.0,896.0 194.0,874.5Q152.0,853.0 152.0,815.0Q152.0,793.0 167.0,777.5Q182.0,762.0 210.0,745.0ZM186.0,355.0Q108.0,355.0 108.0,407.0L108.0,536.0Q108.0,575.0 139.5,608.5Q171.0,642.0 223.5,662.0Q276.0,682.0 340.0,682.0Q405.0,682.0 457.5,661.5Q510.0,641.0 541.0,607.5Q572.0,574.0 572.0,536.0L572.0,463.0Q572.0,377.0 386.0,282.0L200.0,187.0L200.0,122.0Q200.0,70.0 245.0,70.0Q272.0,70.0 297.0,91.0Q352.0,137.0 393.0,166.5Q434.0,196.0 480.0,200.0L480.0,235.0L572.0,279.0L572.0,24.0Q572.0,-12.0 553.0,-30.5Q534.0,-49.0 506.0,-49.0Q481.0,-49.0 465.5,-35.0Q450.0,-21.0 450.0,-4.0Q467.0,9.0 473.5,22.5Q480.0,36.0 480.0,49.0L480.0,130.0Q469.0,130.0 452.5,123.0Q436.0,116.0 396.0,87.0Q363.0,63.0 336.5,43.5Q310.0,24.0 284.0,12.0Q258.0,0.0 224.0,0.0Q175.0,0.0 141.5,29.0Q108.0,58.0 108.0,122.0L108.0,219.0L340.0,338.0Q480.0,409.0 480.0,463.0L480.0,536.0Q480.0,557.0 461.5,575.0Q443.0,593.0 411.5,604.0Q380.0,615.0 341.0,615.0Q280.0,615.0 240.0,591.0Q200.0,567.0 200.0,536.0L200.0,509.0Q236.0,509.0 259.0,491.5Q282.0,474.0 282.0,436.0Q282.0,396.0 256.0,375.5Q230.0,355.0 186.0,355.0ZM200.0,470.0L200.0,396.0Q215.0,396.0 224.0,406.5Q233.0,417.0 233.0,435.0Q233.0,470.0 200.0,470.0Z" transform="translate(1977, 793)"/>
<path d="M145.0,532.0L250.0,447.0L250.0,-184.0Q250.0,-245.0 195.0,-280.5Q140.0,-316.0 30.0,-316.0Q-190.0,-316.0 -190.0,-192.0L-190.0,-113.0Q-190.0,-83.0 -172.0,-66.0Q-154.0,-49.0 -121.0,-49.0Q-84.0,-49.0 -64.5,-67.5Q-45.0,-86.0 -45.0,-111.0Q-45.0,-133.0 -59.5,-151.5Q-74.0,-170.0 -98.0,-170.0L-98.0,-200.0Q-98.0,-221.0 -66.0,-235.0Q-34.0,-249.0 30.0,-249.0Q95.0,-249.0 126.5,-235.0Q158.0,-221.0 158.0,-200.0L158.0,424.0Q121.0,454.0 103.0,471.0Q85.0,488.0 79.0,497.5Q73.0,507.0 73.0,514.0Q73.0,524.0 82.5,538.0Q92.0,552.0 117.0,584.0Q142.0,616.0 188.0,680.0Q220.0,659.0 241.0,647.0Q262.0,635.0 281.5,631.0Q301.0,627.0 326.0,629.0Q326.0,604.0 308.5,580.5Q291.0,557.0 262.0,557.0Q249.0,557.0 231.5,564.0Q214.0,571.0 188.0,590.0L145.0,532.0Z" transform="translate(2645, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(2995, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(3649, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(4176, 777)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4301, 793)"/>
<path d="M-173.0,-191.0L-173.0,-178.0Q-197.0,-177.0 -210.5,-159.5Q-224.0,-142.0 -224.0,-120.0Q-224.0,-89.0 -202.5,-69.0Q-181.0,-49.0 -141.0,-49.0Q-81.0,-49.0 -81.0,-98.0L-81.0,-185.0Q-81.0,-250.0 47.0,-250.0Q175.0,-250.0 175.0,-185.0L175.0,0.0L96.0,0.0L96.0,67.0L175.0,67.0L175.0,424.0Q139.0,454.0 120.5,471.0Q102.0,488.0 96.0,497.5Q90.0,507.0 90.0,514.0Q90.0,524.0 99.5,538.0Q109.0,552.0 134.0,584.0Q159.0,616.0 205.0,680.0Q237.0,659.0 258.0,647.0Q279.0,635.0 298.5,631.0Q318.0,627.0 343.0,629.0Q343.0,604.0 325.5,580.5Q308.0,557.0 279.0,557.0Q266.0,557.0 248.5,564.0Q231.0,571.0 205.0,590.0L162.0,532.0L267.0,447.0L267.0,67.0L340.0,67.0L340.0,0.0L267.0,0.0L267.0,-185.0Q267.0,-246.0 212.0,-281.5Q157.0,-317.0 47.0,-317.0Q-60.0,-317.0 -115.0,-283.5Q-170.0,-250.0 -173.0,-191.0L-173.0,-191.0Z" transform="translate(5302, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(5691, 793)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(6345, 793)"/>
<path d="M-323.0,-318.0Q-372.0,-318.0 -417.0,-310.5Q-462.0,-303.0 -490.0,-283.5Q-518.0,-264.0 -518.0,-228.0Q-518.0,-190.0 -486.0,-186.0L-332.0,-164.0Q-303.0,-160.0 -274.0,-154.0Q-245.0,-148.0 -225.5,-140.0Q-206.0,-132.0 -206.0,-122.0Q-206.0,-113.0 -218.5,-108.5Q-231.0,-104.0 -249.0,-101.5Q-267.0,-99.0 -284.5,-98.5Q-302.0,-98.0 -313.0,-98.0Q-380.0,-98.0 -407.0,-112.5Q-434.0,-127.0 -434.0,-153.0Q-471.0,-153.0 -490.0,-146.5Q-509.0,-140.0 -509.0,-120.0Q-509.0,-85.0 -455.0,-67.0Q-401.0,-49.0 -313.0,-49.0Q-286.0,-49.0 -255.0,-51.0Q-224.0,-53.0 -196.0,-59.5Q-168.0,-66.0 -150.0,-80.0Q-132.0,-94.0 -132.0,-119.0Q-132.0,-129.0 -136.5,-140.5Q-141.0,-152.0 -156.5,-164.0Q-172.0,-176.0 -205.5,-187.0Q-239.0,-198.0 -298.0,-206.0L-446.0,-227.0Q-443.0,-242.0 -423.5,-251.0Q-404.0,-260.0 -377.0,-264.5Q-350.0,-269.0 -326.0,-269.0Q-276.0,-269.0 -240.0,-254.0Q-204.0,-239.0 -204.0,-214.0Q-160.0,-214.0 -144.0,-221.5Q-128.0,-229.0 -128.0,-244.0Q-128.0,-268.0 -157.5,-284.5Q-187.0,-301.0 -231.5,-309.5Q-276.0,-318.0 -323.0,-318.0Z" transform="translate(7037, 777)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(7025, 779)"/>
<path d="M499.0,448.0Q534.0,448.0 550.0,434.0Q566.0,420.0 566.0,395.0L566.0,146.0Q566.0,108.0 535.5,74.5Q505.0,41.0 454.5,20.5Q404.0,0.0 344.0,0.0Q283.0,0.0 232.5,21.0Q182.0,42.0 152.0,75.5Q122.0,109.0 122.0,146.0L122.0,443.0Q98.0,466.0 85.5,483.5Q73.0,501.0 73.0,523.0Q73.0,550.0 88.5,570.0Q104.0,590.0 127.0,612.0Q173.0,656.0 196.5,668.0Q220.0,680.0 230.0,680.0Q242.0,680.0 258.0,667.5Q274.0,655.0 302.0,628.0Q327.0,603.0 337.0,595.0Q347.0,587.0 355.0,587.0Q363.0,587.0 373.0,596.0Q383.0,605.0 406.0,628.0Q430.0,653.0 446.5,666.5Q463.0,680.0 475.0,680.0Q491.0,680.0 518.0,652.0L563.0,604.0Q576.0,590.0 594.0,584.0Q612.0,578.0 635.0,582.0Q627.0,538.0 607.0,519.0Q587.0,500.0 565.0,500.0Q545.0,500.0 532.5,511.0Q520.0,522.0 509.5,537.0Q499.0,552.0 488.0,563.0Q477.0,574.0 460.0,574.0Q446.0,574.0 432.5,563.5Q419.0,553.0 404.0,539.0Q382.0,520.0 367.5,510.0Q353.0,500.0 339.0,500.0Q323.0,500.0 304.5,511.5Q286.0,523.0 265.0,540.0Q237.0,564.0 226.0,572.0Q215.0,580.0 207.0,580.0Q193.0,580.0 178.0,567.0Q163.0,554.0 163.0,540.0Q163.0,535.0 166.0,529.0Q169.0,523.0 179.5,510.0Q190.0,497.0 214.0,471.0L214.0,146.0Q214.0,126.0 232.0,108.0Q250.0,90.0 279.5,78.5Q309.0,67.0 344.0,67.0Q381.0,67.0 410.0,79.0Q439.0,91.0 456.5,109.0Q474.0,127.0 474.0,146.0L474.0,228.0Q431.0,228.0 397.5,255.0Q364.0,282.0 364.0,329.0Q364.0,365.0 383.0,392.0Q402.0,419.0 432.5,433.5Q463.0,448.0 499.0,448.0ZM474.0,295.0L474.0,386.0Q458.0,386.0 443.5,373.0Q429.0,360.0 429.0,337.0Q429.0,315.0 443.5,305.0Q458.0,295.0 474.0,295.0Z" transform="translate(7029, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-300.0,1050.0 -182.0,946.0Q-156.0,924.0 -145.0,908.0Q-134.0,892.0 -134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(7726, 699)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(7682, 793)"/>
<path d="M-525.0,-317.0L-525.0,-171.0Q-525.0,-128.0 -498.5,-101.5Q-472.0,-75.0 -425.5,-62.0Q-379.0,-49.0 -321.0,-49.0Q-262.0,-49.0 -216.0,-62.0Q-170.0,-75.0 -143.5,-101.5Q-117.0,-128.0 -117.0,-171.0L-117.0,-317.0L-199.0,-317.0L-199.0,-171.0Q-199.0,-132.0 -234.5,-115.0Q-270.0,-98.0 -321.0,-98.0Q-372.0,-98.0 -407.5,-115.0Q-443.0,-132.0 -443.0,-171.0L-443.0,-185.0Q-409.0,-185.0 -392.0,-201.0Q-375.0,-217.0 -375.0,-243.0Q-375.0,-265.0 -388.5,-284.5Q-402.0,-304.0 -443.0,-317.0L-525.0,-317.0ZM-443.0,-223.0L-443.0,-281.0Q-429.0,-277.0 -422.5,-266.0Q-416.0,-255.0 -416.0,-245.0Q-416.0,-231.0 -424.0,-227.0Q-432.0,-223.0 -443.0,-223.0Z" transform="translate(8317, 777)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.0,765.0Q520.0,750.0 542.5,720.5Q565.0,691.0 565.0,647.0Q589.0,661.0 620.0,671.5Q651.0,682.0 687.0,682.0Q740.0,682.0 781.0,650.0L875.0,576.0Q913.0,547.0 913.0,501.0L913.0,0.0L821.0,0.0L821.0,501.0L722.0,580.0Q709.0,591.0 692.5,599.0Q676.0,607.0 653.0,607.0Q626.0,607.0 602.0,594.5Q578.0,582.0 555.5,564.5Q533.0,547.0 511.0,532.0Q492.0,516.0 467.0,507.5Q442.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(8315, 793)"/>
<path d="M499.0,448.0Q534.0,448.0 550.0,434.0Q566.0,420.0 566.0,395.0L566.0,146.0Q566.0,108.0 535.5,74.5Q505.0,41.0 454.5,20.5Q404.0,0.0 344.0,0.0Q283.0,0.0 232.5,21.0Q182.0,42.0 152.0,75.5Q122.0,109.0 122.0,146.0L122.0,443.0Q98.0,466.0 85.5,483.5Q73.0,501.0 73.0,523.0Q73.0,550.0 88.5,570.0Q104.0,590.0 127.0,612.0Q173.0,656.0 196.5,668.0Q220.0,680.0 230.0,680.0Q242.0,680.0 258.0,667.5Q274.0,655.0 302.0,628.0Q327.0,603.0 337.0,595.0Q347.0,587.0 355.0,587.0Q363.0,587.0 373.0,596.0Q383.0,605.0 406.0,628.0Q430.0,653.0 446.5,666.5Q463.0,680.0 475.0,680.0Q491.0,680.0 518.0,652.0L563.0,604.0Q576.0,590.0 594.0,584.0Q612.0,578.0 635.0,582.0Q627.0,538.0 607.0,519.0Q587.0,500.0 565.0,500.0Q545.0,500.0 532.5,511.0Q520.0,522.0 509.5,537.0Q499.0,552.0 488.0,563.0Q477.0,574.0 460.0,574.0Q446.0,574.0 432.5,563.5Q419.0,553.0 404.0,539.0Q382.0,520.0 367.5,510.0Q353.0,500.0 339.0,500.0Q323.0,500.0 304.5,511.5Q286.0,523.0 265.0,540.0Q237.0,564.0 226.0,572.0Q215.0,580.0 207.0,580.0Q193.0,580.0 178.0,567.0Q163.0,554.0 163.0,540.0Q163.0,535.0 166.0,529.0Q169.0,523.0 179.5,510.0Q190.0,497.0 214.0,471.0L214.0,146.0Q214.0,126.0 232.0,108.0Q250.0,90.0 279.5,78.5Q309.0,67.0 344.0,67.0Q381.0,67.0 410.0,79.0Q439.0,91.0 456.5,109.0Q474.0,127.0 474.0,146.0L474.0,228.0Q431.0,228.0 397.5,255.0Q364.0,282.0 364.0,329.0Q364.0,365.0 383.0,392.0Q402.0,419.0 432.5,433.5Q463.0,448.0 499.0,448.0ZM474.0,295.0L474.0,386.0Q458.0,386.0 443.5,373.0Q429.0,360.0 429.0,337.0Q429.0,315.0 443.5,305.0Q458.0,295.0 474.0,295.0Z" transform="translate(9320, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(9861, 777)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(9973, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(10657, 793)"/>
<path d="M121.0,532.0L226.0,447.0L226.0,-193.0Q226.0,-250.0 348.0,-250.0Q469.0,-250.0 469.0,-193.0L469.0,-49.0L561.0,-49.0L561.0,-195.0Q561.0,-317.0 348.0,-317.0Q134.0,-317.0 134.0,-195.0L134.0,424.0Q98.0,454.0 79.5,471.0Q61.0,488.0 55.0,497.5Q49.0,507.0 49.0,514.0Q49.0,524.0 58.5,538.0Q68.0,552.0 93.0,584.0Q118.0,616.0 164.0,680.0Q196.0,659.0 217.0,647.0Q238.0,635.0 257.5,631.0Q277.0,627.0 302.0,629.0Q302.0,604.0 284.5,580.5Q267.0,557.0 238.0,557.0Q225.0,557.0 207.5,564.0Q190.0,571.0 164.0,590.0L121.0,532.0Z" transform="translate(10996, 793)"/>
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM539.0,316.0L539.0,0.0L447.0,0.0L447.0,316.0Q447.0,336.0 429.5,353.5Q412.0,371.0 383.0,381.5Q354.0,392.0 318.0,392.0Q262.0,392.0 224.5,368.5Q187.0,345.0 187.0,316.0L187.0,0.0L95.0,0.0L95.0,316.0Q95.0,354.0 125.5,386.5Q156.0,419.0 206.5,439.0Q257.0,459.0 317.0,459.0Q379.0,459.0 429.5,438.5Q480.0,418.0 509.5,385.5Q539.0,353.0 539.0,316.0Z" transform="translate(11367, 793)"/>
<path d="M829.0,532.0L934.0,447.0L934.0,146.0Q934.0,114.0 906.0,80.0Q878.0,46.0 828.5,23.0Q779.0,0.0 714.0,0.0Q665.0,0.0 618.5,15.0Q572.0,30.0 540.0,62.0Q501.0,23.0 454.5,11.5Q408.0,0.0 353.0,0.0Q282.0,0.0 230.0,23.0Q178.0,46.0 150.0,80.0Q122.0,114.0 122.0,146.0L122.0,621.0Q122.0,650.0 144.0,666.0Q166.0,682.0 203.0,682.0Q262.0,682.0 294.0,644.0Q326.0,606.0 326.0,555.0Q326.0,506.0 296.5,469.0Q267.0,432.0 214.0,422.0L214.0,146.0Q214.0,124.0 233.0,106.5Q252.0,89.0 283.5,78.0Q315.0,67.0 353.0,67.0Q394.0,67.0 426.0,79.0Q458.0,91.0 476.0,109.0Q494.0,127.0 494.0,146.0L494.0,424.0Q458.0,454.0 439.5,471.0Q421.0,488.0 415.0,497.5Q409.0,507.0 409.0,514.0Q409.0,524.0 418.5,538.0Q428.0,552.0 453.0,584.0Q478.0,616.0 524.0,680.0Q556.0,659.0 577.0,647.0Q598.0,635.0 617.5,631.0Q637.0,627.0 662.0,629.0Q662.0,604.0 644.5,580.5Q627.0,557.0 598.0,557.0Q585.0,557.0 567.5,564.0Q550.0,571.0 524.0,590.0L481.0,532.0L586.0,447.0L586.0,146.0Q586.0,127.0 603.5,109.0Q621.0,91.0 650.5,79.0Q680.0,67.0 714.0,67.0Q749.0,67.0 778.0,79.0Q807.0,91.0 824.5,109.0Q842.0,127.0 842.0,146.0L842.0,424.0Q806.0,454.0 787.5,471.0Q769.0,488.0 763.0,497.5Q757.0,507.0 757.0,514.0Q757.0,524.0 766.5,538.0Q776.0,552.0 801.0,584.0Q826.0,616.0 872.0,680.0Q904.0,659.0 925.0,647.0Q946.0,635.0 965.5,631.0Q985.0,627.0 1010.0,629.0Q1010.0,604.0 992.5,580.5Q975.0,557.0 946.0,557.0Q933.0,557.0 915.5,564.0Q898.0,571.0 872.0,590.0L829.0,532.0ZM214.0,604.0L214.0,489.0Q231.0,490.0 245.0,506.5Q259.0,523.0 259.0,548.0Q259.0,569.0 247.5,584.5Q236.0,600.0 214.0,604.0Z" transform="translate(12348, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(13373, 793)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(14027, 793)"/>
<path d="M-569.0,-254.0Q-569.0,-239.0 -559.0,-229.5Q-549.0,-220.0 -530.0,-220.0L-530.0,-123.0Q-530.0,-109.0 -539.0,-103.5Q-548.0,-98.0 -569.0,-98.0L-569.0,-49.0L-542.0,-49.0Q-499.0,-49.0 -473.5,-61.0Q-448.0,-73.0 -448.0,-112.0L-448.0,-142.0L-212.0,-142.0L-212.0,-123.0Q-212.0,-108.0 -221.5,-103.0Q-231.0,-98.0 -251.0,-98.0L-251.0,-49.0L-225.0,-49.0Q-181.0,-49.0 -155.5,-61.0Q-130.0,-73.0 -130.0,-112.0L-130.0,-317.0L-212.0,-317.0Q-251.0,-279.0 -251.0,-254.0Q-251.0,-239.0 -241.0,-229.5Q-231.0,-220.0 -212.0,-220.0L-212.0,-191.0L-448.0,-191.0L-448.0,-317.0L-530.0,-317.0Q-569.0,-279.0 -569.0,-254.0Z" transform="translate(14730, 777)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(14711, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(15732, 727)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">នូវជំនឿរបស់ខ្លួនទៅលើសិទ្ធិមូលដ្ឋាននៃមនុស្ស</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: uni1793=0+652|uni17BC=0@-125,-16+0|uni179C=2+323|uni1787=3+655|uni17C6=3@29,-24+0|uni17C1=5+339|uni1793=5+652|uni17BF.right1=5+358|uni179A=7+377|uni1794=8+654|uni179F=9+1001|uni17CB=9@20,-66+0|uni1781=11+664|uni17D2179B=11@-2,-16+0|uni17BD=11@-124,-310+0|uni1793=15+652|uni17C1=16+339|uni179117C5=16+1045|uni17C1=18+339|uni179B=18+1001|uni17B8=18@42,-94+0|uni179F=20+1001|uni17B7=20@20,-94+0|uni1791=22+587|uni17D21792=22@-3,-16+0|uni17B7=22@42,-94+0|uni1798=26+654|uni17BC=26@-116,-16+0|uni179B=28+1001|uni178A17B6=29+1006|uni17D2178B=29@-330,-16+0|uni1793=33+652|uni17C3=34+339|uni1793=34+652|uni1798=36+654|uni1793=37+652|uni17BB=37@-125,-16+0|uni179F=39+1001|uni17D2179F=39+389</pre>



<pre>Got     : uni1793=0+652|uni17BC=0@-125,-16+0|uni179C=2+323|uni1787=3+655|uni17C6=3@29,6+0|uni17C1=5+339|uni1793=5+652|uni17BF.right1=5+358|uni179A=7+377|uni1794=8+654|uni179F=9+1001|uni17CB=9@20,-66+0|uni1781=11+664|uni17D2179B=11@-2,-16+0|uni17BD=11@-124,-310+0|uni1793=15+652|uni17C1=16+339|uni179117C5=16+1045|uni17C1=18+339|uni179B=18+1001|uni17B8=18@42,-94+0|uni179F=20+1001|uni17B7=20@20,-94+0|uni1791=22+587|uni17D21792=22@-3,-16+0|uni17B7=22@42,-94+0|uni1798=26+654|uni17BC=26@-116,-16+0|uni179B=28+1001|uni178A17B6=29+1006|uni17D2178B=29@-330,-16+0|uni1793=33+652|uni17C3=34+339|uni1793=34+652|uni1798=36+654|uni1793=37+652|uni17BB=37@-125,-16+0|uni179F=39+1001|uni17D2179F=39+389</pre>



<pre>                                                                                      ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 17639 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(0, 793)"/>
<path d="M-222.0,-273.0Q-263.0,-273.0 -293.5,-255.0Q-324.0,-237.0 -324.0,-203.0Q-324.0,-188.0 -319.0,-169.5Q-314.0,-151.0 -310.0,-138.0L-307.0,-130.0Q-319.0,-130.0 -327.5,-121.0Q-336.0,-112.0 -336.0,-96.0Q-336.0,-76.0 -320.5,-62.5Q-305.0,-49.0 -279.0,-49.0Q-255.0,-49.0 -241.0,-61.5Q-227.0,-74.0 -227.0,-100.0Q-227.0,-110.0 -230.0,-123.0Q-233.0,-136.0 -241.0,-160.0Q-248.0,-182.0 -242.5,-195.5Q-237.0,-209.0 -215.0,-209.0Q-188.0,-209.0 -172.5,-186.0Q-157.0,-163.0 -138.0,-117.0Q-121.0,-76.0 -110.5,-62.5Q-100.0,-49.0 -86.0,-49.0Q-75.0,-49.0 -64.0,-57.0Q-53.0,-65.0 -53.0,-85.0Q-53.0,-100.0 -60.5,-130.5Q-68.0,-161.0 -87.0,-194.0Q-106.0,-227.0 -139.0,-250.0Q-172.0,-273.0 -222.0,-273.0Z" transform="translate(527, 777)"/>
<path d="M123.0,530.0L226.0,447.0L226.0,0.0L134.0,0.0Q87.0,34.0 63.0,60.5Q39.0,87.0 31.0,108.0Q23.0,129.0 23.0,146.0Q23.0,165.0 32.0,187.5Q41.0,210.0 65.5,226.5Q90.0,243.0 134.0,244.0L134.0,424.0Q98.0,454.0 79.5,470.5Q61.0,487.0 55.0,495.5Q49.0,504.0 49.0,511.0Q49.0,521.0 58.5,535.5Q68.0,550.0 93.0,582.5Q118.0,615.0 164.0,679.0Q184.0,661.0 196.5,653.0Q209.0,645.0 222.0,645.0Q236.0,645.0 248.0,652.5Q260.0,660.0 260.0,676.0Q260.0,694.0 241.5,708.0Q223.0,722.0 195.0,722.0Q195.0,753.0 212.0,766.0Q229.0,779.0 244.0,779.0Q260.0,779.0 277.5,767.0Q295.0,755.0 307.0,733.0Q319.0,711.0 319.0,681.0Q319.0,653.0 306.5,627.5Q294.0,602.0 271.5,586.0Q249.0,570.0 220.0,570.0Q203.0,570.0 189.5,576.0Q176.0,582.0 167.0,589.0L123.0,530.0ZM134.0,84.0L134.0,176.0Q109.0,175.0 99.5,166.0Q90.0,157.0 90.0,143.0Q90.0,110.0 134.0,84.0Z" transform="translate(652, 793)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.5,765.0Q521.0,750.0 543.0,720.5Q565.0,691.0 565.0,646.0Q565.0,606.0 546.5,572.5Q528.0,539.0 493.5,519.0Q459.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(975, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(1659, 799)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(1630, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(1969, 793)"/>
<path d="M166.0,1122.0L166.0,991.0Q215.0,950.0 236.5,904.0Q258.0,858.0 258.0,810.0L258.0,-195.0Q258.0,-317.0 38.0,-317.0Q-182.0,-317.0 -182.0,-195.0L-182.0,-49.0L-90.0,-49.0L-90.0,-185.0Q-90.0,-211.0 -58.0,-230.5Q-26.0,-250.0 38.0,-250.0Q103.0,-250.0 134.5,-230.5Q166.0,-211.0 166.0,-185.0L166.0,810.0Q166.0,903.0 68.0,903.0L-115.0,903.0Q-156.0,903.0 -171.0,927.0Q-186.0,951.0 -186.0,982.0Q-186.0,1029.0 -156.5,1063.5Q-127.0,1098.0 -59.0,1098.0Q-33.0,1098.0 -9.0,1091.0L-9.0,1147.0L58.0,1147.0L58.0,1061.0Q76.0,1051.0 98.0,1037.0L98.0,1122.0L166.0,1122.0ZM-113.0,966.0L76.0,966.0Q40.0,997.0 6.0,1015.5Q-28.0,1034.0 -55.0,1034.0Q-80.0,1034.0 -96.5,1017.0Q-113.0,1000.0 -113.0,966.0Z" transform="translate(2621, 793)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(2979, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(3356, 793)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4010, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(5031, 727)"/>
<path d="M188.0,355.0Q110.0,355.0 110.0,407.0L110.0,536.0Q110.0,575.0 141.5,608.5Q173.0,642.0 225.5,662.0Q278.0,682.0 341.0,682.0Q407.0,682.0 459.5,661.5Q512.0,641.0 543.0,607.5Q574.0,574.0 574.0,536.0L574.0,463.0Q574.0,379.0 388.0,283.0L202.0,187.0L202.0,146.0Q202.0,125.0 221.0,107.0Q240.0,89.0 271.5,78.0Q303.0,67.0 342.0,67.0Q382.0,67.0 413.5,78.5Q445.0,90.0 463.5,108.0Q482.0,126.0 482.0,146.0L482.0,243.0L574.0,292.0L574.0,146.0Q574.0,107.0 542.5,74.0Q511.0,41.0 458.5,20.5Q406.0,0.0 342.0,0.0Q277.0,0.0 224.5,20.5Q172.0,41.0 141.0,74.5Q110.0,108.0 110.0,146.0L110.0,219.0L342.0,338.0Q482.0,409.0 482.0,463.0L482.0,536.0Q482.0,568.0 441.0,591.5Q400.0,615.0 341.0,615.0Q281.0,615.0 241.5,590.5Q202.0,566.0 202.0,536.0L202.0,509.0Q238.0,509.0 261.0,491.5Q284.0,474.0 284.0,436.0Q284.0,396.0 258.0,375.5Q232.0,355.0 188.0,355.0ZM202.0,470.0L202.0,396.0Q217.0,396.0 226.0,406.5Q235.0,417.0 235.0,435.0Q235.0,470.0 202.0,470.0Z" transform="translate(5011, 793)"/>
<path d="M-536.0,-170.0Q-536.0,-120.0 -502.5,-84.5Q-469.0,-49.0 -408.0,-49.0Q-357.0,-49.0 -330.0,-75.5Q-303.0,-102.0 -279.0,-148.0Q-261.0,-182.0 -248.5,-201.0Q-236.0,-220.0 -222.0,-220.0Q-188.0,-220.0 -182.0,-158.0Q-179.0,-126.0 -185.5,-101.0Q-192.0,-76.0 -200.0,-57.0Q-163.0,-38.0 -135.5,-42.5Q-108.0,-47.0 -108.0,-93.0Q-108.0,-106.0 -112.0,-135.0Q-116.0,-164.0 -127.5,-196.0Q-139.0,-228.0 -161.5,-250.5Q-184.0,-273.0 -221.0,-273.0Q-258.0,-273.0 -282.5,-249.0Q-307.0,-225.0 -330.0,-179.0Q-352.0,-134.0 -368.0,-116.0Q-384.0,-98.0 -406.0,-98.0Q-432.0,-98.0 -447.5,-117.5Q-463.0,-137.0 -463.0,-169.0Q-463.0,-193.0 -454.0,-208.0Q-445.0,-223.0 -431.0,-223.0Q-420.0,-223.0 -412.5,-214.5Q-405.0,-206.0 -405.0,-193.0Q-374.0,-190.0 -362.5,-200.0Q-351.0,-210.0 -351.0,-223.0Q-351.0,-242.0 -372.5,-260.0Q-394.0,-278.0 -432.0,-278.0Q-479.0,-278.0 -507.5,-247.5Q-536.0,-217.0 -536.0,-170.0Z" transform="translate(5673, 777)"/>
<path d="M-361.0,-221.0Q-361.0,-204.0 -353.5,-183.5Q-346.0,-163.0 -333.0,-138.0L-329.0,-130.0Q-349.0,-130.0 -358.5,-119.5Q-368.0,-109.0 -368.0,-93.0Q-368.0,-73.0 -353.5,-61.0Q-339.0,-49.0 -308.0,-49.0Q-281.0,-49.0 -262.0,-59.5Q-243.0,-70.0 -243.0,-97.0Q-243.0,-110.0 -249.5,-126.0Q-256.0,-142.0 -264.0,-160.0Q-273.0,-179.0 -278.5,-199.0Q-284.0,-219.0 -269.0,-219.0Q-257.0,-219.0 -238.0,-209.0Q-219.0,-199.0 -190.0,-175.0Q-181.0,-199.0 -171.5,-209.0Q-162.0,-219.0 -150.0,-219.0Q-130.0,-219.0 -116.5,-197.5Q-103.0,-176.0 -99.0,-143.0Q-96.0,-117.0 -99.0,-94.0Q-102.0,-71.0 -109.0,-49.0Q-70.0,-37.0 -46.5,-44.5Q-23.0,-52.0 -23.0,-99.0Q-23.0,-125.0 -31.0,-155.0Q-39.0,-185.0 -54.0,-212.0Q-69.0,-239.0 -90.5,-256.5Q-112.0,-274.0 -139.0,-274.0Q-161.0,-274.0 -177.0,-263.5Q-193.0,-253.0 -204.0,-240.0Q-226.0,-253.0 -248.5,-263.5Q-271.0,-274.0 -297.0,-274.0Q-325.0,-274.0 -343.0,-260.5Q-361.0,-247.0 -361.0,-221.0Z" transform="translate(5551, 483)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(5675, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(6327, 793)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q356.0,682.0 410.0,659.5Q464.0,637.0 491.0,601.0Q551.0,647.0 588.0,664.5Q625.0,682.0 654.0,682.0Q698.0,682.0 739.0,650.0L816.0,589.0L816.0,734.0Q816.0,759.0 804.0,783.0Q792.0,807.0 767.0,819.0Q767.0,844.0 785.0,861.0Q803.0,878.0 833.0,878.0Q874.0,878.0 886.0,848.5Q898.0,819.0 898.0,770.0L898.0,604.0Q898.0,587.0 893.0,561.0Q888.0,535.0 871.0,507.0Q871.0,504.0 871.0,501.0L871.0,0.0L779.0,0.0L779.0,507.0L677.0,588.0Q667.0,596.0 657.0,601.5Q647.0,607.0 639.0,607.0Q629.0,607.0 608.5,596.0Q588.0,585.0 563.0,567.5Q538.0,550.0 514.0,533.0L514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(6666, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(7711, 793)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(8050, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(9093, 699)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(9051, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-300.0,1050.0 -182.0,946.0Q-156.0,924.0 -145.0,908.0Q-134.0,892.0 -134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(10072, 699)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q353.0,682.0 405.0,661.5Q457.0,641.0 485.5,607.5Q514.0,574.0 514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(10052, 793)"/>
<path d="M-524.0,-222.0Q-524.0,-207.0 -517.0,-192.0Q-510.0,-177.0 -492.0,-174.0Q-457.0,-168.0 -419.5,-157.0Q-382.0,-146.0 -349.5,-132.0Q-317.0,-118.0 -296.5,-102.5Q-276.0,-87.0 -276.0,-72.0Q-276.0,-64.0 -284.0,-56.0Q-279.0,-48.0 -270.0,-42.0Q-261.0,-36.0 -246.0,-36.0Q-229.0,-36.0 -219.5,-44.5Q-210.0,-53.0 -210.0,-66.0Q-210.0,-69.0 -211.0,-72.0Q-194.0,-53.0 -170.0,-53.0Q-141.0,-53.0 -132.0,-74.0Q-123.0,-95.0 -123.0,-116.0Q-123.0,-169.0 -157.0,-204.5Q-191.0,-240.0 -244.0,-240.0Q-264.0,-240.0 -279.0,-235.0Q-294.0,-230.0 -305.0,-223.0Q-318.0,-264.0 -346.5,-287.5Q-375.0,-311.0 -420.0,-311.0Q-456.0,-311.0 -479.0,-297.0Q-502.0,-283.0 -513.0,-262.0Q-524.0,-241.0 -524.0,-222.0ZM-197.0,-122.0Q-197.0,-107.0 -202.0,-97.0Q-207.0,-87.0 -214.0,-84.0Q-223.0,-103.0 -245.5,-122.0Q-268.0,-141.0 -294.0,-158.0Q-289.0,-173.0 -277.5,-182.5Q-266.0,-192.0 -250.0,-192.0Q-231.0,-192.0 -219.5,-180.0Q-208.0,-168.0 -202.5,-151.5Q-197.0,-135.0 -197.0,-122.0ZM-450.0,-221.0Q-450.0,-233.0 -440.0,-243.5Q-430.0,-254.0 -411.0,-254.0Q-385.0,-254.0 -366.5,-233.5Q-348.0,-213.0 -348.0,-186.0Q-374.0,-197.0 -400.5,-206.0Q-427.0,-215.0 -450.0,-221.0Z" transform="translate(10636, 777)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-300.0,1050.0 -182.0,946.0Q-156.0,924.0 -145.0,908.0Q-134.0,892.0 -134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(10681, 699)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(10639, 793)"/>
<path d="M-222.0,-273.0Q-263.0,-273.0 -293.5,-255.0Q-324.0,-237.0 -324.0,-203.0Q-324.0,-188.0 -319.0,-169.5Q-314.0,-151.0 -310.0,-138.0L-307.0,-130.0Q-319.0,-130.0 -327.5,-121.0Q-336.0,-112.0 -336.0,-96.0Q-336.0,-76.0 -320.5,-62.5Q-305.0,-49.0 -279.0,-49.0Q-255.0,-49.0 -241.0,-61.5Q-227.0,-74.0 -227.0,-100.0Q-227.0,-110.0 -230.0,-123.0Q-233.0,-136.0 -241.0,-160.0Q-248.0,-182.0 -242.5,-195.5Q-237.0,-209.0 -215.0,-209.0Q-188.0,-209.0 -172.5,-186.0Q-157.0,-163.0 -138.0,-117.0Q-121.0,-76.0 -110.5,-62.5Q-100.0,-49.0 -86.0,-49.0Q-75.0,-49.0 -64.0,-57.0Q-53.0,-65.0 -53.0,-85.0Q-53.0,-100.0 -60.5,-130.5Q-68.0,-161.0 -87.0,-194.0Q-106.0,-227.0 -139.0,-250.0Q-172.0,-273.0 -222.0,-273.0Z" transform="translate(11177, 777)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(11293, 793)"/>
<path d="M914.0,501.0L914.0,0.0L822.0,0.0L822.0,501.0L723.0,580.0Q710.0,591.0 699.0,599.0Q688.0,607.0 680.0,607.0Q672.0,607.0 650.5,596.5Q629.0,586.0 600.0,570.5Q571.0,555.0 539.5,537.5Q508.0,520.0 480.0,506.0Q451.0,487.0 410.5,476.5Q370.0,466.0 318.0,466.0Q258.0,466.0 208.5,482.0Q159.0,498.0 129.5,528.5Q100.0,559.0 100.0,603.0Q100.0,643.0 127.5,674.0Q155.0,705.0 210.0,705.0Q261.0,705.0 288.5,678.0Q316.0,651.0 316.0,610.0Q316.0,589.0 308.0,573.0Q300.0,557.0 280.0,535.0Q301.0,532.0 324.0,532.0Q392.0,532.0 432.0,560.0Q472.0,588.0 472.0,633.0Q472.0,660.0 455.5,679.5Q439.0,699.0 406.0,694.0Q393.0,738.0 415.5,760.5Q438.0,783.0 470.0,783.0Q500.0,783.0 521.0,765.0Q542.0,747.0 553.0,717.5Q564.0,688.0 564.0,654.0Q564.0,645.0 563.0,635.0Q600.0,655.0 636.5,668.5Q673.0,682.0 700.0,682.0Q741.0,682.0 782.0,650.0L876.0,576.0Q914.0,547.0 914.0,501.0ZM245.0,608.0Q245.0,619.0 235.5,629.0Q226.0,639.0 209.0,639.0Q193.0,639.0 182.0,630.0Q171.0,621.0 171.0,606.0Q171.0,579.0 207.0,558.0Q222.0,566.0 233.5,580.5Q245.0,595.0 245.0,608.0ZM100.0,447.0L192.0,413.0L192.0,91.0L332.0,207.0L472.0,91.0L472.0,437.0L564.0,437.0L564.0,0.0L472.0,0.0L332.0,115.0L192.0,0.0L100.0,0.0L100.0,447.0Z" transform="translate(12294, 793)"/>
<path d="M-205.0,-44.0L-123.0,-44.0L-123.0,-74.0L-70.0,-74.0L-70.0,-124.0L-123.0,-124.0L-123.0,-250.0Q-123.0,-271.0 -135.0,-279.5Q-147.0,-288.0 -165.5,-290.0Q-184.0,-292.0 -205.0,-292.0L-322.0,-240.0L-439.0,-292.0Q-473.0,-292.0 -497.0,-286.5Q-521.0,-281.0 -521.0,-250.0L-521.0,-121.0Q-521.0,-95.0 -505.0,-84.5Q-489.0,-74.0 -465.0,-74.0L-205.0,-74.0L-205.0,-44.0ZM-205.0,-234.0L-205.0,-124.0L-439.0,-124.0L-439.0,-238.0L-322.0,-188.0L-205.0,-234.0Z" transform="translate(12970, 777)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(13300, 793)"/>
<path d="M126.0,850.0Q122.0,834.0 132.0,821.0Q142.0,808.0 161.0,808.0Q178.0,808.0 188.5,821.5Q199.0,835.0 199.0,858.0Q199.0,891.0 179.5,903.5Q160.0,916.0 138.0,916.0L116.0,916.0Q79.0,916.0 70.0,926.5Q61.0,937.0 53.0,960.0Q47.0,979.0 37.5,989.0Q28.0,999.0 4.0,999.0Q4.0,1024.0 19.0,1039.0Q34.0,1054.0 62.0,1054.0Q91.0,1054.0 108.5,1035.0Q126.0,1016.0 126.0,975.0L150.0,975.0Q218.0,975.0 245.0,944.5Q272.0,914.0 272.0,872.0Q272.0,844.0 260.0,818.0Q248.0,792.0 222.0,776.0Q196.0,760.0 152.0,760.0Q111.0,760.0 82.0,776.5Q53.0,793.0 53.0,823.0Q53.0,843.0 65.5,852.5Q78.0,862.0 95.0,861.5Q112.0,861.0 126.0,850.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(13952, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(14291, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(14943, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(15597, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(16124, 777)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(16249, 793)"/>
<path d="M-173.0,-191.0L-173.0,-178.0Q-197.0,-177.0 -210.5,-159.5Q-224.0,-142.0 -224.0,-120.0Q-224.0,-89.0 -202.5,-69.0Q-181.0,-49.0 -141.0,-49.0Q-81.0,-49.0 -81.0,-98.0L-81.0,-185.0Q-81.0,-250.0 47.0,-250.0Q175.0,-250.0 175.0,-185.0L175.0,0.0L96.0,0.0L96.0,67.0L175.0,67.0L175.0,424.0Q139.0,454.0 120.5,471.0Q102.0,488.0 96.0,497.5Q90.0,507.0 90.0,514.0Q90.0,524.0 99.5,538.0Q109.0,552.0 134.0,584.0Q159.0,616.0 205.0,680.0Q237.0,659.0 258.0,647.0Q279.0,635.0 298.5,631.0Q318.0,627.0 343.0,629.0Q343.0,604.0 325.5,580.5Q308.0,557.0 279.0,557.0Q266.0,557.0 248.5,564.0Q231.0,571.0 205.0,590.0L162.0,532.0L267.0,447.0L267.0,67.0L340.0,67.0L340.0,0.0L267.0,0.0L267.0,-185.0Q267.0,-246.0 212.0,-281.5Q157.0,-317.0 47.0,-317.0Q-60.0,-317.0 -115.0,-283.5Q-170.0,-250.0 -173.0,-191.0L-173.0,-191.0Z" transform="translate(17250, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 17639 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(0, 793)"/>
<path d="M-222.0,-273.0Q-263.0,-273.0 -293.5,-255.0Q-324.0,-237.0 -324.0,-203.0Q-324.0,-188.0 -319.0,-169.5Q-314.0,-151.0 -310.0,-138.0L-307.0,-130.0Q-319.0,-130.0 -327.5,-121.0Q-336.0,-112.0 -336.0,-96.0Q-336.0,-76.0 -320.5,-62.5Q-305.0,-49.0 -279.0,-49.0Q-255.0,-49.0 -241.0,-61.5Q-227.0,-74.0 -227.0,-100.0Q-227.0,-110.0 -230.0,-123.0Q-233.0,-136.0 -241.0,-160.0Q-248.0,-182.0 -242.5,-195.5Q-237.0,-209.0 -215.0,-209.0Q-188.0,-209.0 -172.5,-186.0Q-157.0,-163.0 -138.0,-117.0Q-121.0,-76.0 -110.5,-62.5Q-100.0,-49.0 -86.0,-49.0Q-75.0,-49.0 -64.0,-57.0Q-53.0,-65.0 -53.0,-85.0Q-53.0,-100.0 -60.5,-130.5Q-68.0,-161.0 -87.0,-194.0Q-106.0,-227.0 -139.0,-250.0Q-172.0,-273.0 -222.0,-273.0Z" transform="translate(527, 777)"/>
<path d="M123.0,530.0L226.0,447.0L226.0,0.0L134.0,0.0Q87.0,34.0 63.0,60.5Q39.0,87.0 31.0,108.0Q23.0,129.0 23.0,146.0Q23.0,165.0 32.0,187.5Q41.0,210.0 65.5,226.5Q90.0,243.0 134.0,244.0L134.0,424.0Q98.0,454.0 79.5,470.5Q61.0,487.0 55.0,495.5Q49.0,504.0 49.0,511.0Q49.0,521.0 58.5,535.5Q68.0,550.0 93.0,582.5Q118.0,615.0 164.0,679.0Q184.0,661.0 196.5,653.0Q209.0,645.0 222.0,645.0Q236.0,645.0 248.0,652.5Q260.0,660.0 260.0,676.0Q260.0,694.0 241.5,708.0Q223.0,722.0 195.0,722.0Q195.0,753.0 212.0,766.0Q229.0,779.0 244.0,779.0Q260.0,779.0 277.5,767.0Q295.0,755.0 307.0,733.0Q319.0,711.0 319.0,681.0Q319.0,653.0 306.5,627.5Q294.0,602.0 271.5,586.0Q249.0,570.0 220.0,570.0Q203.0,570.0 189.5,576.0Q176.0,582.0 167.0,589.0L123.0,530.0ZM134.0,84.0L134.0,176.0Q109.0,175.0 99.5,166.0Q90.0,157.0 90.0,143.0Q90.0,110.0 134.0,84.0Z" transform="translate(652, 793)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.5,765.0Q521.0,750.0 543.0,720.5Q565.0,691.0 565.0,646.0Q565.0,606.0 546.5,572.5Q528.0,539.0 493.5,519.0Q459.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(975, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(1659, 769)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(1630, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(1969, 793)"/>
<path d="M166.0,1122.0L166.0,991.0Q215.0,950.0 236.5,904.0Q258.0,858.0 258.0,810.0L258.0,-195.0Q258.0,-317.0 38.0,-317.0Q-182.0,-317.0 -182.0,-195.0L-182.0,-49.0L-90.0,-49.0L-90.0,-185.0Q-90.0,-211.0 -58.0,-230.5Q-26.0,-250.0 38.0,-250.0Q103.0,-250.0 134.5,-230.5Q166.0,-211.0 166.0,-185.0L166.0,810.0Q166.0,903.0 68.0,903.0L-115.0,903.0Q-156.0,903.0 -171.0,927.0Q-186.0,951.0 -186.0,982.0Q-186.0,1029.0 -156.5,1063.5Q-127.0,1098.0 -59.0,1098.0Q-33.0,1098.0 -9.0,1091.0L-9.0,1147.0L58.0,1147.0L58.0,1061.0Q76.0,1051.0 98.0,1037.0L98.0,1122.0L166.0,1122.0ZM-113.0,966.0L76.0,966.0Q40.0,997.0 6.0,1015.5Q-28.0,1034.0 -55.0,1034.0Q-80.0,1034.0 -96.5,1017.0Q-113.0,1000.0 -113.0,966.0Z" transform="translate(2621, 793)"/>
<path d="M178.0,532.0L283.0,447.0L283.0,0.0L191.0,0.0Q144.0,34.0 120.0,60.5Q96.0,87.0 88.0,108.0Q80.0,129.0 80.0,146.0Q80.0,165.0 89.0,187.5Q98.0,210.0 122.5,226.5Q147.0,243.0 191.0,244.0L191.0,424.0Q155.0,454.0 136.5,471.0Q118.0,488.0 112.0,497.5Q106.0,507.0 106.0,514.0Q106.0,524.0 115.5,538.0Q125.0,552.0 150.0,584.0Q175.0,616.0 221.0,680.0Q253.0,659.0 274.0,647.0Q295.0,635.0 314.5,631.0Q334.0,627.0 359.0,629.0Q359.0,604.0 341.5,580.5Q324.0,557.0 295.0,557.0Q282.0,557.0 264.5,564.0Q247.0,571.0 221.0,590.0L178.0,532.0ZM191.0,84.0L191.0,176.0Q166.0,175.0 156.5,166.0Q147.0,157.0 147.0,143.0Q147.0,110.0 191.0,84.0Z" transform="translate(2979, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(3356, 793)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4010, 793)"/>
<path d="M-390.0,1030.0L-317.0,1030.0L-317.0,860.0Q-317.0,838.0 -324.5,825.5Q-332.0,813.0 -353.0,806.0Q-374.0,813.0 -382.0,825.5Q-390.0,838.0 -390.0,860.0L-390.0,1030.0Z" transform="translate(5031, 727)"/>
<path d="M188.0,355.0Q110.0,355.0 110.0,407.0L110.0,536.0Q110.0,575.0 141.5,608.5Q173.0,642.0 225.5,662.0Q278.0,682.0 341.0,682.0Q407.0,682.0 459.5,661.5Q512.0,641.0 543.0,607.5Q574.0,574.0 574.0,536.0L574.0,463.0Q574.0,379.0 388.0,283.0L202.0,187.0L202.0,146.0Q202.0,125.0 221.0,107.0Q240.0,89.0 271.5,78.0Q303.0,67.0 342.0,67.0Q382.0,67.0 413.5,78.5Q445.0,90.0 463.5,108.0Q482.0,126.0 482.0,146.0L482.0,243.0L574.0,292.0L574.0,146.0Q574.0,107.0 542.5,74.0Q511.0,41.0 458.5,20.5Q406.0,0.0 342.0,0.0Q277.0,0.0 224.5,20.5Q172.0,41.0 141.0,74.5Q110.0,108.0 110.0,146.0L110.0,219.0L342.0,338.0Q482.0,409.0 482.0,463.0L482.0,536.0Q482.0,568.0 441.0,591.5Q400.0,615.0 341.0,615.0Q281.0,615.0 241.5,590.5Q202.0,566.0 202.0,536.0L202.0,509.0Q238.0,509.0 261.0,491.5Q284.0,474.0 284.0,436.0Q284.0,396.0 258.0,375.5Q232.0,355.0 188.0,355.0ZM202.0,470.0L202.0,396.0Q217.0,396.0 226.0,406.5Q235.0,417.0 235.0,435.0Q235.0,470.0 202.0,470.0Z" transform="translate(5011, 793)"/>
<path d="M-536.0,-170.0Q-536.0,-120.0 -502.5,-84.5Q-469.0,-49.0 -408.0,-49.0Q-357.0,-49.0 -330.0,-75.5Q-303.0,-102.0 -279.0,-148.0Q-261.0,-182.0 -248.5,-201.0Q-236.0,-220.0 -222.0,-220.0Q-188.0,-220.0 -182.0,-158.0Q-179.0,-126.0 -185.5,-101.0Q-192.0,-76.0 -200.0,-57.0Q-163.0,-38.0 -135.5,-42.5Q-108.0,-47.0 -108.0,-93.0Q-108.0,-106.0 -112.0,-135.0Q-116.0,-164.0 -127.5,-196.0Q-139.0,-228.0 -161.5,-250.5Q-184.0,-273.0 -221.0,-273.0Q-258.0,-273.0 -282.5,-249.0Q-307.0,-225.0 -330.0,-179.0Q-352.0,-134.0 -368.0,-116.0Q-384.0,-98.0 -406.0,-98.0Q-432.0,-98.0 -447.5,-117.5Q-463.0,-137.0 -463.0,-169.0Q-463.0,-193.0 -454.0,-208.0Q-445.0,-223.0 -431.0,-223.0Q-420.0,-223.0 -412.5,-214.5Q-405.0,-206.0 -405.0,-193.0Q-374.0,-190.0 -362.5,-200.0Q-351.0,-210.0 -351.0,-223.0Q-351.0,-242.0 -372.5,-260.0Q-394.0,-278.0 -432.0,-278.0Q-479.0,-278.0 -507.5,-247.5Q-536.0,-217.0 -536.0,-170.0Z" transform="translate(5673, 777)"/>
<path d="M-361.0,-221.0Q-361.0,-204.0 -353.5,-183.5Q-346.0,-163.0 -333.0,-138.0L-329.0,-130.0Q-349.0,-130.0 -358.5,-119.5Q-368.0,-109.0 -368.0,-93.0Q-368.0,-73.0 -353.5,-61.0Q-339.0,-49.0 -308.0,-49.0Q-281.0,-49.0 -262.0,-59.5Q-243.0,-70.0 -243.0,-97.0Q-243.0,-110.0 -249.5,-126.0Q-256.0,-142.0 -264.0,-160.0Q-273.0,-179.0 -278.5,-199.0Q-284.0,-219.0 -269.0,-219.0Q-257.0,-219.0 -238.0,-209.0Q-219.0,-199.0 -190.0,-175.0Q-181.0,-199.0 -171.5,-209.0Q-162.0,-219.0 -150.0,-219.0Q-130.0,-219.0 -116.5,-197.5Q-103.0,-176.0 -99.0,-143.0Q-96.0,-117.0 -99.0,-94.0Q-102.0,-71.0 -109.0,-49.0Q-70.0,-37.0 -46.5,-44.5Q-23.0,-52.0 -23.0,-99.0Q-23.0,-125.0 -31.0,-155.0Q-39.0,-185.0 -54.0,-212.0Q-69.0,-239.0 -90.5,-256.5Q-112.0,-274.0 -139.0,-274.0Q-161.0,-274.0 -177.0,-263.5Q-193.0,-253.0 -204.0,-240.0Q-226.0,-253.0 -248.5,-263.5Q-271.0,-274.0 -297.0,-274.0Q-325.0,-274.0 -343.0,-260.5Q-361.0,-247.0 -361.0,-221.0Z" transform="translate(5551, 483)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(5675, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(6327, 793)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q356.0,682.0 410.0,659.5Q464.0,637.0 491.0,601.0Q551.0,647.0 588.0,664.5Q625.0,682.0 654.0,682.0Q698.0,682.0 739.0,650.0L816.0,589.0L816.0,734.0Q816.0,759.0 804.0,783.0Q792.0,807.0 767.0,819.0Q767.0,844.0 785.0,861.0Q803.0,878.0 833.0,878.0Q874.0,878.0 886.0,848.5Q898.0,819.0 898.0,770.0L898.0,604.0Q898.0,587.0 893.0,561.0Q888.0,535.0 871.0,507.0Q871.0,504.0 871.0,501.0L871.0,0.0L779.0,0.0L779.0,507.0L677.0,588.0Q667.0,596.0 657.0,601.5Q647.0,607.0 639.0,607.0Q629.0,607.0 608.5,596.0Q588.0,585.0 563.0,567.5Q538.0,550.0 514.0,533.0L514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(6666, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(7711, 793)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(8050, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(9093, 699)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(9051, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-300.0,1050.0 -182.0,946.0Q-156.0,924.0 -145.0,908.0Q-134.0,892.0 -134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(10072, 699)"/>
<path d="M119.0,180.0L206.0,180.0L206.0,145.0Q206.0,108.0 223.0,87.5Q240.0,67.0 265.0,67.0Q291.0,67.0 307.0,87.5Q323.0,108.0 323.0,145.0L323.0,221.0L282.0,221.0Q211.0,221.0 159.0,247.0Q107.0,273.0 78.5,318.5Q50.0,364.0 50.0,421.0L50.0,536.0Q50.0,575.0 81.5,608.5Q113.0,642.0 165.5,662.0Q218.0,682.0 282.0,682.0Q353.0,682.0 405.0,661.5Q457.0,641.0 485.5,607.5Q514.0,574.0 514.0,533.0L514.0,485.0Q514.0,444.0 492.0,428.5Q470.0,413.0 429.0,413.0Q383.0,413.0 364.0,430.5Q345.0,448.0 345.0,479.0Q345.0,517.0 367.0,531.5Q389.0,546.0 422.0,546.0Q422.0,576.0 381.5,595.5Q341.0,615.0 285.0,615.0Q219.0,615.0 180.5,590.5Q142.0,566.0 142.0,536.0L142.0,421.0Q142.0,360.0 180.5,324.0Q219.0,288.0 282.0,288.0L323.0,288.0Q329.0,304.0 343.5,322.0Q358.0,340.0 383.0,353.0Q408.0,366.0 444.0,366.0Q517.0,366.0 517.0,306.0Q517.0,274.0 493.0,250.5Q469.0,227.0 415.0,221.0L415.0,147.0Q415.0,0.0 265.0,0.0Q200.0,0.0 159.5,33.0Q119.0,66.0 119.0,138.0L119.0,180.0ZM422.0,451.0L422.0,510.0Q407.0,510.0 400.5,501.5Q394.0,493.0 394.0,481.0Q394.0,469.0 400.5,460.0Q407.0,451.0 422.0,451.0ZM451.0,319.0Q439.0,319.0 429.5,310.0Q420.0,301.0 415.0,288.0Q440.0,288.0 451.5,295.5Q463.0,303.0 463.0,310.0Q463.0,319.0 451.0,319.0Z" transform="translate(10052, 793)"/>
<path d="M-524.0,-222.0Q-524.0,-207.0 -517.0,-192.0Q-510.0,-177.0 -492.0,-174.0Q-457.0,-168.0 -419.5,-157.0Q-382.0,-146.0 -349.5,-132.0Q-317.0,-118.0 -296.5,-102.5Q-276.0,-87.0 -276.0,-72.0Q-276.0,-64.0 -284.0,-56.0Q-279.0,-48.0 -270.0,-42.0Q-261.0,-36.0 -246.0,-36.0Q-229.0,-36.0 -219.5,-44.5Q-210.0,-53.0 -210.0,-66.0Q-210.0,-69.0 -211.0,-72.0Q-194.0,-53.0 -170.0,-53.0Q-141.0,-53.0 -132.0,-74.0Q-123.0,-95.0 -123.0,-116.0Q-123.0,-169.0 -157.0,-204.5Q-191.0,-240.0 -244.0,-240.0Q-264.0,-240.0 -279.0,-235.0Q-294.0,-230.0 -305.0,-223.0Q-318.0,-264.0 -346.5,-287.5Q-375.0,-311.0 -420.0,-311.0Q-456.0,-311.0 -479.0,-297.0Q-502.0,-283.0 -513.0,-262.0Q-524.0,-241.0 -524.0,-222.0ZM-197.0,-122.0Q-197.0,-107.0 -202.0,-97.0Q-207.0,-87.0 -214.0,-84.0Q-223.0,-103.0 -245.5,-122.0Q-268.0,-141.0 -294.0,-158.0Q-289.0,-173.0 -277.5,-182.5Q-266.0,-192.0 -250.0,-192.0Q-231.0,-192.0 -219.5,-180.0Q-208.0,-168.0 -202.5,-151.5Q-197.0,-135.0 -197.0,-122.0ZM-450.0,-221.0Q-450.0,-233.0 -440.0,-243.5Q-430.0,-254.0 -411.0,-254.0Q-385.0,-254.0 -366.5,-233.5Q-348.0,-213.0 -348.0,-186.0Q-374.0,-197.0 -400.5,-206.0Q-427.0,-215.0 -450.0,-221.0Z" transform="translate(10636, 777)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-300.0,1050.0 -182.0,946.0Q-156.0,924.0 -145.0,908.0Q-134.0,892.0 -134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(10681, 699)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(10639, 793)"/>
<path d="M-222.0,-273.0Q-263.0,-273.0 -293.5,-255.0Q-324.0,-237.0 -324.0,-203.0Q-324.0,-188.0 -319.0,-169.5Q-314.0,-151.0 -310.0,-138.0L-307.0,-130.0Q-319.0,-130.0 -327.5,-121.0Q-336.0,-112.0 -336.0,-96.0Q-336.0,-76.0 -320.5,-62.5Q-305.0,-49.0 -279.0,-49.0Q-255.0,-49.0 -241.0,-61.5Q-227.0,-74.0 -227.0,-100.0Q-227.0,-110.0 -230.0,-123.0Q-233.0,-136.0 -241.0,-160.0Q-248.0,-182.0 -242.5,-195.5Q-237.0,-209.0 -215.0,-209.0Q-188.0,-209.0 -172.5,-186.0Q-157.0,-163.0 -138.0,-117.0Q-121.0,-76.0 -110.5,-62.5Q-100.0,-49.0 -86.0,-49.0Q-75.0,-49.0 -64.0,-57.0Q-53.0,-65.0 -53.0,-85.0Q-53.0,-100.0 -60.5,-130.5Q-68.0,-161.0 -87.0,-194.0Q-106.0,-227.0 -139.0,-250.0Q-172.0,-273.0 -222.0,-273.0Z" transform="translate(11177, 777)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(11293, 793)"/>
<path d="M914.0,501.0L914.0,0.0L822.0,0.0L822.0,501.0L723.0,580.0Q710.0,591.0 699.0,599.0Q688.0,607.0 680.0,607.0Q672.0,607.0 650.5,596.5Q629.0,586.0 600.0,570.5Q571.0,555.0 539.5,537.5Q508.0,520.0 480.0,506.0Q451.0,487.0 410.5,476.5Q370.0,466.0 318.0,466.0Q258.0,466.0 208.5,482.0Q159.0,498.0 129.5,528.5Q100.0,559.0 100.0,603.0Q100.0,643.0 127.5,674.0Q155.0,705.0 210.0,705.0Q261.0,705.0 288.5,678.0Q316.0,651.0 316.0,610.0Q316.0,589.0 308.0,573.0Q300.0,557.0 280.0,535.0Q301.0,532.0 324.0,532.0Q392.0,532.0 432.0,560.0Q472.0,588.0 472.0,633.0Q472.0,660.0 455.5,679.5Q439.0,699.0 406.0,694.0Q393.0,738.0 415.5,760.5Q438.0,783.0 470.0,783.0Q500.0,783.0 521.0,765.0Q542.0,747.0 553.0,717.5Q564.0,688.0 564.0,654.0Q564.0,645.0 563.0,635.0Q600.0,655.0 636.5,668.5Q673.0,682.0 700.0,682.0Q741.0,682.0 782.0,650.0L876.0,576.0Q914.0,547.0 914.0,501.0ZM245.0,608.0Q245.0,619.0 235.5,629.0Q226.0,639.0 209.0,639.0Q193.0,639.0 182.0,630.0Q171.0,621.0 171.0,606.0Q171.0,579.0 207.0,558.0Q222.0,566.0 233.5,580.5Q245.0,595.0 245.0,608.0ZM100.0,447.0L192.0,413.0L192.0,91.0L332.0,207.0L472.0,91.0L472.0,437.0L564.0,437.0L564.0,0.0L472.0,0.0L332.0,115.0L192.0,0.0L100.0,0.0L100.0,447.0Z" transform="translate(12294, 793)"/>
<path d="M-205.0,-44.0L-123.0,-44.0L-123.0,-74.0L-70.0,-74.0L-70.0,-124.0L-123.0,-124.0L-123.0,-250.0Q-123.0,-271.0 -135.0,-279.5Q-147.0,-288.0 -165.5,-290.0Q-184.0,-292.0 -205.0,-292.0L-322.0,-240.0L-439.0,-292.0Q-473.0,-292.0 -497.0,-286.5Q-521.0,-281.0 -521.0,-250.0L-521.0,-121.0Q-521.0,-95.0 -505.0,-84.5Q-489.0,-74.0 -465.0,-74.0L-205.0,-74.0L-205.0,-44.0ZM-205.0,-234.0L-205.0,-124.0L-439.0,-124.0L-439.0,-238.0L-322.0,-188.0L-205.0,-234.0Z" transform="translate(12970, 777)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(13300, 793)"/>
<path d="M126.0,850.0Q122.0,834.0 132.0,821.0Q142.0,808.0 161.0,808.0Q178.0,808.0 188.5,821.5Q199.0,835.0 199.0,858.0Q199.0,891.0 179.5,903.5Q160.0,916.0 138.0,916.0L116.0,916.0Q79.0,916.0 70.0,926.5Q61.0,937.0 53.0,960.0Q47.0,979.0 37.5,989.0Q28.0,999.0 4.0,999.0Q4.0,1024.0 19.0,1039.0Q34.0,1054.0 62.0,1054.0Q91.0,1054.0 108.5,1035.0Q126.0,1016.0 126.0,975.0L150.0,975.0Q218.0,975.0 245.0,944.5Q272.0,914.0 272.0,872.0Q272.0,844.0 260.0,818.0Q248.0,792.0 222.0,776.0Q196.0,760.0 152.0,760.0Q111.0,760.0 82.0,776.5Q53.0,793.0 53.0,823.0Q53.0,843.0 65.5,852.5Q78.0,862.0 95.0,861.5Q112.0,861.0 126.0,850.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(13952, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(14291, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(14943, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(15597, 793)"/>
<path d="M-192.0,-49.0Q-169.0,-49.0 -157.5,-62.0Q-146.0,-75.0 -146.0,-98.0L-146.0,-267.0L-212.0,-267.0L-212.0,-141.0Q-225.0,-138.0 -234.0,-126.0Q-243.0,-114.0 -243.0,-97.0Q-243.0,-77.0 -230.0,-63.0Q-217.0,-49.0 -192.0,-49.0Z" transform="translate(16124, 777)"/>
<path d="M333.0,462.0Q403.0,462.0 454.5,443.0Q506.0,424.0 534.0,391.0Q562.0,358.0 562.0,316.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,319.0Q470.0,350.0 430.0,372.5Q390.0,395.0 331.0,395.0Q269.0,395.0 229.5,372.0Q190.0,349.0 190.0,319.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,316.0Q98.0,358.0 129.0,392.0Q160.0,426.0 214.0,444.0Q187.0,467.0 171.5,482.0Q156.0,497.0 156.0,509.0Q156.0,515.0 159.0,523.5Q162.0,532.0 173.0,548.5Q184.0,565.0 207.5,597.0Q231.0,629.0 271.0,682.0Q309.0,660.0 339.5,645.0Q370.0,630.0 405.0,630.0Q405.0,602.0 387.5,580.0Q370.0,558.0 347.0,558.0Q331.0,558.0 309.5,570.0Q288.0,582.0 274.0,592.0L230.0,534.0L317.0,462.0Q325.0,462.0 333.0,462.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(16249, 793)"/>
<path d="M-173.0,-191.0L-173.0,-178.0Q-197.0,-177.0 -210.5,-159.5Q-224.0,-142.0 -224.0,-120.0Q-224.0,-89.0 -202.5,-69.0Q-181.0,-49.0 -141.0,-49.0Q-81.0,-49.0 -81.0,-98.0L-81.0,-185.0Q-81.0,-250.0 47.0,-250.0Q175.0,-250.0 175.0,-185.0L175.0,0.0L96.0,0.0L96.0,67.0L175.0,67.0L175.0,424.0Q139.0,454.0 120.5,471.0Q102.0,488.0 96.0,497.5Q90.0,507.0 90.0,514.0Q90.0,524.0 99.5,538.0Q109.0,552.0 134.0,584.0Q159.0,616.0 205.0,680.0Q237.0,659.0 258.0,647.0Q279.0,635.0 298.5,631.0Q318.0,627.0 343.0,629.0Q343.0,604.0 325.5,580.5Q308.0,557.0 279.0,557.0Q266.0,557.0 248.5,564.0Q231.0,571.0 205.0,590.0L162.0,532.0L267.0,447.0L267.0,67.0L340.0,67.0L340.0,0.0L267.0,0.0L267.0,-185.0Q267.0,-246.0 212.0,-281.5Q157.0,-317.0 47.0,-317.0Q-60.0,-317.0 -115.0,-283.5Q-170.0,-250.0 -173.0,-191.0L-173.0,-191.0Z" transform="translate(17250, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ដែលប្រហែលជាមានដើមកំណើតតាំងតែពី​</span> (fontdiff-km.html)</li>


<pre>Expected: uni17C2=0+339|uni178A=0+656|uni179B=2+1001|uni17D2179A=3+371|uni1794=3+654|uni17C2=6+339|uni17A0=6+1003|uni179B=8+1001|uni178717B6=9+1005|uni179817B6=11+1001|uni1793=13+652|uni17C1=14+339|uni178A=14+656|uni17B8=14@29,-14+0|uni1798=16+654|uni1780=17+633|uni17C6=17@40,-126+0|uni17C1=19+339|uni178E=19+1327|uni17B8=19@-305,-94+0|uni178F=21+633|uni178F17B6=22+981|uni17C6=22@186,-114+0|uni1784=25+684|uni17C2=26+339|uni178F=26+633|uni1796=28+657|uni17B8=28@-2,-94+0|space=30+0</pre>



<pre>Got     : uni17C2=0+339|uni178A=0+656|uni179B=2+1001|uni17D2179A=3+371|uni1794=3+654|uni17C2=6+339|uni17A0=6+1003|uni179B=8+1001|uni178717B6=9+1005|uni179817B6=11+1001|uni1793=13+652|uni17C1=14+339|uni178A=14+656|uni17B8=14@29,-14+0|uni1798=16+654|uni1780=17+633|uni17C6=17@40,-94+0|uni17C1=19+339|uni178E=19+1327|uni17B8=19@-305,-94+0|uni178F=21+633|uni178F17B6=22+981|uni17C6=22@186,-114+0|uni1784=25+684|uni17C2=26+339|uni178F=26+633|uni1796=28+657|uni17B8=28@-2,-94+0|space=30+0</pre>



<pre>                                                                                                                                                                                                                                                                                      ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15897 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M135.0,855.0Q122.0,855.0 116.5,849.0Q111.0,843.0 111.0,836.0Q111.0,815.0 146.0,815.0Q182.0,815.0 204.0,838.5Q226.0,862.0 226.0,896.0Q226.0,951.0 160.0,951.0Q148.0,969.0 149.0,988.5Q150.0,1008.0 162.5,1021.5Q175.0,1035.0 198.0,1035.0Q222.0,1035.0 245.5,1019.5Q269.0,1004.0 285.0,975.5Q301.0,947.0 301.0,908.0Q301.0,869.0 282.0,835.0Q263.0,801.0 228.0,780.5Q193.0,760.0 144.0,760.0Q92.0,760.0 62.5,784.0Q33.0,808.0 33.0,844.0Q33.0,874.0 52.0,896.0Q71.0,918.0 97.0,918.0Q121.0,918.0 128.0,899.0Q135.0,880.0 135.0,855.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(0, 793)"/>
<path d="M564.0,654.0Q564.0,607.0 538.5,563.5Q513.0,520.0 458.5,493.0Q404.0,466.0 318.0,466.0Q258.0,466.0 208.5,482.0Q159.0,498.0 129.5,528.5Q100.0,559.0 100.0,603.0Q100.0,643.0 127.5,674.0Q155.0,705.0 210.0,705.0Q261.0,705.0 288.5,678.0Q316.0,651.0 316.0,610.0Q316.0,589.0 308.0,573.0Q300.0,557.0 280.0,535.0Q301.0,532.0 324.0,532.0Q392.0,532.0 432.0,560.0Q472.0,588.0 472.0,633.0Q472.0,660.0 455.5,679.5Q439.0,699.0 406.0,694.0Q393.0,738.0 415.5,760.5Q438.0,783.0 470.0,783.0Q500.0,783.0 521.0,765.0Q542.0,747.0 553.0,717.5Q564.0,688.0 564.0,654.0ZM245.0,608.0Q245.0,619.0 235.5,629.0Q226.0,639.0 209.0,639.0Q193.0,639.0 182.0,630.0Q171.0,621.0 171.0,606.0Q171.0,579.0 207.0,558.0Q222.0,566.0 233.5,580.5Q245.0,595.0 245.0,608.0ZM100.0,447.0L192.0,413.0L192.0,91.0L332.0,207.0L472.0,91.0L472.0,437.0L564.0,437.0L564.0,0.0L472.0,0.0L332.0,115.0L192.0,0.0L100.0,0.0L100.0,447.0Z" transform="translate(339, 793)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(995, 793)"/>
<path d="M121.0,532.0L226.0,447.0L226.0,-193.0Q226.0,-250.0 348.0,-250.0Q469.0,-250.0 469.0,-193.0L469.0,-49.0L561.0,-49.0L561.0,-195.0Q561.0,-317.0 348.0,-317.0Q134.0,-317.0 134.0,-195.0L134.0,424.0Q98.0,454.0 79.5,471.0Q61.0,488.0 55.0,497.5Q49.0,507.0 49.0,514.0Q49.0,524.0 58.5,538.0Q68.0,552.0 93.0,584.0Q118.0,616.0 164.0,680.0Q196.0,659.0 217.0,647.0Q238.0,635.0 257.5,631.0Q277.0,627.0 302.0,629.0Q302.0,604.0 284.5,580.5Q267.0,557.0 238.0,557.0Q225.0,557.0 207.5,564.0Q190.0,571.0 164.0,590.0L121.0,532.0Z" transform="translate(1996, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(2367, 793)"/>
<path d="M135.0,855.0Q122.0,855.0 116.5,849.0Q111.0,843.0 111.0,836.0Q111.0,815.0 146.0,815.0Q182.0,815.0 204.0,838.5Q226.0,862.0 226.0,896.0Q226.0,951.0 160.0,951.0Q148.0,969.0 149.0,988.5Q150.0,1008.0 162.5,1021.5Q175.0,1035.0 198.0,1035.0Q222.0,1035.0 245.5,1019.5Q269.0,1004.0 285.0,975.5Q301.0,947.0 301.0,908.0Q301.0,869.0 282.0,835.0Q263.0,801.0 228.0,780.5Q193.0,760.0 144.0,760.0Q92.0,760.0 62.5,784.0Q33.0,808.0 33.0,844.0Q33.0,874.0 52.0,896.0Q71.0,918.0 97.0,918.0Q121.0,918.0 128.0,899.0Q135.0,880.0 135.0,855.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(3021, 793)"/>
<path d="M341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,438.0Q438.0,467.0 427.5,482.0Q417.0,497.0 417.0,508.0Q417.0,522.0 435.5,547.0Q454.0,572.0 513.0,616.0Q562.0,652.0 598.5,667.0Q635.0,682.0 670.0,682.0Q699.0,682.0 735.0,670.0Q771.0,658.0 818.0,622.0Q868.0,584.0 889.5,546.5Q911.0,509.0 911.0,463.0L911.0,0.0L819.0,0.0L819.0,464.0Q819.0,489.0 805.5,515.5Q792.0,542.0 769.0,564.5Q746.0,587.0 718.5,601.0Q691.0,615.0 663.0,615.0Q633.0,615.0 589.5,593.5Q546.0,572.0 494.0,518.0L563.0,463.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Z" transform="translate(3360, 793)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4363, 793)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.0,765.0Q520.0,750.0 542.5,720.5Q565.0,691.0 565.0,647.0Q589.0,661.0 620.0,671.5Q651.0,682.0 687.0,682.0Q740.0,682.0 781.0,650.0L875.0,576.0Q913.0,547.0 913.0,501.0L913.0,0.0L821.0,0.0L821.0,501.0L722.0,580.0Q709.0,591.0 692.5,599.0Q676.0,607.0 653.0,607.0Q626.0,607.0 602.0,594.5Q578.0,582.0 555.5,564.5Q533.0,547.0 511.0,532.0Q492.0,516.0 467.0,507.5Q442.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(5364, 793)"/>
<path d="M211.0,447.0L211.0,327.0L471.0,327.0L471.0,435.0Q430.0,466.0 418.5,480.5Q407.0,495.0 407.0,505.0Q407.0,520.0 423.0,544.5Q439.0,569.0 476.0,607.0Q508.0,640.0 539.0,661.0Q570.0,682.0 610.0,682.0Q647.0,682.0 691.0,663.0Q735.0,644.0 787.0,610.0Q836.0,579.0 862.5,552.0Q889.0,525.0 899.0,497.5Q909.0,470.0 909.0,435.0L909.0,0.0L817.0,0.0L817.0,432.0Q817.0,467.0 794.0,491.0Q771.0,515.0 736.0,540.0Q693.0,571.0 664.5,586.0Q636.0,601.0 606.0,601.0Q568.0,601.0 536.5,578.5Q505.0,556.0 485.0,521.0L563.0,458.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(6369, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(7370, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(8022, 793)"/>
<path d="M564.0,654.0Q564.0,607.0 538.5,563.5Q513.0,520.0 458.5,493.0Q404.0,466.0 318.0,466.0Q258.0,466.0 208.5,482.0Q159.0,498.0 129.5,528.5Q100.0,559.0 100.0,603.0Q100.0,643.0 127.5,674.0Q155.0,705.0 210.0,705.0Q261.0,705.0 288.5,678.0Q316.0,651.0 316.0,610.0Q316.0,589.0 308.0,573.0Q300.0,557.0 280.0,535.0Q301.0,532.0 324.0,532.0Q392.0,532.0 432.0,560.0Q472.0,588.0 472.0,633.0Q472.0,660.0 455.5,679.5Q439.0,699.0 406.0,694.0Q393.0,738.0 415.5,760.5Q438.0,783.0 470.0,783.0Q500.0,783.0 521.0,765.0Q542.0,747.0 553.0,717.5Q564.0,688.0 564.0,654.0ZM245.0,608.0Q245.0,619.0 235.5,629.0Q226.0,639.0 209.0,639.0Q193.0,639.0 182.0,630.0Q171.0,621.0 171.0,606.0Q171.0,579.0 207.0,558.0Q222.0,566.0 233.5,580.5Q245.0,595.0 245.0,608.0ZM100.0,447.0L192.0,413.0L192.0,91.0L332.0,207.0L472.0,91.0L472.0,437.0L564.0,437.0L564.0,0.0L472.0,0.0L332.0,115.0L192.0,0.0L100.0,0.0L100.0,447.0Z" transform="translate(8361, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(9046, 779)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(9017, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(9671, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(10344, 699)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(10304, 793)"/>
<path d="M128.0,515.0L194.0,463.0L194.0,246.0Q250.0,249.0 277.5,222.5Q305.0,196.0 305.0,151.0Q305.0,133.0 297.5,109.0Q290.0,85.0 266.5,57.5Q243.0,30.0 194.0,0.0L102.0,0.0L102.0,438.0Q69.0,467.0 58.5,480.5Q48.0,494.0 48.0,504.0Q48.0,514.0 56.5,526.0Q65.0,538.0 87.0,559.0Q109.0,580.0 148.0,614.0Q194.0,654.0 227.5,668.0Q261.0,682.0 297.0,682.0Q330.0,682.0 366.0,670.0Q402.0,658.0 449.0,622.0Q499.0,584.0 520.5,546.5Q542.0,509.0 542.0,463.0L542.0,91.0L669.0,196.0L797.0,91.0L797.0,438.0Q764.0,467.0 753.5,481.0Q743.0,495.0 743.0,505.0Q743.0,515.0 751.5,527.0Q760.0,539.0 782.0,559.5Q804.0,580.0 843.0,614.0Q889.0,654.0 920.5,668.0Q952.0,682.0 989.0,682.0Q1021.0,682.0 1059.0,670.0Q1097.0,658.0 1144.0,622.0Q1194.0,584.0 1215.5,546.5Q1237.0,509.0 1237.0,463.0L1237.0,0.0L1145.0,0.0L1145.0,464.0Q1145.0,489.0 1130.0,515.5Q1115.0,542.0 1091.0,564.5Q1067.0,587.0 1038.5,601.0Q1010.0,615.0 983.0,615.0Q952.0,615.0 916.5,592.0Q881.0,569.0 823.0,515.0L889.0,463.0L889.0,0.0L797.0,0.0L669.0,105.0L542.0,0.0L450.0,0.0L450.0,464.0Q450.0,489.0 435.5,515.5Q421.0,542.0 397.0,564.5Q373.0,587.0 344.5,601.0Q316.0,615.0 289.0,615.0Q258.0,615.0 222.0,592.0Q186.0,569.0 128.0,515.0ZM194.0,181.0L194.0,89.0Q234.0,114.0 234.0,150.0Q234.0,169.0 222.5,175.0Q211.0,181.0 194.0,181.0Z" transform="translate(10643, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(11665, 699)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(11970, 793)"/>
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM177.0,0.0L85.0,0.0L85.0,316.0Q85.0,354.0 115.5,386.5Q146.0,419.0 196.5,439.0Q247.0,459.0 307.0,459.0Q369.0,459.0 419.5,438.5Q470.0,418.0 499.5,385.5Q529.0,353.0 529.0,316.0L529.0,0.0L437.0,0.0L437.0,316.0Q437.0,336.0 419.5,353.5Q402.0,371.0 373.0,381.5Q344.0,392.0 308.0,392.0Q252.0,392.0 214.5,368.5Q177.0,345.0 177.0,316.0L177.0,246.0Q233.0,249.0 260.5,222.5Q288.0,196.0 288.0,151.0Q288.0,133.0 280.5,109.0Q273.0,85.0 249.5,57.5Q226.0,30.0 177.0,0.0ZM177.0,181.0L177.0,89.0Q217.0,114.0 217.0,150.0Q217.0,169.0 205.5,175.0Q194.0,181.0 177.0,181.0Z" transform="translate(12603, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(13770, 679)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(13584, 793)"/>
<path d="M135.0,855.0Q122.0,855.0 116.5,849.0Q111.0,843.0 111.0,836.0Q111.0,815.0 146.0,815.0Q182.0,815.0 204.0,838.5Q226.0,862.0 226.0,896.0Q226.0,951.0 160.0,951.0Q148.0,969.0 149.0,988.5Q150.0,1008.0 162.5,1021.5Q175.0,1035.0 198.0,1035.0Q222.0,1035.0 245.5,1019.5Q269.0,1004.0 285.0,975.5Q301.0,947.0 301.0,908.0Q301.0,869.0 282.0,835.0Q263.0,801.0 228.0,780.5Q193.0,760.0 144.0,760.0Q92.0,760.0 62.5,784.0Q33.0,808.0 33.0,844.0Q33.0,874.0 52.0,896.0Q71.0,918.0 97.0,918.0Q121.0,918.0 128.0,899.0Q135.0,880.0 135.0,855.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(14268, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(14607, 793)"/>
<path d="M149.0,558.0Q149.0,550.0 161.0,534.5Q173.0,519.0 195.0,499.0L195.0,246.0Q251.0,249.0 278.5,222.5Q306.0,196.0 306.0,151.0Q306.0,133.0 298.5,109.0Q291.0,85.0 267.5,57.5Q244.0,30.0 195.0,0.0L103.0,0.0L103.0,469.0Q54.0,519.0 54.0,542.0Q54.0,553.0 71.5,578.0Q89.0,603.0 117.0,629.0Q140.0,650.0 165.0,666.0Q190.0,682.0 206.0,682.0Q218.0,682.0 235.0,671.0Q252.0,660.0 276.0,639.0Q294.0,623.0 306.5,612.5Q319.0,602.0 320.0,602.0Q323.0,602.0 336.5,614.5Q350.0,627.0 368.0,644.0Q387.0,661.0 401.0,671.5Q415.0,682.0 431.0,682.0Q462.0,682.0 493.0,658.0Q524.0,634.0 545.5,597.0Q567.0,560.0 567.0,521.0L567.0,0.0L475.0,0.0L475.0,521.0Q475.0,548.0 455.5,569.5Q436.0,591.0 417.0,591.0Q403.0,591.0 389.5,580.0Q376.0,569.0 361.5,554.5Q347.0,540.0 331.0,529.0Q315.0,518.0 297.0,518.0Q279.0,518.0 263.0,528.5Q247.0,539.0 233.0,553.0Q219.0,567.0 207.0,577.5Q195.0,588.0 184.0,588.0Q178.0,588.0 172.0,585.0Q166.0,582.0 161.0,577.0Q149.0,567.0 149.0,558.0ZM195.0,181.0L195.0,89.0Q235.0,114.0 235.0,150.0Q235.0,169.0 223.5,175.0Q212.0,181.0 195.0,181.0Z" transform="translate(15240, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(15895, 699)"/>
<path d="" transform="translate(15897, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15897 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M135.0,855.0Q122.0,855.0 116.5,849.0Q111.0,843.0 111.0,836.0Q111.0,815.0 146.0,815.0Q182.0,815.0 204.0,838.5Q226.0,862.0 226.0,896.0Q226.0,951.0 160.0,951.0Q148.0,969.0 149.0,988.5Q150.0,1008.0 162.5,1021.5Q175.0,1035.0 198.0,1035.0Q222.0,1035.0 245.5,1019.5Q269.0,1004.0 285.0,975.5Q301.0,947.0 301.0,908.0Q301.0,869.0 282.0,835.0Q263.0,801.0 228.0,780.5Q193.0,760.0 144.0,760.0Q92.0,760.0 62.5,784.0Q33.0,808.0 33.0,844.0Q33.0,874.0 52.0,896.0Q71.0,918.0 97.0,918.0Q121.0,918.0 128.0,899.0Q135.0,880.0 135.0,855.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(0, 793)"/>
<path d="M564.0,654.0Q564.0,607.0 538.5,563.5Q513.0,520.0 458.5,493.0Q404.0,466.0 318.0,466.0Q258.0,466.0 208.5,482.0Q159.0,498.0 129.5,528.5Q100.0,559.0 100.0,603.0Q100.0,643.0 127.5,674.0Q155.0,705.0 210.0,705.0Q261.0,705.0 288.5,678.0Q316.0,651.0 316.0,610.0Q316.0,589.0 308.0,573.0Q300.0,557.0 280.0,535.0Q301.0,532.0 324.0,532.0Q392.0,532.0 432.0,560.0Q472.0,588.0 472.0,633.0Q472.0,660.0 455.5,679.5Q439.0,699.0 406.0,694.0Q393.0,738.0 415.5,760.5Q438.0,783.0 470.0,783.0Q500.0,783.0 521.0,765.0Q542.0,747.0 553.0,717.5Q564.0,688.0 564.0,654.0ZM245.0,608.0Q245.0,619.0 235.5,629.0Q226.0,639.0 209.0,639.0Q193.0,639.0 182.0,630.0Q171.0,621.0 171.0,606.0Q171.0,579.0 207.0,558.0Q222.0,566.0 233.5,580.5Q245.0,595.0 245.0,608.0ZM100.0,447.0L192.0,413.0L192.0,91.0L332.0,207.0L472.0,91.0L472.0,437.0L564.0,437.0L564.0,0.0L472.0,0.0L332.0,115.0L192.0,0.0L100.0,0.0L100.0,447.0Z" transform="translate(339, 793)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(995, 793)"/>
<path d="M121.0,532.0L226.0,447.0L226.0,-193.0Q226.0,-250.0 348.0,-250.0Q469.0,-250.0 469.0,-193.0L469.0,-49.0L561.0,-49.0L561.0,-195.0Q561.0,-317.0 348.0,-317.0Q134.0,-317.0 134.0,-195.0L134.0,424.0Q98.0,454.0 79.5,471.0Q61.0,488.0 55.0,497.5Q49.0,507.0 49.0,514.0Q49.0,524.0 58.5,538.0Q68.0,552.0 93.0,584.0Q118.0,616.0 164.0,680.0Q196.0,659.0 217.0,647.0Q238.0,635.0 257.5,631.0Q277.0,627.0 302.0,629.0Q302.0,604.0 284.5,580.5Q267.0,557.0 238.0,557.0Q225.0,557.0 207.5,564.0Q190.0,571.0 164.0,590.0L121.0,532.0Z" transform="translate(1996, 793)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0Z" transform="translate(2367, 793)"/>
<path d="M135.0,855.0Q122.0,855.0 116.5,849.0Q111.0,843.0 111.0,836.0Q111.0,815.0 146.0,815.0Q182.0,815.0 204.0,838.5Q226.0,862.0 226.0,896.0Q226.0,951.0 160.0,951.0Q148.0,969.0 149.0,988.5Q150.0,1008.0 162.5,1021.5Q175.0,1035.0 198.0,1035.0Q222.0,1035.0 245.5,1019.5Q269.0,1004.0 285.0,975.5Q301.0,947.0 301.0,908.0Q301.0,869.0 282.0,835.0Q263.0,801.0 228.0,780.5Q193.0,760.0 144.0,760.0Q92.0,760.0 62.5,784.0Q33.0,808.0 33.0,844.0Q33.0,874.0 52.0,896.0Q71.0,918.0 97.0,918.0Q121.0,918.0 128.0,899.0Q135.0,880.0 135.0,855.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(3021, 793)"/>
<path d="M341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,438.0Q438.0,467.0 427.5,482.0Q417.0,497.0 417.0,508.0Q417.0,522.0 435.5,547.0Q454.0,572.0 513.0,616.0Q562.0,652.0 598.5,667.0Q635.0,682.0 670.0,682.0Q699.0,682.0 735.0,670.0Q771.0,658.0 818.0,622.0Q868.0,584.0 889.5,546.5Q911.0,509.0 911.0,463.0L911.0,0.0L819.0,0.0L819.0,464.0Q819.0,489.0 805.5,515.5Q792.0,542.0 769.0,564.5Q746.0,587.0 718.5,601.0Q691.0,615.0 663.0,615.0Q633.0,615.0 589.5,593.5Q546.0,572.0 494.0,518.0L563.0,463.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Z" transform="translate(3360, 793)"/>
<path d="M124.0,515.0L190.0,463.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0L98.0,0.0L98.0,438.0Q65.0,467.0 54.5,482.0Q44.0,497.0 44.0,507.0Q44.0,521.0 63.5,546.0Q83.0,571.0 142.0,616.0Q190.0,653.0 223.5,667.5Q257.0,682.0 294.0,682.0Q326.0,682.0 363.5,669.5Q401.0,657.0 459.0,618.0Q514.0,581.0 538.0,545.0Q562.0,509.0 562.0,463.0L562.0,146.0Q562.0,127.0 579.5,109.0Q597.0,91.0 626.5,79.0Q656.0,67.0 690.0,67.0Q725.0,67.0 754.0,79.0Q783.0,91.0 800.5,109.0Q818.0,127.0 818.0,146.0L818.0,424.0Q782.0,454.0 763.5,471.0Q745.0,488.0 739.0,497.5Q733.0,507.0 733.0,514.0Q733.0,524.0 742.5,538.0Q752.0,552.0 777.0,584.0Q802.0,616.0 848.0,680.0Q880.0,659.0 901.0,647.0Q922.0,635.0 941.5,631.0Q961.0,627.0 986.0,629.0Q986.0,604.0 968.5,580.5Q951.0,557.0 922.0,557.0Q909.0,557.0 891.5,564.0Q874.0,571.0 848.0,590.0L805.0,532.0L910.0,447.0L910.0,146.0Q910.0,114.0 882.0,80.0Q854.0,46.0 804.5,23.0Q755.0,0.0 690.0,0.0Q625.0,0.0 575.0,23.0Q525.0,46.0 497.5,80.0Q470.0,114.0 470.0,146.0L470.0,463.0Q470.0,488.0 452.5,514.5Q435.0,541.0 407.0,564.0Q379.0,587.0 348.0,601.0Q317.0,615.0 290.0,615.0Q258.0,615.0 220.0,591.5Q182.0,568.0 124.0,515.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(4363, 793)"/>
<path d="M138.0,539.0Q138.0,532.0 149.0,519.0Q160.0,506.0 191.0,471.0L191.0,91.0L331.0,207.0L471.0,91.0L471.0,428.0L563.0,428.0L563.0,0.0L471.0,0.0L331.0,115.0L191.0,0.0L99.0,0.0L99.0,443.0Q75.0,466.0 62.5,485.0Q50.0,504.0 50.0,523.0Q50.0,544.0 64.5,563.0Q79.0,582.0 108.0,610.0Q136.0,637.0 163.5,659.5Q191.0,682.0 206.0,682.0Q218.0,682.0 237.0,666.5Q256.0,651.0 294.0,624.0Q332.0,597.0 361.5,582.5Q391.0,568.0 420.0,568.0Q454.0,568.0 476.0,586.0Q498.0,604.0 498.0,633.0Q498.0,660.0 479.5,678.0Q461.0,696.0 433.5,703.0Q406.0,710.0 377.0,704.0Q376.0,738.0 387.5,759.0Q399.0,780.0 431.0,780.0Q458.0,780.0 489.0,765.0Q520.0,750.0 542.5,720.5Q565.0,691.0 565.0,647.0Q589.0,661.0 620.0,671.5Q651.0,682.0 687.0,682.0Q740.0,682.0 781.0,650.0L875.0,576.0Q913.0,547.0 913.0,501.0L913.0,0.0L821.0,0.0L821.0,501.0L722.0,580.0Q709.0,591.0 692.5,599.0Q676.0,607.0 653.0,607.0Q626.0,607.0 602.0,594.5Q578.0,582.0 555.5,564.5Q533.0,547.0 511.0,532.0Q492.0,516.0 467.0,507.5Q442.0,499.0 412.0,499.0Q369.0,499.0 333.5,516.0Q298.0,533.0 263.0,556.0Q233.0,576.0 218.0,585.5Q203.0,595.0 196.0,595.0Q188.0,595.0 178.5,588.5Q169.0,582.0 161.0,574.0Q153.0,566.0 145.5,556.0Q138.0,546.0 138.0,539.0Z" transform="translate(5364, 793)"/>
<path d="M211.0,447.0L211.0,327.0L471.0,327.0L471.0,435.0Q430.0,466.0 418.5,480.5Q407.0,495.0 407.0,505.0Q407.0,520.0 423.0,544.5Q439.0,569.0 476.0,607.0Q508.0,640.0 539.0,661.0Q570.0,682.0 610.0,682.0Q647.0,682.0 691.0,663.0Q735.0,644.0 787.0,610.0Q836.0,579.0 862.5,552.0Q889.0,525.0 899.0,497.5Q909.0,470.0 909.0,435.0L909.0,0.0L817.0,0.0L817.0,432.0Q817.0,467.0 794.0,491.0Q771.0,515.0 736.0,540.0Q693.0,571.0 664.5,586.0Q636.0,601.0 606.0,601.0Q568.0,601.0 536.5,578.5Q505.0,556.0 485.0,521.0L563.0,458.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(6369, 793)"/>
<path d="M384.0,432.0Q384.0,473.0 409.0,489.5Q434.0,506.0 470.0,507.0L470.0,536.0Q470.0,557.0 451.5,575.0Q433.0,593.0 401.0,604.0Q369.0,615.0 330.0,615.0Q269.0,615.0 229.5,590.5Q190.0,566.0 190.0,536.0L190.0,463.0Q190.0,393.0 328.0,345.0L562.0,263.0L562.0,122.0Q562.0,58.0 523.5,29.0Q485.0,0.0 431.0,0.0Q393.0,0.0 366.0,11.5Q339.0,23.0 318.0,40.5Q297.0,58.0 276.0,76.0Q257.0,92.0 236.0,104.5Q215.0,117.0 190.0,118.0L190.0,0.0L98.0,0.0L98.0,279.0L190.0,235.0L190.0,185.0Q222.0,184.0 257.5,163.0Q293.0,142.0 326.0,116.0Q355.0,94.0 371.5,80.5Q388.0,67.0 414.0,67.0Q446.0,67.0 458.0,86.5Q470.0,106.0 470.0,135.0L470.0,224.0L291.0,286.0Q98.0,352.0 98.0,463.0L98.0,536.0Q98.0,575.0 127.5,608.5Q157.0,642.0 209.0,662.0Q261.0,682.0 330.0,682.0Q400.0,682.0 452.0,661.5Q504.0,641.0 533.0,607.5Q562.0,574.0 562.0,536.0L562.0,406.0Q562.0,381.0 539.0,366.5Q516.0,352.0 478.0,352.0Q434.0,352.0 409.0,372.5Q384.0,393.0 384.0,432.0ZM470.0,468.0Q455.0,468.0 444.0,459.5Q433.0,451.0 433.0,432.0Q433.0,413.0 444.0,403.0Q455.0,393.0 470.0,393.0L470.0,468.0Z" transform="translate(7370, 793)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(8022, 793)"/>
<path d="M564.0,654.0Q564.0,607.0 538.5,563.5Q513.0,520.0 458.5,493.0Q404.0,466.0 318.0,466.0Q258.0,466.0 208.5,482.0Q159.0,498.0 129.5,528.5Q100.0,559.0 100.0,603.0Q100.0,643.0 127.5,674.0Q155.0,705.0 210.0,705.0Q261.0,705.0 288.5,678.0Q316.0,651.0 316.0,610.0Q316.0,589.0 308.0,573.0Q300.0,557.0 280.0,535.0Q301.0,532.0 324.0,532.0Q392.0,532.0 432.0,560.0Q472.0,588.0 472.0,633.0Q472.0,660.0 455.5,679.5Q439.0,699.0 406.0,694.0Q393.0,738.0 415.5,760.5Q438.0,783.0 470.0,783.0Q500.0,783.0 521.0,765.0Q542.0,747.0 553.0,717.5Q564.0,688.0 564.0,654.0ZM245.0,608.0Q245.0,619.0 235.5,629.0Q226.0,639.0 209.0,639.0Q193.0,639.0 182.0,630.0Q171.0,621.0 171.0,606.0Q171.0,579.0 207.0,558.0Q222.0,566.0 233.5,580.5Q245.0,595.0 245.0,608.0ZM100.0,447.0L192.0,413.0L192.0,91.0L332.0,207.0L472.0,91.0L472.0,437.0L564.0,437.0L564.0,0.0L472.0,0.0L332.0,115.0L192.0,0.0L100.0,0.0L100.0,447.0Z" transform="translate(8361, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(9046, 779)"/>
<path d="M458.0,532.0L563.0,447.0L563.0,146.0Q563.0,108.0 532.5,74.5Q502.0,41.0 451.5,20.5Q401.0,0.0 341.0,0.0Q280.0,0.0 229.5,21.0Q179.0,42.0 149.0,75.5Q119.0,109.0 119.0,146.0L119.0,424.0Q83.0,454.0 64.5,471.0Q46.0,488.0 40.0,497.5Q34.0,507.0 34.0,514.0Q34.0,524.0 43.5,538.0Q53.0,552.0 78.0,584.0Q103.0,616.0 149.0,680.0Q181.0,659.0 202.0,647.0Q223.0,635.0 242.5,631.0Q262.0,627.0 287.0,629.0Q287.0,604.0 269.5,580.5Q252.0,557.0 223.0,557.0Q210.0,557.0 192.5,564.0Q175.0,571.0 149.0,590.0L106.0,532.0L211.0,447.0L211.0,327.0L471.0,327.0L471.0,424.0Q435.0,454.0 416.5,471.0Q398.0,488.0 392.0,497.5Q386.0,507.0 386.0,514.0Q386.0,524.0 395.5,538.0Q405.0,552.0 430.0,584.0Q455.0,616.0 501.0,680.0Q533.0,659.0 554.0,647.0Q575.0,635.0 594.5,631.0Q614.0,627.0 639.0,629.0Q639.0,604.0 621.5,580.5Q604.0,557.0 575.0,557.0Q562.0,557.0 544.5,564.0Q527.0,571.0 501.0,590.0L458.0,532.0ZM211.0,146.0Q211.0,126.0 229.0,108.0Q247.0,90.0 276.5,78.5Q306.0,67.0 341.0,67.0Q378.0,67.0 407.0,79.0Q436.0,91.0 453.5,109.0Q471.0,127.0 471.0,146.0L471.0,250.0L211.0,250.0L211.0,146.0Z" transform="translate(9017, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0Z" transform="translate(9671, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(10344, 667)"/>
<path d="M92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(10304, 793)"/>
<path d="M128.0,515.0L194.0,463.0L194.0,246.0Q250.0,249.0 277.5,222.5Q305.0,196.0 305.0,151.0Q305.0,133.0 297.5,109.0Q290.0,85.0 266.5,57.5Q243.0,30.0 194.0,0.0L102.0,0.0L102.0,438.0Q69.0,467.0 58.5,480.5Q48.0,494.0 48.0,504.0Q48.0,514.0 56.5,526.0Q65.0,538.0 87.0,559.0Q109.0,580.0 148.0,614.0Q194.0,654.0 227.5,668.0Q261.0,682.0 297.0,682.0Q330.0,682.0 366.0,670.0Q402.0,658.0 449.0,622.0Q499.0,584.0 520.5,546.5Q542.0,509.0 542.0,463.0L542.0,91.0L669.0,196.0L797.0,91.0L797.0,438.0Q764.0,467.0 753.5,481.0Q743.0,495.0 743.0,505.0Q743.0,515.0 751.5,527.0Q760.0,539.0 782.0,559.5Q804.0,580.0 843.0,614.0Q889.0,654.0 920.5,668.0Q952.0,682.0 989.0,682.0Q1021.0,682.0 1059.0,670.0Q1097.0,658.0 1144.0,622.0Q1194.0,584.0 1215.5,546.5Q1237.0,509.0 1237.0,463.0L1237.0,0.0L1145.0,0.0L1145.0,464.0Q1145.0,489.0 1130.0,515.5Q1115.0,542.0 1091.0,564.5Q1067.0,587.0 1038.5,601.0Q1010.0,615.0 983.0,615.0Q952.0,615.0 916.5,592.0Q881.0,569.0 823.0,515.0L889.0,463.0L889.0,0.0L797.0,0.0L669.0,105.0L542.0,0.0L450.0,0.0L450.0,464.0Q450.0,489.0 435.5,515.5Q421.0,542.0 397.0,564.5Q373.0,587.0 344.5,601.0Q316.0,615.0 289.0,615.0Q258.0,615.0 222.0,592.0Q186.0,569.0 128.0,515.0ZM194.0,181.0L194.0,89.0Q234.0,114.0 234.0,150.0Q234.0,169.0 222.5,175.0Q211.0,181.0 194.0,181.0Z" transform="translate(10643, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(11665, 699)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(11970, 793)"/>
<path d="M889.0,455.0L889.0,0.0L797.0,0.0L797.0,432.0Q797.0,467.0 780.0,488.0Q763.0,509.0 716.0,540.0Q674.0,569.0 654.5,578.0Q635.0,587.0 620.0,587.0Q598.0,587.0 577.0,574.5Q556.0,562.0 534.0,546.0Q512.0,530.0 488.5,517.5Q465.0,505.0 437.0,505.0Q409.0,505.0 383.0,518.5Q357.0,532.0 332.5,550.5Q308.0,569.0 283.0,582.5Q258.0,596.0 230.0,596.0Q217.0,596.0 202.0,591.5Q187.0,587.0 168.0,575.0Q156.0,568.0 145.5,557.0Q135.0,546.0 135.0,532.0Q135.0,519.0 148.0,508.0Q161.0,497.0 182.0,483.0L103.0,435.0Q75.0,455.0 59.0,473.5Q43.0,492.0 43.0,517.0Q43.0,543.0 65.5,569.0Q88.0,595.0 139.0,628.0Q186.0,659.0 217.0,670.5Q248.0,682.0 264.0,682.0Q281.0,682.0 305.5,668.0Q330.0,654.0 370.0,628.0Q399.0,609.0 419.5,597.5Q440.0,586.0 457.0,586.0Q475.0,586.0 493.0,599.0Q511.0,612.0 545.0,635.0Q577.0,657.0 598.0,669.5Q619.0,682.0 636.0,682.0Q656.0,682.0 686.0,663.5Q716.0,645.0 767.0,610.0Q816.0,576.0 842.5,552.5Q869.0,529.0 879.0,507.0Q889.0,485.0 889.0,455.0ZM177.0,0.0L85.0,0.0L85.0,316.0Q85.0,354.0 115.5,386.5Q146.0,419.0 196.5,439.0Q247.0,459.0 307.0,459.0Q369.0,459.0 419.5,438.5Q470.0,418.0 499.5,385.5Q529.0,353.0 529.0,316.0L529.0,0.0L437.0,0.0L437.0,316.0Q437.0,336.0 419.5,353.5Q402.0,371.0 373.0,381.5Q344.0,392.0 308.0,392.0Q252.0,392.0 214.5,368.5Q177.0,345.0 177.0,316.0L177.0,246.0Q233.0,249.0 260.5,222.5Q288.0,196.0 288.0,151.0Q288.0,133.0 280.5,109.0Q273.0,85.0 249.5,57.5Q226.0,30.0 177.0,0.0ZM177.0,181.0L177.0,89.0Q217.0,114.0 217.0,150.0Q217.0,169.0 205.5,175.0Q194.0,181.0 177.0,181.0Z" transform="translate(12603, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z" transform="translate(13770, 679)"/>
<path d="M130.0,0.0L130.0,188.0Q87.0,188.0 53.5,215.0Q20.0,242.0 20.0,289.0Q20.0,325.0 39.0,352.0Q58.0,379.0 88.5,393.5Q119.0,408.0 155.0,408.0Q190.0,408.0 206.0,394.0Q222.0,380.0 222.0,355.0L222.0,91.0L362.0,207.0L502.0,91.0L502.0,400.0Q502.0,429.0 482.5,449.0Q463.0,469.0 440.0,484.0Q406.0,464.0 362.5,451.0Q319.0,438.0 276.0,438.0Q210.0,438.0 173.5,471.0Q137.0,504.0 137.0,562.0Q137.0,585.0 141.5,601.5Q146.0,618.0 150.5,636.0Q155.0,654.0 155.0,681.0Q155.0,731.0 106.0,731.0Q106.0,760.0 121.5,780.0Q137.0,800.0 169.0,800.0Q207.0,800.0 222.0,773.0Q237.0,746.0 237.0,711.0Q237.0,679.0 229.5,657.5Q222.0,636.0 214.0,618.0Q206.0,600.0 206.0,576.0Q206.0,535.0 232.0,520.0Q258.0,505.0 293.0,505.0Q310.0,505.0 335.5,508.5Q361.0,512.0 386.0,520.0Q369.0,534.0 357.0,552.5Q345.0,571.0 345.0,595.0Q345.0,630.0 371.0,657.0Q397.0,684.0 440.0,684.0Q481.0,684.0 505.5,659.5Q530.0,635.0 530.0,598.0Q530.0,574.0 519.0,556.0Q508.0,538.0 491.0,522.0Q530.0,494.0 562.0,462.5Q594.0,431.0 594.0,389.0L594.0,0.0L502.0,0.0L362.0,115.0L222.0,0.0L130.0,0.0ZM413.0,599.0Q413.0,586.0 421.0,576.0Q429.0,566.0 441.0,557.0Q450.0,567.0 456.0,578.5Q462.0,590.0 462.0,601.0Q462.0,612.0 456.0,620.0Q450.0,628.0 438.0,628.0Q426.0,628.0 419.5,619.0Q413.0,610.0 413.0,599.0ZM130.0,255.0L130.0,346.0Q114.0,346.0 99.5,333.0Q85.0,320.0 85.0,297.0Q85.0,275.0 99.5,265.0Q114.0,255.0 130.0,255.0Z" transform="translate(13584, 793)"/>
<path d="M135.0,855.0Q122.0,855.0 116.5,849.0Q111.0,843.0 111.0,836.0Q111.0,815.0 146.0,815.0Q182.0,815.0 204.0,838.5Q226.0,862.0 226.0,896.0Q226.0,951.0 160.0,951.0Q148.0,969.0 149.0,988.5Q150.0,1008.0 162.5,1021.5Q175.0,1035.0 198.0,1035.0Q222.0,1035.0 245.5,1019.5Q269.0,1004.0 285.0,975.5Q301.0,947.0 301.0,908.0Q301.0,869.0 282.0,835.0Q263.0,801.0 228.0,780.5Q193.0,760.0 144.0,760.0Q92.0,760.0 62.5,784.0Q33.0,808.0 33.0,844.0Q33.0,874.0 52.0,896.0Q71.0,918.0 97.0,918.0Q121.0,918.0 128.0,899.0Q135.0,880.0 135.0,855.0ZM92.0,532.0L197.0,447.0L197.0,246.0Q253.0,249.0 280.5,222.5Q308.0,196.0 308.0,151.0Q308.0,133.0 300.5,109.0Q293.0,85.0 269.5,57.5Q246.0,30.0 197.0,0.0L105.0,0.0L105.0,424.0Q69.0,454.0 50.5,471.0Q32.0,488.0 26.0,497.5Q20.0,507.0 20.0,514.0Q20.0,524.0 29.5,538.0Q39.0,552.0 64.0,584.0Q89.0,616.0 135.0,680.0Q167.0,659.0 188.0,647.0Q209.0,635.0 228.5,631.0Q248.0,627.0 273.0,629.0Q273.0,604.0 255.5,580.5Q238.0,557.0 209.0,557.0Q196.0,557.0 178.5,564.0Q161.0,571.0 135.0,590.0L92.0,532.0ZM197.0,181.0L197.0,89.0Q237.0,114.0 237.0,150.0Q237.0,169.0 225.5,175.0Q214.0,181.0 197.0,181.0Z" transform="translate(14268, 793)"/>
<path d="M175.0,473.0L102.0,430.0Q78.0,453.0 60.5,478.0Q43.0,503.0 43.0,533.0Q43.0,557.0 59.0,581.0Q75.0,605.0 119.0,643.0Q139.0,660.0 156.5,672.5Q174.0,685.0 186.0,685.0Q197.0,685.0 213.5,671.0Q230.0,657.0 258.0,631.0Q274.0,616.0 287.0,606.0Q300.0,596.0 310.0,596.0Q320.0,596.0 333.5,606.5Q347.0,617.0 366.0,636.0Q389.0,657.0 405.0,670.0Q421.0,683.0 431.0,683.0Q438.0,683.0 449.5,675.5Q461.0,668.0 481.0,648.0L521.0,608.0Q547.0,582.0 591.0,585.0Q581.0,545.0 563.5,532.0Q546.0,519.0 529.0,519.0Q510.0,519.0 495.5,529.5Q481.0,540.0 469.0,553.5Q457.0,567.0 446.0,577.5Q435.0,588.0 422.0,588.0Q409.0,588.0 396.0,576.5Q383.0,565.0 368.0,552.0Q329.0,519.0 299.0,519.0Q284.0,519.0 268.5,529.0Q253.0,539.0 230.0,557.0Q208.0,574.0 196.0,581.5Q184.0,589.0 173.0,589.0Q157.0,589.0 143.0,573.0Q136.0,566.0 131.0,557.0Q126.0,548.0 126.0,536.0Q126.0,520.0 138.0,506.0Q150.0,492.0 175.0,473.0ZM190.0,0.0L98.0,0.0L98.0,316.0Q98.0,354.0 128.5,386.5Q159.0,419.0 209.5,439.0Q260.0,459.0 320.0,459.0Q382.0,459.0 432.5,438.5Q483.0,418.0 512.5,385.5Q542.0,353.0 542.0,316.0L542.0,0.0L450.0,0.0L450.0,316.0Q450.0,336.0 432.5,353.5Q415.0,371.0 386.0,381.5Q357.0,392.0 321.0,392.0Q265.0,392.0 227.5,368.5Q190.0,345.0 190.0,316.0L190.0,246.0Q246.0,249.0 273.5,222.5Q301.0,196.0 301.0,151.0Q301.0,133.0 293.5,109.0Q286.0,85.0 262.5,57.5Q239.0,30.0 190.0,0.0ZM190.0,181.0L190.0,89.0Q230.0,114.0 230.0,150.0Q230.0,169.0 218.5,175.0Q207.0,181.0 190.0,181.0Z" transform="translate(14607, 793)"/>
<path d="M149.0,558.0Q149.0,550.0 161.0,534.5Q173.0,519.0 195.0,499.0L195.0,246.0Q251.0,249.0 278.5,222.5Q306.0,196.0 306.0,151.0Q306.0,133.0 298.5,109.0Q291.0,85.0 267.5,57.5Q244.0,30.0 195.0,0.0L103.0,0.0L103.0,469.0Q54.0,519.0 54.0,542.0Q54.0,553.0 71.5,578.0Q89.0,603.0 117.0,629.0Q140.0,650.0 165.0,666.0Q190.0,682.0 206.0,682.0Q218.0,682.0 235.0,671.0Q252.0,660.0 276.0,639.0Q294.0,623.0 306.5,612.5Q319.0,602.0 320.0,602.0Q323.0,602.0 336.5,614.5Q350.0,627.0 368.0,644.0Q387.0,661.0 401.0,671.5Q415.0,682.0 431.0,682.0Q462.0,682.0 493.0,658.0Q524.0,634.0 545.5,597.0Q567.0,560.0 567.0,521.0L567.0,0.0L475.0,0.0L475.0,521.0Q475.0,548.0 455.5,569.5Q436.0,591.0 417.0,591.0Q403.0,591.0 389.5,580.0Q376.0,569.0 361.5,554.5Q347.0,540.0 331.0,529.0Q315.0,518.0 297.0,518.0Q279.0,518.0 263.0,528.5Q247.0,539.0 233.0,553.0Q219.0,567.0 207.0,577.5Q195.0,588.0 184.0,588.0Q178.0,588.0 172.0,585.0Q166.0,582.0 161.0,577.0Q149.0,567.0 149.0,558.0ZM195.0,181.0L195.0,89.0Q235.0,114.0 235.0,150.0Q235.0,169.0 223.5,175.0Q212.0,181.0 195.0,181.0Z" transform="translate(15240, 793)"/>
<path d="M-571.0,925.0Q-571.0,978.0 -533.5,1014.0Q-496.0,1050.0 -422.0,1050.0Q-310.0,1050.0 -201.0,962.0L-201.0,1099.0L-134.0,1099.0L-134.0,879.0Q-134.0,868.0 -143.5,861.0Q-153.0,854.0 -178.0,854.0L-500.0,854.0Q-571.0,854.0 -571.0,925.0ZM-500.0,917.0L-256.0,917.0Q-303.0,955.0 -344.0,970.5Q-385.0,986.0 -421.0,986.0Q-466.0,986.0 -483.0,966.0Q-500.0,946.0 -500.0,917.0Z" transform="translate(15895, 699)"/>
<path d="" transform="translate(15897, 793)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, old-permic, syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: khojki, devanagari, mahajani, hanunoo, avestan, tirhuta, saurashtra, rejang, brahmi, psalter-pahlavi, khudawadi, chakma, old-hungarian, new-tai-lue, gujarati, grantha, lepcha, gurmukhi, modi, limbu, buhid, myanmar, hanifi-rohingya, mandaic, syriac, tibetan, warang-citi, oriya, kharoshthi, sinhala, kannada, duployan, tagalog, buginese, meetei-mayek, nko, phags-pa, manichaean, tamil, cham, bengali, balinese, thaana, kaithi, javanese, takri, tai-tham, malayalam, sundanese, syloti-nagri, tagbanwa, sharada, siddham, tai-le, tai-viet, telugu, batak, yi, dogra, gunjala-gondi, pahawh-hmong, thai, tifinagh, newa, kayah-li, mongolian
 * U+2010 HYPHEN: try adding one of: lisu, coptic, kaithi, sora-sompeng, syloti-nagri, sundanese, kharoshthi, kayah-li, yi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni1783
	* uni178317B6
	* uni178317C5
	* uni178417B6
	* uni178417C5
	* uni178517B6
	* uni178517C5
	* uni178617B6
	* uni178617C5
	* uni178717B6
	* uni178717C5
	* uni1788
	* uni178817C5
	* uni1789
	* uni1789.a
	* uni178917B6
	* uni178917B6.a
	* uni178917C5
	* uni178917C5.a
	* uni178A17B6
	* uni178A17C5
	* uni178B
	* uni178B17B6
	* uni178B17C5
	* uni179017B6
	* uni179017C5
	* uni179217B6
	* uni179217C5
	* uni179417B6
	* uni179417B6.high
	* uni179417C5
	* uni179417C5.high
	* uni179517B6
	* uni179517C5
	* uni1798
	* uni179817C5
	* uni1799
	* uni179C17B6
	* uni179C17C5
	* uni179D17C5
	* uni179E
	* uni179E17B6
	* uni179E17C5
	* uni179F
	* uni179F17B6
	* uni179F17C5
	* uni17A2
	* uni17A217B6
	* uni17A217C5
	* uni17A3
	* uni17A4
	* uni17AF
	* uni17B0
	* uni17B717CD
	* uni17B717CD.r
	* uni17BE
	* uni17BF
	* uni17C0
	* uni17C0.right1
	* uni17C1
	* uni17C2
	* uni17C3
	* uni17C4
	* uni17C5
	* uni17D21789.a
	* uni17D2179E
	* uni17D2179E.low
	* uni17D2179E17B6
	* uni17D2179E17B6.low
	* uni17D2179E17C5
	* uni17D2179E17C5.low
	* uni17DA and uni17DB
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=314.0,Y=715.0 (should be at cap-height 714?)

	* parenright (U+0029): X=32.0,Y=715.0 (should be at cap-height 714?)

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

	* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=454.5,Y=715.5 (should be at cap-height 714?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0312 (U+0312): X=82.0,Y=715.0 (should be at cap-height 714?)

	* uni17A5 (U+17A5): X=189.5,Y=713.5 (should be at cap-height 714?)

	* uni17A6 (U+17A6): X=827.5,Y=-291.0 (should be at descender -293?)

	* uni17B0 (U+17B0): X=475.0,Y=-2.0 (should be at baseline 0?)

	* uni17B2 (U+17B2): X=461.5,Y=715.5 (should be at cap-height 714?)

	* uni17CA (U+17CA): X=-221.5,Y=1069.5 (should be at ascender 1069?)

	* uni17CC (U+17CC): X=-473.5,Y=1068.0 (should be at ascender 1069?)

	* uni17CF (U+17CF): X=-456.0,Y=1067.5 (should be at ascender 1069?)

	* uni17E5 (U+17E5): X=531.0,Y=716.0 (should be at cap-height 714?)

	* uni17E6 (U+17E6): X=105.5,Y=715.0 (should be at cap-height 714?)

	* uni17E9 (U+17E9): X=315.0,Y=714.5 (should be at cap-height 714?)

	* uni19E0 (U+19E0): X=637.0,Y=1.0 (should be at baseline 0?)

	* uni19E0 (U+19E0): X=545.0,Y=1.0 (should be at baseline 0?)

	* uni19E0 (U+19E0): X=545.0,Y=-295.0 (should be at descender -293?)

	* uni19E2 (U+19E2): X=394.5,Y=715.0 (should be at cap-height 714?)

	* uni19E5 (U+19E5): X=635.0,Y=1070.5 (should be at ascender 1069?)

	* uni19E5 (U+19E5): X=648.0,Y=715.0 (should be at cap-height 714?)

	* uni19EC (U+19EC): X=1094.5,Y=715.0 (should be at cap-height 714?)

	* uni19EF (U+19EF): X=1335.0,Y=1070.5 (should be at ascender 1069?)

	* uni19EF (U+19EF): X=1348.0,Y=715.0 (should be at cap-height 714?)

	* uni19F0 (U+19F0): X=635.0,Y=1.0 (should be at baseline 0?)

	* uni19F0 (U+19F0): X=543.0,Y=1.0 (should be at baseline 0?)

	* uni19F0 (U+19F0): X=543.0,Y=-295.0 (should be at descender -293?)

	* uni19F4 (U+19F4): X=228.5,Y=-0.5 (should be at baseline 0?)

	* uni19F5 (U+19F5): X=458.0,Y=-295.0 (should be at descender -293?)

	* uni19F5 (U+19F5): X=550.0,Y=-295.0 (should be at descender -293?)

	* uni19F8 (U+19F8): X=635.0,Y=1.0 (should be at baseline 0?)

	* uni19F8 (U+19F8): X=543.0,Y=1.0 (should be at baseline 0?)

	* uni19F8 (U+19F8): X=543.0,Y=-295.0 (should be at descender -293?)

	* uni19F9 (U+19F9): X=232.0,Y=1.5 (should be at baseline 0?)

	* uni19FE (U+19FE): X=928.5,Y=-0.5 (should be at baseline 0?)

	* quoteleft (U+2018): X=220.0,Y=715.0 (should be at cap-height 714?)

	* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

	* quotedblleft (U+201C): X=420.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=220.0,Y=715.0 (should be at cap-height 714?)

	* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[15] NotoSerifKhmer-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, old-permic, syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: khojki, devanagari, mahajani, hanunoo, avestan, tirhuta, saurashtra, rejang, brahmi, psalter-pahlavi, khudawadi, chakma, old-hungarian, new-tai-lue, gujarati, grantha, lepcha, gurmukhi, modi, limbu, buhid, myanmar, hanifi-rohingya, mandaic, syriac, tibetan, warang-citi, oriya, kharoshthi, sinhala, kannada, duployan, tagalog, buginese, meetei-mayek, nko, phags-pa, manichaean, tamil, cham, bengali, balinese, thaana, kaithi, javanese, takri, tai-tham, malayalam, sundanese, syloti-nagri, tagbanwa, sharada, siddham, tai-le, tai-viet, telugu, batak, yi, dogra, gunjala-gondi, pahawh-hmong, thai, tifinagh, newa, kayah-li, mongolian
 * U+2010 HYPHEN: try adding one of: lisu, coptic, kaithi, sora-sompeng, syloti-nagri, sundanese, kharoshthi, kayah-li, yi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni178117C5
	* uni1783
	* uni178317B6
	* uni178317C5
	* uni1784
	* uni178417B6
	* uni178417C5
	* uni178517B6
	* uni178517C5
	* uni178617B6
	* uni178617C5
	* uni178717B6
	* uni178717C5
	* uni1788
	* uni178817B6
	* uni178817C5
	* uni1789
	* uni1789.a
	* uni178917B6
	* uni178917B6.a
	* uni178917C5
	* uni178917C5.a
	* uni178A17B6
	* uni178A17C5
	* uni178B
	* uni178B17B6
	* uni178B17C5
	* uni178C17C5
	* uni178D
	* uni178F17C5
	* uni1790
	* uni179017B6
	* uni179017C5
	* uni1792
	* uni179217B6
	* uni179217C5
	* uni179317C5
	* uni1794
	* uni179417B6
	* uni179417B6.high
	* uni179417C5
	* uni179417C5.high
	* uni1795
	* uni179517B6
	* uni179517C5
	* uni179617C5
	* uni1798
	* uni179817B6
	* uni179817C5
	* uni1799
	* uni179917B6
	* uni179917C5
	* uni179A
	* uni179B
	* uni179C
	* uni179C17B6
	* uni179C17C5
	* uni179D
	* uni179D17B6
	* uni179D17C5
	* uni179E
	* uni179E17B6
	* uni179E17C5
	* uni179F
	* uni179F17B6
	* uni179F17C5
	* uni17A0
	* uni17A017B6
	* uni17A017C5
	* uni17A1
	* uni17A2
	* uni17A217B6
	* uni17A217C5
	* uni17A3
	* uni17A4
	* uni17AB
	* uni17AC
	* uni17AF
	* uni17B0
	* uni17B717CD
	* uni17B717CD.r
	* uni17BA
	* uni17BA.r
	* uni17BE
	* uni17BF
	* uni17BF.right1
	* uni17C0
	* uni17C0.right1
	* uni17C1
	* uni17C2
	* uni17C3
	* uni17C4
	* uni17C5
	* uni17D21783
	* uni17D21783.low
	* uni17D2178317C5
	* uni17D2178317C5.low
	* uni17D21789.a
	* uni17D2178D
	* uni17D2178D.low
	* uni17D21794
	* uni17D21794.low
	* uni17D21799
	* uni17D21799.low
	* uni17D2179D
	* uni17D2179E
	* uni17D2179E.low
	* uni17D2179E17B6
	* uni17D2179E17B6.low
	* uni17D2179E17C5
	* uni17D2179E17C5.low
	* uni17D2179F
	* uni17D2179F.low
	* uni17D2179F17C5.low
	* uni17D217A1
	* uni17D8
	* uni17DA
	* uni17DB and uni19FF
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 563 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=119.0,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=343.5,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=131.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=470.0,Y=-1.0 (should be at baseline 0?)

	* a (U+0061): X=186.5,Y=538.0 (should be at x-height 536?)

	* f (U+0066): X=309.0,Y=716.0 (should be at cap-height 714?)

	* y (U+0079): X=254.0,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=343.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=71.0,Y=2.0 (should be at baseline 0?)

	* Aring (U+00C5): X=477.0,Y=715.5 (should be at cap-height 714?)

	* germandbls (U+00DF): X=351.0,Y=715.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=136.0,Y=712.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=170.0,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=140.0,Y=712.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=254.0,Y=-2.0 (should be at baseline 0?)

	* yacute (U+00FD): X=343.0,Y=-1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=343.0,Y=-1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=343.0,Y=-1.0 (should be at baseline 0?)

	* tilde (U+02DC): X=74.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-475.0,Y=712.0 (should be at cap-height 714?)

	* uni1784 (U+1784): X=275.0,Y=712.0 (should be at cap-height 714?)

	* uni17A5 (U+17A5): X=197.5,Y=712.5 (should be at cap-height 714?)

	* uni17A7 (U+17A7): X=447.0,Y=1.0 (should be at baseline 0?)

	* uni17A8 (U+17A8): X=447.0,Y=1.0 (should be at baseline 0?)

	* uni17A9 (U+17A9): X=447.0,Y=1.0 (should be at baseline 0?)

	* uni17AA (U+17AA): X=447.0,Y=712.0 (should be at cap-height 714?)

	* uni17AA (U+17AA): X=447.0,Y=1.0 (should be at baseline 0?)

	* uni17B0 (U+17B0): X=425.5,Y=-0.5 (should be at baseline 0?)

	* uni17B0 (U+17B0): X=479.0,Y=1.0 (should be at baseline 0?)

	* uni17B1 (U+17B1): X=438.0,Y=1.0 (should be at baseline 0?)

	* uni17B3 (U+17B3): X=447.0,Y=1.0 (should be at baseline 0?)

	* uni17BD (U+17BD): X=-140.0,Y=-292.0 (should be at descender -293?)

	* uni17BD (U+17BD): X=-304.0,Y=-292.0 (should be at descender -293?)

	* uni17BF (U+17BF): X=790.0,Y=1068.0 (should be at ascender 1069?)

	* uni17CA (U+17CA): X=-212.5,Y=1069.5 (should be at ascender 1069?)

	* uni17E2 (U+17E2): X=28.0,Y=712.0 (should be at cap-height 714?)

	* uni17E5 (U+17E5): X=389.0,Y=712.0 (should be at cap-height 714?)

	* uni17E6 (U+17E6): X=54.0,Y=712.0 (should be at cap-height 714?)

	* uni17E9 (U+17E9): X=302.0,Y=714.5 (should be at cap-height 714?)

	* uni19E4 (U+19E4): X=112.0,Y=715.0 (should be at cap-height 714?)

	* uni19E6 (U+19E6): X=397.0,Y=712.0 (should be at cap-height 714?)

	* uni19E7 (U+19E7): X=640.0,Y=1071.0 (should be at ascender 1069?)

	* uni19E8 (U+19E8): X=715.0,Y=1068.0 (should be at ascender 1069?)

	* uni19E9 (U+19E9): X=510.5,Y=716.0 (should be at cap-height 714?)

	* uni19EE (U+19EE): X=823.0,Y=715.0 (should be at cap-height 714?)

	* uni19F0 (U+19F0): X=707.0,Y=1068.0 (should be at ascender 1069?)

	* uni19F5 (U+19F5): X=189.0,Y=0.5 (should be at baseline 0?)

	* uni19F5 (U+19F5): X=585.0,Y=-291.0 (should be at descender -293?)

	* ygrave (U+1EF3): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=343.0,Y=-1.0 (should be at baseline 0?)

	* quotesinglbase (U+201A): X=119.0,Y=-1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=325.0,Y=-1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=119.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<419.0,336.0>--<262.0,337.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] NotoSerifKhmer-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, old-permic, syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200D ZERO WIDTH JOINER: try adding one of: khojki, devanagari, mahajani, hanunoo, avestan, tirhuta, saurashtra, rejang, brahmi, psalter-pahlavi, khudawadi, chakma, old-hungarian, new-tai-lue, gujarati, grantha, lepcha, gurmukhi, modi, limbu, buhid, myanmar, hanifi-rohingya, mandaic, syriac, tibetan, warang-citi, oriya, kharoshthi, sinhala, kannada, duployan, tagalog, buginese, meetei-mayek, nko, phags-pa, manichaean, tamil, cham, bengali, balinese, thaana, kaithi, javanese, takri, tai-tham, malayalam, sundanese, syloti-nagri, tagbanwa, sharada, siddham, tai-le, tai-viet, telugu, batak, yi, dogra, gunjala-gondi, pahawh-hmong, thai, tifinagh, newa, kayah-li, mongolian
 * U+2010 HYPHEN: try adding one of: lisu, coptic, kaithi, sora-sompeng, syloti-nagri, sundanese, kharoshthi, kayah-li, yi, cham

Or you can add the above codepoints to one of the subsets supported by the font: `khmer`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1789
	* uni1789.a
	* uni178917B6
	* uni178917B6.a
	* uni178917C5 and uni178917C5.a
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=99.5,Y=-1.5 (should be at baseline 0?)

	* semicolon (U+003B): X=111.5,Y=-1.5 (should be at baseline 0?)

	* C (U+0043): X=407.0,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=477.5,Y=-1.5 (should be at baseline 0?)

	* b (U+0062): X=114.0,Y=715.5 (should be at cap-height 714?)

	* d (U+0064): X=428.0,Y=715.5 (should be at cap-height 714?)

	* g (U+0067): X=394.0,Y=537.5 (should be at x-height 536?)

	* h (U+0068): X=114.0,Y=715.5 (should be at cap-height 714?)

	* k (U+006B): X=114.0,Y=715.5 (should be at cap-height 714?)

	* l (U+006C): X=110.0,Y=715.5 (should be at cap-height 714?)

	* t (U+0074): X=53.5,Y=536.5 (should be at x-height 536?)

	* sterling (U+00A3): X=362.5,Y=-1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=464.5,Y=-0.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=407.0,Y=1.5 (should be at baseline 0?)

	* Oslash (U+00D8): X=437.5,Y=713.5 (should be at cap-height 714?)

	* thorn (U+00FE): X=117.5,Y=716.0 (should be at cap-height 714?)

	* Cacute (U+0106): X=407.0,Y=1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=407.0,Y=1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=407.0,Y=1.5 (should be at baseline 0?)

	* dcaron (U+010F): X=428.0,Y=715.5 (should be at cap-height 714?)

	* dcroat (U+0111): X=427.5,Y=715.5 (should be at cap-height 714?)

	* Gbreve (U+011E): X=477.5,Y=-1.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=477.5,Y=-1.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=477.5,Y=-1.5 (should be at baseline 0?)

	* hbar (U+0127): X=113.5,Y=715.5 (should be at cap-height 714?)

	* uni0137 (U+0137): X=114.0,Y=715.5 (should be at cap-height 714?)

	* lacute (U+013A): X=110.0,Y=715.5 (should be at cap-height 714?)

	* uni013C (U+013C): X=110.0,Y=715.5 (should be at cap-height 714?)

	* lcaron (U+013E): X=110.0,Y=715.5 (should be at cap-height 714?)

	* Eng (U+014A): X=566.0,Y=1.0 (should be at baseline 0?)

	* uni178C (U+178C): X=472.0,Y=-1.0 (should be at baseline 0?)

	* uni17A6 (U+17A6): X=699.0,Y=-291.0 (should be at descender -293?)

	* uni17A7 (U+17A7): X=500.5,Y=1.0 (should be at baseline 0?)

	* uni17A8 (U+17A8): X=500.5,Y=1.0 (should be at baseline 0?)

	* uni17A9 (U+17A9): X=500.5,Y=1.0 (should be at baseline 0?)

	* uni17AA (U+17AA): X=500.5,Y=1.0 (should be at baseline 0?)

	* uni17B1 (U+17B1): X=127.0,Y=713.0 (should be at cap-height 714?)

	* uni17B1 (U+17B1): X=471.5,Y=1.0 (should be at baseline 0?)

	* uni17B3 (U+17B3): X=129.0,Y=713.0 (should be at cap-height 714?)

	* uni17B3 (U+17B3): X=500.5,Y=1.0 (should be at baseline 0?)

	* uni17BF (U+17BF): X=966.0,Y=-291.0 (should be at descender -293?)

	* uni17C0 (U+17C0): X=952.0,Y=-291.0 (should be at descender -293?)

	* uni17CC (U+17CC): X=-144.0,Y=1067.0 (should be at ascender 1069?)

	* uni17CC (U+17CC): X=-392.0,Y=1071.0 (should be at ascender 1069?)

	* uni17CF (U+17CF): X=-198.0,Y=1070.0 (should be at ascender 1069?)

	* uni17E2 (U+17E2): X=85.0,Y=713.0 (should be at cap-height 714?)

	* uni17E9 (U+17E9): X=303.0,Y=713.0 (should be at cap-height 714?)

	* uni17E9 (U+17E9): X=466.0,Y=714.5 (should be at cap-height 714?)

	* uni19E0 (U+19E0): X=571.0,Y=-294.0 (should be at descender -293?)

	* uni19E1 (U+19E1): X=331.0,Y=716.0 (should be at cap-height 714?)

	* uni19E7 (U+19E7): X=661.0,Y=1071.0 (should be at ascender 1069?)

	* uni19E8 (U+19E8): X=543.0,Y=713.0 (should be at cap-height 714?)

	* uni19E9 (U+19E9): X=549.0,Y=1070.0 (should be at ascender 1069?)

	* uni19EA (U+19EA): X=331.0,Y=716.0 (should be at cap-height 714?)

	* uni19EB (U+19EB): X=1064.0,Y=716.0 (should be at cap-height 714?)

	* uni19EB (U+19EB): X=331.0,Y=716.0 (should be at cap-height 714?)

	* uni19EC (U+19EC): X=331.0,Y=716.0 (should be at cap-height 714?)

	* uni19ED (U+19ED): X=331.0,Y=716.0 (should be at cap-height 714?)

	* uni19EE (U+19EE): X=331.0,Y=716.0 (should be at cap-height 714?)

	* uni19EF (U+19EF): X=331.0,Y=716.0 (should be at cap-height 714?)

	* uni19F0 (U+19F0): X=543.0,Y=713.0 (should be at cap-height 714?)

	* uni19F0 (U+19F0): X=543.0,Y=-294.0 (should be at descender -293?)

	* uni19F3 (U+19F3): X=230.0,Y=-294.5 (should be at descender -293?)

	* uni19F5 (U+19F5): X=470.0,Y=-295.0 (should be at descender -293?)

	* uni19F7 (U+19F7): X=230.0,Y=-294.5 (should be at descender -293?)

	* uni19F8 (U+19F8): X=543.0,Y=-294.0 (should be at descender -293?)

	* uni19FD (U+19FD): X=916.0,Y=-294.5 (should be at descender -293?)

	* uni19FF (U+19FF): X=1150.0,Y=-295.0 (should be at descender -293?)

	* Euro (U+20AC): X=406.0,Y=0.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<385.5,450.5>-<412.0,431.0>-<428.0,400.0>>/B<<428.0,400.0>-<403.0,480.0>-<371.5,537.5>> = 9.945547575071476

	* sterling (U+00A3): B<<192.0,89.0>-<173.0,58.0>-<145.0,40.0>>/L<<145.0,40.0>--<149.0,42.0>> = 6.170175095029526 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<149.0,714.0>--<146.0,167.0>>

	* exclamdown (U+00A1): L<<123.0,-177.0>--<126.0,370.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 19 | 115 | 1045 | 55 | 871 | 0 |
| 0% | 1% | 5% | 50% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
