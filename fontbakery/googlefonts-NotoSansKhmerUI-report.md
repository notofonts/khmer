## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[16] NotoSansKhmerUI[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSansKhmerUI[wght].ttf' must be renamed to 'NotoSansKhmerUI[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 261. [code: invalid-default-instance-subfamily-nameid:261]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 270. [code: invalid-default-instance-postscript-nameid:270]
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

	- uni00A0.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[17] NotoSansKhmerUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
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
 FONT_FAMILY_NAME = 'Noto Sans Khmer UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemetleft

	- guillemetright 

	- And uni00A0
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=129.0,Y=0.5 (should be at baseline 0?)

	* six (U+0036): X=510.0,Y=716.0 (should be at cap-height 714?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* C (U+0043): X=506.0,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=282.0,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=143.0,Y=716.0 (should be at cap-height 714?)

	* g (U+0067): X=577.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=386.0,Y=1.0 (should be at baseline 0?) 

	* And 70 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansKhmerUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
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
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemetleft

	- guillemetright 

	- And uni00A0
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* W (U+0057): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* W (U+0057): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wacute (U+1E82): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* Wacute (U+1E82): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wacute (U+1E82): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wcircumflex (U+0174): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* Wcircumflex (U+0174): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wdieresis (U+1E84): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSansKhmerUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
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
 FONT_FAMILY_NAME = 'Noto Sans Khmer UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemetleft

	- guillemetright 

	- And uni00A0
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni1789 (U+1789): L<<603.0,648.0>--<603.0,645.0>> -> L<<603.0,645.0>--<603.0,244.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<329.0,217.5>-<335.0,187.0>-<337.0,166.0>>/B<<337.0,166.0>-<340.0,187.0>-<345.5,217.0>> = 13.570434385161475

	* W (U+0057): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* W (U+0057): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wacute (U+1E82): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wacute (U+1E82): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wcircumflex (U+0174): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wcircumflex (U+0174): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wdieresis (U+1E84): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wdieresis (U+1E84): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wgrave (U+1E80): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475 

	* And Wgrave (U+1E80): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansKhmerUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
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
 FONT_FAMILY_NAME = 'Noto Sans Khmer UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemetleft

	- guillemetright 

	- And uni00A0
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[15] NotoSansKhmerUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
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
 FONT_FAMILY_NAME = 'Noto Sans Khmer UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemetleft

	- guillemetright 

	- And uni00A0
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[16] NotoSansKhmerUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
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
 FONT_FAMILY_NAME = 'Noto Sans Khmer UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemetleft

	- guillemetright 

	- And uni00A0
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wacute (U+1E82): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wcircumflex (U+0174): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wdieresis (U+1E84): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328 

	* And Wgrave (U+1E80): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansKhmerUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/khmer-ui.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf);}
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

<h4>qa/shaping_tests/khmer-ui.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(២១-១)+៤</span> (fontdiff-khm-sample-20161201.html)</li>


<pre>Expected: parenleft=0+300|uni17E2=1+752|uni17E1=2+635|hyphen=3+322|uni17E1=4+635|parenright=5+300|.notdef=6+634|uni17E4=7+635</pre>



<pre>Got     : parenleft=0+300|uni17E2=1+752|uni17E1=2+635|hyphen=3+322|uni17E1=4+635|parenright=5+300|plus=6+572|uni17E4=7+635</pre>



<pre>                                                                                                  ^^^^^^^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4151 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M40.0,518.0Q40.0,640.0 75.5,753.5Q111.0,867.0 187.0,958.0L270.0,958.0Q200.0,864.0 164.5,751.0Q129.0,638.0 129.0,519.0Q129.0,403.0 164.5,291.5Q200.0,180.0 269.0,86.0L187.0,86.0Q111.0,174.0 75.5,285.5Q40.0,397.0 40.0,518.0Z"  transform="translate(0, 793)"/>
<path d="M375.0,244.0Q98.0,244.0 98.0,439.0L98.0,885.0L49.0,885.0L49.0,952.0L144.0,952.0Q190.0,952.0 190.0,911.0L190.0,439.0Q190.0,311.0 375.0,311.0Q562.0,311.0 562.0,439.0L562.0,748.0L462.0,663.0L361.0,748.0L361.0,604.0L386.0,604.0L386.0,537.0L269.0,537.0L269.0,830.0L361.0,830.0L462.0,745.0L562.0,830.0L654.0,830.0L654.0,439.0Q654.0,244.0 375.0,244.0Z"  transform="translate(300, 793)"/>
<path d="M317.0,244.0Q98.0,244.0 98.0,400.0L189.0,400.0Q189.0,311.0 317.0,311.0Q445.0,311.0 445.0,400.0L445.0,674.0Q445.0,763.0 317.0,763.0Q189.0,763.0 189.0,674.0L189.0,615.0Q189.0,574.0 251.0,574.0L317.0,574.0L317.0,498.0L251.0,498.0Q98.0,498.0 98.0,615.0L98.0,674.0Q98.0,830.0 317.0,830.0Q537.0,830.0 537.0,674.0L537.0,400.0Q537.0,244.0 317.0,244.0Z"  transform="translate(1052, 793)"/>
<path d="M40.0,471.0L40.0,553.0L282.0,553.0L282.0,471.0L40.0,471.0Z"  transform="translate(1687, 793)"/>
<path d="M317.0,244.0Q98.0,244.0 98.0,400.0L189.0,400.0Q189.0,311.0 317.0,311.0Q445.0,311.0 445.0,400.0L445.0,674.0Q445.0,763.0 317.0,763.0Q189.0,763.0 189.0,674.0L189.0,615.0Q189.0,574.0 251.0,574.0L317.0,574.0L317.0,498.0L251.0,498.0Q98.0,498.0 98.0,615.0L98.0,674.0Q98.0,830.0 317.0,830.0Q537.0,830.0 537.0,674.0L537.0,400.0Q537.0,244.0 317.0,244.0Z"  transform="translate(2009, 793)"/>
<path d="M260.0,518.0Q260.0,397.0 224.5,285.5Q189.0,174.0 113.0,86.0L31.0,86.0Q100.0,180.0 135.5,291.5Q171.0,403.0 171.0,519.0Q171.0,638.0 135.5,751.0Q100.0,864.0 30.0,958.0L113.0,958.0Q189.0,867.0 224.5,753.5Q260.0,640.0 260.0,518.0Z"  transform="translate(2644, 793)"/>
<path d="M321.0,388.0L520.0,388.0L520.0,317.0L321.0,317.0L321.0,111.0L249.0,111.0L249.0,317.0L50.0,317.0L50.0,388.0L249.0,388.0L249.0,595.0L321.0,595.0L321.0,388.0Z"  transform="translate(2944, 793)"/>
<path d="M317.0,244.0Q98.0,244.0 98.0,439.0L98.0,880.0L49.0,880.0L49.0,947.0L137.0,947.0Q168.0,947.0 178.5,928.5Q189.0,910.0 189.0,874.0L189.0,439.0Q189.0,311.0 317.0,311.0L474.0,311.0L342.0,463.0L342.0,635.0Q342.0,671.0 366.5,686.5Q391.0,702.0 439.0,702.0L537.0,702.0L537.0,635.0L434.0,635.0L434.0,487.0L537.0,311.0L513.0,244.0L317.0,244.0Z"  transform="translate(3516, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4213 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M40.0,518.0Q40.0,640.0 75.5,753.5Q111.0,867.0 187.0,958.0L270.0,958.0Q200.0,864.0 164.5,751.0Q129.0,638.0 129.0,519.0Q129.0,403.0 164.5,291.5Q200.0,180.0 269.0,86.0L187.0,86.0Q111.0,174.0 75.5,285.5Q40.0,397.0 40.0,518.0Z"  transform="translate(0, 793)"/>
<path d="M375.0,244.0Q98.0,244.0 98.0,439.0L98.0,885.0L49.0,885.0L49.0,952.0L144.0,952.0Q190.0,952.0 190.0,911.0L190.0,439.0Q190.0,311.0 375.0,311.0Q562.0,311.0 562.0,439.0L562.0,748.0L462.0,663.0L361.0,748.0L361.0,604.0L386.0,604.0L386.0,537.0L269.0,537.0L269.0,830.0L361.0,830.0L462.0,745.0L562.0,830.0L654.0,830.0L654.0,439.0Q654.0,244.0 375.0,244.0Z"  transform="translate(300, 793)"/>
<path d="M317.0,244.0Q98.0,244.0 98.0,400.0L189.0,400.0Q189.0,311.0 317.0,311.0Q445.0,311.0 445.0,400.0L445.0,674.0Q445.0,763.0 317.0,763.0Q189.0,763.0 189.0,674.0L189.0,615.0Q189.0,574.0 251.0,574.0L317.0,574.0L317.0,498.0L251.0,498.0Q98.0,498.0 98.0,615.0L98.0,674.0Q98.0,830.0 317.0,830.0Q537.0,830.0 537.0,674.0L537.0,400.0Q537.0,244.0 317.0,244.0Z"  transform="translate(1052, 793)"/>
<path d="M40.0,471.0L40.0,553.0L282.0,553.0L282.0,471.0L40.0,471.0Z"  transform="translate(1687, 793)"/>
<path d="M317.0,244.0Q98.0,244.0 98.0,400.0L189.0,400.0Q189.0,311.0 317.0,311.0Q445.0,311.0 445.0,400.0L445.0,674.0Q445.0,763.0 317.0,763.0Q189.0,763.0 189.0,674.0L189.0,615.0Q189.0,574.0 251.0,574.0L317.0,574.0L317.0,498.0L251.0,498.0Q98.0,498.0 98.0,615.0L98.0,674.0Q98.0,830.0 317.0,830.0Q537.0,830.0 537.0,674.0L537.0,400.0Q537.0,244.0 317.0,244.0Z"  transform="translate(2009, 793)"/>
<path d="M260.0,518.0Q260.0,397.0 224.5,285.5Q189.0,174.0 113.0,86.0L31.0,86.0Q100.0,180.0 135.5,291.5Q171.0,403.0 171.0,519.0Q171.0,638.0 135.5,751.0Q100.0,864.0 30.0,958.0L113.0,958.0Q189.0,867.0 224.5,753.5Q260.0,640.0 260.0,518.0Z"  transform="translate(2644, 793)"/>
<path d="M96.0,244.0L96.0,958.0L538.0,958.0L538.0,244.0L96.0,244.0ZM188.0,311.0L446.0,311.0L446.0,891.0L188.0,891.0L188.0,311.0Z"  transform="translate(2944, 793)"/>
<path d="M317.0,244.0Q98.0,244.0 98.0,439.0L98.0,880.0L49.0,880.0L49.0,947.0L137.0,947.0Q168.0,947.0 178.5,928.5Q189.0,910.0 189.0,874.0L189.0,439.0Q189.0,311.0 317.0,311.0L474.0,311.0L342.0,463.0L342.0,635.0Q342.0,671.0 366.5,686.5Q391.0,702.0 439.0,702.0L537.0,702.0L537.0,635.0L434.0,635.0L434.0,487.0L537.0,311.0L513.0,244.0L317.0,244.0Z"  transform="translate(3578, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">រយៈពេលធ្វើដំណើរទៅមក</span> (fontdiff-km-google-app-info.html)</li>


<pre>Expected: uni179A=0+288|uni1799=1+953|uni17C8=1+283|uni17C1=3+288|uni1796=3+635|uni179B=5+928|uni17C1=6+288|uni1792=6+635|uni17D2179C=6@-2,228+0|uni17B8=6@-33,146+0|uni178A=10+635|uni17C6=10@-8,135+0|uni17C1=12+288|uni178E=12+1240|uni17B8=12@-313,146+0|uni179A=14+288|uni17C1=15+288|uni179117C5=15+919|uni1798=17+635|uni1780=18+636</pre>



<pre>Got     : uni179A=0+288|uni1799=1+953|uni17C8=1+283|uni17C1=3+288|uni1796=3+635|uni179B=5+928|uni17C1=6+288|uni1792=6+635|uni17D2179C=6@-2,228+0|uni17B8=6@-33,146+0|uni178A=10+635|uni17C6=10@-8,146+0|uni17C1=12+288|uni178E=12+1240|uni17B8=12@-313,146+0|uni179A=14+288|uni17C1=15+288|uni179117C5=15+919|uni1798=17+635|uni1780=18+636</pre>



