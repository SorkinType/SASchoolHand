## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[21] SaHand-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "SaHand" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 903 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 742 font units wide, non-breaking space named (uni00A0) is 470 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, coptic, math, old-permic, malayalam, tifinagh, tai-le, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: newa, dogra, myanmar, takri, new-tai-lue, psalter-pahlavi, sharada, buhid, kaithi, limbu, cham, modi, malayalam, mongolian, sundanese, syloti-nagri, kayah-li, grantha, brahmi, telugu, thaana, mahajani, sinhala, hanifi-rohingya, tifinagh, buginese, hanunoo, pahawh-hmong, siddham, syriac, tagbanwa, gurmukhi, hatran, gujarati, meetei-mayek, chakma, rejang, bengali, kharoshthi, tai-tham, gunjala-gondi, saurashtra, tai-viet, tibetan, kannada, warang-citi, mandaic, oriya, lepcha, khudawadi, manichaean, tagalog, nko, avestan, khojki, balinese, tirhuta, yi, phags-pa, khmer, thai, javanese, tamil, devanagari, sogdian, batak, tai-le, duployan
 * U+200D ZERO WIDTH JOINER: try adding one of: newa, dogra, myanmar, takri, new-tai-lue, psalter-pahlavi, sharada, buhid, kaithi, limbu, cham, modi, malayalam, mongolian, sundanese, syloti-nagri, kayah-li, grantha, brahmi, telugu, thaana, mahajani, sinhala, hanifi-rohingya, tifinagh, buginese, hanunoo, pahawh-hmong, siddham, syriac, tagbanwa, gurmukhi, old-hungarian, gujarati, meetei-mayek, chakma, rejang, bengali, kharoshthi, tai-tham, gunjala-gondi, saurashtra, tai-viet, tibetan, kannada, warang-citi, mandaic, oriya, lepcha, khudawadi, manichaean, tagalog, nko, avestan, khojki, balinese, tirhuta, yi, phags-pa, thai, javanese, tamil, devanagari, batak, tai-le, duployan
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: newa, old-permic, elbasan, music, buhid, mongolian, cham, sundanese, brahmi, hebrew, syriac, zanabazar-square, kharoshthi, tibetan, gunjala-gondi, mandaic, oriya, manichaean, tirhuta, bhaiksuki, sogdian, duployan, dogra, limbu, modi, malayalam, kayah-li, hanifi-rohingya, adlam, coptic, gurmukhi, ahom, meetei-mayek, rejang, chakma, tai-viet, bengali, soyombo, kannada, masaram-gondi, nko, javanese, marchen, osage, batak, new-tai-lue, psalter-pahlavi, sharada, wancho, grantha, telugu, thaana, sinhala, tifinagh, buginese, gujarati, lepcha, miao, khojki, balinese, devanagari, caucasian-albanian, tai-le, lao, myanmar, takri, kaithi, mende-kikakui, syloti-nagri, math, mahajani, pahawh-hmong, hanunoo, siddham, tagbanwa, symbols, khudawadi, tagalog, bassa-vah, yi, phags-pa, khmer, thai, tamil
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Edieresis.001

	- e.cv21.alt
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


* ⚠ **WARN** The most common width is 1141 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1138:
plus

Width = 1051:
less

Width = 1053:
greater

Width = 1139:
plusminus

Width = 925:
multiply

Width = 958:
divide, minus

Width = 1120:
approxequal

