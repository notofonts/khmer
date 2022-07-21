## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerifKhmer/googlefonts/ttf', 'fonts/NotoSerifKhmer/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[14] NotoSerifKhmer-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni179417B6
	* uni17C0.right3
	* uni179217B6
	* uni179517C5
	* uni178F
	* uni179D
	* uni17A217B6
	* uni1789.a
	* uni1786
	* uni179F and 154 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 52 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* y (U+0079): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yacute (U+00FD): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ycircumflex (U+0177): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ydieresis (U+00FF): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 

	* And ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoSerifKhmer-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni179417B6
	* uni179217B6
	* uni179517C5
	* uni178F
	* uni179D
	* uni17A217B6
	* uni1789.a
	* uni1786
	* uni179F
	* uni17A3 and 136 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[14] NotoSerifKhmer-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni179417B6
	* uni17C0.right3
	* uni179217B6
	* uni179517C5
	* uni178F
	* uni179D
	* uni17A217B6
	* uni1789.a
	* uni1786
	* uni179F and 147 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 57 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* y (U+0079): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* yacute (U+00FD): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ycircumflex (U+0177): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ydieresis (U+00FF): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124 

	* And ygrave (U+1EF3): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<444.0,335.0>--<285.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerifKhmer-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni17A217B6
	* uni1789.a
	* uni17A3
	* uni178917C5
	* uni17A4
	* uni178917B6.a
	* uni17A2
	* uni178917C5.a
	* uni17A217C5
	* uni178917B6 and uni1789
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 40 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSerifKhmer-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni17A217B6
	* uni1789.a
	* uni17A3
	* uni178917C5
	* uni179F17C5
	* uni17A4
	* uni178917B6.a
	* uni17C0
	* uni17A2
	* uni178317C5 and 13 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* question (U+003F): L<<200.0,201.0>--<199.0,346.0>> 

	* And questiondown (U+00BF): L<<203.0,215.0>--<204.0,333.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSerifKhmer-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni179417B6
	* uni179217B6
	* uni179517C5
	* uni179D
	* uni17A217B6
	* uni1789.a
	* uni179F
	* uni17A3
	* uni178917C5
	* uni17BF.right1 and 81 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni17B0 (U+17B0): L<<583.0,-68.0>--<583.0,-68.0>> -> L<<583.0,-68.0>--<583.0,-68.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSerifKhmer-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
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

<li>Shaping did not match: <span class="tf">ាំ</span> (fontdiff-khm-sample-20161201.html)</li>


<pre>Expected: uni25CC=0+635|uni17B6=0+306|uni17C6=0+0</pre>