<pre>                                                                                                                                                                                                   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 9227 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(1241, 793)"/>
<path d=""  transform="translate(1524, 793)"/>
<path d=""  transform="translate(1812, 793)"/>
<path d=""  transform="translate(2447, 793)"/>
<path d=""  transform="translate(3375, 793)"/>
<path d=""  transform="translate(3663, 793)"/>
<path d=""  transform="translate(4296, 1021)"/>
<path d=""  transform="translate(4265, 939)"/>
<path d=""  transform="translate(4298, 793)"/>
<path d=""  transform="translate(4925, 939)"/>
<path d=""  transform="translate(4933, 793)"/>
<path d=""  transform="translate(5221, 793)"/>
<path d=""  transform="translate(6148, 939)"/>
<path d=""  transform="translate(6461, 793)"/>
<path d=""  transform="translate(6749, 793)"/>
<path d=""  transform="translate(7037, 793)"/>
<path d=""  transform="translate(7956, 793)"/>
<path d=""  transform="translate(8591, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 9227 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(1241, 793)"/>
<path d=""  transform="translate(1524, 793)"/>
<path d=""  transform="translate(1812, 793)"/>
<path d=""  transform="translate(2447, 793)"/>
<path d=""  transform="translate(3375, 793)"/>
<path d=""  transform="translate(3663, 793)"/>
<path d=""  transform="translate(4296, 1021)"/>
<path d=""  transform="translate(4265, 939)"/>
<path d=""  transform="translate(4298, 793)"/>
<path d=""  transform="translate(4925, 928)"/>
<path d=""  transform="translate(4933, 793)"/>
<path d=""  transform="translate(5221, 793)"/>
<path d=""  transform="translate(6148, 939)"/>
<path d=""  transform="translate(6461, 793)"/>
<path d=""  transform="translate(6749, 793)"/>
<path d=""  transform="translate(7037, 793)"/>
<path d=""  transform="translate(7956, 793)"/>
<path d=""  transform="translate(8591, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(III)</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: parenleft=0+300|.notdef=1+634|.notdef=2+634|.notdef=3+634|parenright=4+300</pre>



<pre>Got     : parenleft=0+300|I=1+339|I=2+339|I=3+339|parenright=4+300</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1617 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(300, 793)"/>
<path d=""  transform="translate(639, 793)"/>
<path d=""  transform="translate(978, 793)"/>
<path d=""  transform="translate(1317, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2502 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(300, 793)"/>
<path d=""  transform="translate(934, 793)"/>
<path d=""  transform="translate(1568, 793)"/>
<path d=""  transform="translate(2202, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">និងជំនឿ</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: uni1793=0+635|uni17B7=0@-23,146+0|uni1784=2+635|uni1787=3+635|uni17C6=3@-23,155+0|uni17C1=5+288|uni1793=5+635|uni17BF.right1=5+288</pre>



<pre>Got     : uni1793=0+635|uni17B7=0@-23,146+0|uni1784=2+635|uni1787=3+635|uni17C6=3@-23,166+0|uni17C1=5+288|uni1793=5+635|uni17BF.right1=5+288</pre>



<pre>                                                                                       ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3116 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(612, 939)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1270, 793)"/>
<path d=""  transform="translate(1882, 959)"/>
<path d=""  transform="translate(1905, 793)"/>
<path d=""  transform="translate(2193, 793)"/>
<path d=""  transform="translate(2828, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3116 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(612, 939)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1270, 793)"/>
<path d=""  transform="translate(1882, 948)"/>
<path d=""  transform="translate(1905, 793)"/>
<path d=""  transform="translate(2193, 793)"/>
<path d=""  transform="translate(2828, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">នូវជំនឿរបស់ខ្លួនទៅលើសិទ្ធិមូលដ្ឋាននៃមនុស្ស</span> (fontdiff-km-udhr.html)</li>


<pre>Expected: uni1793=0+635|uni17BC=0@-8,244+0|uni179C=2+326|uni1787=3+635|uni17C6=3@-23,155+0|uni17C1=5+288|uni1793=5+635|uni17BF.right1=5+288|uni179A=7+288|uni1794=8+635|uni179F=9+928|uni17CB=9@-32,146+0|uni1781=11+635|uni17D2179B=11@-1,228+0|uni17BD=11@-5,-16+0|uni1793=15+635|uni17C1=16+288|uni179117C5=16+919|uni17C1=18+288|uni179B=18+928|uni17B8=18@-23,146+0|uni179F=20+928|uni17B7=20@-19,146+0|uni1791=22+599|uni17D21792=22@27,228+0|uni17B7=22@3,146+0|uni1798=26+635|uni17BC=26@-8,244+0|uni179B=28+928|uni178A17B6=29+923|uni17D2178B=29@-292,228+0|uni1793=33+635|uni17C3=34+288|uni1793=34+635|uni1798=36+635|uni1793=37+635|uni17BB=37@-8,244+0|uni179F=39+928|uni17D2179F=39+302</pre>



<pre>Got     : uni1793=0+635|uni17BC=0@-8,244+0|uni179C=2+326|uni1787=3+635|uni17C6=3@-23,166+0|uni17C1=5+288|uni1793=5+635|uni17BF.right1=5+288|uni179A=7+288|uni1794=8+635|uni179F=9+928|uni17CB=9@-32,146+0|uni1781=11+635|uni17D2179B=11@-1,228+0|uni17BD=11@-5,-16+0|uni1793=15+635|uni17C1=16+288|uni179117C5=16+919|uni17C1=18+288|uni179B=18+928|uni17B8=18@-23,146+0|uni179F=20+928|uni17B7=20@-19,146+0|uni1791=22+599|uni17D21792=22@27,228+0|uni17B7=22@3,146+0|uni1798=26+635|uni17BC=26@-8,244+0|uni179B=28+928|uni178A17B6=29+923|uni17D2178B=29@-292,228+0|uni1793=33+635|uni17C3=34+288|uni1793=34+635|uni1798=36+635|uni1793=37+635|uni17BB=37@-8,244+0|uni179F=39+928|uni17D2179F=39+302</pre>



<pre>                                                                                      ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16422 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(627, 1037)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(961, 793)"/>
<path d=""  transform="translate(1573, 959)"/>
<path d=""  transform="translate(1596, 793)"/>
<path d=""  transform="translate(1884, 793)"/>
<path d=""  transform="translate(2519, 793)"/>
<path d=""  transform="translate(2807, 793)"/>
<path d=""  transform="translate(3095, 793)"/>
<path d=""  transform="translate(3730, 793)"/>
<path d=""  transform="translate(4626, 939)"/>
<path d=""  transform="translate(4658, 793)"/>
<path d=""  transform="translate(5292, 1021)"/>
<path d=""  transform="translate(5288, 777)"/>
<path d=""  transform="translate(5293, 793)"/>
<path d=""  transform="translate(5928, 793)"/>
<path d=""  transform="translate(6216, 793)"/>
<path d=""  transform="translate(7135, 793)"/>
<path d=""  transform="translate(7423, 793)"/>
<path d=""  transform="translate(8328, 939)"/>
<path d=""  transform="translate(8351, 793)"/>
<path d=""  transform="translate(9260, 939)"/>
<path d=""  transform="translate(9279, 793)"/>
<path d=""  transform="translate(9905, 1021)"/>
<path d=""  transform="translate(9881, 939)"/>
<path d=""  transform="translate(9878, 793)"/>
<path d=""  transform="translate(10505, 1037)"/>
<path d=""  transform="translate(10513, 793)"/>
<path d=""  transform="translate(11441, 793)"/>
<path d=""  transform="translate(12072, 1021)"/>
<path d=""  transform="translate(12364, 793)"/>
<path d=""  transform="translate(12999, 793)"/>
<path d=""  transform="translate(13287, 793)"/>
<path d=""  transform="translate(13922, 793)"/>
<path d=""  transform="translate(14557, 793)"/>
<path d=""  transform="translate(15184, 1037)"/>
<path d=""  transform="translate(15192, 793)"/>
<path d=""  transform="translate(16120, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16422 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(627, 1037)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(961, 793)"/>
<path d=""  transform="translate(1573, 948)"/>
<path d=""  transform="translate(1596, 793)"/>
<path d=""  transform="translate(1884, 793)"/>
<path d=""  transform="translate(2519, 793)"/>
<path d=""  transform="translate(2807, 793)"/>
<path d=""  transform="translate(3095, 793)"/>
<path d=""  transform="translate(3730, 793)"/>
<path d=""  transform="translate(4626, 939)"/>
<path d=""  transform="translate(4658, 793)"/>
<path d=""  transform="translate(5292, 1021)"/>
<path d=""  transform="translate(5288, 777)"/>
<path d=""  transform="translate(5293, 793)"/>
<path d=""  transform="translate(5928, 793)"/>
<path d=""  transform="translate(6216, 793)"/>
<path d=""  transform="translate(7135, 793)"/>
<path d=""  transform="translate(7423, 793)"/>
<path d=""  transform="translate(8328, 939)"/>
<path d=""  transform="translate(8351, 793)"/>
<path d=""  transform="translate(9260, 939)"/>
<path d=""  transform="translate(9279, 793)"/>
<path d=""  transform="translate(9905, 1021)"/>
<path d=""  transform="translate(9881, 939)"/>
<path d=""  transform="translate(9878, 793)"/>
<path d=""  transform="translate(10505, 1037)"/>
<path d=""  transform="translate(10513, 793)"/>
<path d=""  transform="translate(11441, 793)"/>
<path d=""  transform="translate(12072, 1021)"/>
<path d=""  transform="translate(12364, 793)"/>
<path d=""  transform="translate(12999, 793)"/>
<path d=""  transform="translate(13287, 793)"/>
<path d=""  transform="translate(13922, 793)"/>
<path d=""  transform="translate(14557, 793)"/>
<path d=""  transform="translate(15184, 1037)"/>
<path d=""  transform="translate(15192, 793)"/>
<path d=""  transform="translate(16120, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf"> </span> (fontdiff-specimen-khm.html)</li>


<pre>Expected: uni00A0=0+260</pre>



<pre>Got     : nbspace=0+260</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 260 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 260 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">វា៝៍រី៎◌៌ផ៉ុ័ះ</span> (Added by SIESTA)</li>


<pre>Expected: uni179C17B6=0+615|uni17DD.r=0@70,166+0|uni25CC=0+635|uni17CD=0@-7,160+0|uni179A=4+288|uni17B8.r=4@86,146+0|uni17CE=4@172,432+0|uni25CC=7+635|uni17CC=7@-7,160+0|uni1795=9+635|uni17C9=9@-23,166+0|uni17BB=9@-8,244+0|uni17D0=9@490,392+0|uni17C7=9+386</pre>



<pre>Got     : uni179C17B6=0+615|uni17DD.r=0@70,166+0|uni25CC=0+635|uni17CD=0@-7,160+0|uni179A=4+288|uni17B8.r=4@86,146+0|uni17CE=4@172,432+0|uni25CC=7+635|uni17CC=7@-7,160+0|uni1795=9+635|uni17C9=9@-23,166+0|uni17BB=9@-8,244+0|uni17D0=9@474,392+0|uni17C7=9+386</pre>



