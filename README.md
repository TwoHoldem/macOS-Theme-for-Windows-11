# macOS-Theme-for-Windows-11
## Introduzione
Questo è un tutorial su come personalizzare Windows 11 in stile macOS!

Un semplice modo per sentirsi in casa macOS ma usando Windows. Pretty simple right?

Sample:
<img src="https://i.imgur.com/ZDP2Zd2.jpeg">

Consiglio personale: scaricate tutti i file necessari per personalizzare Windows in una cartella, giusto per avere ordine

(tutti i file sono disponibili nella repo)
#
## Disclaimer
Potrebbe distruggere la vostra install di Windows, quindi prima di operare assicuratevi di creare un punto di ripristino (verrà spiegato dopo come fare)
#
## Come funziona
Ho usato ThemeTool per patchare il tema scaricato su Deviant Art, usato 7TSP GUI per patchare le icone del sistema, StartAllBack per rimpicciolire la barra di Windows e impostare l'explorer nello stile di Windows 7, LeftSider per spostare i tasti di Windows da destra a sinistra, installato il cursore di macOS, le sue icone che stanno della dock, e infine MyDock che sostituisce la barra di Windows in una dock in puro stile macOS.
#
## 1) Creazione del punto di ripristino

Premete il tasto Windows e scrivete "Crea un punto di ripristino". Vi si aprirà questa schermata:

<img src="https://i.imgur.com/R9jqrgh.png">

Selezionate il disco di Windows [C:] e cliccate su "Configura",

<img src="https://i.imgur.com/3xErEO4.png">

Attivate la protezione del sistema (vi consiglio di mettere uno spazio di 10GB) e cliccate su OK. Nella finestra principale cliccate su "Crea", gli date un nome a vostro piacimento e infine cliccate "Crea".
#
## 2) Patching del tema
Aprite questo link se il tema di macOS in lightmode per Windows: https://www.deviantart.com/niivu/art/LIT3-for-Windows-888372946

Aprite questo link se il tema di macOS in darkmode per Windows: https://www.deviantart.com/niivu/art/BIB3-for-Windows-886441919

(per scaricare il tema dovete loggarvi su Deviant Art)

Il tema che avete scaricato lo dovete estrarre, entrate in "Windows 10+11 Themes" e copiate in "C:\Windows\Resources\Themes" SOLO questi file:

nel caso della lightmode:

<img src="https://i.imgur.com/OhHlbeF.png">

nel caso della darkmode:

<img src="https://i.imgur.com/4rLMaiw.png">