Width = 1140:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=227.0,Y=-1.0 (should be at baseline 0?)

	* exclam (U+0021): X=227.0,Y=-1.0 (should be at baseline 0?)

	* ampersand (U+0026): X=774.0,Y=2006.0 (should be at cap-height 2008?)

	* period (U+002E): X=229.0,Y=-1.0 (should be at baseline 0?)

	* period (U+002E): X=229.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=139.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=139.0,Y=-1.0 (should be at baseline 0?)

	* X (U+0058): X=329.5,Y=2009.5 (should be at cap-height 2008?)

	* X (U+0058): X=1350.0,Y=2006.5 (should be at cap-height 2008?)

	* X (U+0058): X=1122.5,Y=0.5 (should be at baseline 0?)

	* Y (U+0059): X=525.5,Y=0.5 (should be at baseline 0?)

	* a (U+0061): X=673.5,Y=1081.5 (should be at x-height 1082?)

	* b (U+0062): X=447.0,Y=1.0 (should be at baseline 0?)

	* p (U+0070): X=460.0,Y=1.5 (should be at baseline 0?)

	* s (U+0073): X=598.0,Y=1080.0 (should be at x-height 1082?)

	* braceleft (U+007B): X=418.0,Y=2009.5 (should be at cap-height 2008?)

	* sterling (U+00A3): X=830.0,Y=2010.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=527.5,Y=0.5 (should be at baseline 0?)

	* brokenbar (U+00A6): X=607.0,Y=2006.0 (should be at cap-height 2008?)

	* brokenbar (U+00A6): X=607.0,Y=2006.0 (should be at cap-height 2008?)

	* paragraph (U+00B6): X=1245.0,Y=2007.0 (should be at cap-height 2008?)

	* paragraph (U+00B6): X=1725.0,Y=2007.0 (should be at cap-height 2008?)

	* questiondown (U+00BF): X=504.0,Y=-2.0 (should be at baseline 0?)

	* questiondown (U+00BF): X=504.0,Y=-2.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=699.0,Y=2575.0 (should be at ascender 2576?)

	* Egrave (U+00C8): X=733.0,Y=2575.0 (should be at ascender 2576?)

	* Igrave (U+00CC): X=354.0,Y=2575.0 (should be at ascender 2576?)

	* Ograve (U+00D2): X=727.0,Y=2575.0 (should be at ascender 2576?)

	* Ugrave (U+00D9): X=785.0,Y=2575.0 (should be at ascender 2576?)

	* Yacute (U+00DD): X=525.5,Y=0.5 (should be at baseline 0?)

	* Eng (U+014A): X=264.0,Y=-2.0 (should be at baseline 0?)

	* Eng (U+014A): X=479.0,Y=2010.0 (should be at cap-height 2008?)

	* Eng (U+014A): X=264.0,Y=-2.0 (should be at baseline 0?)

	* eng (U+014B): X=189.0,Y=-1.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=525.5,Y=0.5 (should be at baseline 0?)

	* Ydieresis (U+0178): X=525.5,Y=0.5 (should be at baseline 0?)

	* Wgrave (U+1E80): X=1299.0,Y=2575.0 (should be at ascender 2576?)

	* uni1E9E (U+1E9E): X=283.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=283.0,Y=-2.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=525.5,Y=0.5 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=896.0,Y=2575.0 (should be at ascender 2576?)

	* uni1EF8 (U+1EF8): X=525.5,Y=0.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=139.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=139.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=691.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=691.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1245.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1245.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<1456.0,558.0>-<1446.0,523.0>-<1441.5,484.5>>

	* at (U+0040) contains a short segment B<<1441.5,484.5>-<1437.0,446.0>-<1443.5,420.0>>

	* at (U+0040) contains a short segment B<<1443.5,420.0>-<1450.0,394.0>-<1476.0,394.0>>

	* M (U+004D) contains a short segment B<<99.0,0.0>-<61.0,0.0>-<27.5,20.5>>

	* M (U+004D) contains a short segment B<<27.5,20.5>-<-6.0,41.0>-<-18.0,80.5>>

	* M (U+004D) contains a short segment B<<842.0,1914.0>-<864.0,1959.0>-<891.0,1983.5>>

	* M (U+004D) contains a short segment B<<1346.0,90.0>-<1333.0,65.0>-<1302.0,32.5>>

	* W (U+0057) contains a short segment B<<2412.0,1912.0>-<2426.0,1946.0>-<2462.0,1977.0>>

	* W (U+0057) contains a short segment B<<2645.5,1982.5>-<2676.0,1957.0>-<2685.0,1919.5>>

	* W (U+0057) contains a short segment B<<2685.0,1919.5>-<2694.0,1882.0>-<2679.0,1847.0>>

	* yen (U+00A5) contains a short segment L<<488.0,302.0>--<486.0,302.0>>

	* yen (U+00A5) contains a short segment L<<1194.0,948.0>--<1229.0,948.0>>

	* Hbar (U+0126) contains a short segment L<<1734.0,1523.0>--<1743.0,1523.0>>

	* Lslash (U+0141) contains a short segment L<<173.0,573.0>--<141.0,555.0>>

	* lslash (U+0142) contains a short segment L<<150.0,706.0>--<148.0,706.0>>

	* Eng (U+014A) contains a short segment B<<744.5,-337.0>-<780.0,-337.0>-<792.0,-337.0>>

	* Eng (U+014A) contains a short segment B<<792.0,-337.0>-<804.0,-337.0>-<808.5,-336.0>>

	* Eng (U+014A) contains a short segment B<<808.5,-336.0>-<813.0,-335.0>-<828.0,-333.0>>

	* Eng (U+014A) contains a short segment B<<1065.0,-188.0>-<1084.0,-162.0>-<1096.5,-136.5>>

	* Eng (U+014A) contains a short segment B<<1096.5,-136.5>-<1109.0,-111.0>-<1118.5,-70.5>>

	* eng (U+014B) contains a short segment B<<172.0,964.0>-<175.0,983.0>-<188.5,1011.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2412.0,1912.0>-<2426.0,1946.0>-<2462.0,1977.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2645.5,1982.5>-<2676.0,1957.0>-<2685.0,1919.5>>

	* Wcircumflex (U+0174) contains a short segment B<<2685.0,1919.5>-<2694.0,1882.0>-<2679.0,1847.0>>

	* Wgrave (U+1E80) contains a short segment B<<2412.0,1912.0>-<2426.0,1946.0>-<2462.0,1977.0>>

	* Wgrave (U+1E80) contains a short segment B<<2645.5,1982.5>-<2676.0,1957.0>-<2685.0,1919.5>>

	* Wgrave (U+1E80) contains a short segment B<<2685.0,1919.5>-<2694.0,1882.0>-<2679.0,1847.0>>

	* Wacute (U+1E82) contains a short segment B<<2412.0,1912.0>-<2426.0,1946.0>-<2462.0,1977.0>>

	* Wacute (U+1E82) contains a short segment B<<2645.5,1982.5>-<2676.0,1957.0>-<2685.0,1919.5>>

	* Wacute (U+1E82) contains a short segment B<<2685.0,1919.5>-<2694.0,1882.0>-<2679.0,1847.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2412.0,1912.0>-<2426.0,1946.0>-<2462.0,1977.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2645.5,1982.5>-<2676.0,1957.0>-<2685.0,1919.5>>

	* Wdieresis (U+1E84) contains a short segment B<<2685.0,1919.5>-<2694.0,1882.0>-<2679.0,1847.0>>

	* estimated (U+212E) contains a short segment B<<529.0,948.0>-<510.0,948.0>-<498.5,940.5>>

	* estimated (U+212E) contains a short segment B<<498.5,940.5>-<487.0,933.0>-<487.0,896.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<1118.0,1157.0>--<1098.0,1419.0>> -> L<<1098.0,1419.0>--<1099.0,1658.0>>

	* oslash (U+00F8): L<<346.0,346.0>--<443.0,546.0>> -> L<<443.0,546.0>--<574.0,852.0>>

	* oslash (U+00F8): L<<683.0,736.0>--<557.0,497.0>> -> L<<557.0,497.0>--<447.0,227.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ordfeminine (U+00AA): B<<794.0,1235.5>-<758.0,1271.0>-<773.0,1335.0>>/L<<773.0,1335.0>--<761.0,1302.0>> = 6.792495809693081 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[21] SaHand-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "SaHand" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 903 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 360 font units wide, non-breaking space named (uni00A0) is 470 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, coptic, math, old-permic, malayalam, tifinagh, tai-le, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: newa, dogra, myanmar, takri, new-tai-lue, psalter-pahlavi, sharada, buhid, kaithi, limbu, cham, modi, malayalam, mongolian, sundanese, syloti-nagri, kayah-li, grantha, brahmi, telugu, thaana, mahajani, sinhala, hanifi-rohingya, tifinagh, buginese, hanunoo, pahawh-hmong, siddham, syriac, tagbanwa, gurmukhi, hatran, gujarati, meetei-mayek, chakma, rejang, bengali, kharoshthi, tai-tham, gunjala-gondi, saurashtra, tai-viet, tibetan, kannada, warang-citi, mandaic, oriya, lepcha, khudawadi, manichaean, tagalog, nko, avestan, khojki, balinese, tirhuta, yi, phags-pa, khmer, thai, javanese, tamil, devanagari, sogdian, batak, tai-le, duployan
 * U+200D ZERO WIDTH JOINER: try adding one of: newa, dogra, myanmar, takri, new-tai-lue, psalter-pahlavi, sharada, buhid, kaithi, limbu, cham, modi, malayalam, mongolian, sundanese, syloti-nagri, kayah-li, grantha, brahmi, telugu, thaana, mahajani, sinhala, hanifi-rohingya, tifinagh, buginese, hanunoo, pahawh-hmong, siddham, syriac, tagbanwa, gurmukhi, old-hungarian, gujarati, meetei-mayek, chakma, rejang, bengali, kharoshthi, tai-tham, gunjala-gondi, saurashtra, tai-viet, tibetan, kannada, warang-citi, mandaic, oriya, lepcha, khudawadi, manichaean, tagalog, nko, avestan, khojki, balinese, tirhuta, yi, phags-pa, thai, javanese, tamil, devanagari, batak, tai-le, duployan
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: newa, old-permic, elbasan, music, buhid, mongolian, cham, sundanese, brahmi, hebrew, syriac, zanabazar-square, kharoshthi, tibetan, gunjala-gondi, mandaic, oriya, manichaean, tirhuta, bhaiksuki, sogdian, duployan, dogra, limbu, modi, malayalam, kayah-li, hanifi-rohingya, adlam, coptic, gurmukhi, ahom, meetei-mayek, rejang, chakma, tai-viet, bengali, soyombo, kannada, masaram-gondi, nko, javanese, marchen, osage, batak, new-tai-lue, psalter-pahlavi, sharada, wancho, grantha, telugu, thaana, sinhala, tifinagh, buginese, gujarati, lepcha, miao, khojki, balinese, devanagari, caucasian-albanian, tai-le, lao, myanmar, takri, kaithi, mende-kikakui, syloti-nagri, math, mahajani, pahawh-hmong, hanunoo, siddham, tagbanwa, symbols, khudawadi, tagalog, bassa-vah, yi, phags-pa, khmer, thai, tamil
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Edieresis.001

	- e.cv21.alt
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


