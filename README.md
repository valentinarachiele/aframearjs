# aframearjs
Raccolta di snippet di codice relativi ad A-Frame e AR.js. Usati in accoppiata, consentono di creare progetti di realtà aumentata direttamente nel browser.

**Attenzione!** Se si intende copiare e usare i file contenuti in questo repository, è necessario fare molta attenzione ai _path_ relativi alle librerie JavaScript linkate nella <head> del documento e _assets_ vari, **modificandoli se necessario con i propri**.

## Mappa dei file (vd. cartella "files")
- **01** file di partenza, inserimento script e `<a-scene>`
- **02** inserimento della prima _entity_ con _component_ (colore, in questo caso)
- **03** aggiunta di altri _component_ all'_entity_ (posizione, rotazione, dimensioni)
- **04** uso degli _assets_ per impostare e usare una texture
- **04-mix** uso dei _mixin_
- **05** aggiunta di `<a-sky>` e `<a-plane>`
- **05-bis** uso di un preset per creare un _environment_ (libreria https://github.com/feiss/aframe-environment-component/)
- **06** uso di luci (ambientale e punto)
- **07** aggiunta di modello 3D `gltf` negli _assets_ e nella scena
- **07-bis** aggiunta di modello 3D `obj` negli _assets_ e nella scena
- **08** aggiunta del testo
- **09** animazione di un _entity_
- **09-bis** rotazione infinita di una _entity_
- **09-ter** creazione di una `<curved-image>` a 360°
- **09-quater** attribuire diverse animazioni ad una _entity_
- **010** uso del `<a-cursor>` e animazione legata ad interazione (uso del mouse)
- **011** animare un `<a-cursor>` (e quindi dare _feedback_ nell'interazione)
- **012** usare l'_event component_ per creare animazioni più complesse (libreria https://github.com/ngokevin/kframe/tree/master/components/event-set/)
- **012-bis** usare il _component_ raycaster per interagire con _entity_ specifiche
- **013** usare le animazioni proprie degli oggetti 3D importati (libreria https://github.com/donmccurdy/aframe-extras, all'interno della quale si trova https://github.com/donmccurdy/aframe-extras/blob/master/src/loaders/animation-mixer.js)
- **014** usare i suoni
- **015** combinare suoni e animazioni
- **015-bis** combinare suoni e interazione
- **016** usare oggetti 3D `ply` ottenuti con MagicaVoxel (https://ephtracy.github.io/), usando la libreria https://github.com/donmccurdy/aframe-extras e lo script https://github.com/donmccurdy/aframe-extras/blob/master/src/loaders/ply-model.js
---
- **ar01** aggiunta dello script https://github.com/jeromeetienne/AR.js e uso del marker Hiro per mostrare una `<a-box>`
- **ar02** uso del marker Hiro per mostrare un modello 3D `ply`
- **ar03** uso di un marker _custom_
- **ar04** uso di _multiple marker_ (hiro, kanji, barcode)
