## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[5] NotoSansLinearB-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni10091 (U+10091): B<<179.0,291.0>-<192.0,279.0>-<196.0,258.0>>/L<<196.0,258.0>--<196.0,402.0>> = 10.784297867562596

	* uni10091 (U+10091): L<<196.0,0.0>--<196.0,219.0>>/B<<196.0,219.0>-<190.0,193.0>-<164.5,168.0>> = 12.994616791916512

	* uni10097 (U+10097): B<<245.0,660.0>-<289.0,604.0>-<301.0,520.0>>/L<<301.0,520.0>--<301.0,660.0>> = 8.13010235415596

	* uni10097 (U+10097): L<<371.0,660.0>--<371.0,521.0>>/B<<371.0,521.0>-<382.0,604.0>-<425.0,660.0>> = 7.549421768263246

	* uni1009E (U+1009E): B<<213.0,623.5>-<185.0,669.0>-<180.0,731.0>>/L<<180.0,731.0>--<180.0,166.0>> = 4.610649318660583

	* uni1009E (U+1009E): L<<570.0,166.0>--<570.0,731.0>>/B<<570.0,731.0>-<565.0,669.0>-<536.5,623.5>> = 4.610649318660583

	* uni100C1 (U+100C1): B<<394.5,385.5>-<425.0,427.0>-<452.0,433.0>>/B<<452.0,433.0>-<415.0,433.0>-<380.5,435.5>> = 12.528807709151492

	* uni100C1 (U+100C1): B<<539.5,435.5>-<505.0,433.0>-<469.0,433.0>>/B<<469.0,433.0>-<496.0,427.0>-<526.0,386.0>> = 12.528807709151492

	* uni100D2 (U+100D2): B<<217.0,579.5>-<188.0,619.0>-<180.0,677.0>>/L<<180.0,677.0>--<180.0,63.0>> = 7.853313301978193 

	* And uni100D2 (U+100D2): L<<570.0,63.0>--<570.0,674.0>>/B<<570.0,674.0>-<562.0,617.0>-<533.0,578.0>> = 7.989326766396871 [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 5 | 111 | 7 | 104 | 0 |
| 0% | 0% | 2% | 49% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
