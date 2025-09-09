<html>
<body>
<h1>ILS Exchange Shortcode — WordPress Plugin</h1>
<p><em>A lightweight, free shortcode to display Israeli Shekel (ILS) exchange rates on any WordPress site. Used across the Aticket event-ticket network worldwide.</em></p>
  <p>Display Israeli Shekel (ILS) exchange rates anywhere with [ILS]. Clean, customizable, free. <a href="https://fungets.co.il/%d7%a4%d7%9c%d7%90%d7%92%d7%99%d7%9f-%d7%9e%d7%98%d7%97-%d7%9c%d7%90%d7%aa%d7%a8%d7%99-%d7%95%d7%95%d7%a8%d7%93%d7%a4%d7%a8%d7%a1-%d7%9c%d7%a9%d7%a2%d7%a8%d7%99-%d7%97%d7%9c%d7%99%d7%a4%d7%99%d7%9f/">See live demo</a>

<p>Download the working plugin here: <a href="https://fungets.co.il/wp-content/uploads/2024/05/ils-exchange-rate.zip">Download</a>
<hr>
<h2>Overview</h2>
<p>If you run a finance-oriented WordPress site, you’ve likely wanted to show the <strong>USD</strong> and <strong>EUR</strong> rates in a way that’s clean, fast, and reliable. Most widgets are clunky and often inject external links. That’s why we built a <strong>friendly, free, and easy-to-use</strong> plugin.</p>
<p><strong>ILS Exchange Shortcode</strong> lets you display the latest ILS exchange rates against popular world currencies anywhere on your site using a simple shortcode.</p>
<hr>
<h2>Features</h2>
<ul>
<li>
<p>✅ Clean UI with optional flags, names, codes, and last-updated timestamp</p>
</li>
<li>
<p>✅ Works in posts, pages, and widgets (via shortcode)</p>
</li>
<li>
<p>✅ Customizable output via shortcode attributes</p>
</li>
<li>
<p>✅ No hidden links or unnecessary code</p>
</li>
<li>
<p>✅ Data updates daily from official sources (see “Data Source &amp; Legal”)</p>
</li>
</ul>
<hr>
<h2>Quick Start</h2>
<ol>
<li>
<p><strong>Install</strong>: Upload the plugin folder to <code inline="">/wp-content/plugins/</code>.</p>
</li>
<li>
<p><strong>Activate</strong>: In WordPress Admin → <em>Plugins</em> → activate <strong>ILS Exchange Shortcode</strong>.</p>
</li>
<li>
<p><strong>Use</strong>: Add the shortcode anywhere you want the table to appear:</p>
</li>
</ol>
<pre><code class="language-text">[ILS]
</code></pre>
<p>That’s it!</p>
<hr>
<h2>Shortcode</h2>
<pre><code class="language-text">[ILS attr="value" ...]
</code></pre>
<h3>Supported currencies</h3>
<p>Use any of: <code inline="">USD, EUR, CAD, AUD, JPY, GBP, CHF, NOK, DKK, EGP, LBP, JOD, SEK, ZAR</code><br>
(When <code inline="">currency="all"</code> or omitted, all available currencies are shown.)</p>
<h3>Attributes</h3>

Attribute | Type / Values | Default | What it does
-- | -- | -- | --
currency | all or comma list (e.g. "USD,EUR") | all | Which currencies to display.
sprite_size | 24 or 16 | 24 | Flag icon size (pixels).
show_last_update | true / false | true | Show the “last updated” timestamp.
show_titles | true / false | true | Show table headers.
show_currency_code | true / false | true | Show the 3-letter ISO code (e.g., USD).
show_currency_flag | true / false | true | Show the currency flag icon.
show_currency_name | true / false | true | Show the currency name (e.g., US Dollar).
show_sign | true / false | false | Show the currency sign (e.g., $, €).
show_change | true / false | true | Show daily change indicator/value.