<pre>Got     : uni25CC=0+635|uni17B6=0+306|uni17C6=0@85,-114+0</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 941 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M316.0,462.0Q306.0,462.0 299.0,469.0Q292.0,476.0 292.0,486.0Q292.0,496.0 299.0,503.0Q306.0,510.0 316.0,510.0Q326.0,510.0 333.0,503.0Q340.0,496.0 340.0,486.0Q340.0,476.0 333.0,469.0Q326.0,462.0 316.0,462.0ZM219.0,438.0Q209.0,438.0 202.0,445.0Q195.0,452.0 195.0,462.0Q195.0,472.0 202.0,479.0Q209.0,486.0 219.0,486.0Q229.0,486.0 236.0,479.0Q243.0,472.0 243.0,462.0Q243.0,452.0 236.0,445.0Q229.0,438.0 219.0,438.0ZM413.0,438.0Q403.0,438.0 396.0,445.0Q389.0,452.0 389.0,462.0Q389.0,472.0 396.0,479.0Q403.0,486.0 413.0,486.0Q423.0,486.0 430.0,479.0Q437.0,472.0 437.0,462.0Q437.0,452.0 430.0,445.0Q423.0,438.0 413.0,438.0ZM148.0,368.0Q138.0,368.0 131.0,375.0Q124.0,382.0 124.0,392.0Q124.0,402.0 131.0,409.0Q138.0,416.0 148.0,416.0Q158.0,416.0 165.0,409.0Q172.0,402.0 172.0,392.0Q172.0,382.0 165.0,375.0Q158.0,368.0 148.0,368.0ZM483.0,366.0Q473.0,366.0 466.0,373.0Q459.0,380.0 459.0,390.0Q459.0,400.0 466.0,407.0Q473.0,414.0 483.0,414.0Q493.0,414.0 500.0,407.0Q507.0,400.0 507.0,390.0Q507.0,380.0 500.0,373.0Q493.0,366.0 483.0,366.0ZM122.0,267.0Q112.0,267.0 105.0,274.0Q98.0,281.0 98.0,291.0Q98.0,301.0 105.0,308.0Q112.0,315.0 122.0,315.0Q132.0,315.0 139.0,308.0Q146.0,301.0 146.0,291.0Q146.0,281.0 139.0,274.0Q132.0,267.0 122.0,267.0ZM513.0,267.0Q503.0,267.0 496.0,274.0Q489.0,281.0 489.0,291.0Q489.0,301.0 496.0,308.0Q503.0,315.0 513.0,315.0Q523.0,315.0 530.0,308.0Q537.0,301.0 537.0,291.0Q537.0,281.0 530.0,274.0Q523.0,267.0 513.0,267.0ZM485.0,173.0Q475.0,173.0 468.0,180.0Q461.0,187.0 461.0,197.0Q461.0,207.0 468.0,214.0Q475.0,221.0 485.0,221.0Q495.0,221.0 502.0,214.0Q509.0,207.0 509.0,197.0Q509.0,187.0 502.0,180.0Q495.0,173.0 485.0,173.0ZM146.0,172.0Q136.0,172.0 129.0,179.0Q122.0,186.0 122.0,196.0Q122.0,206.0 129.0,213.0Q136.0,220.0 146.0,220.0Q156.0,220.0 163.0,213.0Q170.0,206.0 170.0,196.0Q170.0,186.0 163.0,179.0Q156.0,172.0 146.0,172.0ZM414.0,101.0Q404.0,101.0 397.0,108.0Q390.0,115.0 390.0,125.0Q390.0,135.0 397.0,142.0Q404.0,149.0 414.0,149.0Q424.0,149.0 431.0,142.0Q438.0,135.0 438.0,125.0Q438.0,115.0 431.0,108.0Q424.0,101.0 414.0,101.0ZM219.0,100.0Q209.0,100.0 202.0,107.0Q195.0,114.0 195.0,124.0Q195.0,134.0 202.0,141.0Q209.0,148.0 219.0,148.0Q229.0,148.0 236.0,141.0Q243.0,134.0 243.0,124.0Q243.0,114.0 236.0,107.0Q229.0,100.0 219.0,100.0ZM316.0,73.0Q306.0,73.0 299.0,80.0Q292.0,87.0 292.0,97.0Q292.0,107.0 299.0,114.0Q306.0,121.0 316.0,121.0Q326.0,121.0 333.0,114.0Q340.0,107.0 340.0,97.0Q340.0,87.0 333.0,80.0Q326.0,73.0 316.0,73.0Z"  transform="translate(0, 793)"/>
<path d="M-98.0,562.0Q-112.0,571.0 -118.5,583.5Q-125.0,596.0 -125.0,607.0Q-125.0,630.0 -94.0,651.0Q-73.0,665.0 -49.0,673.5Q-25.0,682.0 -3.0,682.0Q41.0,682.0 82.0,650.0L176.0,576.0Q214.0,547.0 214.0,501.0L214.0,0.0L122.0,0.0L122.0,507.0L23.0,586.0Q-2.0,607.0 -20.0,607.0Q-30.0,607.0 -45.5,598.5Q-61.0,590.0 -98.0,562.0Z"  transform="translate(635, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z"  transform="translate(1026, 679)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 941 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M316.0,462.0Q306.0,462.0 299.0,469.0Q292.0,476.0 292.0,486.0Q292.0,496.0 299.0,503.0Q306.0,510.0 316.0,510.0Q326.0,510.0 333.0,503.0Q340.0,496.0 340.0,486.0Q340.0,476.0 333.0,469.0Q326.0,462.0 316.0,462.0ZM219.0,438.0Q209.0,438.0 202.0,445.0Q195.0,452.0 195.0,462.0Q195.0,472.0 202.0,479.0Q209.0,486.0 219.0,486.0Q229.0,486.0 236.0,479.0Q243.0,472.0 243.0,462.0Q243.0,452.0 236.0,445.0Q229.0,438.0 219.0,438.0ZM413.0,438.0Q403.0,438.0 396.0,445.0Q389.0,452.0 389.0,462.0Q389.0,472.0 396.0,479.0Q403.0,486.0 413.0,486.0Q423.0,486.0 430.0,479.0Q437.0,472.0 437.0,462.0Q437.0,452.0 430.0,445.0Q423.0,438.0 413.0,438.0ZM148.0,368.0Q138.0,368.0 131.0,375.0Q124.0,382.0 124.0,392.0Q124.0,402.0 131.0,409.0Q138.0,416.0 148.0,416.0Q158.0,416.0 165.0,409.0Q172.0,402.0 172.0,392.0Q172.0,382.0 165.0,375.0Q158.0,368.0 148.0,368.0ZM483.0,366.0Q473.0,366.0 466.0,373.0Q459.0,380.0 459.0,390.0Q459.0,400.0 466.0,407.0Q473.0,414.0 483.0,414.0Q493.0,414.0 500.0,407.0Q507.0,400.0 507.0,390.0Q507.0,380.0 500.0,373.0Q493.0,366.0 483.0,366.0ZM122.0,267.0Q112.0,267.0 105.0,274.0Q98.0,281.0 98.0,291.0Q98.0,301.0 105.0,308.0Q112.0,315.0 122.0,315.0Q132.0,315.0 139.0,308.0Q146.0,301.0 146.0,291.0Q146.0,281.0 139.0,274.0Q132.0,267.0 122.0,267.0ZM513.0,267.0Q503.0,267.0 496.0,274.0Q489.0,281.0 489.0,291.0Q489.0,301.0 496.0,308.0Q503.0,315.0 513.0,315.0Q523.0,315.0 530.0,308.0Q537.0,301.0 537.0,291.0Q537.0,281.0 530.0,274.0Q523.0,267.0 513.0,267.0ZM485.0,173.0Q475.0,173.0 468.0,180.0Q461.0,187.0 461.0,197.0Q461.0,207.0 468.0,214.0Q475.0,221.0 485.0,221.0Q495.0,221.0 502.0,214.0Q509.0,207.0 509.0,197.0Q509.0,187.0 502.0,180.0Q495.0,173.0 485.0,173.0ZM146.0,172.0Q136.0,172.0 129.0,179.0Q122.0,186.0 122.0,196.0Q122.0,206.0 129.0,213.0Q136.0,220.0 146.0,220.0Q156.0,220.0 163.0,213.0Q170.0,206.0 170.0,196.0Q170.0,186.0 163.0,179.0Q156.0,172.0 146.0,172.0ZM414.0,101.0Q404.0,101.0 397.0,108.0Q390.0,115.0 390.0,125.0Q390.0,135.0 397.0,142.0Q404.0,149.0 414.0,149.0Q424.0,149.0 431.0,142.0Q438.0,135.0 438.0,125.0Q438.0,115.0 431.0,108.0Q424.0,101.0 414.0,101.0ZM219.0,100.0Q209.0,100.0 202.0,107.0Q195.0,114.0 195.0,124.0Q195.0,134.0 202.0,141.0Q209.0,148.0 219.0,148.0Q229.0,148.0 236.0,141.0Q243.0,134.0 243.0,124.0Q243.0,114.0 236.0,107.0Q229.0,100.0 219.0,100.0ZM316.0,73.0Q306.0,73.0 299.0,80.0Q292.0,87.0 292.0,97.0Q292.0,107.0 299.0,114.0Q306.0,121.0 316.0,121.0Q326.0,121.0 333.0,114.0Q340.0,107.0 340.0,97.0Q340.0,87.0 333.0,80.0Q326.0,73.0 316.0,73.0Z"  transform="translate(0, 793)"/>
<path d="M-98.0,562.0Q-112.0,571.0 -118.5,583.5Q-125.0,596.0 -125.0,607.0Q-125.0,630.0 -94.0,651.0Q-73.0,665.0 -49.0,673.5Q-25.0,682.0 -3.0,682.0Q41.0,682.0 82.0,650.0L176.0,576.0Q214.0,547.0 214.0,501.0L214.0,0.0L122.0,0.0L122.0,507.0L23.0,586.0Q-2.0,607.0 -20.0,607.0Q-30.0,607.0 -45.5,598.5Q-61.0,590.0 -98.0,562.0Z"  transform="translate(635, 793)"/>
<path d="M-353.0,854.0Q-384.0,854.0 -409.5,869.5Q-435.0,885.0 -450.5,910.5Q-466.0,936.0 -466.0,967.0Q-466.0,998.0 -450.5,1023.5Q-435.0,1049.0 -409.5,1064.5Q-384.0,1080.0 -353.0,1080.0Q-322.0,1080.0 -296.5,1064.5Q-271.0,1049.0 -255.5,1023.5Q-240.0,998.0 -240.0,967.0Q-240.0,936.0 -255.5,910.5Q-271.0,885.0 -296.5,869.5Q-322.0,854.0 -353.0,854.0ZM-354.0,915.0Q-332.0,915.0 -316.5,930.0Q-301.0,945.0 -301.0,967.0Q-301.0,989.0 -316.0,1005.0Q-331.0,1021.0 -354.0,1021.0Q-376.0,1021.0 -391.0,1005.5Q-406.0,990.0 -406.0,967.0Q-406.0,945.0 -390.5,930.0Q-375.0,915.0 -354.0,915.0Z"  transform="translate(941, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(២១-១)+៤</span> (fontdiff-khm-sample-20161201.html)</li>


