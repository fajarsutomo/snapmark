# Guida utente di SnapMark

SnapMark cattura lo schermo di Windows e ti permette di annotarlo con segni che **restano modificabili**: rettangoli, frecce, testo, oscuramenti e altro sono oggetti separati, non pixel dipinti sull'immagine. L'immagine originale non viene mai modificata.

[Altre lingue / Other languages](../README.md)

## Indice

1. [Installazione](#installazione)
2. [Catturare lo schermo](#catturare-lo-schermo)
3. [Strumenti di annotazione](#strumenti-di-annotazione)
4. [Scorciatoie da tastiera](#scorciatoie-da-tastiera)
5. [Copiare e salvare](#copiare-e-salvare)
6. [Progetti e cronologia](#progetti-e-cronologia)
7. [Impostazioni](#impostazioni)
8. [Privacy](#privacy)
9. [Risoluzione dei problemi](#risoluzione-dei-problemi)

## Installazione

Esegui il programma di installazione `SnapMark_x.y.z_x64-setup.exe`. Si installa solo per il tuo account (non servono permessi di amministratore). Poi SnapMark resta nell'**area di notifica** (vicino all'orologio). Se l'icona non si vede, clicca sulla freccia ^ per mostrare le icone nascoste.

Clic destro sull'icona per aprire il menu: **Cattura**, **Cronologia**, **Apri progetto…**, **Impostazioni**, **Esci**.

## Catturare lo schermo

1. Premi **Stamp** (oppure clicca l'icona nell'area di notifica, o scegli **Cattura**). Lo schermo si blocca per un istante; con più monitor vengono catturati tutti.
2. **Trascina** per scegliere un'area. Puoi cambiarla in qualsiasi momento, anche dopo aver aggiunto annotazioni: trascina il suo **bordo** per spostarla, una **maniglia** su un angolo o un lato per ridimensionarla, oppure trascina nella zona scura esterna per sceglierne una nuova. I tasti freccia spostano l'area; **Ctrl + freccia** la ridimensiona; **Maiusc** rende il passo di 10 pixel.
3. Usa la barra degli strumenti per aggiungere annotazioni.
4. Premi **Invio** per copiare negli appunti, oppure **Ctrl+S** per salvare. **Esc** annulla.

Il primo Esc deseleziona gli oggetti; il successivo chiude SnapMark.

## Strumenti di annotazione

| Strumento | Tasto | Note |
|---|---|---|
| Seleziona e modifica | `V` | Clicca un oggetto per selezionarlo; **Maiusc+clic** aggiunge o toglie dalla selezione. Trascina per spostare, tira una maniglia per ridimensionare. |
| Rettangolo | `R` | **Maiusc** = quadrato. Può essere riempito. |
| Ellisse | `E` | **Maiusc** = cerchio. |
| Linea | `L` | **Maiusc** = angoli di 45°. Stili: continua, doppia, tratteggiata. |
| Freccia | `A` | **Maiusc** = 45°. Punta a una o a entrambe le estremità. |
| Penna libera | `P` | Disegno a mano libera. |
| Evidenziatore | `H` | Pennarello traslucido. |
| Oscura | `S` | Mosaico, sfocatura o **blocco nero** (il più sicuro). Forma rettangolare o a pennello. |
| Numero di passaggio | `N` | Clicca per inserire 1, 2, 3… in ordine. |
| Testo | `T` | Sfondo a scelta. **Ctrl+Invio** o **Esc** termina. |

Colore, spessore, dimensione del carattere e grassetto si impostano nella barra degli strumenti; le modifiche valgono per gli oggetti selezionati.

## Scorciatoie da tastiera

| Tasto | Azione |
|---|---|
| `Invio` / `Ctrl+C` | Copia il risultato negli appunti |
| `Ctrl+S` | Salva il PNG nella cartella di salvataggio |
| `Ctrl+Maiusc+S` | Salva con nome… |
| `Ctrl+Alt+S` | Salva un progetto `.snapmark` |
| `Ctrl+Z` / `Ctrl+Y` (o `Ctrl+Maiusc+Z`) | Annulla / ripeti |
| `Ctrl+D` | Duplica gli oggetti selezionati |
| `Ctrl+A` | Seleziona tutti gli oggetti |
| `Ctrl+]` / `Ctrl+[` | In primo piano / in secondo piano |
| `Canc` / `Backspace` | Elimina gli oggetti selezionati |
| Frecce (`Maiusc` = 10 px) | Sposta gli oggetti selezionati; senza selezione sposta l'area (con `Ctrl`: la ridimensiona) |
| `Esc` | Deseleziona, poi chiudi |

## Copiare e salvare

Il risultato è sempre **solo l'area selezionata**, alla **risoluzione originale** dello schermo, esattamente come la vedi.

- **Copia** (Invio): va negli appunti, pronta da incollare.
- **Salva** (Ctrl+S): direttamente nella cartella di salvataggio come `snapmark_20261125_143005.png` (data_ora). I file esistenti non vengono mai sovrascritti (si aggiunge il suffisso `_2`, `_3`, …). Cartella predefinita: `Immagini\SnapMark`.
- **Salva con nome** (Ctrl+Maiusc+S): scegli tu nome e cartella.

Dopo una copia o un salvataggio riuscito, SnapMark si chiude automaticamente.

## Progetti e cronologia

Un **progetto `.snapmark`** conserva l'immagine originale e ogni annotazione come oggetto, così puoi riaprirlo e modificarlo in seguito. Salva con **Ctrl+Alt+S**; aprilo con un doppio clic sul file o dall'area di notifica → **Apri progetto…**.

> **Attenzione agli oscuramenti.** Poiché il file di progetto conserva l'immagine *originale*, chiunque lo apra può vedere ciò che hai oscurato. Per condividere usa **Copia** o **Salva PNG**, che contengono solo il risultato oscurato. SnapMark ti avvisa prima di salvare un progetto che contiene un oscuramento.

**Cronologia**: ogni Copia/Salva viene registrato automaticamente come progetto modificabile (gli ultimi 50 per impostazione predefinita, solo su questo computer). Aprila dall'area di notifica → **Cronologia** e clicca un elemento per modificarlo di nuovo.

## Impostazioni

Area di notifica → **Impostazioni**.

| Impostazione | Descrizione |
|---|---|
| Tasto rapido di cattura | Predefinito `Stamp`. Clicca **Cambia…** e premi la nuova combinazione (usa Ctrl/Alt/Win per non disturbare la digitazione). |
| Cartella di salvataggio | Destinazione di Ctrl+S. |
| Lingua | Bahasa Indonesia, English, Español, Deutsch, 日本語, 简体中文, Français, Italiano, Português (Brasil), 한국어, Русский, العربية, Nederlands, oppure come Windows. |
| Cronologia | Quanti elementi conservare (0 = disattivata, massimo 500). |
| Avvia con Windows | SnapMark è pronto fin dall'accesso. |
| Colore del suggerimento | Colore del testo con le istruzioni durante la scelta dell'area. |
| Tema | Come Windows, Chiaro, Scuro o Liquid Glass. |
| Aggiornamenti | Controllo e installazione automatici ogni 6 ore, oppure **Controlla ora**. |

Gli aggiornamenti vengono scaricati dalla versione ufficiale, installati senza finestra di installazione, e SnapMark si riapre da solo; impostazioni e cronologia restano. Un aggiornamento aspetta che tu finisca di modificare.

## Privacy

- Catture e progetti **non lasciano mai il tuo computer**.
- Nessuna telemetria. L'unico accesso alla rete è il controllo degli aggiornamenti.

## Risoluzione dei problemi

**Stamp non fa nulla / il tasto rapido non è attivo.** Windows 11 può riservare quel tasto al proprio strumento di cattura. Nelle Impostazioni di SnapMark clicca **Apri le impostazioni della tastiera di Windows** e disattiva l'opzione che fa aprire quello strumento al tasto Stamp (nome e posizione dell'opzione cambiano a seconda della versione di Windows). Oppure scegli un altro tasto rapido.

**L'icona nell'area di notifica non c'è.** Clicca la freccia ^ sulla barra delle applicazioni; trascina fuori l'icona di SnapMark per averla sempre visibile.

**Dove sono i dati.** Impostazioni: `%APPDATA%\app.snapmark.desktop\settings.json`. Cronologia: `%LOCALAPPDATA%\app.snapmark.desktop\history`.