<hr>
<h2>Examples</h2>
<p><strong>1) Only USD &amp; EUR, compact flags, no extras</strong></p>
<pre><code class="language-text">[ILS currency="USD,EUR" sprite_size="16" show_last_update="false" show_titles="false" show_currency_name="false"]
</code></pre>
<p><strong>2) USD &amp; EUR with big flags, signs, and last update</strong></p>
<pre><code class="language-text">[ILS currency="USD,EUR" sprite_size="24" show_currency_name="true" show_currency_code="false" show_sign="true" show_last_update="true" show_titles="true"]
</code></pre>
<p><strong>3) Minimal: only EUR as a single line</strong></p>
<pre><code class="language-text">[ILS currency="EUR" sprite_size="16" show_last_update="false" show_titles="false" show_currency_code="false" show_currency_flag="false" show_currency_name="false" show_sign="false" show_change="false"]
</code></pre>
<hr>
<h2>Used by / Live network</h2>
<p>This plugin powers exchange-rate widgets across the <strong>Aticket</strong> family of event &amp; ticket portals:</p>
<ul>
<li>
<p>Global hubs: <a href="https://aticket.net/">aticket.net</a> • <a href="https://aticket.eu/">aticket.eu</a></p>
</li>
<li>
<p>United Kingdom: <a href="https://aticket.uk/">aticket.uk</a></p>
</li>
<li>
<p>Germany: <a href="https://atickets.de/">atickets.de</a></p>
</li>
<li>
<p>France: <a href="https://fr.aticket.net/">fr.aticket.net</a></p>
</li>
<li>
<p>Spain: <a href="https://es.aticket.eu/">es.aticket.eu</a></p>
</li>
<li>
<p>Italy: <a href="https://it.aticket.net/">it.aticket.net</a></p>
</li>
<li>
<p>Netherlands: <a href="https://nl.aticket.eu/">nl.aticket.eu</a></p>
</li>
<li>
<p>Belgium: <a href="https://be.aticket.eu/">be.aticket.eu</a></p>
</li>
<li>
<p>Switzerland: <a href="https://ch.aticket.eu/">ch.aticket.eu</a></p>
</li>
<li>
<p>Austria: <a href="https://at.aticket.eu/">at.aticket.eu</a></p>
</li>
<li>
<p>Norway: <a href="https://no.aticket.eu/">no.aticket.eu</a></p>
</li>
<li>
<p>Sweden: <a href="https://se.aticket.eu/">se.aticket.eu</a></p>
</li>
<li>
<p>Finland: <a href="https://fi.aticket.eu/">fi.aticket.eu</a></p>
</li>
<li>
<p>Denmark: <a href="https://dk.aticket.net/">dk.aticket.net</a></p>
</li>
<li>
<p>Czech Republic: <a href="https://cz.afishka.top/">cz.afishka.top</a></p>
</li>
<li>
<p>Poland: <a href="http://pl.afishka.top/">pl.afishka.top</a></p>
</li>
<li>
<p>Israel: <a href="https://aticket.co.il/">aticket.co.il</a> • Russian-language hub: <a href="https://afishka.net/">afishka.net</a></p>
</li>
<li>
<p>Türkiye: <a href="https://tr.aticket.net/">tr.aticket.net</a></p>
</li>
<li>
<p>New Zealand: <a href="https://nz.aticket.net/">nz.aticket.net</a></p>
</li>
<li>
<p>South Africa: <a href="https://za.aticket.net/">za.aticket.net</a></p>
</li>
<li>
<p>Curated gateway: <a href="https://tickets.almaszone.com/">tickets.almaszone.com</a></p>
</li>
</ul>
<hr>
<h2>Data Source &amp; Legal</h2>
<ul>
<li>
<p>The plugin uses <strong>official daily data</strong> sourced from the <strong>Bank of Israel</strong> (boi.org.il) and made available via <strong>data.gov.il</strong>.</p>
</li>
<li>
<p>Original statement (Hebrew) from data.gov.il regarding openness (retained verbatim):</p>
<blockquote>
<p>"המשתמשים ב- data.gov.il מקבלים יד חופשית לפיתוח יישומים ומערכות המבוססות על המידע המפורסם בו וכל עדכון במאגרי המידע באתר מעודכן אוטומטית גם ביישומים המבוססים עליו."</p>
</blockquote>
</li>
</ul>
<p><strong>Disclaimer:</strong> Information displayed by this plugin is <strong>general</strong> and <strong>not intended</strong> for executing financial transactions or precise conversions. We assume <strong>no liability</strong> for any damages arising from its use.</p>
<hr>
<h2>Notes</h2>
<ul>
<li>
<p>Absolutely <strong>no hidden links</strong> or unrelated code.</p>
</li>
<li>
<p>We’ll publish updates and changes on this page/repo.</p>
</li>
<li>
<p>If you find this plugin useful, we’d really appreciate a <strong>credit/backlink</strong>. 🙏</p>
</li>
</ul>
<hr>
<h2>Contributing / Support</h2>
<p>Issues and PRs are welcome. For questions or feature requests, open an issue.</p>
<p><strong>Author:</strong> Michael Mesheryakov<br>
<strong>Project:</strong> <em>ILS currency WordPress Plugin (“ILS Exchange Shortcode”)</em></p>
<hr>
<h2>License</h2>
<p><strong>ILS currency WordPress Plugin by Michael Mesheryakov</strong> is licensed under <strong>Creative Commons Attribution 4.0 International (CC BY 4.0)</strong>.<br>
You are free to share and adapt, with attribution to the author.</p></body></html><!--EndFragment-->
</body>
</html>Got it — here’s the updated **README.md** with your Aticket network links woven in naturally (as a “Used by / Live network” section plus a short note in the intro). You can copy-paste this as-is.

