## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[14] Fruktur-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 558, but got 540 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* ibreve
	* exclamdown
	* uni01CA
	* obreve
	* Ygrave
	* racute
	* quotereversed
	* Gcircumflex
	* Ucircumflex
	* Ycircumflex and 199 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + f
	- f + i
	- i + f
	- f + l
	- l + f
	- i + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- .null
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: ohorn	Contours detected: 3	Expected: 2
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2
	- Glyph name: uni01EB	Contours detected: 3	Expected: 2
	- Glyph name: Oslashacute	Contours detected: 3	Expected: 4 
	- And 52 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* Eng (U+014A): L<<1212.0,348.0>--<1264.0,60.0>> -> L<<1264.0,60.0>--<1291.0,-60.0>>
	* Eng (U+014A): L<<906.0,-5.0>--<793.0,245.0>> -> L<<793.0,245.0>--<356.0,1170.0>>
	* M (U+004D): L<<193.0,296.0>--<193.0,305.0>> -> L<<193.0,305.0>--<262.0,1175.0>>
	* OE (U+0152): L<<1034.0,1419.0>--<1222.0,1455.0>> -> L<<1222.0,1455.0>--<1591.0,1549.0>>
	* W (U+0057): L<<314.0,291.0>--<107.0,1086.0>> -> L<<107.0,1086.0>--<104.0,1097.0>>
	* Wacute (U+1E82): L<<314.0,291.0>--<107.0,1086.0>> -> L<<107.0,1086.0>--<104.0,1097.0>>
	* Wcircumflex (U+0174): L<<314.0,291.0>--<107.0,1086.0>> -> L<<107.0,1086.0>--<104.0,1097.0>>
	* Wdieresis (U+1E84): L<<314.0,291.0>--<107.0,1086.0>> -> L<<107.0,1086.0>--<104.0,1097.0>>
	* Wgrave (U+1E80): L<<314.0,291.0>--<107.0,1086.0>> -> L<<107.0,1086.0>--<104.0,1097.0>>
	* dong (U+20AB): L<<185.0,203.0>--<632.0,233.0>> -> L<<632.0,233.0>--<1109.0,271.0>> and 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* X (U+0058): B<<671.5,1123.0>-<691.0,1011.0>-<696.0,936.0>>/B<<696.0,936.0>-<712.0,1059.0>-<731.0,1161.0>> = 11.225567693469205 and uni1E8C (U+1E8C): B<<671.5,1123.0>-<691.0,1011.0>-<696.0,936.0>>/B<<696.0,936.0>-<712.0,1059.0>-<731.0,1161.0>> = 11.225567693469205 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Euro (U+20AC): L<<848.0,495.0>--<503.0,494.0>>
 * Euro (U+20AC): L<<878.0,814.0>--<543.0,813.0>>
 * IJ (U+0132): L<<1107.0,726.0>--<1110.0,1160.0>>
 * J (U+004A): L<<441.0,726.0>--<444.0,1160.0>>
 * Jcircumflex (U+0134): L<<441.0,726.0>--<444.0,1160.0>>
 * U (U+0055): L<<524.0,1174.0>--<523.0,786.0>>
 * Uacute (U+00DA): L<<524.0,1174.0>--<523.0,786.0>>
 * Ubreve (U+016C): L<<524.0,1174.0>--<523.0,786.0>>
 * Ucircumflex (U+00DB): L<<524.0,1174.0>--<523.0,786.0>>
 * Udieresis (U+00DC): L<<524.0,1174.0>--<523.0,786.0>> and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 13 | 104 | 7 | 100 | 0 |
| 0% | 0% | 6% | 46% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