* ⚠ **WARN** The most common width is 1168 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1076:
less

Width = 1171:
notequal, equal

Width = 1078:
greater

Width = 948:
multiply

Width = 988:
divide, minus

Width = 1143:
approxequal

Width = 1167:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* X (U+0058): X=347.0,Y=2010.0 (should be at cap-height 2008?)

	* X (U+0058): X=1358.5,Y=2007.0 (should be at cap-height 2008?)

	* Y (U+0059): X=533.0,Y=0.5 (should be at baseline 0?)

	* yen (U+00A5): X=542.0,Y=0.5 (should be at baseline 0?)

	* Yacute (U+00DD): X=533.0,Y=0.5 (should be at baseline 0?)

	* Eng (U+014A): X=488.0,Y=2010.0 (should be at cap-height 2008?)

	* eng (U+014B): X=200.0,Y=-1.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=533.0,Y=0.5 (should be at baseline 0?)

	* Ydieresis (U+0178): X=533.0,Y=0.5 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=533.0,Y=0.5 (should be at baseline 0?)

	* uni1EF8 (U+1EF8): X=533.0,Y=0.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* asterisk (U+002A) contains a short segment L<<437.0,1331.0>--<422.0,1321.0>>

	* asterisk (U+002A) contains a short segment L<<774.0,1867.0>--<784.0,1873.0>>

	* at (U+0040) contains a short segment B<<1369.0,1179.0>-<1388.0,1223.0>-<1424.5,1242.0>>

	* at (U+0040) contains a short segment B<<1502.0,554.0>-<1496.0,531.0>-<1491.0,499.5>>

	* at (U+0040) contains a short segment B<<1491.0,499.5>-<1486.0,468.0>-<1491.5,444.5>>

	* at (U+0040) contains a short segment B<<1491.5,444.5>-<1497.0,421.0>-<1520.0,421.0>>

	* M (U+004D) contains a short segment B<<1371.0,96.0>-<1362.0,78.0>-<1345.0,55.5>>

	* M (U+004D) contains a short segment B<<1345.0,55.5>-<1328.0,33.0>-<1293.5,16.5>>

	* W (U+0057) contains a short segment B<<2709.5,1906.0>-<2720.0,1864.0>-<2704.0,1826.0>>

	* q (U+0071) contains a short segment L<<893.0,-458.0>--<914.0,-440.0>>

	* s (U+0073) contains a short segment B<<522.0,295.0>-<522.0,306.0>-<515.0,318.0>>

	* y (U+0079) contains a short segment B<<398.5,274.0>-<409.0,259.0>-<434.0,259.0>>

	* sterling (U+00A3) contains a short segment B<<178.0,125.0>-<186.0,153.0>-<198.0,169.0>>

	* sterling (U+00A3) contains a short segment B<<687.0,1714.0>-<672.0,1707.0>-<665.5,1690.5>>

	* sterling (U+00A3) contains a short segment B<<665.5,1690.5>-<659.0,1674.0>-<659.0,1654.0>>

	* yen (U+00A5) contains a short segment L<<1237.0,968.0>--<1241.0,968.0>>

	* Oslash (U+00D8) contains a short segment L<<781.0,259.0>--<784.0,259.0>>

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

	* uni1EF9 (U+1EF9) contains a short segment B<<398.5,274.0>-<409.0,259.0>-<434.0,259.0>>

	* daggerdbl (U+2021) contains a short segment L<<461.0,781.0>--<432.0,781.0>>

	* estimated (U+212E) contains a short segment B<<529.0,948.0>-<510.0,948.0>-<498.5,940.5>>

	* estimated (U+212E) contains a short segment B<<498.5,940.5>-<487.0,933.0>-<487.0,896.0>>

	* notequal (U+2260) contains a short segment L<<243.0,372.0>--<233.0,372.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<1119.0,1161.0>--<1103.0,1383.0>> -> L<<1103.0,1383.0>--<1106.0,1613.0>>

	* oslash (U+00F8): L<<371.0,391.0>--<446.0,543.0>> -> L<<446.0,543.0>--<564.0,824.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ordfeminine (U+00AA): B<<781.5,1239.5>-<741.0,1279.0>-<758.0,1351.0>>/L<<758.0,1351.0>--<740.0,1276.0>> = 0.21086679589269736 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] SaHand-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "SaHand" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 903 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 2270 font units wide, non-breaking space named (uni00A0) is 470 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, coptic, math, old-permic, malayalam, tifinagh, tai-le, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: newa, dogra, myanmar, takri, new-tai-lue, psalter-pahlavi, sharada, buhid, kaithi, limbu, cham, modi, malayalam, mongolian, sundanese, syloti-nagri, kayah-li, grantha, brahmi, telugu, thaana, mahajani, sinhala, hanifi-rohingya, tifinagh, buginese, hanunoo, pahawh-hmong, siddham, syriac, tagbanwa, gurmukhi, hatran, gujarati, meetei-mayek, chakma, rejang, bengali, kharoshthi, tai-tham, gunjala-gondi, saurashtra, tai-viet, tibetan, kannada, warang-citi, mandaic, oriya, lepcha, khudawadi, manichaean, tagalog, nko, avestan, khojki, balinese, tirhuta, yi, phags-pa, khmer, thai, javanese, tamil, devanagari, sogdian, batak, tai-le, duployan
 * U+200D ZERO WIDTH JOINER: try adding one of: newa, dogra, myanmar, takri, new-tai-lue, psalter-pahlavi, sharada, buhid, kaithi, limbu, cham, modi, malayalam, mongolian, sundanese, syloti-nagri, kayah-li, grantha, brahmi, telugu, thaana, mahajani, sinhala, hanifi-rohingya, tifinagh, buginese, hanunoo, pahawh-hmong, siddham, syriac, tagbanwa, gurmukhi, old-hungarian, gujarati, meetei-mayek, chakma, rejang, bengali, kharoshthi, tai-tham, gunjala-gondi, saurashtra, tai-viet, tibetan, kannada, warang-citi, mandaic, oriya, lepcha, khudawadi, manichaean, tagalog, nko, avestan, khojki, balinese, tirhuta, yi, phags-pa, thai, javanese, tamil, devanagari, batak, tai-le, duployan
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: newa, old-permic, elbasan, music, buhid, mongolian, cham, sundanese, brahmi, hebrew, syriac, zanabazar-square, kharoshthi, tibetan, gunjala-gondi, mandaic, oriya, manichaean, tirhuta, bhaiksuki, sogdian, duployan, dogra, limbu, modi, malayalam, kayah-li, hanifi-rohingya, adlam, coptic, gurmukhi, ahom, meetei-mayek, rejang, chakma, tai-viet, bengali, soyombo, kannada, masaram-gondi, nko, javanese, marchen, osage, batak, new-tai-lue, psalter-pahlavi, sharada, wancho, grantha, telugu, thaana, sinhala, tifinagh, buginese, gujarati, lepcha, miao, khojki, balinese, devanagari, caucasian-albanian, tai-le, lao, myanmar, takri, kaithi, mende-kikakui, syloti-nagri, math, mahajani, pahawh-hmong, hanunoo, siddham, tagbanwa, symbols, khudawadi, tagalog, bassa-vah, yi, phags-pa, khmer, thai, tamil
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Edieresis.001

	- e.cv21.alt
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