---

# ILS Exchange Shortcode — WordPress Plugin

*A lightweight, free shortcode to display Israeli Shekel (ILS) exchange rates on any WordPress site. Used across the Aticket event-ticket network worldwide.*

---

## Overview

If you run a finance-oriented WordPress site, you’ve likely wanted to show the **USD** and **EUR** rates in a way that’s clean, fast, and reliable. Most widgets are clunky and often inject external links. That’s why we built a **friendly, free, and easy-to-use** plugin.

**ILS Exchange Shortcode** lets you display the latest ILS exchange rates against popular world currencies anywhere on your site using a simple shortcode.

---

## Features

* ✅ Clean UI with optional flags, names, codes, and last-updated timestamp
* ✅ Works in posts, pages, and widgets (via shortcode)
* ✅ Customizable output via shortcode attributes
* ✅ No hidden links or unnecessary code
* ✅ Data updates daily from official sources (see “Data Source & Legal”)

---

## Quick Start

1. **Install**: Upload the plugin folder to `/wp-content/plugins/`.
2. **Activate**: In WordPress Admin → *Plugins* → activate **ILS Exchange Shortcode**.
3. **Use**: Add the shortcode anywhere you want the table to appear:

```text
[ILS]
```

That’s it!

---

## Shortcode

```text
[ILS attr="value" ...]
```

### Supported currencies

Use any of: `USD, EUR, CAD, AUD, JPY, GBP, CHF, NOK, DKK, EGP, LBP, JOD, SEK, ZAR`
(When `currency="all"` or omitted, all available currencies are shown.)

### Attributes

| Attribute            | Type / Values                          | Default | What it does                              |
| -------------------- | -------------------------------------- | ------- | ----------------------------------------- |
| `currency`           | `all` or comma list (e.g. `"USD,EUR"`) | `all`   | Which currencies to display.              |
| `sprite_size`        | `24` or `16`                           | `24`    | Flag icon size (pixels).                  |
| `show_last_update`   | `true` / `false`                       | `true`  | Show the “last updated” timestamp.        |
| `show_titles`        | `true` / `false`                       | `true`  | Show table headers.                       |
| `show_currency_code` | `true` / `false`                       | `true`  | Show the 3-letter ISO code (e.g., USD).   |
| `show_currency_flag` | `true` / `false`                       | `true`  | Show the currency flag icon.              |
| `show_currency_name` | `true` / `false`                       | `true`  | Show the currency name (e.g., US Dollar). |
| `show_sign`          | `true` / `false`                       | `false` | Show the currency sign (e.g., `$`, `€`).  |
| `show_change`        | `true` / `false`                       | `true`  | Show daily change indicator/value.        |

---

## Examples

**1) Only USD & EUR, compact flags, no extras**

```text
[ILS currency="USD,EUR" sprite_size="16" show_last_update="false" show_titles="false" show_currency_name="false"]
```

