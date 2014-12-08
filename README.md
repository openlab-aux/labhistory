# Archiv der Geschehnisse im Openlab Augsburg

Hier werden die epischen Storyarks und Geschehnisse des Labs festgehalten.

## Datenformat

* Ein Ordner stellt ein Ereignis da
* Jedes Ereignis hat zwei Dateien, `info.yaml` und optional `history.md`
* Unterordner stellen Unterereignisse da

### info

Metadaten über das Ereignis in YAML. Das vorherig spezifizierte markup-
format fuer die metadaten war sowieso schon valides YAML. So haben 
wir ein einfach erweiterbares metadatenformat, das schon vielfach in 
verschiedensten Programmiersprachen implementiert wurde um eventuelle 
zukuenftige maschinelle Analyse zu vereinfachen.

    key: value



~~ Der erste `:` ist der Trenner, Whitespace um ihn wird gestripped. ~~


Felder:

    name: Name
    from: Startdatum
    to: Enddatum
    …: weitere sind möglich

### history.md

Markdown-Datei, in der das Ereignis dokumentiert wird.
