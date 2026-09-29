<div align="center">

# Awesome Kling 4.0 Prompts — Guida italiana

52 prompt video originali e orientati alla produzione per cinema, pubblicità, UGC, dialogo, VFX, animazione, cibo, viaggi, istruzione e social media.

[English](README.md) · [Español](README.es-ES.md) · **Italiano** · [15 lingue](docs/LANGUAGES.md)

[Catalogo](prompts/README.md) · [Metodo completo](docs/PROMPT-GUIDE.md) · [Audio multilingue](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **Stato del modello — 29/09/2026:** Kling 4.0 Flash è disponibile in accesso anticipato dal 28 settembre per gli abbonati Ultra annuali. Secondo l’[annuncio ufficiale di Kling AI](https://sg.linkedin.com/company/kling-ai-api), la versione completa di Kling 4.0 e l’accesso API sono previsti per ottobre 2026, senza una data precisa. La generazione nativa fino a **30 secondi** è annunciata per il modello completo; questo limite non è ancora verificato per Flash. I prompt attuali durano 5–15 secondi.

## Kling 4.0: novità e disponibilità

Secondo l’[annuncio ufficiale di Kling AI su X](https://x.com/Kling_ai/status/2104596718067257458), Flash è in accesso anticipato per gli abbonati Ultra annuali; il modello 4.0 completo e l’API sono previsti per ottobre 2026. Per la versione completa sono stati annunciati fino a 30 secondi per generazione, 10 fotogrammi chiave, 15 riferimenti multimodali, output fino a 4K/10-bit HDR, audio stereo e più lingue e accenti. **Questi valori non sono limiti verificati per Flash.** I 52 prompt esistenti usano sequenze di 5–15 secondi. Le pagine FLAQ.AI per 4.0 [Text-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) e [Image-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) riportano ancora “Coming Soon”: non sono un’API 4.0 attiva.

## Video e prompt condivisi su X

**Verificati il 29/09/2026.** Il [video ufficiale di lancio](https://x.com/Kling_ai/status/2104596718067257458) è un montaggio della famiglia 4.0; la durata totale non prova che Flash possa generare una clip altrettanto lunga in un’unica operazione. I casi seguenti sono test descritti dagli autori, non benchmark ufficiali né riproduzioni indipendenti di questo progetto. Video e prompt completi restano nei post originali; qui non vengono copiati.

| Post originale | Spunto per il prompt |
|---|---|
| [Umesh: inseguimento notturno di un gatto, 20 s](https://x.com/umesh_ai/status/2104595267794460949) · [prompt originale](https://x.com/umesh_ai/status/2104595270671724936) | Un solo protagonista, percorso continuo e un evento fisico per luogo; la camera segue senza tagli. |
| [OscarAI: concerto anime, 20 s, con prompt](https://x.com/Artedeingenio/status/2104829034299351079) | Nei primi test l’autore preferisce indicazioni brevi e dirette, pur segnalando che il modello non le segue alla lettera. Provare soggetto → cambiamento → camera → finale. |
| [とすくん: cambio del tempo, 15 s](https://x.com/tokyo_Valentine/status/2104810060811833710) · [prompt originale](https://x.com/tokyo_Valentine/status/2104810064750239987) | Limitare la scheda del personaggio a identità e abiti; indicare a parte quando cambiano meteo, luce e recitazione. |
| [Alexandra Dekimpe: test di produzione](https://x.com/HadesDesign/status/2104878440889417957) | Descrivere microazioni visibili invece di emozioni astratte; fissare la causalità con “solo dopo”; fornire battute esatte o richiedere silenzio. Sono osservazioni dell’autrice. |
| [Aswin Aji Raj: UGC in hindi, 20 s](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | Il prompt integrale non è pubblicato. Specificare parlante e frase esatta; controllare pronuncia, sincronia labiale e affermazioni sul prodotto. |
| [@plasm0: confronto 3.0/Flash con lo stesso prompt](https://x.com/plasm0/status/2104597949485629557) | Mantenere uguali prompt e riferimenti per un test A/B e annotare le impostazioni. Una coppia di clip non è un benchmark formale. |

**Esercizio verticale originale di 15 s, non ancora testato** (non fa parte delle 52 ricette; non copia testi da X):

~~~text
[SOGGETTO/RIFERIMENTO] Una sola luce ricaricabile per bicicletta, senza marchio, corpo grafite opaco e un unico interruttore color ambra. Un’eventuale immagine fissa soltanto la forma della luce.
[SCENA/CAMERA] Officina di biciclette tranquilla al tramonto. Un piano ravvicinato continuo segue le mani della meccanica, la luce e poi il manubrio. Luce naturale dalla finestra; niente tagli o teletrasporti.
[0–4 s] Appoggia la luce spenta accanto al manubrio; mostra entrambe le mani e il supporto.
[4–8 s] Fissa la luce nel supporto. Solo dopo il clic di aggancio il pollice preme l’interruttore ambra.
[8–12 s] La luce si accende una volta sola, illuminando la ruota anteriore e una piccola zona del pavimento. La camera scorre lateralmente per mostrare il fascio.
[12–15 s] Lascia il manubrio; la luce resta salda. Mantieni un’inquadratura finale stabile.
[AUDIO/VINCOLI] Ambiente dell’officina, un clic dell’aggancio e uno dell’interruttore; niente voce né musica. Preserva forma, numero di mani, posizione e direzione della luce. Niente marchi, luci extra o tagli immotivati.
~~~

Provare sia brief brevi sia brief più lunghi ma ben strutturati. Registrare modalità, durata, riferimenti e risultato prima di definire una ricetta “testata”. I contributi originali sono benvenuti tramite la [guida](CONTRIBUTING.md).

## Struttura rapida

```text
[OUTPUT] durata, formato, piano sequenza/multishot, resa visiva
[CONTINUITÀ] caratteristiche fisse di persona, abiti, prodotto e oggetti
[SPAZIO] luogo, orario, luce e posizioni iniziali
[SHOT TEMPORIZZATI] un’azione principale + un intento camera per segmento
[RECITAZIONE E FISICA] sguardo, respiro, contatto, peso e inerzia
[AUDIO] parlante, lingua, tono, ambiente, foley e musica
[VINCOLI] identità, direzione, luce, testo, loghi e deformazioni
```

L’italiano è una lingua di documentazione del progetto, ma non compare nell’elenco verificato delle lingue di dialogo nativo di Kling 3.0. Testare la voce nel modello attivo oppure aggiungere una traccia controllata in post-produzione.

## In evidenza

- [Riunione multilingue](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [Spot di bevanda botanica](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [Film di moda in quattro stagioni](prompts/style-and-performance.md#2-four-seasons-one-coat)
- [Loop comico dell’ombrello](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)

## Informazioni su FLAQ.AI

> Al 29/09/2026, le pagine FLAQ.AI 4.0 per [Text-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) e [Image-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) indicano “Coming Soon”. L’accesso anticipato a Flash su Kling non implica che l’API 4.0 di FLAQ.AI sia già aperta.

[FLAQ.AI](https://flaq.ai/) è una piattaforma web e un livello API unificato per modelli di immagini, video e linguaggio. Attualmente offre pagine per [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) e [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/). Il progetto non dichiara che Kling 4.0 sia disponibile. Verificare impostazioni, prezzi e API live prima della produzione.