<pre>                                                                                                                                                                                                                                          ^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3194 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(685, 959)"/>
<path d=""  transform="translate(615, 793)"/>
<path d=""  transform="translate(1243, 953)"/>
<path d=""  transform="translate(1250, 793)"/>
<path d=""  transform="translate(1624, 939)"/>
<path d=""  transform="translate(1710, 1225)"/>
<path d=""  transform="translate(1538, 793)"/>
<path d=""  transform="translate(2166, 953)"/>
<path d=""  transform="translate(2173, 793)"/>
<path d=""  transform="translate(2785, 959)"/>
<path d=""  transform="translate(2800, 1037)"/>
<path d=""  transform="translate(3282, 1185)"/>
<path d=""  transform="translate(2808, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3194 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(685, 959)"/>
<path d=""  transform="translate(615, 793)"/>
<path d=""  transform="translate(1243, 953)"/>
<path d=""  transform="translate(1250, 793)"/>
<path d=""  transform="translate(1624, 939)"/>
<path d=""  transform="translate(1710, 1225)"/>
<path d=""  transform="translate(1538, 793)"/>
<path d=""  transform="translate(2166, 953)"/>
<path d=""  transform="translate(2173, 793)"/>
<path d=""  transform="translate(2785, 959)"/>
<path d=""  transform="translate(2800, 1037)"/>
<path d=""  transform="translate(3298, 1185)"/>
<path d=""  transform="translate(2808, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">វ៉ិឋាឫ៉ុ័ះ៑៍</span> (Added by SIESTA)</li>


<pre>Expected: uni179C=0+326|uni17BB=0@133,244+0|uni17B7.r=0@66,166+0|uni178B17B6=3+923|uni17AB=5+635|uni17C9=5@-18,146+0|uni17BB=5+0|uni17D0=5@495,372+0|uni17C7=5+386|uni25CC=5+635|uni17D1=5@-20,170+0|uni17CD=5@-7,312+0</pre>



<pre>Got     : uni179C=0+326|uni17BB=0@133,244+0|uni17B7.r=0@66,166+0|uni178B17B6=3+923|uni17AB=5+635|uni17C9=5@-18,146+0|uni17BB=5+0|uni17D0=5@479,372+0|uni17C7=5+386|uni25CC=5+635|uni17D1=5@-20,170+0|uni17CD=5@-7,312+0</pre>



<pre>                                                                                                                                            ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2905 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(459, 1037)"/>
<path d=""  transform="translate(392, 959)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(1249, 793)"/>
<path d=""  transform="translate(1866, 939)"/>
<path d=""  transform="translate(1884, 793)"/>
<path d=""  transform="translate(2363, 1165)"/>
<path d=""  transform="translate(1884, 793)"/>
<path d=""  transform="translate(2270, 793)"/>
<path d=""  transform="translate(2885, 963)"/>
<path d=""  transform="translate(2898, 1105)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2905 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(459, 1037)"/>
<path d=""  transform="translate(392, 959)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(1249, 793)"/>
<path d=""  transform="translate(1866, 939)"/>
<path d=""  transform="translate(1884, 793)"/>
<path d=""  transform="translate(2379, 1165)"/>
<path d=""  transform="translate(1884, 793)"/>
<path d=""  transform="translate(2270, 793)"/>
<path d=""  transform="translate(2885, 963)"/>
<path d=""  transform="translate(2898, 1105)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ឞ័ឬ៝ភ៉័ះព៊</span> (Added by SIESTA)</li>


<pre>Expected: uni179E=0+636|uni17D0=0@-19,146+0|uni17AC=2+684|uni17DD=2@-74,146+0|uni1797=4+635|uni17C9=4@-10,146+0|uni17D0=4@503,372+0|uni17C7=4+386|uni1796=8+635|uni17CA=8@-10,146+0</pre>



<pre>Got     : uni179E=0+636|uni17D0=0@-19,146+0|uni17AC=2+684|uni17DD=2@-74,146+0|uni1797=4+635|uni17C9=4@-10,146+0|uni17D0=4@487,372+0|uni17C7=4+386|uni1796=8+635|uni17CA=8@-10,146+0</pre>



<pre>                                                                                                                          ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2976 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(617, 939)"/>
<path d=""  transform="translate(636, 793)"/>
<path d=""  transform="translate(1246, 939)"/>
<path d=""  transform="translate(1320, 793)"/>
<path d=""  transform="translate(1945, 939)"/>
<path d=""  transform="translate(2442, 1165)"/>
<path d=""  transform="translate(1955, 793)"/>
<path d=""  transform="translate(2341, 793)"/>
<path d=""  transform="translate(2966, 939)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2976 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(617, 939)"/>
<path d=""  transform="translate(636, 793)"/>
<path d=""  transform="translate(1246, 939)"/>
<path d=""  transform="translate(1320, 793)"/>
<path d=""  transform="translate(1945, 939)"/>
<path d=""  transform="translate(2458, 1165)"/>
<path d=""  transform="translate(1955, 793)"/>
<path d=""  transform="translate(2341, 793)"/>
<path d=""  transform="translate(2966, 939)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ន៎ឞ៊ើថីឪ័ះល៉ាំ</span> (Added by SIESTA)</li>


<pre>Expected: uni1793=0+635|uni17CE=0@-23,146+0|uni17C1=2+288|uni179E=2+636|uni17BB=2@-9,244+0|uni17B8=2@-19,146+0|uni1790=5+635|uni17B8=5@-18,166+0|uni17AA=7+636|uni17D0=7@494,375+0|uni17C7=7+386|uni179B17B6=10+1216|uni17BB=10@-281,244+0|uni17C6=10@60,146+0</pre>



<pre>Got     : uni1793=0+635|uni17CE=0@-23,146+0|uni17C1=2+288|uni179E=2+636|uni17BB=2@-9,244+0|uni17B8=2@-19,146+0|uni1790=5+635|uni17B8=5@-18,166+0|uni17AA=7+636|uni17D0=7@478,375+0|uni17C7=7+386|uni179B17B6=10+1216|uni17BB=10@-281,244+0|uni17C6=10@60,146+0</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4432 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(612, 939)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(923, 793)"/>
<path d=""  transform="translate(1550, 1037)"/>
<path d=""  transform="translate(1540, 939)"/>
<path d=""  transform="translate(1559, 793)"/>
<path d=""  transform="translate(2176, 959)"/>
<path d=""  transform="translate(2194, 793)"/>
<path d=""  transform="translate(3308, 1168)"/>
<path d=""  transform="translate(2830, 793)"/>
<path d=""  transform="translate(3216, 793)"/>
<path d=""  transform="translate(4151, 1037)"/>
<path d=""  transform="translate(4492, 939)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4432 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(612, 939)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(923, 793)"/>
<path d=""  transform="translate(1550, 1037)"/>
<path d=""  transform="translate(1540, 939)"/>
<path d=""  transform="translate(1559, 793)"/>
<path d=""  transform="translate(2176, 959)"/>
<path d=""  transform="translate(2194, 793)"/>
<path d=""  transform="translate(3324, 1168)"/>
<path d=""  transform="translate(2830, 793)"/>
<path d=""  transform="translate(3216, 793)"/>
<path d=""  transform="translate(4151, 1037)"/>
<path d=""  transform="translate(4492, 939)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">រីិនុ័ះជាឺ៑</span> (Added by SIESTA)</li>


<pre>Expected: uni179A=0+288|uni17B8.r=0@86,146+0|uni25CC=0+635|uni17B7=0@-7,160+0|uni1793=3+635|uni17BB=3@-8,244+0|uni17D0=3@490,146+0|uni17C7=3+386|uni178717B6=7+923|uni25CC=7+635|uni17BA=7@-7,160+0|uni17D1=7@-20,456+0</pre>



<pre>Got     : uni179A=0+288|uni17B8.r=0@86,146+0|uni25CC=0+635|uni17B7=0@-7,160+0|uni1793=3+635|uni17BB=3@-8,244+0|uni17D0=3@474,146+0|uni17C7=3+386|uni178717B6=7+923|uni25CC=7+635|uni17BA=7@-7,160+0|uni17D1=7@-20,456+0</pre>



<pre>                                                                                                                          ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3502 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(374, 939)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(916, 953)"/>
<path d=""  transform="translate(923, 793)"/>
<path d=""  transform="translate(1550, 1037)"/>
<path d=""  transform="translate(2032, 939)"/>
<path d=""  transform="translate(1558, 793)"/>
<path d=""  transform="translate(1944, 793)"/>
<path d=""  transform="translate(2867, 793)"/>
<path d=""  transform="translate(3495, 953)"/>
<path d=""  transform="translate(3482, 1249)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3502 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(374, 939)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(916, 953)"/>
<path d=""  transform="translate(923, 793)"/>
<path d=""  transform="translate(1550, 1037)"/>
<path d=""  transform="translate(2048, 939)"/>
<path d=""  transform="translate(1558, 793)"/>
<path d=""  transform="translate(1944, 793)"/>
<path d=""  transform="translate(2867, 793)"/>
<path d=""  transform="translate(3495, 953)"/>
<path d=""  transform="translate(3482, 1249)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ឡ័ះនួ</span> (Added by SIESTA)</li>


<pre>Expected: uni17A1=0+846|uni17D0=0@503,146+0|uni17C7=0+386|uni1793=3+635|uni17BD=3@-8,244+0</pre>



<pre>Got     : uni17A1=0+846|uni17D0=0@514,146+0|uni17C7=0+386|uni1793=3+635|uni17BD=3@-8,244+0</pre>



<pre>                                   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1867 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1360, 939)"/>
<path d=""  transform="translate(846, 793)"/>
<path d=""  transform="translate(1232, 793)"/>
<path d=""  transform="translate(1859, 1037)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1867 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1349, 939)"/>
<path d=""  transform="translate(846, 793)"/>
<path d=""  transform="translate(1232, 793)"/>
<path d=""  transform="translate(1859, 1037)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">រីិឬ័ះឡឹរ៑៝</span> (Added by SIESTA)</li>


<pre>Expected: uni179A=0+288|uni17B8.r=0@86,146+0|uni25CC=0+635|uni17B7=0@-7,160+0|uni17AC=3+684|uni17D0=3@503,146+0|uni17C7=3+386|uni17A1=6+846|uni17B9=6@23,146+0|uni179A=8+288|uni17D1.r=8@160,156+0|uni17DD=8@165,298+0</pre>



<pre>Got     : uni179A=0+288|uni17B8.r=0@86,146+0|uni25CC=0+635|uni17B7=0@-7,160+0|uni17AC=3+684|uni17D0=3@480,146+0|uni17C7=3+386|uni17A1=6+846|uni17B9=6@23,146+0|uni179A=8+288|uni17D1.r=8@160,156+0|uni17DD=8@165,298+0</pre>



<pre>                                                                                                      ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3127 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(374, 939)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(916, 953)"/>
<path d=""  transform="translate(923, 793)"/>
<path d=""  transform="translate(2087, 939)"/>
<path d=""  transform="translate(1607, 793)"/>
<path d=""  transform="translate(1993, 793)"/>
<path d=""  transform="translate(2862, 939)"/>
<path d=""  transform="translate(2839, 793)"/>
<path d=""  transform="translate(3287, 949)"/>
<path d=""  transform="translate(3292, 1091)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3127 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(374, 939)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(916, 953)"/>
<path d=""  transform="translate(923, 793)"/>
<path d=""  transform="translate(2110, 939)"/>
<path d=""  transform="translate(1607, 793)"/>
<path d=""  transform="translate(1993, 793)"/>
<path d=""  transform="translate(2862, 939)"/>
<path d=""  transform="translate(2839, 793)"/>
<path d=""  transform="translate(3287, 949)"/>
<path d=""  transform="translate(3292, 1091)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ធ័រ៌៝ី៌៉ំ៉ឝ័</span> (Added by SIESTA)</li>


<pre>Expected: uni1792=0+635|uni17D0=0@-33,146+0|uni179A=2@81,0+369|uni17CC.r=2@172,146+0|uni17DD=2@165,441+0|uni25CC=2+635|uni17B8=2@-7,160+0|uni17CC=2@-7,446+0|uni17C9=2@-7,741+0|uni25CC=2+635|uni17C6=2@-7,160+0|uni17C9=2@-7,160+0|uni179D=10+636|uni17D0=10@-8,146+0</pre>



<pre>Got     : uni1792=0+635|uni17D0=0@-33,146+0|uni179A=2+288|uni17CC.r=2@172,146+0|uni17DD=2@165,441+0|uni25CC=2+635|uni17B8=2@-7,160+0|uni17CC=2@-7,446+0|uni17C9=2@-7,741+0|uni25CC=2+635|uni17C6=2@-7,160+0|uni17BB=2@-7,244+0|uni179D=10+636|uni17D0=10@-8,146+0</pre>



