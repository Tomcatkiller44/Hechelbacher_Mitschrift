# Hechelbacher_Mitschrift

Mitschrift für den Unterricht von Seiwald Markus - Hechelbacher Lucas

Das ist die Readme.md Datei. MD steht für Markdown. MD ist eine heutzutage weit verbreitete Auszeichnungssprache (_Markup Language_, [Wikipedia](https://de.wikipedia.org/wiki/Auszeichnungssprache))

# Allgemeines

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

## Installation von Strapi

Installation mit dem Skript `pnpm create strapi`.
Daraufhin führt das CLI durch die Installation. Falls bei der Installation sogenannter `Build scripts` nicht ausgeführt werden können, schlägt die CLI die Fehlerbehandlung selbstständig vor:

1. Wechsel in das Installationsverzeichnis (z.B. mit `cd my-strapi-project`).
2. Neuerlicher Versuch der Installation mit `pnpm install` oder `npm install`. Dieser scheitert in der Regel - die Build-Skripte müssen mit `pnpm approve-build` manuell freigegeben werden.