* ⚠ **WARN** The most common width is 951 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1020:
plus

Width = 1019:
notequal, equal

Width = 1025:
plusminus

Width = 832:
multiply

Width = 840:
divide, minus

Width = 1027:
approxequal

Width = 1033:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* A (U+0041): X=1245.0,Y=1.0 (should be at baseline 0?)

	* C (U+0043): X=1037.0,Y=2009.0 (should be at cap-height 2008?)

	* G (U+0047): X=1097.0,Y=2009.0 (should be at cap-height 2008?)

	* O (U+004F): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* Q (U+0051): X=766.0,Y=2009.0 (should be at cap-height 2008?)

	* S (U+0053): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* X (U+0058): X=61.5,Y=2.0 (should be at baseline 0?)

	* Y (U+0059): X=512.0,Y=1.0 (should be at baseline 0?)

	* a (U+0061): X=646.5,Y=1084.0 (should be at x-height 1082?)

	* i (U+0069): X=260.0,Y=1083.0 (should be at x-height 1082?)

	* yen (U+00A5): X=488.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=816.0,Y=2009.0 (should be at cap-height 2008?)

	* section (U+00A7): X=1078.0,Y=2009.0 (should be at cap-height 2008?)

	* registered (U+00AE): X=1217.0,Y=2010.0 (should be at cap-height 2008?)

	* registered (U+00AE): X=402.5,Y=2010.0 (should be at cap-height 2008?)

	* degree (U+00B0): X=430.0,Y=2006.0 (should be at cap-height 2008?)

	* cedilla (U+00B8): X=80.0,Y=-2.0 (should be at baseline 0?)

	* ordmasculine (U+00BA): X=815.0,Y=2008.5 (should be at cap-height 2008?)

	* Agrave (U+00C0): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Aacute (U+00C1): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Acircumflex (U+00C2): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Atilde (U+00C3): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Adieresis (U+00C4): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Aring (U+00C5): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=1037.0,Y=2009.0 (should be at cap-height 2008?)

	* Ograve (U+00D2): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* Oacute (U+00D3): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* Ocircumflex (U+00D4): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* Otilde (U+00D5): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* Odieresis (U+00D6): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* Oslash (U+00D8): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* Yacute (U+00DD): X=512.0,Y=1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=195.0,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=1019.0,Y=2009.5 (should be at cap-height 2008?)

	* germandbls (U+00DF): X=195.0,Y=-1.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=293.0,Y=-2.0 (should be at baseline 0?)

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

	* eng (U+014B): X=186.5,Y=2.0 (should be at baseline 0?)

	* Omacron (U+014C): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* Ohungarumlaut (U+0150): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* OE (U+0152): X=900.0,Y=2009.0 (should be at cap-height 2008?)

	* Sacute (U+015A): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* Scedilla (U+015E): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* Scedilla (U+015E): X=418.0,Y=-2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=243.0,Y=-2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* uni0162 (U+0162): X=376.0,Y=-2.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=280.0,Y=-2.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=512.0,Y=1.0 (should be at baseline 0?)

	* Ydieresis (U+0178): X=512.0,Y=1.0 (should be at baseline 0?)

	* Gcaron (U+01E6): X=1097.0,Y=2009.0 (should be at cap-height 2008?)

	* uni0218 (U+0218): X=829.0,Y=2009.0 (should be at cap-height 2008?)

	* uni0327 (U+0327): X=80.0,Y=-2.0 (should be at baseline 0?)

	* uni1E20 (U+1E20): X=1097.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=438.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=1608.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=670.0,Y=1.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=512.0,Y=1.0 (should be at baseline 0?)

	* uni1EF8 (U+1EF8): X=512.0,Y=1.0 (should be at baseline 0?)

	* Euro (U+20AC): X=1229.0,Y=2009.0 (should be at cap-height 2008?)

	* Euro (U+20AC): X=943.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<1071.0,1839.0>--<963.0,1579.0>> -> L<<963.0,1579.0>--<744.0,1139.0>>

	* AE (U+00C6): L<<1113.0,1139.0>--<1080.0,1561.0>> -> L<<1080.0,1561.0>--<1071.0,1839.0>>

	* oslash (U+00F8): L<<259.0,194.0>--<431.0,559.0>> -> L<<431.0,559.0>--<608.0,950.0>>

	* oslash (U+00F8): L<<693.0,856.0>--<528.0,505.0>> -> L<<528.0,505.0>--<349.0,109.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* three (U+0033): B<<1096.5,1232.0>-<982.0,1115.0>-<785.0,1087.0>>/B<<785.0,1087.0>-<995.0,1071.0>-<1112.5,934.5>> = 12.446355419799241 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] SaHand-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "SaHand" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 903 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 1379 font units wide, non-breaking space named (uni00A0) is 470 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, coptic, math, old-permic, malayalam, tifinagh, tai-le, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: newa, dogra, myanmar, takri, new-tai-lue, psalter-pahlavi, sharada, buhid, kaithi, limbu, cham, modi, malayalam, mongolian, sundanese, syloti-nagri, kayah-li, grantha, brahmi, telugu, thaana, mahajani, sinhala, hanifi-rohingya, tifinagh, buginese, hanunoo, pahawh-hmong, siddham, syriac, tagbanwa, gurmukhi, hatran, gujarati, meetei-mayek, chakma, rejang, bengali, kharoshthi, tai-tham, gunjala-gondi, saurashtra, tai-viet, tibetan, kannada, warang-citi, mandaic, oriya, lepcha, khudawadi, manichaean, tagalog, nko, avestan, khojki, balinese, tirhuta, yi, phags-pa, khmer, thai, javanese, tamil, devanagari, sogdian, batak, tai-le, duployan
 * U+200D ZERO WIDTH JOINER: try adding one of: newa, dogra, myanmar, takri, new-tai-lue, psalter-pahlavi, sharada, buhid, kaithi, limbu, cham, modi, malayalam, mongolian, sundanese, syloti-nagri, kayah-li, grantha, brahmi, telugu, thaana, mahajani, sinhala, hanifi-rohingya, tifinagh, buginese, hanunoo, pahawh-hmong, siddham, syriac, tagbanwa, gurmukhi, old-hungarian, gujarati, meetei-mayek, chakma, rejang, bengali, kharoshthi, tai-tham, gunjala-gondi, saurashtra, tai-viet, tibetan, kannada, warang-citi, mandaic, oriya, lepcha, khudawadi, manichaean, tagalog, nko, avestan, khojki, balinese, tirhuta, yi, phags-pa, thai, javanese, tamil, devanagari, batak, tai-le, duployan
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: newa, old-permic, elbasan, music, buhid, mongolian, cham, sundanese, brahmi, hebrew, syriac, zanabazar-square, kharoshthi, tibetan, gunjala-gondi, mandaic, oriya, manichaean, tirhuta, bhaiksuki, sogdian, duployan, dogra, limbu, modi, malayalam, kayah-li, hanifi-rohingya, adlam, coptic, gurmukhi, ahom, meetei-mayek, rejang, chakma, tai-viet, bengali, soyombo, kannada, masaram-gondi, nko, javanese, marchen, osage, batak, new-tai-lue, psalter-pahlavi, sharada, wancho, grantha, telugu, thaana, sinhala, tifinagh, buginese, gujarati, lepcha, miao, khojki, balinese, devanagari, caucasian-albanian, tai-le, lao, myanmar, takri, kaithi, mende-kikakui, syloti-nagri, math, mahajani, pahawh-hmong, hanunoo, siddham, tagbanwa, symbols, khudawadi, tagalog, bassa-vah, yi, phags-pa, khmer, thai, tamil
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Edieresis.001

	- e.cv21.alt
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