<pre>                                                     ^ ^^^^^^^                                                                                                                                                        ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2829 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(602, 939)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1095, 939)"/>
<path d=""  transform="translate(1088, 1234)"/>
<path d=""  transform="translate(923, 793)"/>
<path d=""  transform="translate(1551, 953)"/>
<path d=""  transform="translate(1551, 1239)"/>
<path d=""  transform="translate(1551, 1534)"/>
<path d=""  transform="translate(1558, 793)"/>
<path d=""  transform="translate(2186, 953)"/>
<path d=""  transform="translate(2186, 1037)"/>
<path d=""  transform="translate(2193, 793)"/>
<path d=""  transform="translate(2821, 939)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2910 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(602, 939)"/>
<path d=""  transform="translate(716, 793)"/>
<path d=""  transform="translate(1176, 939)"/>
<path d=""  transform="translate(1169, 1234)"/>
<path d=""  transform="translate(1004, 793)"/>
<path d=""  transform="translate(1632, 953)"/>
<path d=""  transform="translate(1632, 1239)"/>
<path d=""  transform="translate(1632, 1534)"/>
<path d=""  transform="translate(1639, 793)"/>
<path d=""  transform="translate(2267, 953)"/>
<path d=""  transform="translate(2267, 953)"/>
<path d=""  transform="translate(2274, 793)"/>
<path d=""  transform="translate(2902, 939)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">៌់្កប៉ិអឹណុ័ះ</span> (Added by SIESTA)</li>


<pre>Expected: uni17CC=0+0|uni25CC=0+635|uni17CB=0@-20,160+0|uni17D21780=0@0,228+0|uni1794=4+635|uni17BB=4@-8,244+0|uni17B7=4@-18,146+0|uni17A2=7+635|uni17B9=7@-10,146+0|uni178E=9+1240|uni17BB=9@-310,244+0|uni17D0=9@503,146+0|uni17C7=9+386</pre>



<pre>Got     : uni17CC=0+0|uni25CC=0+635|uni17CB=0@-20,160+0|uni17D21780=0@0,228+0|uni1794=4+635|uni17BB=4@-8,244+0|uni17B7=4@-18,146+0|uni17A2=7+635|uni17B9=7@-10,146+0|uni178E=9+1240|uni17BB=9@-310,244+0|uni17D0=9@485,146+0|uni17C7=9+386</pre>



<pre>                                                                                                                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3531 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(615, 953)"/>
<path d=""  transform="translate(635, 1021)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1262, 1037)"/>
<path d=""  transform="translate(1252, 939)"/>
<path d=""  transform="translate(1270, 793)"/>
<path d=""  transform="translate(1895, 939)"/>
<path d=""  transform="translate(1905, 793)"/>
<path d=""  transform="translate(2835, 1037)"/>
<path d=""  transform="translate(3630, 939)"/>
<path d=""  transform="translate(3145, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3531 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(615, 953)"/>
<path d=""  transform="translate(635, 1021)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1262, 1037)"/>
<path d=""  transform="translate(1252, 939)"/>
<path d=""  transform="translate(1270, 793)"/>
<path d=""  transform="translate(1895, 939)"/>
<path d=""  transform="translate(1905, 793)"/>
<path d=""  transform="translate(2835, 1037)"/>
<path d=""  transform="translate(3648, 939)"/>
<path d=""  transform="translate(3145, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">វ់ីឹ៎៎វី៓ឪ៉័ះ</span> (Added by SIESTA)</li>


<pre>Expected: uni179C=0+326|uni17CB.r=0@99,117+0|uni17B8=0@152,351+0|uni25CC=0+635|uni17B9=0@-7,160+0|uni17CE=0@-7,446+0|uni17CE=0@-7,725+0|uni179C=6+326|uni17B8.r=6@66,166+0|uni17D3=6@139,442+0|uni17AA=9+636|uni17C9=9@-19,375+0|uni17D0=9@494,601+0|uni17C7=9+386</pre>



<pre>Got     : uni179C=0+326|uni17CB.r=0@99,117+0|uni17B8=0@152,351+0|uni25CC=0+635|uni17B9=0@-7,160+0|uni17CE=0@-7,446+0|uni17CE=0@-7,725+0|uni179C=6+326|uni17B8.r=6@66,166+0|uni17D3=6@139,442+0|uni17AA=9+636|uni17C9=9@-19,375+0|uni17D0=9@478,601+0|uni17C7=9+386</pre>



<pre>                                                                                                                                                                                                                                            ^^^^^^^^^^^^^^^^^^^^ ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2309 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(425, 910)"/>
<path d=""  transform="translate(478, 1144)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(954, 953)"/>
<path d=""  transform="translate(954, 1239)"/>
<path d=""  transform="translate(954, 1518)"/>
<path d=""  transform="translate(961, 793)"/>
<path d=""  transform="translate(1353, 959)"/>
<path d=""  transform="translate(1426, 1235)"/>
<path d=""  transform="translate(1287, 793)"/>
<path d=""  transform="translate(1904, 1168)"/>
<path d=""  transform="translate(2401, 1394)"/>
<path d=""  transform="translate(1923, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2309 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(425, 910)"/>
<path d=""  transform="translate(478, 1144)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(954, 953)"/>
<path d=""  transform="translate(954, 1239)"/>
<path d=""  transform="translate(954, 1518)"/>
<path d=""  transform="translate(961, 793)"/>
<path d=""  transform="translate(1353, 959)"/>
<path d=""  transform="translate(1426, 1235)"/>
<path d=""  transform="translate(1287, 793)"/>
<path d=""  transform="translate(1904, 1168)"/>
<path d=""  transform="translate(2417, 1394)"/>
<path d=""  transform="translate(1923, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ហ៉ូ័ះឡ៏ញួប</span> (Added by SIESTA)</li>


<pre>Expected: uni17A0=0+928|uni17C9=0@3,146+0|uni17BC=0@13,244+0|uni17D0=0@483,372+0|uni17C7=0+386|uni17A1=5+846|uni17CF=5@23,146+0|uni1789=7+952|uni17BD=7@-160,0+0|uni1794=9+635</pre>



<pre>Got     : uni17A0=0+928|uni17C9=0@3,146+0|uni17BC=0@13,244+0|uni17D0=0@494,372+0|uni17C7=0+386|uni17A1=5+846|uni17CF=5@23,146+0|uni1789=7+952|uni17BD=7@-160,0+0|uni1794=9+635</pre>



<pre>                                                                        ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3747 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(931, 939)"/>
<path d=""  transform="translate(941, 1037)"/>
<path d=""  transform="translate(1422, 1165)"/>
<path d=""  transform="translate(928, 793)"/>
<path d=""  transform="translate(1314, 793)"/>
<path d=""  transform="translate(2183, 939)"/>
<path d=""  transform="translate(2160, 793)"/>
<path d=""  transform="translate(2952, 793)"/>
<path d=""  transform="translate(3112, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3747 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(931, 939)"/>
<path d=""  transform="translate(941, 1037)"/>
<path d=""  transform="translate(1411, 1165)"/>
<path d=""  transform="translate(928, 793)"/>
<path d=""  transform="translate(1314, 793)"/>
<path d=""  transform="translate(2183, 939)"/>
<path d=""  transform="translate(2160, 793)"/>
<path d=""  transform="translate(2952, 793)"/>
<path d=""  transform="translate(3112, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ញ៝ឍ៉ុ័ះឞ៊ិ៉៎ជ័</span> (Added by SIESTA)</li>


<pre>Expected: uni1789=0+952|uni17DD=0@-17,146+0|uni178D=2+924|uni17C9=2@23,146+0|uni17BB=2@57,244+0|uni17D0=2@503,372+0|uni17C7=2+386|uni179E=7+636|uni17BB=7@-9,244+0|uni17B7=7@-19,146+0|uni17C9=7@-19,392+0|uni25CC=7+635|uni17CE=7@-7,160+0|uni1787=12+635|uni17D0=12@-23,166+0</pre>



<pre>Got     : uni1789=0+952|uni17DD=0@-17,146+0|uni178D=2+924|uni17C9=2@23,146+0|uni17BB=2@57,244+0|uni17D0=2@514,372+0|uni17C7=2+386|uni179E=7+636|uni17BB=7@-9,244+0|uni17B7=7@-19,146+0|uni17C9=7@-19,392+0|uni25CC=7+635|uni17CE=7@-7,160+0|uni1787=12+635|uni17D0=12@-23,166+0</pre>



<pre>                                                                                                           ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4168 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(935, 939)"/>
<path d=""  transform="translate(952, 793)"/>
<path d=""  transform="translate(1899, 939)"/>
<path d=""  transform="translate(1933, 1037)"/>
<path d=""  transform="translate(2390, 1165)"/>
<path d=""  transform="translate(1876, 793)"/>
<path d=""  transform="translate(2262, 793)"/>
<path d=""  transform="translate(2889, 1037)"/>
<path d=""  transform="translate(2879, 939)"/>
<path d=""  transform="translate(2879, 1185)"/>
<path d=""  transform="translate(2898, 793)"/>
<path d=""  transform="translate(3526, 953)"/>
<path d=""  transform="translate(3533, 793)"/>
<path d=""  transform="translate(4145, 959)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4168 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(935, 939)"/>
<path d=""  transform="translate(952, 793)"/>
<path d=""  transform="translate(1899, 939)"/>
<path d=""  transform="translate(1933, 1037)"/>
<path d=""  transform="translate(2379, 1165)"/>
<path d=""  transform="translate(1876, 793)"/>
<path d=""  transform="translate(2262, 793)"/>
<path d=""  transform="translate(2889, 1037)"/>
<path d=""  transform="translate(2879, 939)"/>
<path d=""  transform="translate(2879, 1185)"/>
<path d=""  transform="translate(2898, 793)"/>
<path d=""  transform="translate(3526, 953)"/>
<path d=""  transform="translate(3533, 793)"/>
<path d=""  transform="translate(4145, 959)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ឝ៉័ក៉ួ័ះ៎ឣ</span> (Added by SIESTA)</li>


<pre>Expected: uni179D=0+636|uni17BB=0@-9,244+0|uni17D0=0@-8,146+0|uni1780=3+636|uni17C9=3@-10,146+0|uni17BD=3@-9,244+0|uni17D0=3@503,372+0|uni17C7=3+386|uni25CC=3+635|uni17CE=3@-7,160+0|uni17A3=9+635</pre>



<pre>Got     : uni179D=0+636|uni17BB=0@-9,244+0|uni17D0=0@-8,146+0|uni1780=3+636|uni17C9=3@-10,146+0|uni17BD=3@-9,244+0|uni17D0=3@487,372+0|uni17C7=3+386|uni25CC=3+635|uni17CE=3@-7,160+0|uni17A3=9+635</pre>



<pre>                                                                                                                             ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2928 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(627, 1037)"/>
<path d=""  transform="translate(628, 939)"/>
<path d=""  transform="translate(636, 793)"/>
<path d=""  transform="translate(1262, 939)"/>
<path d=""  transform="translate(1263, 1037)"/>
<path d=""  transform="translate(1759, 1165)"/>
<path d=""  transform="translate(1272, 793)"/>
<path d=""  transform="translate(1658, 793)"/>
<path d=""  transform="translate(2286, 953)"/>
<path d=""  transform="translate(2293, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2928 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(627, 1037)"/>
<path d=""  transform="translate(628, 939)"/>
<path d=""  transform="translate(636, 793)"/>
<path d=""  transform="translate(1262, 939)"/>
<path d=""  transform="translate(1263, 1037)"/>
<path d=""  transform="translate(1775, 1165)"/>
<path d=""  transform="translate(1272, 793)"/>
<path d=""  transform="translate(1658, 793)"/>
<path d=""  transform="translate(2286, 953)"/>
<path d=""  transform="translate(2293, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">‍៊័ឆ៉ូ័ះ</span> (Added by SIESTA)</li>


<pre>Expected: space=0+0|uni17CA=0+0|uni25CC=0+635|uni17D0=0@-7,160+0|uni1786=3+635|uni17C9=3@-23,146+0|uni17BC=3@-21,244+0|uni17D0=3@490,372+0|uni17C7=3+386</pre>



