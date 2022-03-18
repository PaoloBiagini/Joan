## Fontbakery report

Fontbakery version: 0.8.8.dev29+g809e15c6

<details><summary><b>[1] Family checks</b></summary><div><details><summary>ℹ <b>INFO:</b> Check axis ordering on the STAT table.  (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT/axis_order">com.google.fonts/check/STAT/axis_order</a>)</summary><div>


* ℹ **INFO** From a total of 1 font files, 1 of them (100.00%) lack a STAT table.

	And these are the most common STAT axis orderings:
	 [code: summary]
</div></details><br></div></details><details><summary><b>[18] Joan-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/ttx-roundtrip">com.google.fonts/check/ttx-roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
* ℹ **INFO** While converting TTF into an XML file, ttx emited the messages listed below.
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- T + T
	- T + h
	- f + f
	- f + l
	- l + f
	- f + b
	- b + f
	- f + h
	- h + f
	- f + i
	- i + f
	- f + j
	- j + f
	- f + k
	- k + f
	- f + t
	- t + b
	- h + i
	- i + j
	- j + k
	- k + l
	- l + t
	- longs + longs
	- longs + b
	- b + longs
	- longs + h
	- h + longs
	- longs + i
	- i + longs
	- longs + j
	- j + longs
	- longs + k
	- k + longs
	- longs + l
	- l + longs
	- longs + t
	- b + h
	- t + f
	- f + longs
	- t.sc + t.sc

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2
	- Glyph name: uni01F5	Contours detected: 4	Expected: 3
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1 
	- And Glyph name: aogonek	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* radical (U+221A): L<<48.0,402.0>--<114.0,429.0>> -> L<<114.0,429.0>--<187.0,456.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* at (U+0040): L<<530.0,1.0>--<572.0,209.0>>/B<<572.0,209.0>-<545.0,148.0>-<509.0,99.0>> = 12.45944132952049
	* ornament350 (U+E027): B<<170.0,17.5>-<176.0,34.0>-<185.0,58.0>>/B<<185.0,58.0>-<176.0,45.0>-<157.0,32.0>> = 14.139108311650475 and ornament355 (U+E02C): B<<797.5,358.5>-<766.0,348.0>-<731.0,334.0>>/B<<731.0,334.0>-<782.0,341.0>-<808.5,329.0>> = 13.98611593958492 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * d (U+0064): L<<360.0,446.0>--<359.0,704.0>>
 * d (U+0064): L<<362.0,114.0>--<361.0,357.0>>
 * dcaron (U+010F): L<<360.0,446.0>--<359.0,704.0>>
 * dcaron (U+010F): L<<362.0,114.0>--<361.0,357.0>>
 * dcroat (U+0111): L<<362.0,114.0>--<361.0,357.0>>
 * germandbls (U+00DF): L<<187.0,537.0>--<188.0,46.0>>
 * ornament300 (U+E000): L<<44.0,269.0>--<809.0,264.0>>
 * ornament300 (U+E000): L<<809.0,227.0>--<28.0,221.0>>
 * ornament302 (U+E002): L<<205.0,-125.0>--<199.0,656.0>>
 * ornament302 (U+E002): L<<247.0,640.0>--<242.0,-125.0>> and 16 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><details><summary>ℹ <b>INFO:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* ℹ **INFO** Hinting filesize impact:

 |               | Joan-Regular.ttf          |
 |:------------- | ---------------:|
 | Dehinted Size | 390.5kb |
 | Hinted Size   | 449.9kb   |
 | Increase      | 59.4kb      |
 | Change        | 15.2 %  |
 [code: size-impact]
</div></details><details><summary>ℹ <b>INFO:</b> EPAR table present in font? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/epar">com.google.fonts/check/epar</a>)</summary><div>


* ℹ **INFO** EPAR table not present in font. To learn more see https://github.com/googlefonts/fontbakery/issues/818 [code: lacks-EPAR]
</div></details><details><summary>ℹ <b>INFO:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* ℹ **INFO** These are the ppm ranges declared on the gasp table:

PPM <= 65535:
	flag = 0x0F
	- Use grid-fitting
	- Use grayscale rendering
	- Use gridfitting with ClearType symmetric smoothing
	- Use smoothing along multiple axes with ClearType®
 [code: ranges]
</div></details><details><summary>ℹ <b>INFO:</b> Check for font-v versioning. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontv">com.google.fonts/check/fontv</a>)</summary><div>


* ℹ **INFO** Version string is: "Version 1.000; ttfautohint (v1.8.3)"
The version string must ideally include a git commit hash and either a "dev" or a "release" suffix such as in the example below:
"Version 1.3; git-0d08353-release" [code: bad-format]
</div></details><details><summary>ℹ <b>INFO:</b> Font contains all required tables? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/required_tables">com.google.fonts/check/required_tables</a>)</summary><div>


* ℹ **INFO** This font contains the following optional tables:
	- cvt 
	- fpgm
	- loca
	- prep
	- GPOS
	- GSUB 
	- And gasp [code: optional-tables]
</div></details><details><summary>ℹ <b>INFO:</b> List all superfamily filepaths (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/superfamily/list">com.google.fonts/check/superfamily/list</a>)</summary><div>


* ℹ **INFO** . [code: family-path]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 11 | 107 | 7 | 99 | 0 |
| 0% | 0% | 5% | 48% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **PASS**
* **DEBUG**
