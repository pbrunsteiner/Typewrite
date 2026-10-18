# Typewrite

Typewrite ist ein Schreibprogramm für macOS, das wie Fineliner auf Papier funktioniert.
Was du geschrieben hast, trocknet und bleibt stehen. Ändern heißt streichen und neu schreiben, und die alte Fassung bleibt sichtbar.

[Typewrite 1.0 laden](https://github.com/pbrunsteiner/Typewrite/releases/latest)

## Funktionen

- **Nasse Tinte:** Was du gerade schreibst, ist fett und lässt sich bis zum nächsten Satzzeichen löschen. Dann trocknet die Tinte.
- **Streichen und ersetzen:** Du markierst Text und drückst Enter, oder du tippst gleich den Ersatz. Er steht in Korrekturtinte darüber oder daneben.
- **Schreiben und Lektorat:** Beim Schreiben streichst du ganze Satzteile. Im Lektorat (⌘L) korrigierst du einzelne Wörter in roter Tinte.
- **Randnotizen und Verlauf:** ⌘K setzt eine Notiz an den Rand. ⌘Y zeigt alle Korrekturen und Randnotizen.
- **Laden und Zettel:** Jede Szene steht auf einem Zettel, die Zettel liegen in Laden. Du ordnest sie frei und liest mehrere zusammen.
- **Fundkiste:** Du sammelst Ideen als Haftzettel, für ein Projekt oder für alle. Der Würfel zieht drei zufällige Ideen.
- **Fassungen:** Du schreibst einen Zettel für die nächste Fassung ab und vergleichst zwei Fassungen nebeneinander.
- **Fokus:** Das Blatt läuft wie in einer Schreibmaschine, dazu gibt es einen Timer, ein Tages- und ein Projektziel sowie den Klang der Tasten.
- **Export:** Normseite als PDF oder Druck, dazu Word, Markdown und Text.
- **Sprache:** Deutsch und Englisch, nach der Systemsprache oder nach Einstellung.

## Installation

1. Lade `Typewrite-1.0.dmg` von der [Release-Seite](https://github.com/pbrunsteiner/Typewrite/releases/latest).
2. Öffne die Datei und ziehe Typewrite in den Ordner „Programme“.
3. Öffne Typewrite. Beim ersten Start meldet macOS, dass es die App nicht prüfen konnte. Klicke auf „Fertig“.
4. Öffne Systemeinstellungen → Datenschutz & Sicherheit. Ganz unten steht „Typewrite wurde blockiert“. Klicke auf „Dennoch öffnen“ und bestätige mit Passwort oder Touch ID.

Diesen Schritt brauchst du nur beim ersten Start, weil Apple Typewrite noch nicht beglaubigt (notarisiert) hat.
Typewrite läuft ab macOS 13 (Ventura) auf Macs mit Apple-Chip und mit Intel.

## Deine Texte

Deine Texte bleiben auf deinem Mac. Unter Ablage → „Projekt öffnen …“ wählst du einen Ordner. Typewrite speichert dort jeden Zettel als Markdown-Datei mit [CriticMarkup](https://github.com/CriticMarkup/CriticMarkup-toolkit), die du auch in Obsidian lesen kannst.

```
Mein Roman/
  projekt.md                         Titel, Ziele, Gliederung
  01-ankunft/_gruppe.md
  01-ankunft/01-der-bahnhof.md       aktuelle Fassung
  fassungen/01-ankunft/01-der-bahnhof.f1.md
  fundkiste.md
  .typewrite/projekt.json            Verknüpfungen und Ansicht
```

`{--gestrichen--}`, `{++eingefügt++}`, `{~~alt~>neu~~}`, `{==Wörter==}{>>Randnotiz<<}`

---

## Typewrite in English

Typewrite is a writing app for macOS that works like a fineliner on paper. What you write dries and stays. You change text by striking it and writing anew, and the old version stays visible.

Download `Typewrite-1.0.dmg` from the [release page](https://github.com/pbrunsteiner/Typewrite/releases/latest), drag Typewrite into “Applications” and open it. On the first launch, open System Settings → Privacy & Security and click “Open Anyway”. Typewrite follows your system language. You can change it in Settings → Appearance.