<pre>Got     : space=0+0|uni17CA=0+0|uni25CC=0+635|uni17D0=0@-7,160+0|uni1786=3+635|uni17C9=3@-23,146+0|uni17BC=3@-21,244+0|uni17D0=3@474,372+0|uni17C7=3+386</pre>



<pre>                                                                                                                                  ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1656 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(628, 953)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1247, 939)"/>
<path d=""  transform="translate(1249, 1037)"/>
<path d=""  transform="translate(1744, 1165)"/>
<path d=""  transform="translate(1270, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1656 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(628, 953)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1247, 939)"/>
<path d=""  transform="translate(1249, 1037)"/>
<path d=""  transform="translate(1760, 1165)"/>
<path d=""  transform="translate(1270, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ភ៍ឡុ័ះទ៉ុ័ះ</span> (Added by SIESTA)</li>


<pre>Expected: uni1797=0+635|uni17CD=0@-10,146+0|uni17A1=2+846|uni17BB=2@5,5+0|uni17D0=2@503,146+0|uni17C7=2+386|uni1791=6+599|uni17C9=6@3,146+0|uni17BB=6@20,244+0|uni17D0=6@516,372+0|uni17C7=6+386</pre>



<pre>Got     : uni1797=0+635|uni17CD=0@-10,146+0|uni17A1=2+846|uni17BB=2@5,5+0|uni17D0=2@514,146+0|uni17C7=2+386|uni1791=6+599|uni17C9=6@3,146+0|uni17BB=6@20,244+0|uni17D0=6@500,372+0|uni17C7=6+386</pre>



<pre>                                                                                     ^^                                                                                   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2852 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(625, 939)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1486, 798)"/>
<path d=""  transform="translate(1995, 939)"/>
<path d=""  transform="translate(1481, 793)"/>
<path d=""  transform="translate(1867, 793)"/>
<path d=""  transform="translate(2469, 939)"/>
<path d=""  transform="translate(2486, 1037)"/>
<path d=""  transform="translate(2966, 1165)"/>
<path d=""  transform="translate(2466, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2852 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(625, 939)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1486, 798)"/>
<path d=""  transform="translate(1984, 939)"/>
<path d=""  transform="translate(1481, 793)"/>
<path d=""  transform="translate(1867, 793)"/>
<path d=""  transform="translate(2469, 939)"/>
<path d=""  transform="translate(2486, 1037)"/>
<path d=""  transform="translate(2982, 1165)"/>
<path d=""  transform="translate(2466, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">រុ័ះ៊៑ង៉ឹរឺីឆ៉ុ័ះ</span> (Added by SIESTA)</li>


<pre>Expected: uni179A=0+288|uni17BB=0@172,244+0|uni17D0=0@503,146+0|uni17C7=0+386|uni17CA=0+0|uni25CC=0+635|uni17D1=0@-20,170+0|uni1784=6+635|uni17BB=6@-7,244+0|uni17B9=6@-35,166+0|uni179A=9+288|uni17BA.r=9@86,146+0|uni25CC=9+635|uni17B8=9@-7,160+0|uni1786=12+635|uni17C9=12@-23,146+0|uni17BB=12@-21,244+0|uni17D0=12@490,372+0|uni17C7=12+386</pre>



<pre>Got     : uni179A=0+288|uni17BB=0@172,244+0|uni17D0=0@513,146+0|uni17C7=0+386|uni17CA=0+0|uni25CC=0+635|uni17D1=0@-20,170+0|uni1784=6+635|uni17BB=6@-7,244+0|uni17B9=6@-35,166+0|uni179A=9+288|uni17BA.r=9@86,146+0|uni25CC=9+635|uni17B8=9@-7,160+0|uni1786=12+635|uni17C9=12@-23,146+0|uni17BB=12@-21,244+0|uni17D0=12@474,372+0|uni17C7=12+386</pre>



<pre>                                                       ^                                                                                                                                                                                                                                                                  ^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3888 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(460, 1037)"/>
<path d=""  transform="translate(801, 939)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(674, 793)"/>
<path d=""  transform="translate(674, 793)"/>
<path d=""  transform="translate(1289, 963)"/>
<path d=""  transform="translate(1309, 793)"/>
<path d=""  transform="translate(1937, 1037)"/>
<path d=""  transform="translate(1909, 959)"/>
<path d=""  transform="translate(1944, 793)"/>
<path d=""  transform="translate(2318, 939)"/>
<path d=""  transform="translate(2232, 793)"/>
<path d=""  transform="translate(2860, 953)"/>
<path d=""  transform="translate(2867, 793)"/>
<path d=""  transform="translate(3479, 939)"/>
<path d=""  transform="translate(3481, 1037)"/>
<path d=""  transform="translate(3976, 1165)"/>
<path d=""  transform="translate(3502, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3888 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(460, 1037)"/>
<path d=""  transform="translate(791, 939)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(674, 793)"/>
<path d=""  transform="translate(674, 793)"/>
<path d=""  transform="translate(1289, 963)"/>
<path d=""  transform="translate(1309, 793)"/>
<path d=""  transform="translate(1937, 1037)"/>
<path d=""  transform="translate(1909, 959)"/>
<path d=""  transform="translate(1944, 793)"/>
<path d=""  transform="translate(2318, 939)"/>
<path d=""  transform="translate(2232, 793)"/>
<path d=""  transform="translate(2860, 953)"/>
<path d=""  transform="translate(2867, 793)"/>
<path d=""  transform="translate(3479, 939)"/>
<path d=""  transform="translate(3481, 1037)"/>
<path d=""  transform="translate(3992, 1165)"/>
<path d=""  transform="translate(3502, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">វ៑ៅឌុ័ះ</span> (Added by SIESTA)</li>


<pre>Expected: uni17C1=0+288|uni179C17C5=0+615|uni17D1.r=0@-149,176+0|uni178C=3+635|uni17BB=3@-8,244+0|uni17D0=3@494,146+0|uni17C7=3+386</pre>



<pre>Got     : uni17C1=0+288|uni179C17C5=0+615|uni17D1.r=0@-149,176+0|uni178C=3+635|uni17BB=3@-8,244+0|uni17D0=3@478,146+0|uni17C7=3+386</pre>



<pre>                                                                                                             ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1924 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(754, 969)"/>
<path d=""  transform="translate(903, 793)"/>
<path d=""  transform="translate(1530, 1037)"/>
<path d=""  transform="translate(2016, 939)"/>
<path d=""  transform="translate(1538, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1924 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(754, 969)"/>
<path d=""  transform="translate(903, 793)"/>
<path d=""  transform="translate(1530, 1037)"/>
<path d=""  transform="translate(2032, 939)"/>
<path d=""  transform="translate(1538, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">រ៑ឞ៍ណ៉ូ័ះរ់៏</span> (Added by SIESTA)</li>


<pre>Expected: uni179A=0+288|uni17D1.r=0@160,156+0|uni179E=2+636|uni17CD=2@-19,146+0|uni178E=4+1240|uni17C9=4@-313,146+0|uni17BC=4@-310,244+0|uni17D0=4@503,372+0|uni17C7=4+386|uni179A=9+288|uni17CB.r=9@119,97+0|uni17CF=9@172,331+0</pre>



<pre>Got     : uni179A=0+288|uni17D1.r=0@160,156+0|uni179E=2+636|uni17CD=2@-19,146+0|uni178E=4+1240|uni17C9=4@-313,146+0|uni17BC=4@-310,244+0|uni17D0=4@485,372+0|uni17C7=4+386|uni179A=9+288|uni17CB.r=9@119,97+0|uni17CF=9@172,331+0</pre>



<pre>                                                                                                                                                    ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2838 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(448, 949)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(905, 939)"/>
<path d=""  transform="translate(924, 793)"/>
<path d=""  transform="translate(1851, 939)"/>
<path d=""  transform="translate(1854, 1037)"/>
<path d=""  transform="translate(2649, 1165)"/>
<path d=""  transform="translate(2164, 793)"/>
<path d=""  transform="translate(2550, 793)"/>
<path d=""  transform="translate(2957, 890)"/>
<path d=""  transform="translate(3010, 1124)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2838 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(448, 949)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(905, 939)"/>
<path d=""  transform="translate(924, 793)"/>
<path d=""  transform="translate(1851, 939)"/>
<path d=""  transform="translate(1854, 1037)"/>
<path d=""  transform="translate(2667, 1165)"/>
<path d=""  transform="translate(2164, 793)"/>
<path d=""  transform="translate(2550, 793)"/>
<path d=""  transform="translate(2957, 890)"/>
<path d=""  transform="translate(3010, 1124)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">វុ៍៊ឺនុ័ះិ៑ឝ៏</span> (Added by SIESTA)</li>


<pre>Expected: uni179C=0+326|uni17BB=0@133,244+0|uni17CD.r=0@152,166+0|uni17CA=0@152,411+0|uni25CC=0+635|uni17BA=0@-7,160+0|uni1793=5+635|uni17BB=5@-8,244+0|uni17D0=5@490,146+0|uni17C7=5+386|uni25CC=5+635|uni17B7=5@-7,160+0|uni17D1=5@-20,416+0|uni179D=11+636|uni17CF=11@-8,146+0</pre>



<pre>Got     : uni179C=0+326|uni17BB=0@133,244+0|uni17CD.r=0@152,166+0|uni17CA=0@152,411+0|uni25CC=0+635|uni17BA=0@-7,160+0|uni1793=5+635|uni17BB=5@-8,244+0|uni17D0=5@474,146+0|uni17C7=5+386|uni25CC=5+635|uni17B7=5@-7,160+0|uni17D1=5@-20,416+0|uni179D=11+636|uni17CF=11@-8,146+0</pre>



<pre>                                                                                                                                                                   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3253 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(459, 1037)"/>
<path d=""  transform="translate(478, 959)"/>
<path d=""  transform="translate(478, 1204)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(954, 953)"/>
<path d=""  transform="translate(961, 793)"/>
<path d=""  transform="translate(1588, 1037)"/>
<path d=""  transform="translate(2070, 939)"/>
<path d=""  transform="translate(1596, 793)"/>
<path d=""  transform="translate(1982, 793)"/>
<path d=""  transform="translate(2610, 953)"/>
<path d=""  transform="translate(2597, 1209)"/>
<path d=""  transform="translate(2617, 793)"/>
<path d=""  transform="translate(3245, 939)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3253 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(459, 1037)"/>
<path d=""  transform="translate(478, 959)"/>
<path d=""  transform="translate(478, 1204)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(954, 953)"/>
<path d=""  transform="translate(961, 793)"/>
<path d=""  transform="translate(1588, 1037)"/>
<path d=""  transform="translate(2086, 939)"/>
<path d=""  transform="translate(1596, 793)"/>
<path d=""  transform="translate(1982, 793)"/>
<path d=""  transform="translate(2610, 953)"/>
<path d=""  transform="translate(2597, 1209)"/>
<path d=""  transform="translate(2617, 793)"/>
<path d=""  transform="translate(3245, 939)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ឤ័ះចាវ៉័វ៓៓</span> (Added by SIESTA)</li>


<pre>Expected: uni17A4=0+933|uni17D0=0@503,146+0|uni17C7=0+386|uni178517B6=3+923|uni179C=5+326|uni17BB=5@133,244+0|uni17D0=5@152,166+0|uni179C=8+326|uni17D3.r=8@139,156+0|uni17D3=8@139,156+0</pre>



<pre>Got     : uni17A4=0+933|uni17D0=0@488,146+0|uni17C7=0+386|uni178517B6=3+923|uni179C=5+326|uni17BB=5@133,244+0|uni17D0=5@152,166+0|uni179C=8+326|uni17D3.r=8@139,156+0|uni17D3=8@139,156+0</pre>



