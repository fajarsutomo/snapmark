# SnapMark – Benutzerhandbuch

SnapMark nimmt den Windows-Bildschirm auf und lässt dich ihn mit Markierungen versehen, die **bearbeitbar bleiben**: Rahmen, Pfeile, Text, Schwärzungen und mehr sind eigene Objekte, keine ins Bild gemalten Pixel. Das Originalbild wird nie verändert.

[Andere Sprachen / Other languages](../README.md)

## Inhalt

1. [Installation](#installation)
2. [Bildschirm aufnehmen](#bildschirm-aufnehmen)
3. [Anmerkungswerkzeuge](#anmerkungswerkzeuge)
4. [Tastenkürzel](#tastenkürzel)
5. [Kopieren und Speichern](#kopieren-und-speichern)
6. [Projekte und Verlauf](#projekte-und-verlauf)
7. [Einstellungen](#einstellungen)
8. [Datenschutz](#datenschutz)
9. [Problemlösung](#problemlösung)

## Installation

Starte das Installationsprogramm `SnapMark_x.y.z_x64-setup.exe`. Es installiert nur für dein Konto (keine Administratorrechte nötig). Danach läuft SnapMark im **Infobereich** der Taskleiste (neben der Uhr). Ist das Symbol nicht zu sehen, zeige mit dem Pfeil ^ die ausgeblendeten Symbole an.

Rechtsklick auf das Symbol öffnet das Menü: **Aufnehmen**, **Verlauf**, **Projekt öffnen…**, **Einstellungen**, **Beenden**.

## Bildschirm aufnehmen

1. Drücke **Druck** (oder klicke auf das Symbol im Infobereich bzw. wähle **Aufnehmen**). Der Bildschirm friert kurz ein; bei mehreren Monitoren werden alle aufgenommen.
2. **Ziehe**, um einen Bereich zu wählen. Du kannst ihn jederzeit ändern, auch nach dem Hinzufügen von Anmerkungen: Ziehe den **Rand**, um ihn zu verschieben, einen **Griff** an Ecke oder Seite, um die Größe zu ändern, oder ziehe im dunklen Bereich außerhalb, um neu zu wählen. Pfeiltasten verschieben den Bereich; **Strg + Pfeil** ändert seine Größe; **Umschalt** macht die Schritte 10 Pixel groß.
3. Füge mit der Symbolleiste Anmerkungen hinzu.
4. **Eingabe** kopiert in die Zwischenablage, **Strg+S** speichert. **Esc** bricht ab.

Das erste Esc hebt die Objektauswahl auf, das nächste schließt SnapMark.

## Anmerkungswerkzeuge

| Werkzeug | Taste | Hinweise |
|---|---|---|
| Auswählen & bearbeiten | `V` | Objekt anklicken zum Auswählen; **Umschalt+Klick** fügt hinzu/entfernt. Ziehen verschiebt, am Griff ziehen ändert die Größe. |
| Rechteck | `R` | **Umschalt** = Quadrat. Kann gefüllt werden. |
| Ellipse | `E` | **Umschalt** = Kreis. |
| Linie | `L` | **Umschalt** = auf 45° einrasten. Stile: durchgezogen, doppelt, gestrichelt. |
| Pfeil | `A` | **Umschalt** = 45°. Spitze an einem oder beiden Enden. |
| Freihandstift | `P` | Freies Zeichnen. |
| Textmarker | `H` | Durchscheinender Marker. |
| Schwärzen | `S` | Mosaik, Weichzeichnen oder **schwarzer Block** (am sichersten). Rechteck- oder Pinselform. |
| Schrittnummer | `N` | Klicken setzt 1, 2, 3… der Reihe nach. |
| Text | `T` | Hintergrund wählbar. **Strg+Eingabe** oder **Esc** beendet. |

Farbe, Linienstärke, Schriftgröße und Fett stellst du in der Symbolleiste ein; Änderungen gelten für die ausgewählten Objekte.

## Tastenkürzel

| Taste | Aktion |
|---|---|
| `Eingabe` / `Strg+C` | Ergebnis in die Zwischenablage kopieren |
| `Strg+S` | PNG im Speicherordner speichern |
| `Strg+Umschalt+S` | Speichern unter… |
| `Strg+Alt+S` | `.snapmark`-Projekt speichern |
| `Strg+Z` / `Strg+Y` (oder `Strg+Umschalt+Z`) | Rückgängig / Wiederholen |
| `Strg+D` | Ausgewählte Objekte duplizieren |
| `Strg+A` | Alle Objekte auswählen |
| `Strg+]` / `Strg+[` | Nach vorne / nach hinten |
| `Entf` / `Rücktaste` | Ausgewählte Objekte löschen |
| Pfeile (`Umschalt` = 10 px) | Ausgewählte Objekte verschieben; ohne Auswahl den Bereich verschieben (mit `Strg`: Größe ändern) |
| `Esc` | Auswahl aufheben, dann schließen |

## Kopieren und Speichern

Das Ergebnis ist immer **nur der gewählte Bereich** in der **Originalauflösung** des Bildschirms, genau wie du es siehst.

- **Kopieren** (Eingabe): landet in der Zwischenablage, bereit zum Einfügen.
- **Speichern** (Strg+S): direkt im Speicherordner als `snapmark_20261125_143005.png` (Datum_Uhrzeit). Vorhandene Dateien werden nie überschrieben (es wird `_2`, `_3`, … angehängt). Standardordner: `Bilder\SnapMark`.
- **Speichern unter** (Strg+Umschalt+S): Name und Ordner selbst wählen.

Nach erfolgreichem Kopieren oder Speichern schließt sich SnapMark automatisch.

## Projekte und Verlauf

Ein **`.snapmark`-Projekt** speichert das Originalbild und jede Anmerkung als Objekt, sodass du es später wieder öffnen und bearbeiten kannst. Speichern mit **Strg+Alt+S**; öffnen per Doppelklick auf die Datei oder über Infobereich → **Projekt öffnen…**.

> **Vorsicht bei Schwärzungen.** Da die Projektdatei das *Originalbild* enthält, kann jeder, der die Datei öffnet, Geschwärztes sehen. Zum Teilen nutze **Kopieren** oder **PNG speichern**; sie enthalten nur das geschwärzte Ergebnis. SnapMark warnt dich, bevor ein Projekt mit Schwärzung gespeichert wird.

**Verlauf**: Jedes Kopieren/Speichern wird automatisch als bearbeitbares Projekt erfasst (standardmäßig die letzten 50, nur auf diesem Computer). Öffne ihn über Infobereich → **Verlauf** und klicke einen Eintrag, um ihn erneut zu bearbeiten.

## Einstellungen

Infobereich → **Einstellungen**.

| Einstellung | Beschreibung |
|---|---|
| Aufnahme-Hotkey | Standard `Druck`. Klicke auf **Ändern…** und drücke die neue Kombination (mit Strg/Alt/Win, damit sie das Tippen nicht stört). |
| Speicherordner | Ziel von Strg+S. |
| Sprache | Bahasa Indonesia, English, Español, Deutsch, 日本語, 简体中文, Français, Italiano, Português (Brasil), 한국어, Русский, العربية, Nederlands oder wie Windows. |
| Verlauf | Wie viele Einträge behalten werden (0 = aus, höchstens 500). |
| Mit Windows starten | SnapMark ist ab der Anmeldung bereit. |
| Hinweisfarbe | Farbe des Anleitungstextes bei der Bereichsauswahl. |
| Design | Wie Windows, Hell, Dunkel oder Liquid Glass. |
| Updates | Alle 6 Stunden automatisch suchen und installieren, oder **Jetzt prüfen**. |

Updates werden aus dem offiziellen Release geladen, ohne Installationsfenster installiert, und SnapMark startet von selbst neu; Einstellungen und Verlauf bleiben erhalten. Ein Update wartet, bis du mit dem Bearbeiten fertig bist.

## Datenschutz

- Aufnahmen und Projekte **verlassen deinen Computer nie**.
- Keine Telemetrie. Der einzige Netzwerkzugriff ist die Update-Suche.

## Problemlösung

**Druck tut nichts / der Hotkey ist nicht aktiv.** Windows 11 kann diese Taste für sein eigenes Aufnahmetool belegen. Klicke in den SnapMark-Einstellungen auf **Windows-Tastatureinstellungen öffnen** und schalte die Option aus, mit der die Druck-Taste dieses Tool öffnet (Name und Ort der Option unterscheiden sich je nach Windows-Version). Oder wähle einen anderen Hotkey.

**Das Symbol im Infobereich fehlt.** Klicke auf den Pfeil ^ in der Taskleiste und ziehe das SnapMark-Symbol heraus, damit es immer sichtbar ist.

**Wo die Daten liegen.** Einstellungen: `%APPDATA%\app.snapmark.desktop\settings.json`. Verlauf: `%LOCALAPPDATA%\app.snapmark.desktop\history`.
