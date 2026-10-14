<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="MioType-Symbol">
</p>

<h1 align="center">MioType</h1>

<p align="center">
  <b>Sprechen statt tippen.</b> Spracheingabe und Sofortübersetzung für den Mac.<br>
  <kbd>Fn</kbd> drücken, sprechen, <kbd>Fn</kbd> noch einmal drücken – der Text steht an deinem Cursor, in jeder App.
</p>

<p align="center">
  <a href="https://miotype.com/download"><b>Für macOS herunterladen</b></a> ·
  <a href="https://miotype.com">Website</a> ·
  <a href="https://miotype.com/pricing">Preise</a>
</p>

<p align="center"><sub><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.pt.md">Português</a> · <a href="README.ru.md">Русский</a></sub></p>

---

Ob dein Cursor im Terminal, in VS Code, in Cursor, im Prompt von Claude Code oder Codex, in einem Slack-Thread oder in einer Commit-Message steht – MioType ist das egal. Es schreibt dorthin, wo der Fokus liegt.

## Tastenkürzel

| Tasten | Was passiert |
|---|---|
| <kbd>Fn</kbd> | Drücken und sprechen, noch einmal drücken, um den Text einzufügen. <kbd>Esc</kbd> bricht ab |
| <kbd>Fn</kbd> + <kbd>Space</kbd> | Frag, was du willst. Markiere vorher Text, um dazu zu fragen, oder sag „mach das kürzer“, um ihn direkt umzuschreiben |
| <kbd>Fn</kbd> + <kbd>Left Shift</kbd> | Chinesisch sprechen, Englisch erhalten – und umgekehrt |
| <kbd>Fn</kbd> + <kbd>Control</kbd> | Markierten Text übersetzen. Ein einzelnes englisches Wort öffnet eine Wörterbuchkarte |
| <kbd>Fn</kbd> + <kbd>R</kbd> | Markierten Text direkt überarbeiten |
| <kbd>Fn</kbd> + <kbd>S</kbd> | Ein Wort oder eine Wendung nachschlagen |

Alle Tastenkürzel lassen sich in den Einstellungen ändern.

## Warum Entwickler es mögen

- **Es schreibt dort, wo dein Cursor ist.** Kein zusätzliches Fenster, kein Kopieren und Einfügen. Diktiere einen langen Prompt für deinen Coding-Agent, eine PR-Beschreibung oder eine Antwort auf ein Issue direkt an Ort und Stelle.
- **Gemischtes Chinesisch und Englisch bleibt gemischt.** Sagst du „把这个 function 改成 async“, steht genau das da. Englische Fachbegriffe werden nicht ins Chinesische übersetzt.
- **Es lernt deinen Wortschatz.** Korrigiere ein falsch erkanntes Wort direkt nach dem Diktat (`kubectl`, `useEffect`, den Namen eines Kollegen), und MioType nimmt es ins Wörterbuch auf – beim nächsten Mal stimmt es. Du kannst auch ein Wörterbuch importieren.
- **Offline ist nur einen Schalter entfernt.** Wähle in den Einstellungen das lokale Whisper-Modell, und deine Sprache verlässt den Mac nie. Funktioniert ohne Netz und ohne Konto.
- **Eigener API-Schlüssel.** Erkennung und Überarbeitung können statt über MioType Cloud über deinen eigenen API-Anbieter laufen.

## Kostenlos und kostenpflichtig

| | |
|---|---|
| **Lokal** | Für immer kostenlos. Offline-Diktat mit Whisper, Übersetzung und Überarbeitung mit deinem eigenen API-Schlüssel. Verlauf, Wörterbuch und Einstellungen bleiben auf deinem Mac |
| **Kostenlose Cloud** | Nach der Anmeldung 3.000 Cloud-Wörter pro Woche |
| **MioType Cloud** | 100.000 Cloud-Wörter im Monat für Cloud-Erkennung, KI-Überarbeitung und Übersetzung, ohne eigenen API-Schlüssel. 9,99 US$/Monat, 59,99 US$/Jahr oder einmalig 149 US$ |

Details auf der [Preisseite](https://miotype.com/pricing). Jeder Kauf kann innerhalb von 14 Tagen ohne Angabe von Gründen erstattet werden.

## Datenschutz

- Lokales Whisper läuft vollständig auf deinem Mac.
- Im Cloud-Modus gehen Audio oder Text jeder Anfrage über unseren Server an Alibaba Cloud Model Studio, das Ergebnis kommt direkt zurück. Unser Server speichert weder Audio noch Text, sondern nur Wortanzahl, Art und Zeitpunkt der Anfrage, um dein Kontingent zu berechnen.
- Mit deinem eigenen API-Schlüssel gehen Anfragen direkt von deinem Mac an den gewählten Anbieter.
- Wir trainieren keine Modelle mit deinen Inhalten und verwenden weder Werbung noch Tracker.
- Vollständige Richtlinie (Englisch): [miotype.com/privacy](https://miotype.com/privacy)

## Voraussetzungen

- Ein Mac mit Apple Silicon (M1 oder neuer)
- Mikrofon- und Bedienungshilfen-Berechtigung. MioType fragt bei der Einrichtung danach

## Feedback

Einen Fehler gefunden oder einen Wunsch? [Eröffne ein Issue](https://github.com/miotype/miotype/issues/new/choose). Für Privates schreib an [hi@miotype.com](mailto:hi@miotype.com).

Die Versionshinweise erscheinen unter [Releases](https://github.com/miotype/miotype/releases). Mit **Watch → Custom → Releases** wirst du über neue Versionen benachrichtigt.

---

MioType ist nicht Open Source. Dieses Repository dient als öffentlicher Issue-Tracker und für die Versionshinweise.