<pre>                                  ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2894 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1421, 939)"/>
<path d=""  transform="translate(933, 793)"/>
<path d=""  transform="translate(1319, 793)"/>
<path d=""  transform="translate(2242, 793)"/>
<path d=""  transform="translate(2701, 1037)"/>
<path d=""  transform="translate(2720, 959)"/>
<path d=""  transform="translate(2568, 793)"/>
<path d=""  transform="translate(3033, 949)"/>
<path d=""  transform="translate(3033, 949)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2894 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1436, 939)"/>
<path d=""  transform="translate(933, 793)"/>
<path d=""  transform="translate(1319, 793)"/>
<path d=""  transform="translate(2242, 793)"/>
<path d=""  transform="translate(2701, 1037)"/>
<path d=""  transform="translate(2720, 959)"/>
<path d=""  transform="translate(2568, 793)"/>
<path d=""  transform="translate(3033, 949)"/>
<path d=""  transform="translate(3033, 949)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">៏ហ៑វ៝៏៎ីឤ៉ុ័ះ</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+635|uni17CF=0@-7,160+0|uni17A0=1+928|uni17D1=1@-10,156+0|uni179C=3+326|uni17DD.r=3@162,166+0|uni25CC=3+635|uni17CF=3@-7,160+0|uni17CE=3@-7,416+0|uni17B8=3@-7,695+0|uni17A4=8+933|uni17C9=8@60,146+0|uni17BB=8@16,244+0|uni17D0=8@503,372+0|uni17C7=8+386</pre>



<pre>Got     : uni25CC=0+635|uni17CF=0@-7,160+0|uni17A0=1+928|uni17D1=1@-10,156+0|uni179C=3+326|uni17DD.r=3@162,166+0|uni25CC=3+635|uni17CF=3@-7,160+0|uni17CE=3@-7,416+0|uni17B8=3@-7,695+0|uni17A4=8+933|uni17C9=8@60,146+0|uni17BB=8@16,244+0|uni17D0=8@488,372+0|uni17C7=8+386</pre>



<pre>                                                                                                                                                                                                                                                      ^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3843 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(628, 953)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1553, 949)"/>
<path d=""  transform="translate(1563, 793)"/>
<path d=""  transform="translate(2051, 959)"/>
<path d=""  transform="translate(1889, 793)"/>
<path d=""  transform="translate(2517, 953)"/>
<path d=""  transform="translate(2517, 1209)"/>
<path d=""  transform="translate(2517, 1488)"/>
<path d=""  transform="translate(2524, 793)"/>
<path d=""  transform="translate(3517, 939)"/>
<path d=""  transform="translate(3473, 1037)"/>
<path d=""  transform="translate(3945, 1165)"/>
<path d=""  transform="translate(3457, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3843 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(628, 953)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1553, 949)"/>
<path d=""  transform="translate(1563, 793)"/>
<path d=""  transform="translate(2051, 959)"/>
<path d=""  transform="translate(1889, 793)"/>
<path d=""  transform="translate(2517, 953)"/>
<path d=""  transform="translate(2517, 1209)"/>
<path d=""  transform="translate(2517, 1488)"/>
<path d=""  transform="translate(2524, 793)"/>
<path d=""  transform="translate(3517, 939)"/>
<path d=""  transform="translate(3473, 1037)"/>
<path d=""  transform="translate(3960, 1165)"/>
<path d=""  transform="translate(3457, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">វ៏៝ឧ័ឬ៉ូ័ះវ៌៊</span> (Added by SIESTA)</li>


<pre>Expected: uni179C=0+326|uni17CF.r=0@152,166+0|uni17DD=0@145,422+0|uni17A7=3+635|uni17D0=3@-7,175+0|uni17AC=5+684|uni17C9=5@-67,146+0|uni17BC=5+0|uni17D0=5@503,372+0|uni17C7=5+386|uni179C=10+326|uni17CC.r=10@152,166+0|uni17CA=10@152,461+0</pre>



<pre>Got     : uni179C=0+326|uni17CF.r=0@152,166+0|uni17DD=0@145,422+0|uni17A7=3+635|uni17D0=3@-7,175+0|uni17AC=5+684|uni17C9=5@-67,146+0|uni17BC=5+0|uni17D0=5@480,372+0|uni17C7=5+386|uni179C=10+326|uni17CC.r=10@152,166+0|uni17CA=10@152,461+0</pre>



<pre>                                                                                                                                                           ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2357 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(478, 959)"/>
<path d=""  transform="translate(471, 1215)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(954, 968)"/>
<path d=""  transform="translate(961, 793)"/>
<path d=""  transform="translate(1578, 939)"/>
<path d=""  transform="translate(1645, 793)"/>
<path d=""  transform="translate(2125, 1165)"/>
<path d=""  transform="translate(1645, 793)"/>
<path d=""  transform="translate(2031, 793)"/>
<path d=""  transform="translate(2509, 959)"/>
<path d=""  transform="translate(2509, 1254)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2357 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(478, 959)"/>
<path d=""  transform="translate(471, 1215)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(954, 968)"/>
<path d=""  transform="translate(961, 793)"/>
<path d=""  transform="translate(1578, 939)"/>
<path d=""  transform="translate(1645, 793)"/>
<path d=""  transform="translate(2148, 1165)"/>
<path d=""  transform="translate(1645, 793)"/>
<path d=""  transform="translate(2031, 793)"/>
<path d=""  transform="translate(2509, 959)"/>
<path d=""  transform="translate(2509, 1254)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ញ៉ិថ៌ឬ៉័ះវីឺ</span> (Added by SIESTA)</li>


<pre>Expected: uni1789=0+952|uni17BB=0@-160,0+0|uni17B7=0@-10,146+0|uni1790=3+635|uni17CC=3@-18,166+0|uni17AC=5+684|uni17C9=5@-67,146+0|uni17D0=5@503,372+0|uni17C7=5+386|uni179C=9+326|uni17B8.r=9@66,166+0|uni25CC=9+635|uni17BA=9@-7,160+0</pre>



<pre>Got     : uni1789=0+952|uni17BB=0@-160,0+0|uni17B7=0@-10,146+0|uni1790=3+635|uni17CC=3@-18,166+0|uni17AC=5+684|uni17C9=5@-67,146+0|uni17D0=5@480,372+0|uni17C7=5+386|uni179C=9+326|uni17B8.r=9@66,166+0|uni25CC=9+635|uni17BA=9@-7,160+0</pre>



<pre>                                                                                                                                             ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3618 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(792, 793)"/>
<path d=""  transform="translate(942, 939)"/>
<path d=""  transform="translate(952, 793)"/>
<path d=""  transform="translate(1569, 959)"/>
<path d=""  transform="translate(1587, 793)"/>
<path d=""  transform="translate(2204, 939)"/>
<path d=""  transform="translate(2751, 1165)"/>
<path d=""  transform="translate(2271, 793)"/>
<path d=""  transform="translate(2657, 793)"/>
<path d=""  transform="translate(3049, 959)"/>
<path d=""  transform="translate(2983, 793)"/>
<path d=""  transform="translate(3611, 953)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3618 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(792, 793)"/>
<path d=""  transform="translate(942, 939)"/>
<path d=""  transform="translate(952, 793)"/>
<path d=""  transform="translate(1569, 959)"/>
<path d=""  transform="translate(1587, 793)"/>
<path d=""  transform="translate(2204, 939)"/>
<path d=""  transform="translate(2774, 1165)"/>
<path d=""  transform="translate(2271, 793)"/>
<path d=""  transform="translate(2657, 793)"/>
<path d=""  transform="translate(3049, 959)"/>
<path d=""  transform="translate(2983, 793)"/>
<path d=""  transform="translate(3611, 953)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">មប៉ាំឡ៉័ះត៑៏៍</span> (Added by SIESTA)</li>


<pre>Expected: uni1798=0+635|uni179417B6=1+923|uni17BB=1@-296,204+0|uni17C6=1@60,146+0|uni17A1=5+846|uni17C9=5@23,146+0|uni17D0=5@503,372+0|uni17C7=5+386|uni178F=9+635|uni17D1=9@-20,156+0|uni17CF=9@-7,298+0|uni17CD=9@-7,554+0</pre>



<pre>Got     : uni1798=0+635|uni179417B6=1+923|uni17BB=1@-296,204+0|uni17C6=1@60,146+0|uni17A1=5+846|uni17C9=5@23,146+0|uni17D0=5@514,372+0|uni17C7=5+386|uni178F=9+635|uni17D1=9@-20,156+0|uni17CF=9@-7,298+0|uni17CD=9@-7,554+0</pre>



<pre>                                                                                                                              ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3425 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1262, 997)"/>
<path d=""  transform="translate(1618, 939)"/>
<path d=""  transform="translate(1558, 793)"/>
<path d=""  transform="translate(2427, 939)"/>
<path d=""  transform="translate(2918, 1165)"/>
<path d=""  transform="translate(2404, 793)"/>
<path d=""  transform="translate(2790, 793)"/>
<path d=""  transform="translate(3405, 949)"/>
<path d=""  transform="translate(3418, 1091)"/>
<path d=""  transform="translate(3418, 1347)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3425 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1262, 997)"/>
<path d=""  transform="translate(1618, 939)"/>
<path d=""  transform="translate(1558, 793)"/>
<path d=""  transform="translate(2427, 939)"/>
<path d=""  transform="translate(2907, 1165)"/>
<path d=""  transform="translate(2404, 793)"/>
<path d=""  transform="translate(2790, 793)"/>
<path d=""  transform="translate(3405, 949)"/>
<path d=""  transform="translate(3418, 1091)"/>
<path d=""  transform="translate(3418, 1347)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">រ៉ី៉ឝ័រ៉ឹ</span> (Added by SIESTA)</li>


<pre>Expected: uni179A=0+288|uni17BB=0@172,244+0|uni17B8.r=0@86,146+0|uni17C9=0@172,432+0|uni179D=4+636|uni17D0=4@-8,146+0|uni179A=6@81,0+369|uni17BB=6@172,244+0|uni17B9.r=6@86,146+0</pre>



<pre>Got     : uni179A=0+288|uni17BB=0@172,244+0|uni17B8.r=0@86,146+0|uni17BB=0@172,244+0|uni179D=4+636|uni17D0=4@-8,146+0|uni179A=6+288|uni17BB=6@172,244+0|uni17B9.r=6@86,146+0</pre>



<pre>                                                                      ^^       ++                                              +++++ ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1212 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(460, 1037)"/>
<path d=""  transform="translate(374, 939)"/>
<path d=""  transform="translate(460, 1037)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(916, 939)"/>
<path d=""  transform="translate(924, 793)"/>
<path d=""  transform="translate(1384, 1037)"/>
<path d=""  transform="translate(1298, 939)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1293 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(460, 1037)"/>
<path d=""  transform="translate(374, 939)"/>
<path d=""  transform="translate(460, 1225)"/>
<path d=""  transform="translate(288, 793)"/>
<path d=""  transform="translate(916, 939)"/>
<path d=""  transform="translate(1005, 793)"/>
<path d=""  transform="translate(1465, 1037)"/>
<path d=""  transform="translate(1379, 939)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ស៉ូ័ះ្លណ៊ទ៎រ៑ិ</span> (Added by SIESTA)</li>


<pre>Expected: uni179F=0+928|uni17C9=0@-19,146+0|uni17BC=0@7,244+0|uni17D0=0@494,372+0|uni17C7=0+386|uni25CC=0+635|uni17D2179B=0@0,228+0|uni178E=7+1240|uni17CA17CE=7@-313,146+0|uni1791=7+599|uni179A=11+288|uni17D1.r=11@160,156+0|uni17B7=11@172,298+0</pre>



<pre>Got     : uni179F=0+928|uni17C9=0@-19,146+0|uni17BC=0@7,244+0|uni17D0=0@478,372+0|uni17C7=0+386|uni25CC=0+635|uni17D2179B=0@0,228+0|uni178E=7+1240|uni17CA17CE=7@-313,146+0|uni1791=7+599|uni179A=11+288|uni17D1.r=11@160,156+0|uni17B7=11@172,298+0</pre>



