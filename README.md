# Hechelbacher_Mitschrift

Mitschrift für den Unterricht von Seiwald Markus - Hechelbacher Lucas

Das ist die Readme.md Datei. MD steht für Markdown. MD ist eine heutzutage weit verbreitete Auszeichnungssprache (_Markup Language_, [Wikipedia](https://de.wikipedia.org/wiki/Auszeichnungssprache))

# Allgemeines

Website ist aufgebaut mit HTML, CSS und JavaScript.
HTML wird als Root gesehen, also als grundlegende Struktur einer Webseite, auf der CSS und JavaScript aufbauen.

DOM (_Document Object Model_) ist eine Programmierschnittstelle für HTML- und XML-Dokumente. Sie stellt die Struktur eines Dokuments als Baum von Objekten dar, sodass Programmiersprachen wie JavaScript auf die Elemente zugreifen und diese manipulieren können.

UI-Komponente

- Daten
- Template(Vorlage)
- Logik

**_Unterschied Zuweisung und Mutation_**

- **Zuweisung**: Das Zuweisen eines neuen Wertes zu einer Variablen. Beispiel in JavaScript:

  ```javascript
  let x = 5; // Zuweisung
  x = 10; // Neue Zuweisung
  ```

- **Mutation**: Das Ändern des Inhalts eines bestehenden Objekts oder Arrays, ohne die Referenz zu ändern. Beispiel in JavaScript.

**Der Begriff Stack**

Ein Stack ist eine lineare Datenstruktur, die auf dem Prinzip "Last In, First Out" (LIFO) basiert. Das bedeutet, dass das letzte Element, das in den Stack eingefügt wird, als erstes wieder entfernt wird.
Das andere ist die Queue, die auf dem Prinzip "First In, First Out" (FIFO) basiert. Das bedeutet, dass das erste Element, das in die Queue eingefügt wird, als erstes wieder entfernt wird.

Ein **Serverstack** ist eine Sammlung von Technologien, die zusammen verwendet werden, um eine Webanwendung zu erstellen. Ein typischer Web-Stack besteht aus:

- **Frontend**: Die Benutzeroberfläche der Anwendung, die im Browser des Benutzers angezeigt wird. Technologien wie HTML, CSS und JavaScript werden verwendet, um das Frontend zu erstellen.
- **API (Application Programming Interface)**: Eine Schnittstelle, die es dem Frontend ermöglicht, mit dem Backend zu kommunizieren. APIs definieren, wie Daten zwischen den beiden Teilen der Anwendung ausgetauscht werden.
- **Backend**: Der Serverteil der Anwendung, der die Geschäftslogik, Datenverarbeitung und Datenbankinteraktionen verwaltet. Programmiersprachen wie Node.js, Python, Ruby oder Java werden häufig für die Backend-Entwicklung verwendet.
- **Datenbank**: Ein System zur Speicherung und Verwaltung von Daten, das vom Backend verwendet wird. Beliebte Datenbanken sind MySQL, PostgreSQL, MongoDB und SQLite.

**Komponente und Props**

Jede Komponente besteht aus drei Hauptbestandteilen: Daten, Template und Logik.

- **Daten**: Enthalten den Zustand der Komponente und werden verwendet, um die Darstellung und das Verhalten zu steuern.
- **Template**: Definiert die Struktur und das Layout der Komponente, oft in HTML oder einer ähnlichen Markup-Sprache.
- **Logik**: Beinhaltet die Funktionen und Methoden, die das Verhalten der Komponente steuern, einschließlich der Reaktion auf Benutzerinteraktionen und der Manipulation der Daten.

**Props** sind die Eigenschaften oder Attribute einer Komponente, die deren Verhalten und Darstellung beeinflussen.

Beispiel für die Verwendung von Props in einer Komponente:
//---//

<script>
  import Child from './Child.svelte';
</script>

<ul>
  <child prop="xyz"> </child>
</ul>

//---//

## ARIA (Accessible Rich Internet Applications)

Aria ist eine Sammlung von Attributen, die verwendet werden, um die Zugänglichkeit von Webinhalten für Menschen mit Behinderungen zu verbessern. Sie steht für _Accessible Rich Internet Applications_ und hilft dabei, dynamische Inhalte und benutzerdefinierte Benutzeroberflächen für Screenreader und andere Hilfstechnologien zugänglich zu machen.

Beispiele für ARIA-Attribute:

- `aria-label`: Gibt eine zugängliche Bezeichnung für ein Element an.
- `aria-hidden`: Gibt an, ob ein Element für Screenreader verborgen ist.
- `aria-expanded`: Gibt an, ob ein Element erweitert oder zusammengeklappt ist.
- `aria-role`: Definiert die Rolle eines Elements, z.B. `button`, `dialog`, `navigation`.

- **Wichtige Runen in JavaScript:**

- $state()
- $derived()
- $effect() "Konstruktor für ein "svelte-File" => SFC

  ```javascript
  let arr = [1, 2, 3];
  arr.push(4); // Mutation des Arrays
  ```

Weitere Bekannte Auszeichnungssprachen sind:

- Hypertext Markup Language (HTML)
- Extensible Markup Language (XML)
- Yet Another Markup Language (YAML, YML)

var benutzt man nicht mehr
let x = 5;
let y = 10;
let x:number = 3;

int x=3
double y=5.0;

Push-benachrichtigungen sind Mitteilungen, die von einer Anwendung an den Benutzer gesendet werden, auch wenn die Anwendung gerade nicht aktiv genutzt wird. Sie werden häufig in mobilen Apps und Webanwendungen verwendet, um Benutzer über neue Inhalte, Nachrichten oder Ereignisse zu informieren.

onclick
(property(JS),attribute(html))

## Zuständigkeiten von HTML und JAVASCRIPT

- **HTML**: Verantwortlich für die Struktur und den Inhalt einer Webseite. HTML definiert Elemente wie Überschriften, Absätze, Listen, Links, Bilder und Formulare.
- **JavaScript**: Verantwortlich für die Interaktivität und das Verhalten einer Webseite. JavaScript kann HTML-Elemente manipulieren, auf Benutzeraktionen reagieren, Daten verarbeiten und dynamische Inhalte erstellen.
- **HTML Grundstruktur**:
  HTML ist das parent von Head und Body, wobei head die meta daten und andere Informationen über das Dokument enthält, während body den eigentlichen Inhalt der Webseite enthält.

---

Unterschied User-Installer vs. System-Installer

- **User-Installer**: Installiert die Software nur für den aktuellen Benutzer. Keine Administratorrechte erforderlich. Die Software wird typischerweise im Benutzerverzeichnis installiert.(Braucht keine Administratorrechte)
- **System-Installer**: Installiert die Software für alle Benutzer des Systems. Administratorrechte erforderlich. Die Software wird typischerweise in einem systemweiten Verzeichnis installiert.(Braucht Administratorrechte)

## Installation von NodeJS

Javascript läuft unter normalen Umständen in einer Browser-Sandbox. (nur im Browser).
Seit ca. 2010 gibt es aber eine Laufzeitumgebung (_Runtime Environment_) für JS, damit man auch Serverseitig JS programmieren und ausführen kann. Diese Laufzeitumgebung heißt [NodeJS](https://nodejs.org/en/download).

## Installation von pnpm

Der Standardmäßige _Paketmanager_ für NodeJS ist `npm` (Node Package Manager). Eine etwas modernere und beliebtere Alternative ist `pnpm` (Performant NPM). Die Webseite ist [https://pnpm.io/]
Die Installation von pnpm erfolgt über npm:

```bash
npm install -g pnpm@latest-11
```

## Installation von Python

Python ist eine weit verbreitete Programmiersprache, die für viele Zwecke verwendet wird, von Webentwicklung bis hin zu Datenanalyse und künstlicher Intelligenz. Die offizielle Webseite für Python ist [https://www.python.org/downloads/](https://www.python.org/downloads/).

Ein Path ist eine Umgebungsvariable, die dem Betriebssystem mitteilt, wo es nach ausführbaren Dateien suchen soll. Wenn du Python installierst, solltest du sicherstellen, dass der Pfad zu Python in deiner PATH-Variable enthalten ist, damit du Python von der Kommandozeile aus ausführen kannst.

---

## Installation von Strapi

Installation mit dem Skript `pnpm create strapi`.
Daraufhin führt das CLI(_Command Line Interface_) durch die Installation. Falls bei der Installation sogenannter `Build scripts` nicht ausgeführt werden können, schlägt die CLI die Fehlerbehandlung selbstständig vor:

1. Wechsel in das Installationsverzeichnis (z.B. mit `cd my-strapi-project`).
2. Neuerlicher Versuch der Installation mit `pnpm install` oder `npm install`. Dieser scheitert in der Regel - die Build-Skripte müssen mit `pnpm approve-build` manuell freigegeben werden.

---

## VibeCoding / AgenticEngineering mit VS Code und GitHub Copilot

VibeCoding passiert in VS Code in erster Linie über die neu eingeführte Agent View.
Dort können alle Anpassungen des "_Coding Harness_" vorgenommen werden. Wir können unserem Harness verschiedene Methoden zum anpassen geben.

# **MCP - Server **

MCP steht für _Model Context Protocoll_. Es ist ein Standard, der von Antrophic entwickelt wurde. Mit Hilfe von MCP können Chatbots/LLMs (_Large Language Models_) mit externen Tools kommunizieren. Diese machen sie zu einem Experten in dem gewissen Bereich, in dem das Tool eingesetzt wird.

# Historische Entwicklung von Webdevelopment

Die Entwicklung des Webs hat mehrere Phasen durchlaufen:

1. **Web 1.0 (statisches Web)**: In den frühen Tagen des Internets bestand das Web hauptsächlich aus statischen HTML-Seiten. Benutzer konnten Inhalte nur lesen, aber nicht interaktiv mit ihnen interagieren. Dominant in den 1990er Jahren.

2. **Web 2.0 (dynamisches Web)**: Mit der Einführung von Technologien wie JavaScript, AJAX und serverseitigen Skriptsprachen wurde das Web interaktiver. Benutzer konnten Inhalte erstellen, teilen und mit anderen interagieren (z.B. soziale Netzwerke, Blogs).Nutzen Datenbanken. Dominant in den 2000er Jahren.

3. **Web 2.5 (Übergang zum semantischen Web - SPA (Single Page Application))**: Diese Phase beschreibt die Übergangszeit zwischen Web 2.0 und Web 3.0, in der erste Ansätze des semantischen Webs und der Dezentralisierung sichtbar wurden.Mit Javascript-Frameworks erstellte "webapps", die ähnlich zu klassischen Desktop-Anwendungen funktionierten(Push,Kamera,GPS,MIKROFON,Bluetooth,Gyroskop).Um Handyapps möglichst nahe zu kommen, wurden oft progressiv webapps entwickelt, die offline funktionieren und native Funktionen des Geräts nutzen konnten, damit konnten sie push-Benachrichtigungen senden. Um als PWA zu gelten, mussten sie bestimmte Kriterien erfüllen, diese sind:
4. Musste über Web-App-Manifest(das ist eine JSON-Datei, die Metadaten über die Web-App enthält) verfügen.

5. Musste Service Worker(das ist ein Skript, das im Hintergrund läuft und Funktionen wie Caching und Push-Benachrichtigungen ermöglicht) implementieren.

6. Musste responsive Design(das bedeutet, dass die Web-App auf verschiedenen Bildschirmgrößen und Geräten gut aussieht und funktioniert) haben und außerdem HTTPS haben.

Frontend-Frameworks wenden folgende Architekturprinzipien an, um eine möglichst gute _User Experience_ zu gewährleisten:

- **Komponentenbasierte Architektur**: **Komponenten** sind wiederverwendbare, eigenständige Bausteine, die die Benutzeroberfläche einer Anwendung darstellen. Jede Komponente kapselt ihre eigene Logik, ihr eigenes Template und ihren eigenen Zustand.

- **Deklarative Programmierung**: Anstatt Schritt für Schritt zu beschreiben, wie die Benutzeroberfläche aktualisiert werden soll, beschreibt man, wie sie aussehen soll, und das Framework kümmert sich um die Aktualisierung der Ansicht, wenn sich der Zustand ändert. Dabei kommt **Reaktivität** ins Spiel, das bedeutet, dass Änderungen im Zustand automatisch die Benutzeroberfläche(UI) aktualisieren. Wenn die aktualisierung auch in andere richtungen funktioniert nennt man das bidirektionale Bindung(two-way binding). Logikelemente(schleifen zur darstellung von Listen und Bedingungen für das konditionale Ein- und ausblenden von UI-Elementen)werden in den Templates der Komponenten definiert, wodurch die Trennung von Logik und Darstellung erleichtert wird. Komponenten können **Props** (Eigenschaften) und **Events** (Ereignisse) verwenden, um Daten zwischen ihnen auszutauschen. Props ermöglichen es, Daten von einer übergeordneten Komponente an eine untergeordnete Komponente zu übergeben, während Events es einer untergeordneten Komponente ermöglichen, Informationen an eine übergeordnete Komponente zurückzusenden.

Dominant in den 2010er Jahren.

4. **Web 3.0 (semantisches Web / dezentrales Web)**: Das Web entwickelt sich hin zu einer semantischen und dezentralen Struktur, in der Daten besser vernetzt und maschinenlesbar sind. Technologien wie Blockchain und KI spielen eine wichtige Rolle. Dominant in den 2020er Jahren.
