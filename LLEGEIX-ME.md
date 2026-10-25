# On t'has ficat aquesta nit? · el joc

Joc de ritme amb la cançó de La Ludwig Band, en un barri de blocs isomètrics. Sis fases, una per músic, i concert final amb tot el públic.

## Què hi ha al repositori

| Fitxer | Què és |
|---|---|
| `index.html` | El joc (lògica, mapa de girs, temps de la lletra) |
| `mon_0.bin` … `mon_3.bin` | El barri dibuixat (4 paquets d'uns 2,7 MB; es descarreguen a mesura que cal) |
| `sprites.webp` | Els sis músics, el públic i els ninots |
| `canco.mp3` | La cançó (MP3 de 192 kbps, 4,8 MB) |
| `lletra.txt` | La lletra, un vers per línia. El joc la llegeix sola (no cal tocar-la) |

**Important:** els cinc fitxers nous (`index.html`, `mon_0.bin`, `mon_1.bin`, `mon_2.bin`, `mon_3.bin` i `sprites.webp`) s'han de pujar junts. L'`index.html` sol no funciona.

## Actualitzar-lo

A GitHub: **Add file → Upload files**, arrossega-hi els fitxers de la carpeta (en una sola tirada: són només 7) i **Commit changes**. Substitueixen els anteriors. `canco.mp3` i `lletra.txt` es queden com estan (si ja hi són, no cal tornar-los a pujar).

En un o dos minuts ja és a `https://fobdbat.github.io/On-thas-ficat-aquesta-nit/`. Al mòbil, si encara veus la versió antiga, recarrega la pàgina.

## Com es juga

- Toca la pantalla (o prem l'espai) quan el corredor arriba a l'anell blanc de cada gir.
- A la fase del **Lluc** (palmes) no es gira: es toca **al ritme de les palmes** perquè salti les palanganes. Les palanganes estan separades segons el ritme real de les palmes (curtes, mitjanes i llargues), així es veu què ve.
- Cada fase la fa un músic: Quim, Gabriel, Andreu, Lluc, Pau i Roger. Entre fase i fase el següent surt del costat i agafa el relleu.
- Si falles («Massa d'hora» o «Massa tard») tornes a començar la fase on eres, no tota la cançó.
- Hi ha **Mode passeig** (sense errors, sense marcador) per mirar el barri i la cançó.

## Què es veu pel camí

El barri s'ha dibuixat amb blocs: l'estació de la Sagrera, la Rambla amb la pluja, el monument a Colom (a la riba del port, amb cartell «COLOM» il·luminat), el vident, les havaneres, la sardana, l'estadi, la tangana, el port… Els rètols només porten noms de llocs. Els versos de la lletra surten en cartells a la part baixa de la pantalla (lluny del corredor i dels girs que venen) just abans que sonin, i a sota de tot surt el vers que sona (es pot treure a la pausa amb «Lletra a sota»).

Cada músic porta els seus detalls: la perilla i el cabell llarg del Pau, les arracades del Lluc, els rínxols de l'Andreu, el tupè del Quim amb les ulleres…

## Pausa

El botó de dalt a la dreta fa pausa. Esc o P també, i el joc s'atura sol si canvies d'aplicació al mòbil. En continuar, la cançó torna dos segons enrere i els tocs d'aquest tros no compten.

## Marcador final

Quan el Roger arriba a l'escenari surt el públic ballant i el marcador:

- **Cops perfectes:** tocs a menys de 60 ms del cop.
- **Desviació total:** suma en mil·lisegons de la distància de cada toc al seu cop, en valor absolut.
- **Intents:** les vegades que s'ha començat aquella partida.

Guanya qui suma menys mil·lisegons.

## Sincronia del so (mòbil i Bluetooth)

Cada aparell té un retard d'àudio diferent (els auriculars Bluetooth poden arribar a 150–250 ms). Si els girs et semblen avançats o endarrerits: **Calibra tocant** a la pantalla d'inici, amb els auriculars o l'altaveu amb què jugaràs. Queda desat en aquell aparell.

## Rendiment

El joc dibuixa a doble resolució (retina) i, si el mòbil va just, baixa la resolució sol. El paquet 0 (2,7 MB) basta per començar; la resta es baixa jugant.

## Comptador de visites

L'`index.html` porta la línia de GoatCounter del teu compte (`fobdbat.goatcounter.com`) abans de `</body>`.

## Versió anterior

La versió vectorial anterior (ninots plans) queda a l'historial de GitHub; si vols tornar-hi, restaura aquell `index.html`.