<pre>Expected: parenleft=0+346|uni17E2=1+765|uni17E1=2+683|hyphen=3+310|uni17E1=4+683|parenright=5+346|.notdef=6+634|uni17E4=7+758</pre>



<pre>Got     : parenleft=0+346|uni17E2=1+765|uni17E1=2+683|hyphen=3+310|uni17E1=4+683|parenright=5+346|plus=6+559|uni17E4=7+758</pre>



<pre>                                                                                                  ^^^^^^^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4450 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M314.0,-128.0Q222.0,-91.0 165.5,-33.5Q109.0,24.0 83.0,110.5Q57.0,197.0 57.0,317.0Q57.0,437.0 83.0,522.5Q109.0,608.0 165.5,666.0Q222.0,724.0 314.0,760.0L314.0,715.0Q245.0,674.0 212.5,611.0Q180.0,548.0 170.5,472.5Q161.0,397.0 161.0,317.0Q161.0,238.0 170.5,162.0Q180.0,86.0 212.5,23.0Q245.0,-40.0 314.0,-82.0L314.0,-128.0Z"  transform="translate(0, 793)"/>
<path d="M545.0,682.0Q556.0,682.0 575.5,670.5Q595.0,659.0 615.5,639.0Q636.0,619.0 650.5,592.5Q665.0,566.0 665.0,536.0L665.0,195.0Q665.0,140.0 634.5,95.5Q604.0,51.0 544.0,25.5Q484.0,0.0 396.0,0.0L372.0,0.0Q284.0,0.0 224.0,25.5Q164.0,51.0 133.5,95.5Q103.0,140.0 103.0,195.0L103.0,618.0Q103.0,637.0 95.0,657.0Q87.0,677.0 71.0,691.0Q55.0,705.0 30.0,705.0Q30.0,737.0 52.0,758.5Q74.0,780.0 105.0,780.0Q147.0,780.0 171.0,740.0Q195.0,700.0 195.0,638.0L195.0,195.0Q195.0,133.0 240.5,100.0Q286.0,67.0 372.0,67.0L396.0,67.0Q482.0,67.0 527.5,100.0Q573.0,133.0 573.0,195.0L573.0,536.0Q573.0,558.0 565.0,575.5Q557.0,593.0 544.0,593.0Q526.0,593.0 470.0,537.0Q441.0,566.0 425.0,579.5Q409.0,593.0 398.0,593.0Q384.0,593.0 375.0,573.0Q366.0,553.0 366.0,536.0L366.0,447.0Q422.0,447.0 449.5,420.0Q477.0,393.0 477.0,352.0Q477.0,336.0 469.5,317.0Q462.0,298.0 438.5,274.5Q415.0,251.0 366.0,221.0L274.0,221.0L274.0,536.0Q274.0,566.0 288.5,592.5Q303.0,619.0 323.0,639.0Q343.0,659.0 363.0,670.5Q383.0,682.0 393.0,682.0Q405.0,682.0 426.5,665.5Q448.0,649.0 470.0,617.0Q493.0,649.0 513.0,665.5Q533.0,682.0 545.0,682.0ZM406.0,353.0Q406.0,368.0 394.5,375.0Q383.0,382.0 366.0,382.0L366.0,310.0Q386.0,322.0 396.0,331.0Q406.0,340.0 406.0,353.0Z"  transform="translate(346, 793)"/>
<path d="M583.0,389.0Q583.0,248.0 544.0,162.5Q505.0,77.0 429.0,38.5Q353.0,0.0 241.0,0.0L192.0,0.0L192.0,67.0L241.0,67.0Q335.0,67.0 389.5,97.0Q444.0,127.0 467.5,197.5Q491.0,268.0 491.0,389.0Q491.0,478.0 468.5,527.0Q446.0,576.0 408.0,595.5Q370.0,615.0 322.0,615.0Q243.0,615.0 202.5,572.0Q162.0,529.0 162.0,456.0Q162.0,402.0 183.0,366.5Q204.0,331.0 248.0,331.0Q292.0,331.0 305.0,365.0Q286.0,368.0 275.5,382.5Q265.0,397.0 265.0,416.0Q265.0,442.0 282.5,458.5Q300.0,475.0 328.0,475.0Q387.0,475.0 387.0,402.0Q387.0,365.0 371.5,333.5Q356.0,302.0 323.5,283.0Q291.0,264.0 241.0,264.0Q165.0,264.0 117.5,313.5Q70.0,363.0 70.0,447.0Q70.0,509.0 99.5,562.5Q129.0,616.0 185.5,649.0Q242.0,682.0 321.0,682.0Q400.0,682.0 458.5,651.5Q517.0,621.0 550.0,556.5Q583.0,492.0 583.0,389.0Z"  transform="translate(1111, 793)"/>
<path d="M25.0,235.0L25.0,310.0L285.0,310.0L285.0,235.0L25.0,235.0Z"  transform="translate(1794, 793)"/>
<path d="M583.0,389.0Q583.0,248.0 544.0,162.5Q505.0,77.0 429.0,38.5Q353.0,0.0 241.0,0.0L192.0,0.0L192.0,67.0L241.0,67.0Q335.0,67.0 389.5,97.0Q444.0,127.0 467.5,197.5Q491.0,268.0 491.0,389.0Q491.0,478.0 468.5,527.0Q446.0,576.0 408.0,595.5Q370.0,615.0 322.0,615.0Q243.0,615.0 202.5,572.0Q162.0,529.0 162.0,456.0Q162.0,402.0 183.0,366.5Q204.0,331.0 248.0,331.0Q292.0,331.0 305.0,365.0Q286.0,368.0 275.5,382.5Q265.0,397.0 265.0,416.0Q265.0,442.0 282.5,458.5Q300.0,475.0 328.0,475.0Q387.0,475.0 387.0,402.0Q387.0,365.0 371.5,333.5Q356.0,302.0 323.5,283.0Q291.0,264.0 241.0,264.0Q165.0,264.0 117.5,313.5Q70.0,363.0 70.0,447.0Q70.0,509.0 99.5,562.5Q129.0,616.0 185.5,649.0Q242.0,682.0 321.0,682.0Q400.0,682.0 458.5,651.5Q517.0,621.0 550.0,556.5Q583.0,492.0 583.0,389.0Z"  transform="translate(2104, 793)"/>
<path d="M32.0,-128.0L32.0,-82.0Q101.0,-40.0 133.5,23.0Q166.0,86.0 175.5,162.0Q185.0,238.0 185.0,317.0Q185.0,397.0 175.5,472.5Q166.0,548.0 133.5,611.0Q101.0,674.0 32.0,715.0L32.0,760.0Q124.0,724.0 180.5,666.0Q237.0,608.0 263.0,522.5Q289.0,437.0 289.0,317.0Q289.0,197.0 263.0,110.5Q237.0,24.0 180.5,-33.5Q124.0,-91.0 32.0,-128.0Z"  transform="translate(2787, 793)"/>
<path d="M249.0,143.0L249.0,328.0L65.0,328.0L65.0,387.0L249.0,387.0L249.0,572.0L309.0,572.0L309.0,387.0L494.0,387.0L494.0,328.0L309.0,328.0L309.0,143.0L249.0,143.0Z"  transform="translate(3133, 793)"/>
<path d="M110.0,146.0L110.0,379.0Q110.0,462.0 155.0,517.0Q200.0,572.0 288.0,600.0L426.0,645.0Q531.0,680.0 531.0,722.0Q531.0,738.0 519.5,745.5Q508.0,753.0 482.0,753.0Q482.0,780.0 499.5,800.0Q517.0,820.0 551.0,820.0Q586.0,820.0 604.5,796.5Q623.0,773.0 623.0,735.0Q623.0,682.0 581.0,645.5Q539.0,609.0 456.0,583.0L307.0,536.0Q255.0,520.0 228.5,479.5Q202.0,439.0 202.0,379.0L202.0,146.0Q202.0,127.0 219.5,109.0Q237.0,91.0 266.5,79.0Q296.0,67.0 330.0,67.0L531.0,67.0Q494.0,123.0 476.0,162.0Q458.0,201.0 458.0,220.0L458.0,397.0Q458.0,438.0 483.0,463.0Q508.0,488.0 553.0,488.0Q608.0,488.0 633.0,453.5Q658.0,419.0 658.0,371.0Q658.0,333.0 642.0,308.5Q626.0,284.0 601.0,272.5Q576.0,261.0 550.0,261.0L550.0,220.0Q550.0,170.0 586.0,116.0L623.0,61.0L623.0,0.0L330.0,0.0Q265.0,0.0 215.0,23.0Q165.0,46.0 137.5,80.0Q110.0,114.0 110.0,146.0ZM550.0,322.0Q577.0,322.0 588.5,341.0Q600.0,360.0 600.0,377.0Q600.0,392.0 589.5,411.0Q579.0,430.0 550.0,436.0L550.0,322.0Z"  transform="translate(3692, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4525 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M314.0,-128.0Q222.0,-91.0 165.5,-33.5Q109.0,24.0 83.0,110.5Q57.0,197.0 57.0,317.0Q57.0,437.0 83.0,522.5Q109.0,608.0 165.5,666.0Q222.0,724.0 314.0,760.0L314.0,715.0Q245.0,674.0 212.5,611.0Q180.0,548.0 170.5,472.5Q161.0,397.0 161.0,317.0Q161.0,238.0 170.5,162.0Q180.0,86.0 212.5,23.0Q245.0,-40.0 314.0,-82.0L314.0,-128.0Z"  transform="translate(0, 793)"/>
<path d="M545.0,682.0Q556.0,682.0 575.5,670.5Q595.0,659.0 615.5,639.0Q636.0,619.0 650.5,592.5Q665.0,566.0 665.0,536.0L665.0,195.0Q665.0,140.0 634.5,95.5Q604.0,51.0 544.0,25.5Q484.0,0.0 396.0,0.0L372.0,0.0Q284.0,0.0 224.0,25.5Q164.0,51.0 133.5,95.5Q103.0,140.0 103.0,195.0L103.0,618.0Q103.0,637.0 95.0,657.0Q87.0,677.0 71.0,691.0Q55.0,705.0 30.0,705.0Q30.0,737.0 52.0,758.5Q74.0,780.0 105.0,780.0Q147.0,780.0 171.0,740.0Q195.0,700.0 195.0,638.0L195.0,195.0Q195.0,133.0 240.5,100.0Q286.0,67.0 372.0,67.0L396.0,67.0Q482.0,67.0 527.5,100.0Q573.0,133.0 573.0,195.0L573.0,536.0Q573.0,558.0 565.0,575.5Q557.0,593.0 544.0,593.0Q526.0,593.0 470.0,537.0Q441.0,566.0 425.0,579.5Q409.0,593.0 398.0,593.0Q384.0,593.0 375.0,573.0Q366.0,553.0 366.0,536.0L366.0,447.0Q422.0,447.0 449.5,420.0Q477.0,393.0 477.0,352.0Q477.0,336.0 469.5,317.0Q462.0,298.0 438.5,274.5Q415.0,251.0 366.0,221.0L274.0,221.0L274.0,536.0Q274.0,566.0 288.5,592.5Q303.0,619.0 323.0,639.0Q343.0,659.0 363.0,670.5Q383.0,682.0 393.0,682.0Q405.0,682.0 426.5,665.5Q448.0,649.0 470.0,617.0Q493.0,649.0 513.0,665.5Q533.0,682.0 545.0,682.0ZM406.0,353.0Q406.0,368.0 394.5,375.0Q383.0,382.0 366.0,382.0L366.0,310.0Q386.0,322.0 396.0,331.0Q406.0,340.0 406.0,353.0Z"  transform="translate(346, 793)"/>
<path d="M583.0,389.0Q583.0,248.0 544.0,162.5Q505.0,77.0 429.0,38.5Q353.0,0.0 241.0,0.0L192.0,0.0L192.0,67.0L241.0,67.0Q335.0,67.0 389.5,97.0Q444.0,127.0 467.5,197.5Q491.0,268.0 491.0,389.0Q491.0,478.0 468.5,527.0Q446.0,576.0 408.0,595.5Q370.0,615.0 322.0,615.0Q243.0,615.0 202.5,572.0Q162.0,529.0 162.0,456.0Q162.0,402.0 183.0,366.5Q204.0,331.0 248.0,331.0Q292.0,331.0 305.0,365.0Q286.0,368.0 275.5,382.5Q265.0,397.0 265.0,416.0Q265.0,442.0 282.5,458.5Q300.0,475.0 328.0,475.0Q387.0,475.0 387.0,402.0Q387.0,365.0 371.5,333.5Q356.0,302.0 323.5,283.0Q291.0,264.0 241.0,264.0Q165.0,264.0 117.5,313.5Q70.0,363.0 70.0,447.0Q70.0,509.0 99.5,562.5Q129.0,616.0 185.5,649.0Q242.0,682.0 321.0,682.0Q400.0,682.0 458.5,651.5Q517.0,621.0 550.0,556.5Q583.0,492.0 583.0,389.0Z"  transform="translate(1111, 793)"/>
<path d="M25.0,235.0L25.0,310.0L285.0,310.0L285.0,235.0L25.0,235.0Z"  transform="translate(1794, 793)"/>
<path d="M583.0,389.0Q583.0,248.0 544.0,162.5Q505.0,77.0 429.0,38.5Q353.0,0.0 241.0,0.0L192.0,0.0L192.0,67.0L241.0,67.0Q335.0,67.0 389.5,97.0Q444.0,127.0 467.5,197.5Q491.0,268.0 491.0,389.0Q491.0,478.0 468.5,527.0Q446.0,576.0 408.0,595.5Q370.0,615.0 322.0,615.0Q243.0,615.0 202.5,572.0Q162.0,529.0 162.0,456.0Q162.0,402.0 183.0,366.5Q204.0,331.0 248.0,331.0Q292.0,331.0 305.0,365.0Q286.0,368.0 275.5,382.5Q265.0,397.0 265.0,416.0Q265.0,442.0 282.5,458.5Q300.0,475.0 328.0,475.0Q387.0,475.0 387.0,402.0Q387.0,365.0 371.5,333.5Q356.0,302.0 323.5,283.0Q291.0,264.0 241.0,264.0Q165.0,264.0 117.5,313.5Q70.0,363.0 70.0,447.0Q70.0,509.0 99.5,562.5Q129.0,616.0 185.5,649.0Q242.0,682.0 321.0,682.0Q400.0,682.0 458.5,651.5Q517.0,621.0 550.0,556.5Q583.0,492.0 583.0,389.0Z"  transform="translate(2104, 793)"/>
<path d="M32.0,-128.0L32.0,-82.0Q101.0,-40.0 133.5,23.0Q166.0,86.0 175.5,162.0Q185.0,238.0 185.0,317.0Q185.0,397.0 175.5,472.5Q166.0,548.0 133.5,611.0Q101.0,674.0 32.0,715.0L32.0,760.0Q124.0,724.0 180.5,666.0Q237.0,608.0 263.0,522.5Q289.0,437.0 289.0,317.0Q289.0,197.0 263.0,110.5Q237.0,24.0 180.5,-33.5Q124.0,-91.0 32.0,-128.0Z"  transform="translate(2787, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(3133, 793)"/>
<path d="M110.0,146.0L110.0,379.0Q110.0,462.0 155.0,517.0Q200.0,572.0 288.0,600.0L426.0,645.0Q531.0,680.0 531.0,722.0Q531.0,738.0 519.5,745.5Q508.0,753.0 482.0,753.0Q482.0,780.0 499.5,800.0Q517.0,820.0 551.0,820.0Q586.0,820.0 604.5,796.5Q623.0,773.0 623.0,735.0Q623.0,682.0 581.0,645.5Q539.0,609.0 456.0,583.0L307.0,536.0Q255.0,520.0 228.5,479.5Q202.0,439.0 202.0,379.0L202.0,146.0Q202.0,127.0 219.5,109.0Q237.0,91.0 266.5,79.0Q296.0,67.0 330.0,67.0L531.0,67.0Q494.0,123.0 476.0,162.0Q458.0,201.0 458.0,220.0L458.0,397.0Q458.0,438.0 483.0,463.0Q508.0,488.0 553.0,488.0Q608.0,488.0 633.0,453.5Q658.0,419.0 658.0,371.0Q658.0,333.0 642.0,308.5Q626.0,284.0 601.0,272.5Q576.0,261.0 550.0,261.0L550.0,220.0Q550.0,170.0 586.0,116.0L623.0,61.0L623.0,0.0L330.0,0.0Q265.0,0.0 215.0,23.0Q165.0,46.0 137.5,80.0Q110.0,114.0 110.0,146.0ZM550.0,322.0Q577.0,322.0 588.5,341.0Q600.0,360.0 600.0,377.0Q600.0,392.0 589.5,411.0Q579.0,430.0 550.0,436.0L550.0,322.0Z"  transform="translate(3767, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">=</span> (fontdiff-khm-sample-20161201.html)</li>