* ⚠ **WARN** The most common width is 1090 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1089:
plus

Width = 1009:
less

Width = 1010:
greater

Width = 1092:
plusminus

Width = 886:
multiply

Width = 909:
divide, minus

Width = 1081:
approxequal

Width = 1096:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=196.0,Y=-2.0 (should be at baseline 0?)

	* exclam (U+0021): X=196.0,Y=-2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=782.0,Y=2007.0 (should be at cap-height 2008?)

	* period (U+002E): X=198.0,Y=-2.0 (should be at baseline 0?)

	* period (U+002E): X=198.0,Y=-2.0 (should be at baseline 0?)

	* colon (U+003A): X=108.0,Y=-2.0 (should be at baseline 0?)

	* colon (U+003A): X=108.0,Y=-2.0 (should be at baseline 0?)

	* A (U+0041): X=1269.0,Y=1.0 (should be at baseline 0?)

	* X (U+0058): X=1304.0,Y=2007.0 (should be at cap-height 2008?)

	* Y (U+0059): X=543.5,Y=1.5 (should be at baseline 0?)

	* i (U+0069): X=294.0,Y=1083.0 (should be at x-height 1082?)

	* sterling (U+00A3): X=834.0,Y=2009.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=534.5,Y=1.5 (should be at baseline 0?)

	* section (U+00A7): X=848.0,Y=2009.0 (should be at cap-height 2008?)

	* section (U+00A7): X=1091.0,Y=2009.0 (should be at cap-height 2008?)

	* paragraph (U+00B6): X=1188.0,Y=2006.0 (should be at cap-height 2008?)

	* paragraph (U+00B6): X=1613.0,Y=2006.0 (should be at cap-height 2008?)

	* questiondown (U+00BF): X=495.0,Y=-1.0 (should be at baseline 0?)

	* questiondown (U+00BF): X=495.0,Y=-1.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=1269.0,Y=1.0 (should be at baseline 0?)

	* Aacute (U+00C1): X=1269.0,Y=1.0 (should be at baseline 0?)

	* Acircumflex (U+00C2): X=1269.0,Y=1.0 (should be at baseline 0?)

	* Atilde (U+00C3): X=1269.0,Y=1.0 (should be at baseline 0?)

	* Adieresis (U+00C4): X=1269.0,Y=1.0 (should be at baseline 0?)

	* Aring (U+00C5): X=1269.0,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=1068.0,Y=2010.0 (should be at cap-height 2008?)

	* Oslash (U+00D8): X=588.0,Y=2.0 (should be at baseline 0?)

	* Yacute (U+00DD): X=543.5,Y=1.5 (should be at baseline 0?)

	* germandbls (U+00DF): X=1024.5,Y=2006.5 (should be at cap-height 2008?)

	* Amacron (U+0100): X=1269.0,Y=1.0 (should be at baseline 0?)

	* Abreve (U+0102): X=1269.0,Y=1.0 (should be at baseline 0?)

	* Aogonek (U+0104): X=1269.0,Y=1.0 (should be at baseline 0?)

	* Eng (U+014A): X=246.0,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=463.0,Y=2009.0 (should be at cap-height 2008?)

	* Eng (U+014A): X=246.0,Y=-1.0 (should be at baseline 0?)

	* eng (U+014B): X=1045.0,Y=-2.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=543.5,Y=1.5 (should be at baseline 0?)

	* Ydieresis (U+0178): X=543.5,Y=1.5 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=471.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=1633.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=724.0,Y=1.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=543.5,Y=1.5 (should be at baseline 0?)

	* uni1EF8 (U+1EF8): X=543.5,Y=1.5 (should be at baseline 0?)

	* dagger (U+2020): X=639.0,Y=2007.0 (should be at cap-height 2008?)

	* daggerdbl (U+2021): X=639.0,Y=2007.0 (should be at cap-height 2008?)

	* ellipsis (U+2026): X=108.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=108.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=604.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=604.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1102.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1102.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<1087.0,1734.0>--<991.0,1488.0>> -> L<<991.0,1488.0>--<819.0,1149.0>>

	* AE (U+00C6): L<<1116.0,1149.0>--<1091.0,1478.0>> -> L<<1091.0,1478.0>--<1087.0,1734.0>>

	* oslash (U+00F8): L<<308.0,280.0>--<438.0,552.0>> -> L<<438.0,552.0>--<589.0,895.0>>

	* oslash (U+00F8): L<<689.0,787.0>--<545.0,500.0>> -> L<<545.0,500.0>--<407.0,176.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 12 | 20 | 49 | 478 | 21 | 365 | 0 |
| 1% | 2% | 5% | 51% | 2% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
