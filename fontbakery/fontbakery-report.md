## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[19] EduSABeginner-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoAscender is 2642 when it should be 2032 [code: bad-typo-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoDescender is -926 when it should be -488 [code: bad-typo-descender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Ascender is 2642 when it should be 2032 [code: bad-hhea-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Descender is -926 when it should be -488 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2866, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: macron	Expected: 1

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: cedilla	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oslash	Expected: 3

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0307	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: breve	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0307	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2
 [code: no-contour]
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

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, old-permic, malayalam, coptic, syriac, tai-le, canadian-aboriginal, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
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
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 889 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 813:
greater, less

Width = 890:
equal, notequal

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

	* questiondown (U+00BF): X=491.0,Y=-1.0 (should be at baseline 0?)

	* questiondown (U+00BF): X=491.0,Y=-1.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Atilde (U+00C3): X=1254.0,Y=1.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=534.0,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=96.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=96.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=569.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=569.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1044.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=1044.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* numbersign (U+0023) contains a short segment B<<1.0,533.0>-<-2.0,565.0>-<21.0,587.5>>

	* five (U+0035) contains a short segment B<<48.0,290.0>-<67.0,290.0>-<85.0,277.0>>

	* five (U+0035) contains a short segment B<<85.0,277.0>-<103.0,264.0>-<121.0,250.0>>

	* at (U+0040) contains a short segment B<<1193.0,1154.0>-<1205.0,1201.0>-<1232.0,1220.0>>

	* at (U+0040) contains a short segment B<<1232.0,1220.0>-<1259.0,1239.0>-<1308.0,1239.0>>

	* at (U+0040) contains a short segment B<<1121.0,-43.5>-<1162.0,-53.0>-<1175.0,-95.0>>

	* at (U+0040) contains a short segment B<<1175.0,-95.0>-<1186.0,-136.0>-<1166.5,-168.0>>

	* G (U+0047) contains a short segment B<<1370.0,1050.5>-<1389.0,1082.0>-<1409.5,1093.5>>

	* G (U+0047) contains a short segment B<<1409.5,1093.5>-<1430.0,1105.0>-<1465.0,1105.0>>

	* H (U+0048) contains a short segment B<<1372.0,75.0>-<1369.0,46.0>-<1347.5,23.0>>

	* K (U+004B) contains a short segment B<<1444.0,1998.5>-<1467.0,2008.0>-<1491.0,2008.0>>

	* M (U+004D) contains a short segment B<<46.0,0.0>-<0.0,0.0>-<-24.0,34.0>>

	* M (U+004D) contains a short segment B<<847.0,1930.0>-<865.0,1967.0>-<886.0,1987.5>>

	* M (U+004D) contains a short segment B<<886.0,1987.5>-<907.0,2008.0>-<951.0,2008.0>>

	* M (U+004D) contains a short segment B<<951.0,2008.0>-<1004.0,2008.0>-<1025.0,1987.0>>

	* M (U+004D) contains a short segment B<<1025.0,1987.0>-<1046.0,1966.0>-<1050.0,1934.0>>

	* M (U+004D) contains a short segment B<<1972.0,1925.0>-<1989.0,1959.0>-<2013.5,1983.5>>

	* M (U+004D) contains a short segment B<<2013.5,1983.5>-<2038.0,2008.0>-<2080.0,2008.0>>

	* M (U+004D) contains a short segment B<<2080.0,2008.0>-<2143.0,2008.0>-<2158.5,1984.5>>

	* M (U+004D) contains a short segment B<<2158.5,1984.5>-<2174.0,1961.0>-<2180.0,1914.0>>

	* M (U+004D) contains a short segment B<<2384.0,90.0>-<2389.0,50.0>-<2366.5,25.0>>

	* M (U+004D) contains a short segment B<<2366.5,25.0>-<2344.0,0.0>-<2301.0,0.0>>

	* M (U+004D) contains a short segment B<<2301.0,0.0>-<2250.0,0.0>-<2226.0,26.0>>

	* M (U+004D) contains a short segment B<<2226.0,26.0>-<2202.0,52.0>-<2198.0,83.0>>

	* M (U+004D) contains a short segment B<<1286.0,77.0>-<1276.0,56.0>-<1252.0,28.0>>

	* M (U+004D) contains a short segment B<<1252.0,28.0>-<1228.0,0.0>-<1173.0,0.0>>

	* M (U+004D) contains a short segment B<<1173.0,0.0>-<1120.0,0.0>-<1099.5,25.0>>

	* M (U+004D) contains a short segment B<<1099.5,25.0>-<1079.0,50.0>-<1075.0,82.0>>

	* M (U+004D) contains a short segment B<<163.0,80.0>-<142.0,36.0>-<108.5,18.0>>

	* M (U+004D) contains a short segment B<<108.5,18.0>-<75.0,0.0>-<46.0,0.0>>

	* N (U+004E) contains a short segment B<<1372.0,85.0>-<1368.0,45.0>-<1352.0,22.5>>

	* W (U+0057) contains a short segment B<<745.0,0.0>-<706.0,0.0>-<679.0,24.5>>

	* W (U+0057) contains a short segment B<<679.0,24.5>-<652.0,49.0>-<645.0,94.0>>

	* W (U+0057) contains a short segment B<<447.0,2008.0>-<501.0,2008.0>-<524.5,1984.0>>

	* W (U+0057) contains a short segment B<<524.5,1984.0>-<548.0,1960.0>-<552.0,1927.0>>

	* W (U+0057) contains a short segment B<<1383.0,1927.0>-<1396.0,1960.0>-<1419.5,1984.0>>

	* W (U+0057) contains a short segment B<<1419.5,1984.0>-<1443.0,2008.0>-<1490.0,2008.0>>

	* W (U+0057) contains a short segment B<<1490.0,2008.0>-<1547.0,2008.0>-<1568.5,1985.5>>

	* W (U+0057) contains a short segment B<<1568.5,1985.5>-<1590.0,1963.0>-<1595.0,1927.0>>

	* W (U+0057) contains a short segment B<<2436.0,1929.0>-<2451.0,1968.0>-<2474.5,1988.0>>

	* W (U+0057) contains a short segment B<<2474.5,1988.0>-<2498.0,2008.0>-<2549.0,2008.0>>

	* W (U+0057) contains a short segment B<<2549.0,2008.0>-<2596.0,2008.0>-<2618.5,1975.0>>

	* W (U+0057) contains a short segment B<<2618.5,1975.0>-<2641.0,1942.0>-<2622.0,1895.0>>

	* W (U+0057) contains a short segment B<<1897.0,90.0>-<1879.0,46.0>-<1857.5,23.0>>

	* W (U+0057) contains a short segment B<<1857.5,23.0>-<1836.0,0.0>-<1792.0,0.0>>

	* W (U+0057) contains a short segment B<<1792.0,0.0>-<1750.0,0.0>-<1725.0,24.5>>

	* W (U+0057) contains a short segment B<<1725.0,24.5>-<1700.0,49.0>-<1694.0,88.0>>

	* W (U+0057) contains a short segment B<<851.0,92.0>-<836.0,52.0>-<812.5,26.0>>

	* W (U+0057) contains a short segment B<<812.5,26.0>-<789.0,0.0>-<745.0,0.0>>

	* Ntilde (U+00D1) contains a short segment B<<1372.0,85.0>-<1368.0,45.0>-<1352.0,22.5>>

	* Wgrave (U+1E80) contains a short segment B<<745.0,0.0>-<706.0,0.0>-<679.0,24.5>>

	* Wgrave (U+1E80) contains a short segment B<<679.0,24.5>-<652.0,49.0>-<645.0,94.0>>

	* Wgrave (U+1E80) contains a short segment B<<447.0,2008.0>-<501.0,2008.0>-<524.5,1984.0>>

	* Wgrave (U+1E80) contains a short segment B<<524.5,1984.0>-<548.0,1960.0>-<552.0,1927.0>>

	* Wgrave (U+1E80) contains a short segment B<<1383.0,1927.0>-<1396.0,1960.0>-<1419.5,1984.0>>

	* Wgrave (U+1E80) contains a short segment B<<1419.5,1984.0>-<1443.0,2008.0>-<1490.0,2008.0>>

	* Wgrave (U+1E80) contains a short segment B<<1490.0,2008.0>-<1547.0,2008.0>-<1568.5,1985.5>>

	* Wgrave (U+1E80) contains a short segment B<<1568.5,1985.5>-<1590.0,1963.0>-<1595.0,1927.0>>

	* Wgrave (U+1E80) contains a short segment B<<2436.0,1929.0>-<2451.0,1968.0>-<2474.5,1988.0>>

	* Wgrave (U+1E80) contains a short segment B<<2474.5,1988.0>-<2498.0,2008.0>-<2549.0,2008.0>>

	* Wgrave (U+1E80) contains a short segment B<<2549.0,2008.0>-<2596.0,2008.0>-<2618.5,1975.0>>

	* Wgrave (U+1E80) contains a short segment B<<2618.5,1975.0>-<2641.0,1942.0>-<2622.0,1895.0>>

	* Wgrave (U+1E80) contains a short segment B<<1897.0,90.0>-<1879.0,46.0>-<1857.5,23.0>>

	* Wgrave (U+1E80) contains a short segment B<<1857.5,23.0>-<1836.0,0.0>-<1792.0,0.0>>

	* Wgrave (U+1E80) contains a short segment B<<1792.0,0.0>-<1750.0,0.0>-<1725.0,24.5>>

	* Wgrave (U+1E80) contains a short segment B<<1725.0,24.5>-<1700.0,49.0>-<1694.0,88.0>>

	* Wgrave (U+1E80) contains a short segment B<<851.0,92.0>-<836.0,52.0>-<812.5,26.0>>

	* Wgrave (U+1E80) contains a short segment B<<812.5,26.0>-<789.0,0.0>-<745.0,0.0>>

	* Euro (U+20AC) contains a short segment B<<39.5,653.0>-<18.0,678.0>-<18.0,709.0>>

	* Euro (U+20AC) contains a short segment B<<18.0,709.0>-<18.0,739.0>-<39.5,764.5>>

	* Euro (U+20AC) contains a short segment B<<84.5,1080.0>-<63.0,1105.0>-<63.0,1135.0>>

	* Euro (U+20AC) contains a short segment B<<63.0,1135.0>-<63.0,1164.0>-<84.5,1190.0>>

	* Euro (U+20AC) contains a short segment B<<929.0,1190.5>-<951.0,1165.0>-<951.0,1136.0>>

	* Euro (U+20AC) contains a short segment B<<951.0,1136.0>-<951.0,1107.0>-<929.0,1081.0>>

	* Euro (U+20AC) contains a short segment B<<561.0,1055.0>-<559.0,1043.0>-<557.0,1031.0>>

	* Euro (U+20AC) contains a short segment B<<885.0,765.0>-<906.0,740.0>-<906.0,711.0>>

	* Euro (U+20AC) contains a short segment B<<906.0,711.0>-<906.0,682.0>-<884.5,655.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[19] EduSABeginner-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoAscender is 2642 when it should be 2032 [code: bad-typo-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoDescender is -926 when it should be -488 [code: bad-typo-descender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Ascender is 2642 when it should be 2032 [code: bad-hhea-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Descender is -926 when it should be -488 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2866, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: macron	Expected: 1

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: cedilla	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oslash	Expected: 3

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0307	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: breve	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0307	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2
 [code: no-contour]
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

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, old-permic, malayalam, coptic, syriac, tai-le, canadian-aboriginal, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
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
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 939 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 854:
less

Width = 940:
equal, plusminus, notequal

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

	* questiondown (U+00BF): X=501.0,Y=-2.0 (should be at baseline 0?)

	* questiondown (U+00BF): X=501.0,Y=-2.0 (should be at baseline 0?)

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

	* Wgrave (U+1E80) contains a short segment B<<569.5,1978.5>-<604.0,1949.0>-<610.0,1907.0>>

	* Wgrave (U+1E80) contains a short segment B<<1374.0,1909.0>-<1390.0,1950.0>-<1419.5,1979.0>>

	* Wgrave (U+1E80) contains a short segment B<<1608.0,1980.0>-<1638.0,1952.0>-<1645.0,1907.0>>

	* Wgrave (U+1E80) contains a short segment B<<2419.0,1917.0>-<2433.0,1952.0>-<2465.5,1980.0>>

	* Euro (U+20AC) contains a short segment L<<609.0,1028.0>--<609.0,1027.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[18] EduSABeginner-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoAscender is 2642 when it should be 2032 [code: bad-typo-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoDescender is -926 when it should be -488 [code: bad-typo-descender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Ascender is 2642 when it should be 2032 [code: bad-hhea-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Descender is -926 when it should be -488 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2866, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: macron	Expected: 1

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: cedilla	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oslash	Expected: 3

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0307	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: breve	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0307	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2
 [code: no-contour]
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

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, old-permic, malayalam, coptic, syriac, tai-le, canadian-aboriginal, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
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
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 988 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 896:
less

Width = 991:
equal, notequal

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

	* Wgrave (U+1E80) contains a short segment B<<2709.5,1906.0>-<2720.0,1864.0>-<2704.0,1826.0>>

	* ygrave (U+1EF3) contains a short segment B<<398.5,274.0>-<409.0,259.0>-<434.0,259.0>>

	* notequal (U+2260) contains a short segment L<<153.0,372.0>--<143.0,372.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[18] EduSABeginner-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoAscender is 2642 when it should be 2032 [code: bad-typo-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: OS/2 sTypoDescender is -926 when it should be -488 [code: bad-typo-descender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Ascender is 2642 when it should be 2032 [code: bad-hhea-ascender]
* 🔥 **FAIL** Edu SA Beginner Regular: hhea Descender is -926 when it should be -488 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2866, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 946, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: macron	Expected: 1

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: cedilla	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oslash	Expected: 3

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0307	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: breve	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0307	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2
 [code: no-contour]
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

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, old-permic, malayalam, coptic, syriac, tai-le, canadian-aboriginal, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
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
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 840 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 771:
greater, less

Width = 839:
equal, notequal

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

	* registered (U+00AE): X=1217.0,Y=2010.0 (should be at cap-height 2008?)

	* registered (U+00AE): X=402.5,Y=2010.0 (should be at cap-height 2008?)

	* degree (U+00B0): X=430.0,Y=2006.0 (should be at cap-height 2008?)

	* Agrave (U+00C0): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Atilde (U+00C3): X=1245.0,Y=1.0 (should be at baseline 0?)

	* Ograve (U+00D2): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Otilde (U+00D5): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* Ygrave (U+1EF2): X=512.0,Y=1.0 (should be at baseline 0?)

	* Euro (U+20AC): X=1139.0,Y=2009.0 (should be at cap-height 2008?)

	* Euro (U+20AC): X=853.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* three (U+0033): B<<916.5,1232.0>-<802.0,1115.0>-<605.0,1087.0>>/B<<605.0,1087.0>-<815.0,1071.0>-<932.5,934.5>> = 12.446355419799241 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 12 | 20 | 42 | 482 | 21 | 368 | 0 |
| 1% | 2% | 4% | 51% | 2% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
