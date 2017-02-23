
---
Titel: Über das Schreiben und Formatierung auf GitHub
Intro: {{ site.data.guides.dotcom-writing-on-github.shortdesc.about-writing-and-formatting-on-github }}
---

[Markdown] (http://daringfireball.net/ proProjekte / Abschlags /) ist ein einfach zu lesen, einfach zu schreiben Syntax für Klartextformatierung.

Wir haben einige benutzerdefinierte Funktionen hinzugefügt zu erstellen {{site.data.variables. proKanal. product_name}} Flavored Markdown verwendet Format prose und Code auf unserer Seite.

Sie können auch mit anderen Benutzern in Pull-Anforderungen, Probleme und Wikis mit Funktionen wie [@mentions] (/ articles / basic-Schreiben-und-Formatierung-Syntax / # Erwähnens-users-and-Teams) interagieren, [Ausgabe und PR Referenzen] (/ articles / basic-Schreiben-und-Formatierung-Syntax / # Referenzierung-Fragen-und-Pull-Requests) und [emoji] (/ articles / basic-Schreiben-und-Formatierung-Syntax / # using-emoji ).

{% If page.version == 'Dotcom' oder page.version == 'Wolke' oder page.version> 2,5%}

### Textformatierungssymbolleiste
Jeder Kommentarfeld auf {{site.data.variables. proKanal. product_name}} enthält eine Textformatierungssymbolleiste, so dass Sie Ihren Text zu formatieren, ohne Markdown-Syntax lernen. Neben Markdown Formatierung wie fett und kursiv und Erstellen von Headern, Links und lists, enthält die Symbolleiste {{site.data.variables proKanal product_name}..} - Spezifische Funktionen wie @ erwähnt, Aufgabe lists, und Links zu Fragen und Anfragen zu ziehen.

![Markdown toolbar](/assets/images/help/writing/markdown-toolbar.gif)

{% endif %}

### Weiterführende Literatur

- "[Grund Schreiben und Formatieren Syntax] (/ articles / basic-Schreiben-und-Formatierung-Syntax)"
- "[Arbeiten mit erweiterten Formatierungs] (/ articles / Arbeiter mit fortgeschrittenen-Formatierung)"
- "[Mastering Markdown] (https://guides.github.com/features/mastering-markdown/)"
- "[Markdown-Tutorial] (http://markdowntutorial.com/)"


    var s = "JavaScript syntax highlighting";
    alert(s);
    
    return s;

Ein Tisch
=======

Markdown | Weniger | Ziemlich
--- | --- | ---
* Noch * | `Renders` | **schön**
1 | 2 | 3


`` `Java
            
            Optional <BlockMarker>newBlock = findStartingBlockMarker (Linie);

            if (newBlock.isPresent ()) {
              if (! lastLineWasEmpty) {
                segments.add (seg);
                seg = new Segment ();
              }

              seg.addLine (Linie, lineEmpty);
              actualBlock = newBlock.get ();
`` `

<dl>
  <dt>Definition list</dt>
  <dd>Ist etwas, das Menschen manchmal verwenden. </dd>

  <dt>Markdown in HTML </dt>
  <dd>* nicht * Arbeit ** sehr ** gut. Verwenden Sie HTML <em>Tags </em>. </dd>
</dl>

>Blockzitate sind sehr praktisch in emailAntworttext zu emulieren.
>Diese Zeile ist Teil des gleichen Zitat.
>
>Eine leere Zeile in einem Block vorhanden war