<pre>                                                                         ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4076 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(909, 939)"/>
<path d=""  transform="translate(935, 1037)"/>
<path d=""  transform="translate(1406, 1165)"/>
<path d=""  transform="translate(928, 793)"/>
<path d=""  transform="translate(1314, 793)"/>
<path d=""  transform="translate(1949, 1021)"/>
<path d=""  transform="translate(1949, 793)"/>
<path d=""  transform="translate(2876, 939)"/>
<path d=""  transform="translate(3189, 793)"/>
<path d=""  transform="translate(3788, 793)"/>
<path d=""  transform="translate(4236, 949)"/>
<path d=""  transform="translate(4248, 1091)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4076 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(909, 939)"/>
<path d=""  transform="translate(935, 1037)"/>
<path d=""  transform="translate(1422, 1165)"/>
<path d=""  transform="translate(928, 793)"/>
<path d=""  transform="translate(1314, 793)"/>
<path d=""  transform="translate(1949, 1021)"/>
<path d=""  transform="translate(1949, 793)"/>
<path d=""  transform="translate(2876, 939)"/>
<path d=""  transform="translate(3189, 793)"/>
<path d=""  transform="translate(3788, 793)"/>
<path d=""  transform="translate(4236, 949)"/>
<path d=""  transform="translate(4248, 1091)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ី៑វី៎័ែ</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+635|uni17B8=0@-7,160+0|uni17D1=0@-20,456+0|uni179C=2+326|uni17B8.r=2@66,166+0|uni17CE=2@152,452+0|uni17D0=2@152,731+0|uni17C2=2@51,0+339|uni25CC=2+635</pre>



<pre>Got     : uni25CC=0+635|uni17B8=0@-7,160+0|uni17D1=0@-20,456+0|uni179C=2+326|uni17B8.r=2@66,166+0|uni17CE=2@152,452+0|uni17D0=2@152,731+0|uni17C2=2+288|uni25CC=2+635</pre>



<pre>                                                                                                                                                   +++++ ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1884 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(628, 953)"/>
<path d=""  transform="translate(615, 1249)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1027, 959)"/>
<path d=""  transform="translate(1113, 1245)"/>
<path d=""  transform="translate(1113, 1524)"/>
<path d=""  transform="translate(961, 793)"/>
<path d=""  transform="translate(1249, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1935 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(628, 953)"/>
<path d=""  transform="translate(615, 1249)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1027, 959)"/>
<path d=""  transform="translate(1113, 1245)"/>
<path d=""  transform="translate(1113, 1524)"/>
<path d=""  transform="translate(1012, 793)"/>
<path d=""  transform="translate(1300, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">អ៉័ះ្ឝរ៓៝</span> (Added by SIESTA)</li>


<pre>Expected: uni17A2=0+635|uni17C9=0@-10,146+0|uni17D0=0@503,372+0|uni17C7=0+386|uni25CC=0+635|uni17D2179D=0@0,228+0|uni179A=6+288|uni17D3.r=6@159,136+0|uni17DD=6@165,146+0</pre>



<pre>Got     : uni17A2=0+635|uni17C9=0@-10,146+0|uni17D0=0@487,372+0|uni17C7=0+386|uni25CC=0+635|uni17D2179D=0@0,228+0|uni179A=6+288|uni17D3.r=6@159,136+0|uni17DD=6@165,146+0</pre>



<pre>                                                      ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1944 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(625, 939)"/>
<path d=""  transform="translate(1122, 1165)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1021, 793)"/>
<path d=""  transform="translate(1656, 1021)"/>
<path d=""  transform="translate(1656, 793)"/>
<path d=""  transform="translate(2103, 929)"/>
<path d=""  transform="translate(2109, 939)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1944 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(625, 939)"/>
<path d=""  transform="translate(1138, 1165)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1021, 793)"/>
<path d=""  transform="translate(1656, 1021)"/>
<path d=""  transform="translate(1656, 793)"/>
<path d=""  transform="translate(2103, 929)"/>
<path d=""  transform="translate(2109, 939)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">វ៏៏វ័ះវ៝</span> (Added by SIESTA)</li>


<pre>Expected: uni179C=0+326|uni17CF.r=0@152,166+0|uni17CF=0@152,422+0|uni179C=3+326|uni17D0=3@483,166+0|uni17C7=3+386|uni179C=6+326|uni17DD.r=6@162,166+0</pre>



<pre>Got     : uni179C=0+326|uni17CF.r=0@152,166+0|uni17CF=0@152,422+0|uni179C=3+326|uni17D0=3@493,166+0|uni17C7=3+386|uni179C=6+326|uni17DD.r=6@162,166+0</pre>



<pre>                                                                                           ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1364 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(478, 959)"/>
<path d=""  transform="translate(478, 1215)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(1145, 959)"/>
<path d=""  transform="translate(652, 793)"/>
<path d=""  transform="translate(1038, 793)"/>
<path d=""  transform="translate(1526, 959)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1364 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(478, 959)"/>
<path d=""  transform="translate(478, 1215)"/>
<path d=""  transform="translate(326, 793)"/>
<path d=""  transform="translate(1135, 959)"/>
<path d=""  transform="translate(652, 793)"/>
<path d=""  transform="translate(1038, 793)"/>
<path d=""  transform="translate(1526, 959)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">រា់វ‌ា៝័ ែឃ៉ុ័ះ</span> (Added by SIESTA)</li>


<pre>Expected: uni179A17B6=0+615|uni17CB.r=0@7,97+0|uni179C=3+326|space=4+0|uni25CC=4+635|uni17B6=4+288|uni17DD=4+0|uni25CC=4+635|uni17D0=4@-7,160+0|space=8+260|uni17C2=8@51,0+339|uni25CC=8+635|uni1783=10+928|uni17C9=10@3,146+0|uni17BB=10@8,244+0|uni17D0=10@516,372+0|uni17C7=10+386</pre>



<pre>Got     : uni179A17B6=0+615|uni17CB.r=0@7,97+0|uni179C=3+326|space=4+0|uni25CC=4+635|uni17B6=4+288|uni17DD=4+0|uni25CC=4+635|uni17D0=4@-7,160+0|space=8+260|uni17C2=8+288|uni25CC=8+635|uni1783=10+928|uni17C9=10@3,146+0|uni17BB=10@8,244+0|uni17D0=10@500,372+0|uni17C7=10+386</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4996 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(622, 890)"/>
<path d=""  transform="translate(615, 793)"/>
<path d=""  transform="translate(941, 793)"/>
<path d=""  transform="translate(941, 793)"/>
<path d=""  transform="translate(1576, 793)"/>
<path d=""  transform="translate(1864, 793)"/>
<path d=""  transform="translate(1864, 793)"/>
<path d=""  transform="translate(2492, 953)"/>
<path d=""  transform="translate(2499, 793)"/>
<path d=""  transform="translate(2759, 793)"/>
<path d=""  transform="translate(3047, 793)"/>
<path d=""  transform="translate(3682, 793)"/>
<path d=""  transform="translate(4613, 939)"/>
<path d=""  transform="translate(4618, 1037)"/>
<path d=""  transform="translate(5110, 1165)"/>
<path d=""  transform="translate(4610, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5047 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(622, 890)"/>
<path d=""  transform="translate(615, 793)"/>
<path d=""  transform="translate(941, 793)"/>
<path d=""  transform="translate(941, 793)"/>
<path d=""  transform="translate(1576, 793)"/>
<path d=""  transform="translate(1864, 793)"/>
<path d=""  transform="translate(1864, 793)"/>
<path d=""  transform="translate(2492, 953)"/>
<path d=""  transform="translate(2499, 793)"/>
<path d=""  transform="translate(2810, 793)"/>
<path d=""  transform="translate(3098, 793)"/>
<path d=""  transform="translate(3733, 793)"/>
<path d=""  transform="translate(4664, 939)"/>
<path d=""  transform="translate(4669, 1037)"/>
<path d=""  transform="translate(5177, 1165)"/>
<path d=""  transform="translate(4661, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ឆិ័ណ៉័ះ</span> (Added by SIESTA)</li>


<pre>Expected: uni1786=0+635|uni17B7=0@-23,146+0|uni17D0=0@-23,392+0|uni178E=3+1240|uni17C9=3@-313,146+0|uni17D0=3@503,372+0|uni17C7=3+386</pre>



<pre>Got     : uni1786=0+635|uni17B7=0@-23,146+0|uni17D0=0@-23,392+0|uni178E=3+1240|uni17C9=3@-313,146+0|uni17D0=3@485,372+0|uni17C7=3+386</pre>



<pre>                                                                                                               ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2261 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(612, 939)"/>
<path d=""  transform="translate(612, 1185)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1562, 939)"/>
<path d=""  transform="translate(2360, 1165)"/>
<path d=""  transform="translate(1875, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2261 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(612, 939)"/>
<path d=""  transform="translate(612, 1185)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1562, 939)"/>
<path d=""  transform="translate(2378, 1165)"/>
<path d=""  transform="translate(1875, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ញាគ៉ួ័ះរុ័ះឤ៉័ះរ៑៊</span> (Added by SIESTA)</li>


<pre>Expected: uni178917B6=0+1240|uni1782=2+635|uni17C9=2@-7,146+0|uni17BD=2@-8,244+0|uni17D0=2@506,372+0|uni17C7=2+386|uni179A=7+288|uni17BB=7@172,244+0|uni17D0=7@503,146+0|uni17C7=7+386|uni17A4=11+933|uni17C9=11@60,146+0|uni17D0=11@503,372+0|uni17C7=11+386|uni179A=15+288|uni17D1.r=15@160,156+0|uni17CA=15@172,298+0</pre>



<pre>Got     : uni178917B6=0+1240|uni1782=2+635|uni17C9=2@-7,146+0|uni17BD=2@-8,244+0|uni17D0=2@490,372+0|uni17C7=2+386|uni179A=7+288|uni17BB=7@172,244+0|uni17D0=7@513,146+0|uni17C7=7+386|uni17A4=11+933|uni17C9=11@60,146+0|uni17D0=11@488,372+0|uni17C7=11+386|uni179A=15+288|uni17D1.r=15@160,156+0|uni17CA=15@172,298+0</pre>



<pre>                                                                                           ^^^                                                                  ^                                                                    ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4542 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1240, 793)"/>
<path d=""  transform="translate(1868, 939)"/>
<path d=""  transform="translate(1867, 1037)"/>
<path d=""  transform="translate(2365, 1165)"/>
<path d=""  transform="translate(1875, 793)"/>
<path d=""  transform="translate(2261, 793)"/>
<path d=""  transform="translate(2721, 1037)"/>
<path d=""  transform="translate(3062, 939)"/>
<path d=""  transform="translate(2549, 793)"/>
<path d=""  transform="translate(2935, 793)"/>
<path d=""  transform="translate(3928, 939)"/>
<path d=""  transform="translate(4356, 1165)"/>
<path d=""  transform="translate(3868, 793)"/>
<path d=""  transform="translate(4254, 793)"/>
<path d=""  transform="translate(4702, 949)"/>
<path d=""  transform="translate(4714, 1091)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4542 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1240, 793)"/>
<path d=""  transform="translate(1868, 939)"/>
<path d=""  transform="translate(1867, 1037)"/>
<path d=""  transform="translate(2381, 1165)"/>
<path d=""  transform="translate(1875, 793)"/>
<path d=""  transform="translate(2261, 793)"/>
<path d=""  transform="translate(2721, 1037)"/>
<path d=""  transform="translate(3052, 939)"/>
<path d=""  transform="translate(2549, 793)"/>
<path d=""  transform="translate(2935, 793)"/>
<path d=""  transform="translate(3928, 939)"/>
<path d=""  transform="translate(4371, 1165)"/>
<path d=""  transform="translate(3868, 793)"/>
<path d=""  transform="translate(4254, 793)"/>
<path d=""  transform="translate(4702, 949)"/>
<path d=""  transform="translate(4714, 1091)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ឃ័ះរ័្ដឬ៓</span> (Added by SIESTA)</li>


<pre>Expected: uni1783=0+928|uni17D0=0@516,146+0|uni17C7=0+386|uni179A=3+288|uni17D0=3@172,146+0|uni17D2178A.r=3@58,228+0|uni17AC=7+684|uni17D3=7@-80,136+0</pre>



<pre>Got     : uni1783=0+928|uni17D0=0@500,146+0|uni17C7=0+386|uni179A=3+288|uni17D0=3@172,146+0|uni17D2178A.r=3@58,228+0|uni17AC=7+684|uni17D3=7@-80,136+0</pre>



