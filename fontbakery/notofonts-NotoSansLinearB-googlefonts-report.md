## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[8] NotoSansLinearB-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansLinearB/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, todhri, coptic, syriac, malayalam, duployan, math, hebrew, canadian-aboriginal, tai-le, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>linear-b</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kaska (Latn, 125 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Han (Latn, 6 speakers), Nateni (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Navajo (Latn, 166,319 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Vute (Latn, 21,000 speakers), Cicipu (Latn, 44,000 speakers), Avokaya (Latn, 100,000 speakers), Mfumte (Latn, 79,000 speakers), Koonzime (Latn, 40,000 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Fur (Latn, 1,230,163 speakers), Ekpeye (Latn, 226,000 speakers), Heiltsuk (Latn, 300 speakers), Ngbaka (Latn, 1,020,000 speakers), Igbo (Latn, 27,823,640 speakers), Dii (Latn, 71,000 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers), Kom (Latn, 360,685 speakers), Gulay (Latn, 250,478 speakers), Ebira (Latn, 2,200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Makaa (Latn, 221,000 speakers), Southern Kisi (Latn, 360,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni10091 (U+10091): B&lt;&lt;179.0,291.0&gt;-&lt;192.0,279.0&gt;-&lt;196.0,258.0&gt;&gt;/L&lt;&lt;196.0,258.0&gt;--&lt;196.0,402.0&gt;&gt; = 10.784297867562596

* uni10091 (U+10091): L&lt;&lt;196.0,0.0&gt;--&lt;196.0,219.0&gt;&gt;/B&lt;&lt;196.0,219.0&gt;-&lt;190.0,193.0&gt;-&lt;164.5,168.0&gt;&gt; = 12.994616791916512

* uni10097 (U+10097): B&lt;&lt;245.0,660.0&gt;-&lt;289.0,604.0&gt;-&lt;301.0,520.0&gt;&gt;/L&lt;&lt;301.0,520.0&gt;--&lt;301.0,660.0&gt;&gt; = 8.13010235415596

* uni10097 (U+10097): L&lt;&lt;371.0,660.0&gt;--&lt;371.0,521.0&gt;&gt;/B&lt;&lt;371.0,521.0&gt;-&lt;382.0,604.0&gt;-&lt;425.0,660.0&gt;&gt; = 7.549421768263246

* uni1009E (U+1009E): B&lt;&lt;213.0,623.5&gt;-&lt;185.0,669.0&gt;-&lt;180.0,731.0&gt;&gt;/L&lt;&lt;180.0,731.0&gt;--&lt;180.0,166.0&gt;&gt; = 4.610649318660583

* uni1009E (U+1009E): L&lt;&lt;570.0,166.0&gt;--&lt;570.0,731.0&gt;&gt;/B&lt;&lt;570.0,731.0&gt;-&lt;565.0,669.0&gt;-&lt;536.5,623.5&gt;&gt; = 4.610649318660583

* uni100C1 (U+100C1): B&lt;&lt;394.5,385.5&gt;-&lt;425.0,427.0&gt;-&lt;452.0,433.0&gt;&gt;/B&lt;&lt;452.0,433.0&gt;-&lt;415.0,433.0&gt;-&lt;380.5,435.5&gt;&gt; = 12.528807709151492

* uni100C1 (U+100C1): B&lt;&lt;539.5,435.5&gt;-&lt;505.0,433.0&gt;-&lt;469.0,433.0&gt;&gt;/B&lt;&lt;469.0,433.0&gt;-&lt;496.0,427.0&gt;-&lt;526.0,386.0&gt;&gt; = 12.528807709151492

* uni100D2 (U+100D2): B&lt;&lt;217.0,579.5&gt;-&lt;188.0,619.0&gt;-&lt;180.0,677.0&gt;&gt;/L&lt;&lt;180.0,677.0&gt;--&lt;180.0,63.0&gt;&gt; = 7.853313301978193

* uni100D2 (U+100D2): L&lt;&lt;570.0,63.0&gt;--&lt;570.0,674.0&gt;&gt;/B&lt;&lt;570.0,674.0&gt;-&lt;562.0,617.0&gt;-&lt;533.0,578.0&gt;&gt; = 7.989326766396871
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 7 | 117 | 6 | 120 | 0 | 
| 0% | 0% | 0% | 3% | 47% | 2% | 48% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
