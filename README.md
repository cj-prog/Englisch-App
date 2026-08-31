# 🦊 Fred der Englisch-Fuchs

## 🆕 Was zuletzt neu kam

- **Version 2.1:** Deine Freunde **schreiben dir jetzt von selbst**! 📩 Wenn du
  eine Weile weg warst, warten neue Nachrichten auf dich (grüner Punkt und
  „NEU" in der Liste, 📩-Zähler auf der Startseite) – und auch beim Spielen
  meldet sich ab und zu einer. Antippen, und ihr redet einfach da weiter!
  (Das Tablet klingelt nur, wenn die App offen ist – zaubern kann sie nicht. 😉)

- **Version 2.0:** Die Themen im Chat stehen jetzt **groß untereinander** –
  wie eine richtige Liste zum Antippen, bei jedem Freund gleich. Oben siehst
  du immer das Bild von deinem Freund.

- **Version 1.9:** Deine Freunde wohnen jetzt in einem **Messenger wie auf dem
  Handy**! 📱 Tippe auf „Mit deinen Freunden reden" und du siehst alle 8
  Freunde untereinander zum Hoch- und Runterschieben – mit der letzten
  Nachricht darunter. Freund antippen → er fragt dich, worüber ihr reden
  wollt. Und das Beste: Eure alten Nachrichten bleiben gespeichert, wie in
  einem echten Chat!

- **Version 1.8:** Jetzt hast du eine ganze **Freundes-Bande**! 🎉 Neben Fred
  und Lucy warten: Koko der Koala 🐨, Pip das Pinguin-Mädchen 🐧, Rex der
  Dino 🦖 (mit Brummstimme!), Milo der Affe 🐵, Stella das Einhorn 🦄 und
  Sparky der Roboter 🤖. Jeder wohnt woanders, mag andere Sachen und klingt
  anders – such dir vor jedem Gespräch aus, mit wem du reden willst!

- **Version 1.7:** Du hast jetzt eine zweite Freundin: **Lucy, die Wölfin aus
  Amerika**! 🐺 Beim „Mit Fred & Lucy reden" suchst du dir vorher aus, mit wem
  du quatschen willst. Lucy liebt Tiere, Fußball und Klettern, spielt auch
  JonahCraft – und spricht mit einer Mädchenstimme, amerikanisch!

- **Version 1.6:** Die Stimmen-Auswahl funktioniert jetzt wirklich! Vorher hat
  die App heimlich immer „Britisch" verlangt – da haben viele Geräte einfach
  ihre Standardstimme genommen, egal was man wählte. Jetzt zählt deine Wahl,
  „Tiefer" klingt deutlich tiefer, und im Elternbereich steht, welche Stimme
  gerade wirklich spricht.
- **Version 1.5:** Deine Sticker wohnen jetzt in einem richtigen Heft mit
  Deckblatt und Seiten zum Umblättern – einfach wischen! 👉
- **Version 1.4:** Quiz spielen mit 3 Fragearten! Dazu 4 neue Themen (Karate,
  Werkstatt, Essen, Farben & Zahlen), Fred kennt jetzt dein JonahCraft-Spiel
  (Hunde zähmen, Autos, Geheimfestung!), Fred kann eine Jungen-Stimme haben,
  und im Chat siehst du, ob der echte KI-Fred da ist (🤖) oder der Übungs-Fred (📖).
- **Version 1.3:** Der „Wie sagt man …?"-Helfer im Chat: Sag ein Wort auf
  Deutsch und Fred verrät dir das Englische.

Eine kleine Englisch-Lern-App für Jonah (9 Jahre, 3. Klasse). Fred ist ein
frecher Fuchs aus England, der sich wie ein Brieffreund mit Jonah unterhält –
über Tiere, Minecraft und den Alltag. Gelernt wird wenig, aber das Richtige:
einfache Sätze, die man wirklich braucht.

## Was die App kann (Prototyp)

- **Wortschatz-Kisten**: 3 Themen (Hallo Fred!, Tiere, Minecraft) mit je
  7 alltagstauglichen Wörtern/Sätzen – mit Vorlesestimme zum Nachsprechen.
- **Mit Fred reden**: echtes Gespräch per Mikrofon oder Antwort-Chips.
  - **Übungsmodus** (ohne API-Schlüssel): vorbereitete Dialoge, funktioniert sofort.
  - **KI-Modus** (mit Anthropic-API-Schlüssel): Fred antwortet frei, bleibt aber
    bei einfachem Englisch, dem Themen-Wortschatz und kindgerechten Inhalten.
- **Sticker-Album**: Für jede Wortschatz-Kiste und jedes Gespräch gibt es einen
  Sticker – mit seltenen und super-seltenen Exemplaren zum Sammeln.
- **Elternbereich** (Zahnrad oben rechts, Rechenaufgabe als Kindersicherung):
  Name, API-Schlüssel, Modellwahl, gelernte Wörter, letztes Gespräch einsehen,
  alles zurücksetzen.

## Benutzen

Die ganze App ist **eine einzige Datei**: `index.html`.

1. Datei herunterladen und im Browser öffnen (am Tablet am besten **Chrome** –
   dort funktionieren Vorlesen *und* Spracheingabe).
2. Optional: Über das Browser-Menü „Zum Startbildschirm hinzufügen" – dann
   fühlt es sich wie eine richtige App an.
3. Alternativ per GitHub Pages hosten (Settings → Pages → Branch wählen), dann
   ist die App unter einer festen Adresse erreichbar.

Alle Daten (Sticker, Fortschritt, Einstellungen, API-Schlüssel) bleiben lokal
im Browser des Geräts. Nichts wird irgendwo hochgeladen – im KI-Modus gehen
nur die Chat-Nachrichten an die Anthropic-API.

## KI-Modus einrichten

1. Auf [console.anthropic.com](https://console.anthropic.com) ein Konto anlegen.
2. Unter **Billing** Guthaben aufladen (Prepaid, z. B. 5 $ – mehr kann nicht
   abgebucht werden, solange „Auto-Reload" ausgeschaltet bleibt).
3. Unter **API Keys** einen Schlüssel erstellen (`sk-ant-…`).
4. In der App: Zahnrad → Rechenaufgabe lösen → Schlüssel einfügen. Fertig.

Kosten bei täglicher Nutzung, grob geschätzt: Claude Opus 5 ≈ 5–10 €/Monat,
Claude Haiku 4.5 ≈ 1–2 €/Monat (im Elternbereich wählbar).

## Ideen für später

- Mehr Themen (Karate, Werkstatt, Essen, Zahlen & Farben beim Tauschen)
- Wiederholung nach Lernkarten-Prinzip (Wörter kommen wieder, bis sie sitzen)
- Bessere Fred-Stimme über eine Sprach-API
- Sticker-Tauschbörse / Quests („Benutze heute 3 neue Wörter")
- Wochenrückblick für Eltern