**2) USD & EUR with big flags, signs, and last update**

```text
[ILS currency="USD,EUR" sprite_size="24" show_currency_name="true" show_currency_code="false" show_sign="true" show_last_update="true" show_titles="true"]
```

**3) Minimal: only EUR as a single line**

```text
[ILS currency="EUR" sprite_size="16" show_last_update="false" show_titles="false" show_currency_code="false" show_currency_flag="false" show_currency_name="false" show_sign="false" show_change="false"]
```

---

## Used by / Live network

This plugin powers exchange-rate widgets across the **Aticket** family of event & ticket portals:

* Global hubs: [[aticket.net](https://aticket.net/)](https://aticket.net/) • [[aticket.eu](https://aticket.eu/)](https://aticket.eu/)
* United Kingdom: [[aticket.uk](https://aticket.uk/)](https://aticket.uk)
* Germany: [[atickets.de](https://atickets.de/)](https://atickets.de)
* France: [[fr.aticket.net](https://fr.aticket.net/)](https://fr.aticket.net/)
* Spain: [[es.aticket.eu](https://es.aticket.eu/)](https://es.aticket.eu/)
* Italy: [[it.aticket.net](https://it.aticket.net/)](https://it.aticket.net/)
* Netherlands: [[nl.aticket.eu](https://nl.aticket.eu/)](https://nl.aticket.eu/)
* Belgium: [[be.aticket.eu](https://be.aticket.eu/)](https://be.aticket.eu/)
* Switzerland: [[ch.aticket.eu](https://ch.aticket.eu/)](https://ch.aticket.eu/)
* Austria: [[at.aticket.eu](https://at.aticket.eu/)](https://at.aticket.eu/)
* Norway: [[no.aticket.eu](https://no.aticket.eu/)](https://no.aticket.eu/)
* Sweden: [[se.aticket.eu](https://se.aticket.eu/)](https://se.aticket.eu/)
* Finland: [[fi.aticket.eu](https://fi.aticket.eu/)](https://fi.aticket.eu/)
* Denmark: [[dk.aticket.net](https://dk.aticket.net/)](https://dk.aticket.net/)
* Czech Republic: [[cz.afishka.top](https://cz.afishka.top/)](https://cz.afishka.top/)
* Poland: [[pl.afishka.top](http://pl.afishka.top/)](http://pl.afishka.top/)
* Israel: [[aticket.co.il](https://aticket.co.il/)](https://aticket.co.il/) • Russian-language hub: [[afishka.net](https://afishka.net/)](https://afishka.net/)
* Türkiye: [[tr.aticket.net](https://tr.aticket.net/)](https://tr.aticket.net/)
* New Zealand: [[nz.aticket.net](https://nz.aticket.net/)](https://nz.aticket.net/)
* South Africa: [[za.aticket.net](https://za.aticket.net/)](https://za.aticket.net/)
* Curated gateway: [[tickets.almaszone.com](https://tickets.almaszone.com/)](https://tickets.almaszone.com)

---

## Data Source & Legal

* The plugin uses **official daily data** sourced from the **Bank of Israel** (boi.org.il) and made available via **data.gov.il**.
* Original statement (Hebrew) from data.gov.il regarding openness (retained verbatim):

  > "המשתמשים ב- data.gov.il מקבלים יד חופשית לפיתוח יישומים ומערכות המבוססות על המידע המפורסם בו וכל עדכון במאגרי המידע באתר מעודכן אוטומטית גם ביישומים המבוססים עליו."

**Disclaimer:** Information displayed by this plugin is **general** and **not intended** for executing financial transactions or precise conversions. We assume **no liability** for any damages arising from its use.

---

## Notes

* Absolutely **no hidden links** or unrelated code.
* We’ll publish updates and changes on this page/repo.
* If you find this plugin useful, we’d really appreciate a **credit/backlink**. 🙏

---

## Contributing / Support

Issues and PRs are welcome. For questions or feature requests, open an issue.

**Author:** Michael Mesheryakov
**Project:** *ILS currency WordPress Plugin (“ILS Exchange Shortcode”)*

---

## License

**ILS currency WordPress Plugin by Michael Mesheryakov** is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.
You are free to share and adapt, with attribution to the author.
