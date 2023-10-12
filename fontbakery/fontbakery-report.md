## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[20] EduSABeginner-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x02D9 (DOT ABOVE)


	- 0x00A8 (DIAERESIS)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoAscender is 2642 when it should be 2032 [code: bad-typo-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoDescender is -926 when it should be -488 [code: bad-typo-descender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Ascender is 2642 when it should be 2032 [code: bad-hhea-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Descender is -926 when it should be -488 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, syriac, old-permic, math, malayalam, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* B
	* C
	* D
	* E
	* Euro
	* F
	* G
	* H
	* I
	* J
	* K
	* L
	* M
	* N
	* O
	* P
	* Q
	* R
	* S
	* T
	* U
	* V
	* W
	* X
	* Y
	* Z
	* a
	* ampersand
	* approxequal
	* asciicircum
	* asciitilde
	* asterisk
	* at
	* b
	* backslash
	* bar
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cent
	* colon
	* comma
	* copyright
	* d
	* degree
	* divide
	* dollar
	* e
	* eight
	* ellipsis
	* emdash
	* endash
	* equal
	* exclam
	* exclamdown
	* f
	* five
	* four
	* g
	* grave
	* greater
	* greaterequal
	* h
	* hyphen
	* i
	* infinity
	* j
	* k
	* l
	* less
	* lessequal
	* m
	* minus
	* multiply
	* n
	* nine
	* notequal
	* numbersign
	* o
	* one
	* p
	* parenleft
	* parenright
	* percent
	* period
	* periodcentered
	* plus
	* plusminus
	* q
	* question
	* questiondown
	* quotedbl
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
	* quotesingle
	* r
	* registered
	* s
	* semicolon
	* seven
	* six
	* slash
	* sterling
	* t
	* three
	* tilde
	* trademark
	* two
	* u
	* underscore
	* v
	* w
	* x
	* y
	* yen
	* z and zero
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Edu SA Beginner Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.cv21.alt

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- tildecomb.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 889 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 813:
less, greater

Width = 890:
notequal, equal

Width = 893:
plusminus

Width = 871:
multiply

Width = 886:
approxequal

Width = 898:
lessequal, greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=94.0,Y=-2.0 (should be at baseline 0?)

	* exclam (U+0021): X=94.0,Y=-2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=785.0,Y=2007.0 (should be at cap-height 2008?)

	* parenleft (U+0028): X=783.5,Y=2009.0 (should be at cap-height 2008?)

	* parenleft (U+0028): X=477.0,Y=-924.5 (should be at descender -926?)

	* parenright (U+0029): X=26.0,Y=-927.0 (should be at descender -926?)

	* period (U+002E): X=96.0,Y=-2.0 (should be at baseline 0?)

	* period (U+002E): X=96.0,Y=-2.0 (should be at baseline 0?)

	* colon (U+003A): X=96.0,Y=-2.0 (should be at baseline 0?)

	* colon (U+003A): X=96.0,Y=-2.0 (should be at baseline 0?)

	* at (U+0040): X=118.0,Y=0.5 (should be at baseline 0?)

	* A (U+0041): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Q (U+0051): X=1063.0,Y=-1.0 (should be at baseline 0?)

	* X (U+0058): X=1302.0,Y=2006.5 (should be at cap-height 2008?)

	* X (U+0058): X=95.0,Y=0.5 (should be at baseline 0?)

	* Y (U+0059): X=534.0,Y=1.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=249.0,Y=2007.0 (should be at cap-height 2008?)

	* bracketleft (U+005B): X=669.0,Y=2007.0 (should be at cap-height 2008?)

	* i (U+0069): X=318.0,Y=1083.0 (should be at x-height 1082?)

	* braceright (U+007D): X=286.0,Y=2006.5 (should be at cap-height 2008?)

	* sterling (U+00A3): X=549.0,Y=2009.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=314.5,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=589.0,Y=2009.0 (should be at cap-height 2008?)

	* section (U+00A7): X=837.0,Y=2009.0 (should be at cap-height 2008?)

	* paragraph (U+00B6): X=1165.0,Y=2006.0 (should be at cap-height 2008?)

	* paragraph (U+00B6): X=1569.0,Y=2006.0 (should be at cap-height 2008?)

	* questiondown (U+00BF): X=491.0,Y=-1.0 (should be at baseline 0?)

	* questiondown (U+00BF): X=491.0,Y=-1.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Aacute (U+00C1): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Aacute (U+00C1): X=1180.0,Y=2641.0 (should be at ascender 2642?)

	* Acircumflex (U+00C2): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Atilde (U+00C3): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Adieresis (U+00C4): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Aring (U+00C5): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Eacute (U+00C9): X=1165.0,Y=2641.0 (should be at ascender 2642?)

	* Iacute (U+00CD): X=791.0,Y=2641.0 (should be at ascender 2642?)

	* Oacute (U+00D3): X=1206.0,Y=2641.0 (should be at ascender 2642?)

	* Uacute (U+00DA): X=1259.0,Y=2641.0 (should be at ascender 2642?)

	* Yacute (U+00DD): X=534.0,Y=1.0 (should be at baseline 0?)

	* Yacute (U+00DD): X=1396.0,Y=2641.0 (should be at ascender 2642?)

	* germandbls (U+00DF): X=1022.5,Y=2007.0 (should be at cap-height 2008?)

	* oslash (U+00F8): X=321.0,Y=-2.0 (should be at baseline 0?)

	* Amacron (U+0100): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Abreve (U+0102): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Aogonek (U+0104): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Cacute (U+0106): X=1146.0,Y=2641.0 (should be at ascender 2642?)

	* Ccaron (U+010C): X=739.0,Y=2640.0 (should be at ascender 2642?)

	* Dcaron (U+010E): X=790.0,Y=2640.0 (should be at ascender 2642?)

	* Ecaron (U+011A): X=759.0,Y=2640.0 (should be at ascender 2642?)

	* Lacute (U+0139): X=1127.0,Y=2641.0 (should be at ascender 2642?)

	* lacute (U+013A): X=694.0,Y=2641.0 (should be at ascender 2642?)

	* Nacute (U+0143): X=1254.0,Y=2641.0 (should be at ascender 2642?)

	* Ncaron (U+0147): X=847.0,Y=2640.0 (should be at ascender 2642?)

	* Eng (U+014A): X=238.0,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=457.0,Y=2009.0 (should be at cap-height 2008?)

	* Eng (U+014A): X=238.0,Y=-1.0 (should be at baseline 0?)

	* eng (U+014B): X=857.0,Y=1.0 (should be at baseline 0?)

	* Racute (U+0154): X=1162.0,Y=2641.0 (should be at ascender 2642?)

	* Rcaron (U+0158): X=755.0,Y=2640.0 (should be at ascender 2642?)

	* Sacute (U+015A): X=1080.0,Y=2641.0 (should be at ascender 2642?)

	* Scaron (U+0160): X=674.0,Y=2640.0 (should be at ascender 2642?)

	* Tcaron (U+0164): X=656.0,Y=2640.0 (should be at ascender 2642?)

	* tcaron (U+0165): X=890.0,Y=2007.0 (should be at cap-height 2008?)

	* Ycircumflex (U+0176): X=534.0,Y=1.0 (should be at baseline 0?)

	* Ydieresis (U+0178): X=534.0,Y=1.0 (should be at baseline 0?)

	* Zacute (U+0179): X=1146.0,Y=2641.0 (should be at ascender 2642?)

	* Zcaron (U+017D): X=740.0,Y=2640.0 (should be at ascender 2642?)

	* Wacute (U+1E82): X=1782.0,Y=2641.0 (should be at ascender 2642?)

	* uni1E9E (U+1E9E): X=461.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=1626.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=708.0,Y=1.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=534.0,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=96.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=96.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=569.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=569.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1044.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1044.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<1074.0,1764.0>--<975.0,1514.0>> -> L<<975.0,1514.0>--<789.0,1146.0>>

	* AE (U+00C6): L<<1107.0,1146.0>--<1079.0,1502.0>> -> L<<1079.0,1502.0>--<1074.0,1764.0>>

	* oslash (U+00F8): L<<293.0,255.0>--<436.0,554.0>> -> L<<436.0,554.0>--<594.0,911.0>>

	* oslash (U+00F8): L<<691.0,807.0>--<540.0,502.0>> -> L<<540.0,502.0>--<390.0,157.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[21] EduSABeginner-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x02D9 (DOT ABOVE)


	- 0x00A8 (DIAERESIS)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoAscender is 2642 when it should be 2032 [code: bad-typo-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoDescender is -926 when it should be -488 [code: bad-typo-descender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Ascender is 2642 when it should be 2032 [code: bad-hhea-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Descender is -926 when it should be -488 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, syriac, old-permic, math, malayalam, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* B
	* C
	* D
	* E
	* Euro
	* F
	* G
	* H
	* I
	* J
	* K
	* L
	* M
	* N
	* O
	* P
	* Q
	* R
	* S
	* T
	* U
	* V
	* W
	* X
	* Y
	* Z
	* a
	* ampersand
	* approxequal
	* asciicircum
	* asciitilde
	* asterisk
	* at
	* b
	* backslash
	* bar
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cent
	* colon
	* comma
	* copyright
	* d
	* degree
	* divide
	* dollar
	* e
	* eight
	* ellipsis
	* emdash
	* endash
	* equal
	* exclam
	* exclamdown
	* f
	* five
	* four
	* g
	* grave
	* greater
	* greaterequal
	* h
	* hyphen
	* i
	* infinity
	* j
	* k
	* l
	* less
	* lessequal
	* m
	* minus
	* multiply
	* n
	* nine
	* notequal
	* numbersign
	* o
	* one
	* p
	* parenleft
	* parenright
	* percent
	* period
	* periodcentered
	* plus
	* plusminus
	* q
	* question
	* questiondown
	* quotedbl
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
	* quotesingle
	* r
	* registered
	* s
	* semicolon
	* seven
	* six
	* slash
	* sterling
	* t
	* three
	* tilde
	* trademark
	* two
	* u
	* underscore
	* v
	* w
	* x
	* y
	* yen
	* z and zero
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Edu SA Beginner SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.cv21.alt

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- tildecomb.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 939 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 854:
less

Width = 940:
plusminus, notequal, equal

Width = 856:
greater

Width = 909:
multiply

Width = 924:
approxequal

Width = 942:
lessequal, greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=125.0,Y=-1.0 (should be at baseline 0?)

	* exclam (U+0021): X=125.0,Y=-1.0 (should be at baseline 0?)

	* ampersand (U+0026): X=777.0,Y=2006.0 (should be at cap-height 2008?)

	* parenleft (U+0028): X=497.5,Y=-927.5 (should be at descender -926?)

	* parenright (U+0029): X=332.0,Y=2006.5 (should be at cap-height 2008?)

	* period (U+002E): X=127.0,Y=-1.0 (should be at baseline 0?)

	* period (U+002E): X=127.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=127.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=127.0,Y=-1.0 (should be at baseline 0?)

	* X (U+0058): X=1308.0,Y=2007.5 (should be at cap-height 2008?)

	* X (U+0058): X=1120.0,Y=0.5 (should be at baseline 0?)

	* X (U+0058): X=128.5,Y=-0.5 (should be at baseline 0?)

	* Y (U+0059): X=520.0,Y=1.5 (should be at baseline 0?)

	* b (U+0062): X=430.5,Y=1.5 (should be at baseline 0?)

	* d (U+0064): X=657.5,Y=1081.0 (should be at x-height 1082?)

	* g (U+0067): X=689.5,Y=1083.0 (should be at x-height 1082?)

	* braceright (U+007D): X=283.0,Y=2007.0 (should be at cap-height 2008?)

	* sterling (U+00A3): X=578.0,Y=2010.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=304.5,Y=1.5 (should be at baseline 0?)

	* paragraph (U+00B6): X=1222.0,Y=2007.0 (should be at cap-height 2008?)

	* paragraph (U+00B6): X=1680.0,Y=2007.0 (should be at cap-height 2008?)

	* questiondown (U+00BF): X=501.0,Y=-2.0 (should be at baseline 0?)

	* questiondown (U+00BF): X=501.0,Y=-2.0 (should be at baseline 0?)

	* Yacute (U+00DD): X=520.0,Y=1.5 (should be at baseline 0?)

	* Abreve (U+0102): X=1269.0,Y=2644.0 (should be at ascender 2642?)

	* Gbreve (U+011E): X=1390.0,Y=2644.0 (should be at ascender 2642?)

	* Eng (U+014A): X=257.0,Y=-2.0 (should be at baseline 0?)

	* Eng (U+014A): X=472.0,Y=2009.0 (should be at cap-height 2008?)

	* Eng (U+014A): X=257.0,Y=-2.0 (should be at baseline 0?)

	* eng (U+014B): X=184.0,Y=-1.0 (should be at baseline 0?)

	* eng (U+014B): X=1060.0,Y=2.0 (should be at baseline 0?)

	* Ubreve (U+016C): X=1367.0,Y=2644.0 (should be at ascender 2642?)

	* Ycircumflex (U+0176): X=520.0,Y=1.5 (should be at baseline 0?)

	* Ydieresis (U+0178): X=520.0,Y=1.5 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=520.0,Y=1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=127.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=127.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=656.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=656.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1188.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1188.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<1289.0,474.5>-<1284.0,432.0>-<1291.5,403.5>>

	* at (U+0040) contains a short segment B<<1291.5,403.5>-<1299.0,375.0>-<1326.0,375.0>>

	* M (U+004D) contains a short segment B<<84.0,0.0>-<48.0,0.0>-<17.5,19.0>>

	* M (U+004D) contains a short segment B<<17.5,19.0>-<-13.0,38.0>-<-23.0,74.5>>

	* M (U+004D) contains a short segment B<<844.0,1918.0>-<864.0,1961.0>-<889.5,1984.5>>

	* M (U+004D) contains a short segment B<<889.5,1984.5>-<915.0,2008.0>-<969.0,2008.0>>

	* M (U+004D) contains a short segment B<<1069.0,1980.0>-<1096.0,1952.0>-<1102.0,1903.0>>

	* M (U+004D) contains a short segment B<<1949.0,1915.0>-<1969.0,1957.0>-<2003.0,1982.5>>

	* M (U+004D) contains a short segment B<<2197.0,32.0>-<2162.0,64.0>-<2158.0,104.0>>

	* M (U+004D) contains a short segment B<<1329.0,86.0>-<1316.0,62.0>-<1287.5,31.0>>

	* M (U+004D) contains a short segment B<<1094.5,30.5>-<1065.0,61.0>-<1061.0,104.0>>

	* M (U+004D) contains a short segment B<<164.0,20.5>-<119.0,0.0>-<84.0,0.0>>

	* W (U+0057) contains a short segment B<<569.5,1978.5>-<604.0,1949.0>-<610.0,1907.0>>

	* W (U+0057) contains a short segment B<<1374.0,1909.0>-<1390.0,1950.0>-<1419.5,1979.0>>

	* W (U+0057) contains a short segment B<<1608.0,1980.0>-<1638.0,1952.0>-<1645.0,1907.0>>

	* W (U+0057) contains a short segment B<<2419.0,1917.0>-<2433.0,1952.0>-<2465.5,1980.0>>

	* yen (U+00A5) contains a short segment L<<287.0,306.0>--<264.0,306.0>>

	* Hbar (U+0126) contains a short segment L<<1702.0,1506.0>--<1736.0,1506.0>>

	* lslash (U+0142) contains a short segment L<<161.0,737.0>--<137.0,729.0>>

	* Eng (U+014A) contains a short segment B<<725.0,-361.0>-<758.0,-361.0>-<771.5,-360.5>>

	* Eng (U+014A) contains a short segment B<<771.5,-360.5>-<785.0,-360.0>-<793.0,-358.5>>

	* Eng (U+014A) contains a short segment B<<793.0,-358.5>-<801.0,-357.0>-<819.0,-356.0>>

	* Eng (U+014A) contains a short segment B<<1063.0,-202.0>-<1084.0,-172.0>-<1097.0,-143.0>>

	* Eng (U+014A) contains a short segment B<<1097.0,-143.0>-<1110.0,-114.0>-<1120.0,-72.5>>

	* eng (U+014B) contains a short segment B<<898.5,873.0>-<889.0,900.0>-<860.0,900.0>>

	* eng (U+014B) contains a short segment B<<179.0,972.0>-<182.0,992.0>-<194.5,1018.0>>

	* Wcircumflex (U+0174) contains a short segment B<<569.5,1978.5>-<604.0,1949.0>-<610.0,1907.0>>

	* Wcircumflex (U+0174) contains a short segment B<<1374.0,1909.0>-<1390.0,1950.0>-<1419.5,1979.0>>

	* Wcircumflex (U+0174) contains a short segment B<<1608.0,1980.0>-<1638.0,1952.0>-<1645.0,1907.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2419.0,1917.0>-<2433.0,1952.0>-<2465.5,1980.0>>

	* Wgrave (U+1E80) contains a short segment B<<569.5,1978.5>-<604.0,1949.0>-<610.0,1907.0>>

	* Wgrave (U+1E80) contains a short segment B<<1374.0,1909.0>-<1390.0,1950.0>-<1419.5,1979.0>>

	* Wgrave (U+1E80) contains a short segment B<<1608.0,1980.0>-<1638.0,1952.0>-<1645.0,1907.0>>

	* Wgrave (U+1E80) contains a short segment B<<2419.0,1917.0>-<2433.0,1952.0>-<2465.5,1980.0>>

	* Wacute (U+1E82) contains a short segment B<<569.5,1978.5>-<604.0,1949.0>-<610.0,1907.0>>

	* Wacute (U+1E82) contains a short segment B<<1374.0,1909.0>-<1390.0,1950.0>-<1419.5,1979.0>>

	* Wacute (U+1E82) contains a short segment B<<1608.0,1980.0>-<1638.0,1952.0>-<1645.0,1907.0>>

	* Wacute (U+1E82) contains a short segment B<<2419.0,1917.0>-<2433.0,1952.0>-<2465.5,1980.0>>

	* Wdieresis (U+1E84) contains a short segment B<<569.5,1978.5>-<604.0,1949.0>-<610.0,1907.0>>

	* Wdieresis (U+1E84) contains a short segment B<<1374.0,1909.0>-<1390.0,1950.0>-<1419.5,1979.0>>

	* Wdieresis (U+1E84) contains a short segment B<<1608.0,1980.0>-<1638.0,1952.0>-<1645.0,1907.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2419.0,1917.0>-<2433.0,1952.0>-<2465.5,1980.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<1760.0,1943.0>-<1778.0,1913.0>-<1775.5,1877.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<1775.5,1877.5>-<1773.0,1842.0>-<1751.0,1814.0>>

	* Euro (U+20AC) contains a short segment L<<609.0,1028.0>--<609.0,1027.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<1100.0,1154.0>--<1079.0,1442.0>> -> L<<1079.0,1442.0>--<1078.0,1688.0>>

	* oslash (U+00F8): L<<330.0,319.0>--<441.0,548.0>> -> L<<441.0,548.0>--<580.0,870.0>>

	* oslash (U+00F8): L<<686.0,757.0>--<552.0,498.0>> -> L<<552.0,498.0>--<431.0,207.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[20] EduSABeginner-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x02D9 (DOT ABOVE)


	- 0x00A8 (DIAERESIS)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoAscender is 2642 when it should be 2032 [code: bad-typo-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoDescender is -926 when it should be -488 [code: bad-typo-descender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Ascender is 2642 when it should be 2032 [code: bad-hhea-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Descender is -926 when it should be -488 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, syriac, old-permic, math, malayalam, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* B
	* C
	* D
	* E
	* Euro
	* F
	* G
	* H
	* I
	* J
	* K
	* L
	* M
	* N
	* O
	* P
	* Q
	* R
	* S
	* T
	* U
	* V
	* W
	* X
	* Y
	* Z
	* a
	* ampersand
	* approxequal
	* asciicircum
	* asciitilde
	* asterisk
	* at
	* b
	* backslash
	* bar
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cent
	* colon
	* comma
	* copyright
	* d
	* degree
	* divide
	* dollar
	* e
	* eight
	* ellipsis
	* emdash
	* endash
	* equal
	* exclam
	* exclamdown
	* f
	* five
	* four
	* g
	* grave
	* greater
	* greaterequal
	* h
	* hyphen
	* i
	* infinity
	* j
	* k
	* l
	* less
	* lessequal
	* m
	* minus
	* multiply
	* n
	* nine
	* notequal
	* numbersign
	* o
	* one
	* p
	* parenleft
	* parenright
	* percent
	* period
	* periodcentered
	* plus
	* plusminus
	* q
	* question
	* questiondown
	* quotedbl
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
	* quotesingle
	* r
	* registered
	* s
	* semicolon
	* seven
	* six
	* slash
	* sterling
	* t
	* three
	* tilde
	* trademark
	* two
	* u
	* underscore
	* v
	* w
	* x
	* y
	* yen
	* z and zero
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.cv21.alt

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- tildecomb.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 988 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 896:
less

Width = 991:
notequal, equal

Width = 898:
greater

Width = 948:
multiply

Width = 963:
approxequal

Width = 987:
lessequal, greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* X (U+0058): X=347.0,Y=2010.0 (should be at cap-height 2008?)

	* X (U+0058): X=1358.5,Y=2007.0 (should be at cap-height 2008?)

	* Y (U+0059): X=533.0,Y=0.5 (should be at baseline 0?)

	* braceleft (U+007B): X=645.0,Y=2006.0 (should be at cap-height 2008?)

	* braceright (U+007D): X=240.5,Y=2009.5 (should be at cap-height 2008?)

	* yen (U+00A5): X=322.0,Y=0.5 (should be at baseline 0?)

	* Yacute (U+00DD): X=533.0,Y=0.5 (should be at baseline 0?)

	* Eng (U+014A): X=488.0,Y=2010.0 (should be at cap-height 2008?)

	* eng (U+014B): X=200.0,Y=-1.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=533.0,Y=0.5 (should be at baseline 0?)

	* Ydieresis (U+0178): X=533.0,Y=0.5 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=533.0,Y=0.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* asterisk (U+002A) contains a short segment L<<347.0,1331.0>--<332.0,1321.0>>

	* asterisk (U+002A) contains a short segment L<<684.0,1867.0>--<694.0,1873.0>>

	* at (U+0040) contains a short segment B<<1249.0,1179.0>-<1268.0,1223.0>-<1304.5,1242.0>>

	* at (U+0040) contains a short segment B<<1382.0,554.0>-<1376.0,531.0>-<1371.0,499.5>>

	* at (U+0040) contains a short segment B<<1371.0,499.5>-<1366.0,468.0>-<1371.5,444.5>>

	* at (U+0040) contains a short segment B<<1371.5,444.5>-<1377.0,421.0>-<1400.0,421.0>>

	* M (U+004D) contains a short segment B<<1371.0,96.0>-<1362.0,78.0>-<1345.0,55.5>>

	* M (U+004D) contains a short segment B<<1345.0,55.5>-<1328.0,33.0>-<1293.5,16.5>>

	* W (U+0057) contains a short segment B<<2709.5,1906.0>-<2720.0,1864.0>-<2704.0,1826.0>>

	* q (U+0071) contains a short segment L<<893.0,-458.0>--<914.0,-440.0>>

	* s (U+0073) contains a short segment B<<522.0,295.0>-<522.0,306.0>-<515.0,318.0>>

	* y (U+0079) contains a short segment B<<398.5,274.0>-<409.0,259.0>-<434.0,259.0>>

	* sterling (U+00A3) contains a short segment B<<-42.0,125.0>-<-34.0,153.0>-<-22.0,169.0>>

	* sterling (U+00A3) contains a short segment B<<467.0,1714.0>-<452.0,1707.0>-<445.5,1690.5>>

	* sterling (U+00A3) contains a short segment B<<445.5,1690.5>-<439.0,1674.0>-<439.0,1654.0>>

	* yen (U+00A5) contains a short segment L<<1017.0,968.0>--<1021.0,968.0>>

	* Oslash (U+00D8) contains a short segment L<<826.0,259.0>--<829.0,259.0>>

	* eth (U+00F0) contains a short segment B<<725.0,1081.0>-<734.0,1081.0>-<746.5,1080.0>>

	* oslash (U+00F8) contains a short segment B<<471.0,259.0>-<472.0,259.0>-<477.0,259.0>>

	* yacute (U+00FD) contains a short segment B<<398.5,274.0>-<409.0,259.0>-<434.0,259.0>>

	* ydieresis (U+00FF) contains a short segment B<<398.5,274.0>-<409.0,259.0>-<434.0,259.0>>

	* Lslash (U+0141) contains a short segment L<<161.0,553.0>--<156.0,550.0>>

	* Eng (U+014A) contains a short segment B<<1384.0,-201.0>-<1375.0,-231.0>-<1361.5,-257.0>>

	* Eng (U+014A) contains a short segment B<<1361.5,-257.0>-<1348.0,-283.0>-<1327.0,-320.0>>

	* Eng (U+014A) contains a short segment B<<774.5,-302.0>-<814.0,-302.0>-<823.0,-302.0>>

	* Eng (U+014A) contains a short segment B<<823.0,-302.0>-<832.0,-302.0>-<831.5,-301.5>>

	* Eng (U+014A) contains a short segment B<<831.5,-301.5>-<831.0,-301.0>-<843.0,-300.0>>

	* Eng (U+014A) contains a short segment B<<1068.0,-167.0>-<1085.0,-147.0>-<1096.0,-126.0>>

	* Eng (U+014A) contains a short segment B<<1096.0,-126.0>-<1107.0,-105.0>-<1115.5,-66.5>>

	* sacute (U+015B) contains a short segment B<<522.0,295.0>-<522.0,306.0>-<515.0,318.0>>

	* scedilla (U+015F) contains a short segment B<<522.0,295.0>-<522.0,306.0>-<515.0,318.0>>

	* scaron (U+0161) contains a short segment B<<522.0,295.0>-<522.0,306.0>-<515.0,318.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2709.5,1906.0>-<2720.0,1864.0>-<2704.0,1826.0>>

	* ycircumflex (U+0177) contains a short segment B<<398.5,274.0>-<409.0,259.0>-<434.0,259.0>>

	* uni0219 (U+0219) contains a short segment B<<522.0,295.0>-<522.0,306.0>-<515.0,318.0>>

	* Wgrave (U+1E80) contains a short segment B<<2709.5,1906.0>-<2720.0,1864.0>-<2704.0,1826.0>>

	* Wacute (U+1E82) contains a short segment B<<2709.5,1906.0>-<2720.0,1864.0>-<2704.0,1826.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2709.5,1906.0>-<2720.0,1864.0>-<2704.0,1826.0>>

	* ygrave (U+1EF3) contains a short segment B<<398.5,274.0>-<409.0,259.0>-<434.0,259.0>>

	* notequal (U+2260) contains a short segment L<<153.0,372.0>--<143.0,372.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<1094.0,1161.0>--<1078.0,1383.0>> -> L<<1078.0,1383.0>--<1081.0,1613.0>>

	* oslash (U+00F8): L<<371.0,391.0>--<446.0,543.0>> -> L<<446.0,543.0>--<564.0,824.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[20] EduSABeginner-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x02D9 (DOT ABOVE)


	- 0x00A8 (DIAERESIS)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoAscender is 2642 when it should be 2032 [code: bad-typo-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoDescender is -926 when it should be -488 [code: bad-typo-descender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Ascender is 2642 when it should be 2032 [code: bad-hhea-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Descender is -926 when it should be -488 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, syriac, old-permic, math, malayalam, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* B
	* C
	* D
	* E
	* Euro
	* F
	* G
	* H
	* I
	* J
	* K
	* L
	* M
	* N
	* O
	* P
	* Q
	* R
	* S
	* T
	* U
	* V
	* W
	* X
	* Y
	* Z
	* a
	* ampersand
	* approxequal
	* asciicircum
	* asciitilde
	* at
	* b
	* backslash
	* bar
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cent
	* colon
	* copyright
	* d
	* degree
	* divide
	* dollar
	* e
	* eight
	* ellipsis
	* emdash
	* endash
	* equal
	* exclam
	* exclamdown
	* f
	* five
	* four
	* g
	* greater
	* greaterequal
	* h
	* hyphen
	* i
	* infinity
	* j
	* k
	* l
	* less
	* lessequal
	* m
	* minus
	* multiply
	* n
	* nine
	* notequal
	* numbersign
	* o
	* one
	* p
	* parenleft
	* parenright
	* percent
	* plus
	* plusminus
	* q
	* question
	* questiondown
	* quotedbl
	* quotedblleft
	* quotedblright
	* r
	* registered
	* s
	* semicolon
	* seven
	* six
	* slash
	* sterling
	* t
	* three
	* tilde
	* trademark
	* two
	* u
	* underscore
	* v
	* w
	* x
	* y
	* yen
	* z and zero
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.cv21.alt

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- tildecomb.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 840 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 771:
less, greater

Width = 839:
notequal, equal

Width = 845:
plusminus

Width = 832:
multiply

Width = 847:
approxequal

Width = 853:
lessequal, greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* A (U+0041): X=1245.0,Y=1.0 (should be at baseline 0?)

	* C (U+0043): X=1037.0,Y=2009.0 (should be at cap-height 2008?)

	* G (U+0047): X=1097.0,Y=2009.0 (should be at cap-height 2008?)

	* O (U+004F): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Q (U+0051): X=766.0,Y=2009.0 (should be at cap-height 2008?)

	* S (U+0053): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* X (U+0058): X=61.5,Y=2.0 (should be at baseline 0?)

	* Y (U+0059): X=512.0,Y=1.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=223.0,Y=2007.0 (should be at cap-height 2008?)

	* bracketleft (U+005B): X=647.0,Y=2007.0 (should be at cap-height 2008?)

	* a (U+0061): X=646.5,Y=1084.0 (should be at x-height 1082?)

	* i (U+0069): X=310.0,Y=1083.0 (should be at x-height 1082?)

	* braceleft (U+007B): X=419.0,Y=-926.5 (should be at descender -926?)

	* yen (U+00A5): X=288.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=566.0,Y=2009.0 (should be at cap-height 2008?)

	* section (U+00A7): X=828.0,Y=2009.0 (should be at cap-height 2008?)

	* registered (U+00AE): X=1217.0,Y=2010.0 (should be at cap-height 2008?)

	* registered (U+00AE): X=402.5,Y=2010.0 (should be at cap-height 2008?)

	* degree (U+00B0): X=430.0,Y=2006.0 (should be at cap-height 2008?)

	* Agrave (U+00C0): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Aacute (U+00C1): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Acircumflex (U+00C2): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Atilde (U+00C3): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Adieresis (U+00C4): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Aring (U+00C5): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Aring (U+00C5): X=928.5,Y=2640.5 (should be at ascender 2642?)

	* Ccedilla (U+00C7): X=1037.0,Y=2009.0 (should be at cap-height 2008?)

	* Ccedilla (U+00C7): X=511.0,Y=-2.0 (should be at baseline 0?)

	* Ograve (U+00D2): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Oacute (U+00D3): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Ocircumflex (U+00D4): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Otilde (U+00D5): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Odieresis (U+00D6): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Oslash (U+00D8): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Yacute (U+00DD): X=512.0,Y=1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=195.0,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=1019.0,Y=2009.5 (should be at cap-height 2008?)

	* germandbls (U+00DF): X=195.0,Y=-1.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=311.0,Y=-2.0 (should be at baseline 0?)

	* oslash (U+00F8): X=300.0,Y=2.0 (should be at baseline 0?)

	* Amacron (U+0100): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Abreve (U+0102): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Aogonek (U+0104): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Cacute (U+0106): X=1037.0,Y=2009.0 (should be at cap-height 2008?)

	* Cdotaccent (U+010A): X=1037.0,Y=2009.0 (should be at cap-height 2008?)

	* Ccaron (U+010C): X=1037.0,Y=2009.0 (should be at cap-height 2008?)

	* Gbreve (U+011E): X=1097.0,Y=2009.0 (should be at cap-height 2008?)

	* Gdotaccent (U+0120): X=1097.0,Y=2009.0 (should be at cap-height 2008?)

	* uni0122 (U+0122): X=1097.0,Y=2009.0 (should be at cap-height 2008?)

	* iogonek (U+012F): X=230.0,Y=-2.0 (should be at baseline 0?)

	* lcaron (U+013E): X=733.0,Y=2010.0 (should be at cap-height 2008?)

	* eng (U+014B): X=191.5,Y=2.0 (should be at baseline 0?)

	* Omacron (U+014C): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Ohungarumlaut (U+0150): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* OE (U+0152): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Sacute (U+015A): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* Scedilla (U+015E): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* Scedilla (U+015E): X=418.0,Y=-2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=243.0,Y=-2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* Uring (U+016E): X=988.5,Y=2640.5 (should be at ascender 2642?)

	* Ycircumflex (U+0176): X=512.0,Y=1.0 (should be at baseline 0?)

	* Ydieresis (U+0178): X=512.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* uni0327 (U+0327): X=-40.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=438.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=1608.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=670.0,Y=1.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=512.0,Y=1.0 (should be at baseline 0?)

	* Euro (U+20AC): X=1139.0,Y=2009.0 (should be at cap-height 2008?)

	* Euro (U+20AC): X=853.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<1071.0,1839.0>--<963.0,1579.0>> -> L<<963.0,1579.0>--<744.0,1139.0>>

	* AE (U+00C6): L<<1113.0,1139.0>--<1080.0,1561.0>> -> L<<1080.0,1561.0>--<1071.0,1839.0>>

	* oslash (U+00F8): L<<259.0,194.0>--<431.0,559.0>> -> L<<431.0,559.0>--<608.0,950.0>>

	* oslash (U+00F8): L<<693.0,856.0>--<528.0,505.0>> -> L<<528.0,505.0>--<349.0,109.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* three (U+0033): B<<916.5,1232.0>-<802.0,1115.0>-<605.0,1087.0>>/B<<605.0,1087.0>-<815.0,1071.0>-<932.5,934.5>> = 12.446355419799241 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 12 | 20 | 49 | 482 | 21 | 361 | 0 |
| 1% | 2% | 5% | 51% | 2% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