<pre>                                   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2286 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1428, 939)"/>
<path d=""  transform="translate(928, 793)"/>
<path d=""  transform="translate(1314, 793)"/>
<path d=""  transform="translate(1774, 939)"/>
<path d=""  transform="translate(1660, 1021)"/>
<path d=""  transform="translate(1602, 793)"/>
<path d=""  transform="translate(2206, 929)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2286 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1444, 939)"/>
<path d=""  transform="translate(928, 793)"/>
<path d=""  transform="translate(1314, 793)"/>
<path d=""  transform="translate(1774, 939)"/>
<path d=""  transform="translate(1660, 1021)"/>
<path d=""  transform="translate(1602, 793)"/>
<path d=""  transform="translate(2206, 929)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ឤ៉ូ័ះបឤុ័ះវ៊៑៏</span> (Added by SIESTA)</li>


<pre>Expected: uni17A4=0+933|uni17C9=0@60,146+0|uni17BC=0@16,244+0|uni17D0=0@503,372+0|uni17C7=0+386|uni1794=5+635|uni17A4=6+933|uni17BB=6@16,244+0|uni17D0=6@503,146+0|uni17C7=6+386|uni179C=10+326|uni17CA.r=10@152,166+0|uni17D1=10@139,288+0|uni17CF=10@152,430+0</pre>



<pre>Got     : uni17A4=0+933|uni17C9=0@60,146+0|uni17BC=0@16,244+0|uni17D0=0@488,372+0|uni17C7=0+386|uni1794=5+635|uni17A4=6+933|uni17BB=6@16,244+0|uni17D0=6@488,146+0|uni17C7=6+386|uni179C=10+326|uni17CA.r=10@152,166+0|uni17D1=10@139,288+0|uni17CF=10@152,430+0</pre>



<pre>                                                                        ^^^                                                                              ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3599 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(993, 939)"/>
<path d=""  transform="translate(949, 1037)"/>
<path d=""  transform="translate(1421, 1165)"/>
<path d=""  transform="translate(933, 793)"/>
<path d=""  transform="translate(1319, 793)"/>
<path d=""  transform="translate(1954, 793)"/>
<path d=""  transform="translate(2903, 1037)"/>
<path d=""  transform="translate(3375, 939)"/>
<path d=""  transform="translate(2887, 793)"/>
<path d=""  transform="translate(3273, 793)"/>
<path d=""  transform="translate(3751, 959)"/>
<path d=""  transform="translate(3738, 1081)"/>
<path d=""  transform="translate(3751, 1223)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3599 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(993, 939)"/>
<path d=""  transform="translate(949, 1037)"/>
<path d=""  transform="translate(1436, 1165)"/>
<path d=""  transform="translate(933, 793)"/>
<path d=""  transform="translate(1319, 793)"/>
<path d=""  transform="translate(1954, 793)"/>
<path d=""  transform="translate(2903, 1037)"/>
<path d=""  transform="translate(3390, 939)"/>
<path d=""  transform="translate(2887, 793)"/>
<path d=""  transform="translate(3273, 793)"/>
<path d=""  transform="translate(3751, 959)"/>
<path d=""  transform="translate(3738, 1081)"/>
<path d=""  transform="translate(3751, 1223)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">្ឫឋ៉័ះឪ័ះវ៝៝</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+635|uni17D217AB=0@18,228+0|uni178B=2+635|uni17C9=2@-28,166+0|uni17D0=2@485,392+0|uni17C7=2+386|uni17AA=6+636|uni17D0=6@494,375+0|uni17C7=6+386|uni179C=9+326|uni17DD.r=9@162,166+0|uni17DD=9@145,166+0</pre>



<pre>Got     : uni25CC=0+635|uni17D217AB=0@18,228+0|uni178B=2+635|uni17C9=2@-28,166+0|uni17D0=2@469,392+0|uni17C7=2+386|uni17AA=6+636|uni17D0=6@478,375+0|uni17C7=6+386|uni179C=9+326|uni17DD.r=9@162,166+0|uni17DD=9@145,166+0</pre>



<pre>                                                                                            ^^                                              ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3004 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(653, 1021)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1242, 959)"/>
<path d=""  transform="translate(1739, 1185)"/>
<path d=""  transform="translate(1270, 793)"/>
<path d=""  transform="translate(1656, 793)"/>
<path d=""  transform="translate(2770, 1168)"/>
<path d=""  transform="translate(2292, 793)"/>
<path d=""  transform="translate(2678, 793)"/>
<path d=""  transform="translate(3166, 959)"/>
<path d=""  transform="translate(3149, 959)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3004 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(653, 1021)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1242, 959)"/>
<path d=""  transform="translate(1755, 1185)"/>
<path d=""  transform="translate(1270, 793)"/>
<path d=""  transform="translate(1656, 793)"/>
<path d=""  transform="translate(2786, 1168)"/>
<path d=""  transform="translate(2292, 793)"/>
<path d=""  transform="translate(2678, 793)"/>
<path d=""  transform="translate(3166, 959)"/>
<path d=""  transform="translate(3149, 959)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">៑័ប៉ុ័ះ៊៎ឬុ័ះហ៊ើ</span> (Added by SIESTA)</li>


<pre>Expected: uni25CC=0+635|uni17D1=0@-20,170+0|uni17D0=0@-7,312+0|uni1794=2+635|uni17C9=2@-18,146+0|uni17BB=2@-8,244+0|uni17D0=2@495,372+0|uni17C7=2+386|uni17CA=2+0|uni25CC=2+635|uni17CE=2@-7,160+0|uni17AC=9+684|uni17BB=9+0|uni17D0=9@503,146+0|uni17C7=9+386|uni17C1=13+288|uni17A0=13+928|uni17BB=13@13,244+0|uni17B8=13@3,146+0</pre>



<pre>Got     : uni25CC=0+635|uni17D1=0@-20,170+0|uni17D0=0@-7,312+0|uni1794=2+635|uni17C9=2@-18,146+0|uni17BB=2@-8,244+0|uni17D0=2@479,372+0|uni17C7=2+386|uni17CA=2+0|uni25CC=2+635|uni17CE=2@-7,160+0|uni17AC=9+684|uni17BB=9+0|uni17D0=9@480,146+0|uni17C7=9+386|uni17C1=13+288|uni17A0=13+928|uni17BB=13@13,244+0|uni17B8=13@3,146+0</pre>



<pre>                                                                                                                               ^^                                                                                                      ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4577 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(615, 963)"/>
<path d=""  transform="translate(628, 1105)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1252, 939)"/>
<path d=""  transform="translate(1262, 1037)"/>
<path d=""  transform="translate(1749, 1165)"/>
<path d=""  transform="translate(1270, 793)"/>
<path d=""  transform="translate(1656, 793)"/>
<path d=""  transform="translate(1656, 793)"/>
<path d=""  transform="translate(2284, 953)"/>
<path d=""  transform="translate(2291, 793)"/>
<path d=""  transform="translate(2975, 793)"/>
<path d=""  transform="translate(3455, 939)"/>
<path d=""  transform="translate(2975, 793)"/>
<path d=""  transform="translate(3361, 793)"/>
<path d=""  transform="translate(3649, 793)"/>
<path d=""  transform="translate(4590, 1037)"/>
<path d=""  transform="translate(4580, 939)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4577 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(615, 963)"/>
<path d=""  transform="translate(628, 1105)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1252, 939)"/>
<path d=""  transform="translate(1262, 1037)"/>
<path d=""  transform="translate(1765, 1165)"/>
<path d=""  transform="translate(1270, 793)"/>
<path d=""  transform="translate(1656, 793)"/>
<path d=""  transform="translate(1656, 793)"/>
<path d=""  transform="translate(2284, 953)"/>
<path d=""  transform="translate(2291, 793)"/>
<path d=""  transform="translate(2975, 793)"/>
<path d=""  transform="translate(3478, 939)"/>
<path d=""  transform="translate(2975, 793)"/>
<path d=""  transform="translate(3361, 793)"/>
<path d=""  transform="translate(3649, 793)"/>
<path d=""  transform="translate(4590, 1037)"/>
<path d=""  transform="translate(4580, 939)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ខ៉័ះវិឹង៉ិរ៏៎ៅ</span> (Added by SIESTA)</li>


<pre>Expected: uni1781=0+635|uni17C9=0@-7,146+0|uni17D0=0@506,372+0|uni17C7=0+386|uni179C=4+326|uni17B7.r=4@66,166+0|uni25CC=4+635|uni17B9=4@-7,160+0|uni1784=7+635|uni17BB=7@-7,244+0|uni17B7=7@-35,166+0|uni17C1=10+288|uni179A17C5=10+615|uni17CF.r=10@-155,146+0|uni17CE=10@-155,402+0</pre>



<pre>Got     : uni1781=0+635|uni17C9=0@-7,146+0|uni17D0=0@490,372+0|uni17C7=0+386|uni179C=4+326|uni17B7.r=4@66,166+0|uni25CC=4+635|uni17B9=4@-7,160+0|uni1784=7+635|uni17BB=7@-7,244+0|uni17B7=7@-35,166+0|uni17C1=10+288|uni179A17C5=10+615|uni17CF.r=10@-155,146+0|uni17CE=10@-155,402+0</pre>



<pre>                                                     ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3520 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(628, 939)"/>
<path d=""  transform="translate(1125, 1165)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1021, 793)"/>
<path d=""  transform="translate(1413, 959)"/>
<path d=""  transform="translate(1347, 793)"/>
<path d=""  transform="translate(1975, 953)"/>
<path d=""  transform="translate(1982, 793)"/>
<path d=""  transform="translate(2610, 1037)"/>
<path d=""  transform="translate(2582, 959)"/>
<path d=""  transform="translate(2617, 793)"/>
<path d=""  transform="translate(2905, 793)"/>
<path d=""  transform="translate(3365, 939)"/>
<path d=""  transform="translate(3365, 1195)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3520 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(628, 939)"/>
<path d=""  transform="translate(1141, 1165)"/>
<path d=""  transform="translate(635, 793)"/>
<path d=""  transform="translate(1021, 793)"/>
<path d=""  transform="translate(1413, 959)"/>
<path d=""  transform="translate(1347, 793)"/>
<path d=""  transform="translate(1975, 953)"/>
<path d=""  transform="translate(1982, 793)"/>
<path d=""  transform="translate(2610, 1037)"/>
<path d=""  transform="translate(2582, 959)"/>
<path d=""  transform="translate(2617, 793)"/>
<path d=""  transform="translate(2905, 793)"/>
<path d=""  transform="translate(3365, 939)"/>
<path d=""  transform="translate(3365, 1195)"/>
</svg>


</div> [code: shaping-regression]
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
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemetleft

	- guillemetright 

	- And uni00A0
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[16] NotoSansKhmerUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
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
 FONT_FAMILY_NAME = 'Noto Sans Khmer UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemetleft

	- guillemetright 

	- And uni00A0
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wacute (U+1E82): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wcircumflex (U+0174): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wdieresis (U+1E84): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216 

	* And Wgrave (U+1E80): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSansKhmerUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
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
 FONT_FAMILY_NAME = 'Noto Sans Khmer UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemetleft

	- guillemetright 

	- And uni00A0
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,418.0>--<98.0,958.0>>

	* exclam (U+0021): L<<126.0,958.0>--<124.0,418.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>> 

	* And exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSansKhmerUI[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansKhmerUI/googlefonts/slim-variable-ttf/NotoSansKhmerUI[wght].ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Black.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Bold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-ExtraLight.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Light.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Medium.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Regular.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-SemiBold.ttf', 'fonts/NotoSansKhmerUI/googlefonts/ttf/NotoSansKhmerUI-Thin.ttf', 'fonts/NotoSansKhmerUI/googlefonts/variable-ttf/NotoSansKhmerUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 436, but got 293 instead. [code: descent]
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

	- uni00A0.1 

	- And guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni17B4 (U+17B4) and uni17B5 (U+17B5) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+17BE [code: non-mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 62 | 110 | 1228 | 77 | 958 | 0 |
| 0% | 3% | 5% | 50% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**