# Softwareentwicklung und Projektmanagement (SWPP)

## Allgemeines <!-- {docsify-ignore} -->

Diese **Dokumentation** begleitet das Fach **SWPP**. Es werden diverse
Dokumentationen für unterschiedliche Projekte mit `Markdown`erstellt.

![Projektmanagement](_media/desk-g28d1c7952_1280.png)

## Lehrplan<!-- {docsify-ignore} -->

<!-- tabs:start -->
### ** Bildungs- und Lehraufgabe **

* Phasen des Projektmanagements in der Softwareentwicklung
erläutern 
* phasenbezogenene Dokumente unterscheiden und erklären
* zyklische Sichtweise des Phasenmodells
* Projektmanagement in Bezug auf eine *komplexe betriebswirtschaftliche
Applikation* aus **APR**
### ** Lehrstoff **

- Planungsphase 
- Defintionsphase
- Entwurfsphase
- Implementierungsphase
- Abnahme
- Einführungsphase
- Wartungs- und Pflegephase

<!-- tabs:end -->

## Technische Umsetzung<!-- {docsify-ignore} -->
Die technische Umsetzung erfolgt in einem **GitHub-Projekt.**
Für die Arbeit mit der Dokumentation wird mit `Markdown` gearbeitet. 
Als Software zur Erstellung der Dokumentation wird
[docsify](https://docsify.js.org/#/) eingesetzt.

### Hinweise
Hinweise werden mittels `?>` erstellt.
Ein wichtiger Inhalt kann mit `!>` gekennzeichnet werden.

?> Das ist ein Hinweis. 

!> Das ist absolut wichtig!

### Quelltext
Quelltexte werden mit `Prism.js` dargestellt und
werden folgendermaßen gestaltet:

```bash
npm i docsify-cli -g
```

```bash
docsify init ./docs
```

```bash
docsify serve ./docs
```

Eine C#-Datei wird mit `Datei.cs` benannt.
Der Quellcode einer Datei wird formatiert dargestellt:

```csharp
public class Demo {
    public string Text => "Hallo, Welt!"
}
```

### Emoji

Emojis werden ebenfalls unterstützt:

:100: :fire: :apple: :grin: :wink: :relaxed: :mask:

```markdown
:100: :fire: :apple: :grin: :wink: :relaxed: :mask:
```

?> Mehr Emojis sind unter <https://gist.github.com/rxaviers/7360908>


### Tabellen

Tabellen werden ebenfalls in `Markdown` erstellt.

| Begriff                | Erklärung                                            |
| :---------------------:| -----------------------------------------------------|
| Interface              | **Schnittstelle:** legt Methoden und Attribute fest. |
| OOP                    | Objektorientierte Programmierung                     |
| Klasse                 | Bauplan                                              |

***

```markdown
| Begriff                | Erklärung                                            |
| :---------------------:| -----------------------------------------------------|
| Interface              | **Schnittstelle:** legt Methoden und Attribute fest. |
| OOP                    | Objektorientierte Programmierung                     |
| Klasse                 | Bauplan                                              |
```

### Aufgaben

- [x] eine erledigte Aufgabe
- [ ] noch nicht erledigte Aufgabe
- [ ] eine weitere noch nicht erledigte Aufgabe