Scaricate [ThemeTool](https://github.com/TwoHoldem/macOS-Theme-for-Windows-11/raw/main/ThemeTool.zip) e spostatelo nel disco di Windows [C:]. Fate tasto destro su di esso ed eseguitelo come amministratore. Accettate la licenza e vi ritroverete con questo:

<img src="https://i.imgur.com/Md22Pfc.png">

Nella sezione "Installation", attivate "Hook SystemSettings" e "Hook LogonUI", infine cliccate "Install" (vi chiederà di riavviare dopo l'installazione).

Dopo il riavvio riaprite ThemeTool (sempre come amministratore) e nel riquadro a sinistra vi ritroverete tutti i temi installati su Windows, cliccate su:

- "LIT3 MAC" se volete la lightmode
- "BIB3DM MAC" se volete la darkmode

e poi sul tasto "Patch". Una volta patchato il tema cliccate su "Apply" per impostarlo.
#
## 3) Patching delle icone
Scaricate lo [zip](https://github.com/TwoHoldem/macOS-Theme-for-Windows-11/raw/main/7TSP%20Icon%20Theme.zip) contenente il tool 7TSP GUI e le icone e unzippatelo. Avviate 7TSP GUI e vi ritroverete questo:

<img src="https://i.imgur.com/WP6NNmx.png">

Cliccate su "Add a Custom Pack", andate nella cartella che avete scaricato con il tool e le icone da patchare, poi selezionate il file .7z:

- "7tsp Big Sur LightMode" se volete la lightmode
- "7tsp Big Sur DarkMode" se volete la darkmode

e poi sul tasto "Start Patching". Vi chiederà se può creare un punto di ripristino (nel caso vada male qualcosa), cliccate "Si", e lui inizierà a patchare le icone su tutto il sistema.

NOTA: l'explorer viene chiuso durante il patching, non andate in panico ;)

Dopo aver patchato le icone riavviate per confermare i cambiamenti. Dopo il riavvio vi dirà che avete patchato con successo!
#
## 4) Installazione di StartAllBack
Scaricate [StartAllBack](https://github.com/TwoHoldem/macOS-Theme-for-Windows-11/raw/main/StartAllBack.zip) e fate doppio click su di esso per installarlo. Una volta installato fate tasto destro in uno spazio vuoto della barra di Windows e cliccate "Proprietà".

- Sezione "Benvenuto"

Cliccate su "Vero 11"

<img src="https://i.imgur.com/2v0eIgv.png">

- Sezione "Barra Applicazioni"

Modificate la dimensione delle icone su "Small (S)".

<img src="https://i.imgur.com/OnnYUSe.png">

- Sezione "Esplora File"

Lo stile dell'Explorer deve essere quello di Windows 7, quindi selezionate "Barra comandi di Win7". Tra tutte le opzioni disponibili, attivate SOLO "Restore Control Panel applets".

<img src="https://i.imgur.com/Skxrcke.png">

- Sezione "Avanzate"

Attivare l'opzione "Usa colori personalizzati nel menu Avvio" e portare lo slider in fondo a sinistra.

Attivate anche "Memorizza e mostra programmi recenti" e "Memorizza e mostra dati recenti".

<img src="https://i.imgur.com/s3vqPbS.png">

Infine, fate tasto destro in uno spazio vuoto della barra di Windows e cliccate "Sblocca la barra delle applicazioni". Trascinate la barra di Windows in alto.
#
## 5) Installazione di Leftsider
Scaricate lo [zip](https://github.com/TwoHoldem/macOS-Theme-for-Windows-11/raw/main/Leftsider.zip) contenente i file di Leftsider. Copiate la sua cartella nel disco di Windows [C:] e fate: tasto destro su "leftsider.exe" -> Mostra altre opzioni -> Invia a -> Desktop (crea collegamento).

Tagliate il collegamento appena creato sul desktop e fate: CTRL + R -> shell:startup -> incollate il collegamento.

Una volta fatto ciò potete fare doppio click su di esso per avviarlo. Le finestre avranno i tasti a sinistra.

<img src="https://i.imgur.com/f2yQhoT.png">

NOTA: Se nei settings di StartAllBack sta impostato lo stile dell'explorer su "Windows 11", i tasti delle finestre si compenetreranno nel nome della finestra, quindi impostate lo stile su "Windows 7".
#
## 6) Installazione del cursore di macOS
Scaricate lo [zip](https://github.com/TwoHoldem/macOS-Theme-for-Windows-11/raw/main/Cursors.zip) contenente i file del cursore. Aprite la cartella con i file estratti e fate: tasto destro sul file rinominato "Install" -> Mostra altre opzioni -> Installa.

Aprite le impostazioni, nella sezione "Bluetooth e dispositivi" cliccate "Mouse", poi su "Impostazioni aggiuntive per il mouse" e vi si aprirà questa finestra:

<img src="https://i.imgur.com/uptElhD.png">

Andate nella sezione "Puntatori", cliccate il menu a tendina "Combinazione" e cliccate su "Big Sur", infine su OK.
#
## 7) Copia delle icone della Dock
Scaricate lo [zip](https://github.com/TwoHoldem/macOS-Theme-for-Windows-11/raw/main/Icons.zip) contenente le icone della Dock che installeremo tra poco. Copiate la cartella con i file estratti nel disco di Windows [C:].
#
## 8) Installazione di MyDock
Scaricate lo [zip](https://mega.nz/file/PMNGiZJT#8pZUpx25dzqyVKmm_cxIrd9chDSp0Z3J3QcJFBIXgFw) contenente i file di MyDock. Copiate la cartella con i file estratti nel disco di Windows [C:] ed aprite il file "MyDock.exe".

Adesso dobbiamo customizzare un po' la dock.

I settings riportati in basso sono quelli che sto utilizzando io, ovviamente ve la potete personalizzare a vostro piacimento

- Global Settings

<img src="https://i.imgur.com/Zr8XdcI.png">

<img src="https://i.imgur.com/71nffBZ.png">

- General

<img src="https://i.imgur.com/htNgqwr.png">

<img src="https://i.imgur.com/ukPPO95.png">

- Advanced

<img src="https://i.imgur.com/RVRapUy.png">

<img src="https://i.imgur.com/gSa5LVI.png">

<img src="https://i.imgur.com/T4b3998.png">

- Minimize window

<img src="https://i.imgur.com/dLC2Zno.png">

<img src="https://i.imgur.com/YLGZf64.png">

- Window preview

<img src="https://i.imgur.com/kGMpAFW.png">

- General

<img src="https://i.imgur.com/qs3gqlP.png">

- Time

<img src="https://i.imgur.com/SfqGhws.png">

- Audio

<img src="https://i.imgur.com/NjbEnof.png">

- Display

<img src="https://i.imgur.com/FEAClAs.png">

- Network

<img src="https://i.imgur.com/XnQOvai.png">

- Monitor

<img src="https://i.imgur.com/DfVONUv.png">

<img src="https://i.imgur.com/JglFA9N.png">

- Battery

<img src="https://i.imgur.com/wruYas5.png">

- Wallpaper

<img src="https://i.imgur.com/wyGyfpD.png">

#
Hai installato il tema di macOS su Windows 11 con successo!