<pre>Expected: .notdef=0+634</pre>



<pre>Got     : equal=0+559</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 559 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M65.0,426.0L65.0,485.0L494.0,485.0L494.0,426.0L65.0,426.0ZM65.0,229.0L65.0,288.0L494.0,288.0L494.0,229.0L65.0,229.0Z"  transform="translate(0, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 634 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(0, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">Google</span> (fontdiff-km-google-app-info.html)</li>


<pre>Expected: .notdef=0+634|.notdef=1+634|.notdef=2+634|.notdef=3+634|.notdef=4+634|.notdef=5+634</pre>



<pre>Got     : G=0+714|o=1+577|o=2+577|g=3+538|l=4+310|e=5+535</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3251 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M401.0,-10.0Q285.0,-10.0 208.5,36.0Q132.0,82.0 94.5,164.5Q57.0,247.0 57.0,358.0Q57.0,466.0 96.5,548.5Q136.0,631.0 214.0,677.5Q292.0,724.0 407.0,724.0Q518.0,724.0 573.0,692.0Q628.0,660.0 628.0,612.0Q628.0,580.0 601.0,561.0Q574.0,542.0 535.0,542.0Q535.0,573.0 522.5,602.5Q510.0,632.0 481.0,651.5Q452.0,671.0 403.0,671.0Q276.0,671.0 222.0,589.5Q168.0,508.0 168.0,358.0Q168.0,208.0 224.5,127.5Q281.0,47.0 417.0,47.0Q446.0,47.0 473.0,50.0Q500.0,53.0 521.0,59.0L521.0,220.0Q521.0,264.0 496.5,276.0Q472.0,288.0 439.0,288.0L435.0,288.0L435.0,330.0L695.0,330.0L695.0,288.0L691.0,288.0Q663.0,288.0 642.5,275.5Q622.0,263.0 622.0,216.0L622.0,36.0Q572.0,13.0 519.0,1.5Q466.0,-10.0 401.0,-10.0Z"  transform="translate(0, 793)"/>
<path d="M287.0,-10.0Q179.0,-10.0 117.0,59.0Q55.0,128.0 55.0,269.0Q55.0,409.0 114.5,477.5Q174.0,546.0 290.0,546.0Q398.0,546.0 460.0,477.5Q522.0,409.0 522.0,269.0Q522.0,128.0 462.5,59.0Q403.0,-10.0 287.0,-10.0ZM289.0,42.0Q364.0,42.0 394.5,99.5Q425.0,157.0 425.0,269.0Q425.0,381.0 394.0,437.0Q363.0,493.0 288.0,493.0Q213.0,493.0 182.5,437.0Q152.0,381.0 152.0,269.0Q152.0,157.0 183.0,99.5Q214.0,42.0 289.0,42.0Z"  transform="translate(714, 793)"/>
<path d="M287.0,-10.0Q179.0,-10.0 117.0,59.0Q55.0,128.0 55.0,269.0Q55.0,409.0 114.5,477.5Q174.0,546.0 290.0,546.0Q398.0,546.0 460.0,477.5Q522.0,409.0 522.0,269.0Q522.0,128.0 462.5,59.0Q403.0,-10.0 287.0,-10.0ZM289.0,42.0Q364.0,42.0 394.5,99.5Q425.0,157.0 425.0,269.0Q425.0,381.0 394.0,437.0Q363.0,493.0 288.0,493.0Q213.0,493.0 182.5,437.0Q152.0,381.0 152.0,269.0Q152.0,157.0 183.0,99.5Q214.0,42.0 289.0,42.0Z"  transform="translate(1291, 793)"/>
<path d="M231.0,-240.0Q127.0,-240.0 75.0,-201.5Q23.0,-163.0 23.0,-94.0Q23.0,-35.0 61.0,-5.0Q99.0,25.0 148.0,34.0Q128.0,43.0 110.5,63.5Q93.0,84.0 93.0,116.0Q93.0,146.0 108.5,168.0Q124.0,190.0 158.0,210.0Q115.0,228.0 91.5,269.5Q68.0,311.0 68.0,361.0Q68.0,447.0 115.0,496.5Q162.0,546.0 256.0,546.0Q292.0,546.0 324.0,536.0Q356.0,526.0 370.0,513.0Q384.0,529.0 409.0,548.0Q434.0,567.0 467.0,567.0Q497.0,567.0 511.5,551.5Q526.0,536.0 526.0,515.0Q526.0,494.0 513.5,478.5Q501.0,463.0 473.0,463.0Q473.0,474.0 466.5,485.5Q460.0,497.0 440.0,497.0Q417.0,497.0 397.0,485.0Q414.0,464.0 425.0,435.5Q436.0,407.0 436.0,364.0Q436.0,290.0 391.5,241.0Q347.0,192.0 256.0,192.0Q244.0,192.0 228.5,193.5Q213.0,195.0 203.0,197.0Q184.0,187.0 170.0,172.0Q156.0,157.0 156.0,134.0Q156.0,116.0 167.5,106.0Q179.0,96.0 218.0,96.0L331.0,96.0Q420.0,96.0 458.0,54.0Q496.0,12.0 496.0,-53.0Q496.0,-139.0 431.5,-189.5Q367.0,-240.0 231.0,-240.0ZM253.0,240.0Q302.0,240.0 322.0,270.0Q342.0,300.0 342.0,365.0Q342.0,433.0 321.5,465.0Q301.0,497.0 252.0,497.0Q204.0,497.0 183.0,464.0Q162.0,431.0 162.0,364.0Q162.0,300.0 183.5,270.0Q205.0,240.0 253.0,240.0ZM233.0,-191.0Q305.0,-191.0 344.0,-175.5Q383.0,-160.0 398.5,-132.5Q414.0,-105.0 414.0,-70.0Q414.0,-24.0 388.0,-8.5Q362.0,7.0 312.0,7.0L214.0,7.0Q186.0,7.0 161.0,-0.5Q136.0,-8.0 120.0,-28.0Q104.0,-48.0 104.0,-88.0Q104.0,-117.0 115.0,-140.5Q126.0,-164.0 154.0,-177.5Q182.0,-191.0 233.0,-191.0Z"  transform="translate(1868, 793)"/>
<path d="M13.0,0.0L13.0,42.0L26.0,42.0Q60.0,42.0 84.0,54.5Q108.0,67.0 108.0,114.0L108.0,650.0Q108.0,694.0 83.5,706.0Q59.0,718.0 26.0,718.0L13.0,718.0L13.0,760.0L202.0,760.0L202.0,114.0Q202.0,67.0 226.0,54.5Q250.0,42.0 284.0,42.0L297.0,42.0L297.0,0.0L13.0,0.0Z"  transform="translate(2406, 793)"/>
<path d="M287.0,-10.0Q178.0,-10.0 116.5,62.0Q55.0,134.0 55.0,264.0Q55.0,404.0 113.0,475.0Q171.0,546.0 277.0,546.0Q374.0,546.0 429.5,486.0Q485.0,426.0 485.0,307.0L485.0,261.0L152.0,261.0Q154.0,152.0 191.5,102.5Q229.0,53.0 301.0,53.0Q353.0,53.0 389.5,74.5Q426.0,96.0 444.0,123.0Q451.0,120.0 457.0,111.0Q463.0,102.0 463.0,89.0Q463.0,69.0 444.0,46.0Q425.0,23.0 386.0,6.5Q347.0,-10.0 287.0,-10.0ZM384.0,315.0Q384.0,395.0 359.5,443.5Q335.0,492.0 275.0,492.0Q220.0,492.0 189.5,446.5Q159.0,401.0 154.0,315.0L384.0,315.0Z"  transform="translate(2716, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3804 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(0, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(634, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(1268, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(1902, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(2536, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(3170, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">A</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: .notdef=0+634</pre>



<pre>Got     : A=0+705</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 705 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M0.0,0.0L0.0,42.0L19.0,42.0Q48.0,42.0 62.5,57.0Q77.0,72.0 95.0,120.0L317.0,714.0L395.0,714.0L621.0,95.0Q632.0,64.0 647.5,53.0Q663.0,42.0 692.0,42.0L705.0,42.0L705.0,0.0L430.0,0.0L430.0,42.0L453.0,42.0Q513.0,42.0 513.0,90.0Q513.0,98.0 511.0,107.0Q509.0,116.0 505.0,127.0L465.0,239.0L202.0,239.0L164.0,134.0Q155.0,110.0 155.0,91.0Q155.0,42.0 221.0,42.0L244.0,42.0L244.0,0.0L0.0,0.0ZM221.0,289.0L447.0,289.0L385.0,464.0Q369.0,508.0 356.0,547.0Q343.0,586.0 335.0,622.0Q328.0,586.0 317.0,553.0Q306.0,520.0 289.0,473.0L221.0,289.0Z"  transform="translate(0, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 634 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(0, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(III)</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: parenleft=0+346|.notdef=1+634|.notdef=2+634|.notdef=3+634|parenright=4+346</pre>



<pre>Got     : parenleft=0+346|I=1+367|I=2+367|I=3+367|parenright=4+346</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1793 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M314.0,-128.0Q222.0,-91.0 165.5,-33.5Q109.0,24.0 83.0,110.5Q57.0,197.0 57.0,317.0Q57.0,437.0 83.0,522.5Q109.0,608.0 165.5,666.0Q222.0,724.0 314.0,760.0L314.0,715.0Q245.0,674.0 212.5,611.0Q180.0,548.0 170.5,472.5Q161.0,397.0 161.0,317.0Q161.0,238.0 170.5,162.0Q180.0,86.0 212.5,23.0Q245.0,-40.0 314.0,-82.0L314.0,-128.0Z"  transform="translate(0, 793)"/>
<path d="M38.0,0.0L38.0,42.0L51.0,42.0Q85.0,42.0 109.0,54.5Q133.0,67.0 133.0,114.0L133.0,600.0Q133.0,647.0 109.0,659.5Q85.0,672.0 51.0,672.0L38.0,672.0L38.0,714.0L329.0,714.0L329.0,672.0L316.0,672.0Q282.0,672.0 258.0,659.5Q234.0,647.0 234.0,600.0L234.0,114.0Q234.0,67.0 258.0,54.5Q282.0,42.0 316.0,42.0L329.0,42.0L329.0,0.0L38.0,0.0Z"  transform="translate(346, 793)"/>
<path d="M38.0,0.0L38.0,42.0L51.0,42.0Q85.0,42.0 109.0,54.5Q133.0,67.0 133.0,114.0L133.0,600.0Q133.0,647.0 109.0,659.5Q85.0,672.0 51.0,672.0L38.0,672.0L38.0,714.0L329.0,714.0L329.0,672.0L316.0,672.0Q282.0,672.0 258.0,659.5Q234.0,647.0 234.0,600.0L234.0,114.0Q234.0,67.0 258.0,54.5Q282.0,42.0 316.0,42.0L329.0,42.0L329.0,0.0L38.0,0.0Z"  transform="translate(713, 793)"/>
<path d="M38.0,0.0L38.0,42.0L51.0,42.0Q85.0,42.0 109.0,54.5Q133.0,67.0 133.0,114.0L133.0,600.0Q133.0,647.0 109.0,659.5Q85.0,672.0 51.0,672.0L38.0,672.0L38.0,714.0L329.0,714.0L329.0,672.0L316.0,672.0Q282.0,672.0 258.0,659.5Q234.0,647.0 234.0,600.0L234.0,114.0Q234.0,67.0 258.0,54.5Q282.0,42.0 316.0,42.0L329.0,42.0L329.0,0.0L38.0,0.0Z"  transform="translate(1080, 793)"/>
<path d="M32.0,-128.0L32.0,-82.0Q101.0,-40.0 133.5,23.0Q166.0,86.0 175.5,162.0Q185.0,238.0 185.0,317.0Q185.0,397.0 175.5,472.5Q166.0,548.0 133.5,611.0Q101.0,674.0 32.0,715.0L32.0,760.0Q124.0,724.0 180.5,666.0Q237.0,608.0 263.0,522.5Q289.0,437.0 289.0,317.0Q289.0,197.0 263.0,110.5Q237.0,24.0 180.5,-33.5Q124.0,-91.0 32.0,-128.0Z"  transform="translate(1447, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2594 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M314.0,-128.0Q222.0,-91.0 165.5,-33.5Q109.0,24.0 83.0,110.5Q57.0,197.0 57.0,317.0Q57.0,437.0 83.0,522.5Q109.0,608.0 165.5,666.0Q222.0,724.0 314.0,760.0L314.0,715.0Q245.0,674.0 212.5,611.0Q180.0,548.0 170.5,472.5Q161.0,397.0 161.0,317.0Q161.0,238.0 170.5,162.0Q180.0,86.0 212.5,23.0Q245.0,-40.0 314.0,-82.0L314.0,-128.0Z"  transform="translate(0, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(346, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(980, 793)"/>
<path d="M96.0,0.0L96.0,714.0L538.0,714.0L538.0,0.0L96.0,0.0ZM188.0,67.0L446.0,67.0L446.0,647.0L188.0,647.0L188.0,67.0Z"  transform="translate(1614, 793)"/>
<path d="M32.0,-128.0L32.0,-82.0Q101.0,-40.0 133.5,23.0Q166.0,86.0 175.5,162.0Q185.0,238.0 185.0,317.0Q185.0,397.0 175.5,472.5Q166.0,548.0 133.5,611.0Q101.0,674.0 32.0,715.0L32.0,760.0Q124.0,724.0 180.5,666.0Q237.0,608.0 263.0,522.5Q289.0,437.0 289.0,317.0Q289.0,197.0 263.0,110.5Q237.0,24.0 180.5,-33.5Q124.0,-91.0 32.0,-128.0Z"  transform="translate(2248, 793)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni179417B6
	* uni179217B6
	* uni179517C5
	* uni17A217B6
	* uni1789.a
	* uni179F
	* uni17A3
	* uni178917C5
	* uni179F17C5
	* uni179017C5 and 63 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[13] NotoSerifKhmer-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni179417B6
	* uni179217B6
	* uni179517C5
	* uni179D
	* uni17A217B6
	* uni1789.a
	* uni179F
	* uni17A3
	* uni178917C5
	* uni17A1 and 109 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 45 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<419.0,336.0>--<262.0,337.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSerifKhmer-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1789.a
	* uni178917C5
	* uni178917B6.a
	* uni178917C5.a
	* uni178917B6 and uni1789
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Khmer Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 59 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<385.5,450.5>-<412.0,431.0>-<428.0,400.0>>/B<<428.0,400.0>-<403.0,480.0>-<371.5,537.5>> = 9.945547575071476 

	* And sterling (U+00A3): B<<192.0,89.0>-<173.0,58.0>-<145.0,40.0>>/L<<145.0,40.0>--<149.0,42.0>> = 6.170175095029526 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<149.0,714.0>--<146.0,167.0>> 

	* And exclamdown (U+00A1): L<<123.0,-177.0>--<126.0,370.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] NotoSerifKhmer[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1294, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 839, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 283. [code: invalid-default-instance-subfamily-nameid:283]
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

	- And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=314.0,Y=715.0 (should be at cap-height 714?)

	* parenright (U+0029): X=32.0,Y=715.0 (should be at cap-height 714?)

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=328.0,Y=0.5 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* C (U+0043): X=457.5,Y=0.5 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* bracketleft (U+005B): X=239.0,Y=713.0 (should be at cap-height 714?) 

	* And 84 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 10 | 13 | 104 | 1099 | 62 | 927 | 0 |
| 0% | 1% | 5% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
