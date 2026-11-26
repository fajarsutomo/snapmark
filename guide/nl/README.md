# SnapMark-gebruikershandleiding

SnapMark maakt opnamen van je Windows-scherm en laat je er annotaties op zetten die **bewerkbaar blijven**: kaders, pijlen, tekst, afdekkingen en meer zijn losse objecten, geen pixels die in de afbeelding zijn geschilderd. De originele afbeelding wordt nooit gewijzigd.

[Andere talen / Other languages](../README.md)

## Inhoud

1. [Installeren](#installeren)
2. [Het scherm vastleggen](#het-scherm-vastleggen)
3. [Annotatiehulpmiddelen](#annotatiehulpmiddelen)
4. [Sneltoetsen](#sneltoetsen)
5. [Kopiëren en opslaan](#kopiëren-en-opslaan)
6. [Projecten en geschiedenis](#projecten-en-geschiedenis)
7. [Instellingen](#instellingen)
8. [Privacy](#privacy)
9. [Problemen oplossen](#problemen-oplossen)

## Installeren

Start het installatieprogramma `SnapMark_x.y.z_x64-setup.exe`. Het installeert alleen voor jouw account (geen beheerdersrechten nodig). Daarna draait SnapMark in het **systeemvak** (het pictogrammengebied bij de klok). Zie je het pictogram niet, klik dan op de pijl ^ om verborgen pictogrammen te tonen.

Klik met rechts op het pictogram voor het menu: **Opname**, **Geschiedenis**, **Project openen…**, **Instellingen**, **Afsluiten**.

## Het scherm vastleggen

1. Druk op **Print Screen** (of klik op het pictogram in het systeemvak, of kies **Opname**). Het scherm bevriest even; bij meerdere beeldschermen worden alle vastgelegd.
2. **Sleep** om een gebied te kiezen. Je kunt het op elk moment aanpassen, ook na het toevoegen van annotaties: sleep de **rand** om het te verplaatsen, een **handvat** op een hoek of zijde om het formaat te wijzigen, of sleep in het donkere gebied eromheen om opnieuw te kiezen. Pijltoetsen verschuiven het gebied; **Ctrl + pijl** wijzigt het formaat; **Shift** maakt de stap 10 pixels.
3. Voeg annotaties toe met de werkbalk.
4. Druk op **Enter** om naar het klembord te kopiëren, of op **Ctrl+S** om op te slaan. **Esc** annuleert.

De eerste Esc heft de selectie van objecten op; de volgende sluit SnapMark.

## Annotatiehulpmiddelen

| Hulpmiddel | Toets | Opmerkingen |
|---|---|---|
| Selecteren en bewerken | `V` | Klik op een object om het te selecteren; **Shift+klik** voegt toe aan of verwijdert uit de selectie. Sleep om te verplaatsen, trek aan een handvat om het formaat te wijzigen. |
| Rechthoek | `R` | **Shift** = vierkant. Kan gevuld worden. |
| Ellips | `E` | **Shift** = cirkel. |
| Lijn | `L` | **Shift** = vergrendelen op hoeken van 45°. Stijlen: ononderbroken, dubbel, gestippeld. |
| Pijl | `A` | **Shift** = 45°. Punt aan één of beide uiteinden. |
| Vrije pen | `P` | Vrij tekenen. |
| Markeerstift | `H` | Doorschijnende marker. |
| Afdekken | `S` | Mozaïek, vervagen of **zwart blok** (het veiligst). Rechthoek- of penseelvorm. |
| Stapnummer | `N` | Klik om 1, 2, 3… in volgorde te plaatsen. |
| Tekst | `T` | Achtergrond naar keuze. **Ctrl+Enter** of **Esc** voltooit. |

Kleur, lijndikte, lettergrootte en vet stel je in op de werkbalk; wijzigingen gelden voor de geselecteerde objecten.

## Sneltoetsen

| Toets | Actie |
|---|---|
| `Enter` / `Ctrl+C` | Resultaat naar het klembord kopiëren |
| `Ctrl+S` | PNG opslaan in de opslagmap |
| `Ctrl+Shift+S` | Opslaan als… |
| `Ctrl+Alt+S` | Een `.snapmark`-project opslaan |
| `Ctrl+Z` / `Ctrl+Y` (of `Ctrl+Shift+Z`) | Ongedaan maken / opnieuw |
| `Ctrl+D` | Geselecteerde objecten dupliceren |
| `Ctrl+A` | Alle objecten selecteren |
| `Ctrl+]` / `Ctrl+[` | Naar voren / naar achteren |
| `Delete` / `Backspace` | Geselecteerde objecten verwijderen |
| Pijltoetsen (`Shift` = 10 px) | Geselecteerde objecten verplaatsen; zonder selectie het gebied verplaatsen (met `Ctrl`: formaat wijzigen) |
| `Esc` | Selectie opheffen, daarna sluiten |

## Kopiëren en opslaan

Het resultaat is altijd **alleen het gekozen gebied**, in de **oorspronkelijke resolutie** van het scherm, precies zoals je het ziet.

- **Kopiëren** (Enter): naar het klembord, klaar om te plakken.
- **Opslaan** (Ctrl+S): direct in de opslagmap als `snapmark_20261125_143005.png` (datum_tijd). Bestaande bestanden worden nooit overschreven (er wordt `_2`, `_3`, … toegevoegd). Standaardmap: `Afbeeldingen\SnapMark`.
- **Opslaan als** (Ctrl+Shift+S): kies zelf naam en map.

Na succesvol kopiëren of opslaan sluit SnapMark automatisch.

## Projecten en geschiedenis

Een **`.snapmark`-project** bewaart de originele afbeelding plus elke annotatie als object, zodat je het later opnieuw kunt openen en bewerken. Sla op met **Ctrl+Alt+S**; open door te dubbelklikken op het bestand of via systeemvak → **Project openen…**.

> **Pas op met afdekkingen.** Omdat het projectbestand de *originele* afbeelding bewaart, kan iedereen die het bestand opent zien wat je hebt afgedekt. Gebruik om te delen **Kopiëren** of **PNG opslaan**; die bevatten alleen het afgedekte resultaat. SnapMark waarschuwt je voordat een project met een afdekking wordt opgeslagen.

**Geschiedenis**: elke keer Kopiëren/Opslaan wordt automatisch vastgelegd als bewerkbaar project (standaard de laatste 50, alleen op deze computer). Open het via systeemvak → **Geschiedenis** en klik op een item om het opnieuw te bewerken.

## Instellingen

Systeemvak → **Instellingen**.

| Instelling | Beschrijving |
|---|---|
| Sneltoets voor schermopname | Standaard `Print Screen`. Klik op **Wijzigen…** en druk op de nieuwe combinatie (gebruik Ctrl/Alt/Win zodat het typen niet hinderlijk wordt). |
| Opslagmap | Bestemming van Ctrl+S. |
| Taal | Bahasa Indonesia, English, Español, Deutsch, 日本語, 简体中文, Français, Italiano, Português (Brasil), 한국어, Русский, العربية, Nederlands, of zoals Windows. |
| Geschiedenis | Hoeveel items bewaard blijven (0 = uit, maximaal 500). |
| Starten met Windows | SnapMark staat klaar zodra je inlogt. |
| Hintkleur | Kleur van de instructietekst tijdens het kiezen van een gebied. |
| Thema | Zoals Windows, Licht, Donker of Liquid Glass. |
| Updates | Elke 6 uur automatisch zoeken en installeren, of **Nu controleren**. |

Updates worden van de officiële release gedownload, zonder installatievenster geïnstalleerd, en SnapMark opent zichzelf weer; je instellingen en geschiedenis blijven behouden. Een update wacht tot je klaar bent met bewerken.

## Privacy

- Opnamen en projecten **verlaten je computer nooit**.
- Geen telemetrie. De enige netwerktoegang is de updatecontrole.

## Problemen oplossen

**Print Screen doet niets / de sneltoets is niet actief.** Windows 11 kan die toets reserveren voor zijn eigen opnamehulpmiddel. Klik in de SnapMark-instellingen op **Windows-toetsenbordinstellingen openen** en schakel de optie uit waarmee de Print Screen-toets dat hulpmiddel opent (naam en plaats van de optie verschillen per Windows-versie). Of kies een andere sneltoets.

**Het pictogram in het systeemvak ontbreekt.** Klik op de pijl ^ in de taakbalk en sleep het SnapMark-pictogram naar buiten zodat het altijd zichtbaar is.

**Waar de gegevens staan.** Instellingen: `%APPDATA%\app.snapmark.desktop\settings.json`. Geschiedenis: `%LOCALAPPDATA%\app.snapmark.desktop\history`.
