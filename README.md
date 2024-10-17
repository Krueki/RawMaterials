# RawMaterials

<h1>HTML Basics Guide</h1>

<p>In dieser Anleitung lernst du die grundlegenden Elemente von HTML kennen, die dir helfen werden, eine einfache Webseite zu erstellen.</p>

<hr>

<h2>1. Was ist HTML?</h2>

<p>HTML (Hypertext Markup Language) ist die Standardsprache zur Erstellung von Webseiten. HTML verwendet <strong>Tags</strong> (Elemente), um den Inhalt einer Seite zu strukturieren.</p>

<hr>

<h2>2. Grundgerüst einer HTML-Datei</h2>

<p>Jede HTML-Datei hat ein grundlegendes Gerüst. Hier ein Beispiel:</p>

<pre>
<code>&lt;!DOCTYPE html&gt;
&lt;html lang="de"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
    &lt;title&gt;Meine Webseite&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;h1&gt;Willkommen auf meiner Webseite!&lt;/h1&gt;
    &lt;p&gt;Dies ist ein Absatz.&lt;/p&gt;
&lt;/body&gt;
&lt;/html&gt;
</code>
</pre>

<p><strong>Erklärung:</strong></p>
<ul>
    <li><code>&lt;!DOCTYPE html&gt;</code>: Deklariert den Dokumenttyp als HTML5.</li>
    <li><code>&lt;html lang="de"&gt;</code>: Beginnt das HTML-Dokument und legt die Sprache auf Deutsch fest.</li>
    <li><code>&lt;head&gt;</code>: Enthält Metadaten über das Dokument (z. B. Zeichensatz und Titel).</li>
    <li><code>&lt;body&gt;</code>: Hier kommt der sichtbare Inhalt der Seite rein.</li>
</ul>

<hr>

<h2>3. Wichtige HTML-Tags</h2>

<h3>3.1. Überschriften (Header)</h3>
<p>Überschriften gibt es in verschiedenen Größen, von <code>&lt;h1&gt;</code> (größte) bis <code>&lt;h6&gt;</code> (kleinste).</p>

<pre>
<code>&lt;h1&gt;Dies ist eine Hauptüberschrift&lt;/h1&gt;
&lt;h2&gt;Dies ist eine Unterüberschrift&lt;/h2&gt;
</code>
</pre>

<h3>3.2. Absätze (Paragraph)</h3>
<p>Absätze werden mit dem <code>&lt;p&gt;</code>-Tag erstellt.</p>

<pre>
<code>&lt;p&gt;Das ist ein Absatz.&lt;/p&gt;
</code>
</pre>

<h3>3.3. Links (Anchor)</h3>
<p>Verwende das <code>&lt;a&gt;</code>-Tag, um Links zu erstellen.</p>

<pre>
<code>&lt;a href="https://www.example.com"&gt;Hier klicken&lt;/a&gt;
</code>
</pre>

<h3>3.4. Bilder (Image)</h3>
<p>Das <code>&lt;img&gt;</code>-Tag fügt ein Bild hinzu. Beispiel:</p>

<pre>
<code>&lt;img src="images/bild.png" alt="Beschreibung des Bildes"&gt;
</code>
</pre>

<hr>

<h2>4. Listen</h2>

<h3>4.1. Geordnete Liste (Ordered List)</h3>
<p>Geordnete Listen verwenden das <code>&lt;ol&gt;</code>-Tag.</p>

<pre>
<code>&lt;ol&gt;
    &lt;li&gt;Erster Punkt&lt;/li&gt;
    &lt;li&gt;Zweiter Punkt&lt;/li&gt;
&lt;/ol&gt;
</code>
</pre>

<h3>4.2. Ungeordnete Liste (Unordered List)</h3>
<p>Ungeordnete Listen verwenden das <code>&lt;ul&gt;</code>-Tag.</p>

<pre>
<code>&lt;ul&gt;
    &lt;li&gt;Erster Punkt&lt;/li&gt;
    &lt;li&gt;Zweiter Punkt&lt;/li&gt;
&lt;/ul&gt;
</code>
</pre>

<hr>

<h2>5. Kommentare in HTML</h2>

<p>Kommentare werden nicht auf der Webseite angezeigt und helfen, den Code zu erklären:</p>

<pre>
<code>&lt;!-- Dies ist ein Kommentar --&gt;
</code>
</pre>

<hr>

<h2>6. Weitere nützliche Ressourcen</h2>

<ul>
    <li><a href="https://developer.mozilla.org/de/docs/Web/HTML">MDN Web Docs: HTML</a></li>
    <li><a href="https://www.w3schools.com/html/">W3Schools: HTML Tutorial</a></li>
</ul>

<hr>




Wie gehe ich mit HTML um? -> Kein Plan!!!

<!-- Dies ist ein HTML Kommentar -->
/* Dies ist ein CSS Kommentar */

Wenn ich in HTML <style> .... <style> verwende, kann man innerhalb dieses Segmentas mit "/* ... */" kommentieren, da es ein CSS code ist

Dieses Style-Segment kann man mit class="Segmentname" callen
