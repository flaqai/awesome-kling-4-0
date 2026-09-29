<div align="center">

# Awesome Kling 4.0 Prompts — Deutscher Leitfaden

52 eigenständige, produktionsnahe KI-Videoprompts für Film, Werbung, UGC, Dialog, VFX, Animation, Essen, Reisen, Bildung und Social Media.

[English](README.md) · [简体中文](README.zh-CN.md) · **Deutsch** · [15 Sprachen](docs/LANGUAGES.md)

[Prompt-Katalog](prompts/README.md) · [Vollständige Methode](docs/PROMPT-GUIDE.md) · [Mehrsprachiges Audio](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **Modellstatus — 29.09.2026:** Kling 4.0 Flash ist seit dem 28. September für Ultra-Jahresabonnenten vorab zugänglich. Laut der [offiziellen Ankündigung von Kling AI](https://sg.linkedin.com/company/kling-ai-api) sind das vollständige Kling 4.0 und der API-Zugang für Oktober 2026 geplant; ein genauer Tag wurde nicht genannt. Die angekündigten **bis zu 30 Sekunden pro Generierung** gelten für das vollständige Modell und sind für Flash noch nicht als verfügbar bestätigt. Die vorhandenen Prompts dauern 5–15 Sekunden.

## Kling 4.0: Neuerungen und Verfügbarkeit

Laut der [offiziellen Ankündigung von Kling AI auf X](https://x.com/Kling_ai/status/2104596718067257458) ist Flash für Ultra-Jahresabonnenten vorab verfügbar; das vollständige 4.0-Modell und die API sind für Oktober 2026 geplant. Für das vollständige Modell wurden bis zu 30 Sekunden pro Generierung, 10 Keyframes, 15 multimodale Referenzen, bis zu 4K/10-bit HDR, Stereo-Audio sowie mehr Sprachen und Akzente angekündigt. **Diese Werte sind keine bestätigten Flash-Grenzen.** Die vorhandenen 52 Prompts verwenden 5–15 Sekunden lange Abläufe. Die FLAQ.AI-Seiten für 4.0 [Text-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) und [Image-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) tragen noch „Coming Soon“ und sind keine aktive 4.0-API.

## Videos und Prompts auf X

**Geprüft am 29.09.2026.** Das [offizielle Einführungsvideo](https://x.com/Kling_ai/status/2104596718067257458) ist ein Werbeschnitt zur 4.0-Familie; seine Gesamtlänge belegt keine entsprechende Flash-Einzelgenerierung. Die folgenden Beiträge sind von ihren Urhebern beschriebene Tests, weder offizielle Benchmarks noch unabhängig durch dieses Projekt reproduziert. Videos und vollständige Originalprompts bleiben bei den Originalposts.

| Originalpost | Praktischer Prompt-Ansatz |
|---|---|
| [Umesh: 20-Sekunden-Katzenverfolgung](https://x.com/umesh_ai/status/2104595267794460949) · [Originalprompt](https://x.com/umesh_ai/status/2104595270671724936) | Ein Motiv, eine zusammenhängende Route und ein physisches Ereignis pro Ort; die Kamera folgt ohne Schnitt. |
| [OscarAI: 20-Sekunden-Animekonzert samt Prompt](https://x.com/Artedeingenio/status/2104829034299351079) | Der Autor bevorzugt in ersten Tests kurze, direkte Anweisungen, meldet aber keine perfekte Befolgung. Erst Motiv → Veränderung → Kamera → Ende testen. |
| [とすくん: 15-Sekunden-Wetterwechsel](https://x.com/tokyo_Valentine/status/2104810060811833710) · [Originalprompt](https://x.com/tokyo_Valentine/status/2104810064750239987) | Das Charakterblatt nur für Identität und Kleidung nutzen; Wetter-, Licht- und Spielwechsel getrennt terminieren. |
| [Alexandra Dekimpe: Produktionstests](https://x.com/HadesDesign/status/2104878440889417957) | Beobachtbare Mikrogesten statt abstrakter Emotionen; Kausalität mit „erst danach“ festlegen; exakten Dialog oder Stille verlangen. Persönliche Beobachtungen. |
| [Aswin Aji Raj: 20-Sekunden-UGC auf Hindi](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | Kein vollständiger Prompt veröffentlicht. Sprecher und genauen Wortlaut festlegen; Aussprache, Lippenbewegung und Produktbehauptungen prüfen. |
| [@plasm0: 3.0/Flash mit gleichem Prompt](https://x.com/plasm0/status/2104597949485629557) | Prompt und Referenzen für einen A/B-Test konstant halten und Einstellungen notieren. Ein Clip-Paar ist kein belastbarer Benchmark. |

**Eigene, noch nicht getestete 15-Sekunden-Übung im Hochformat** (außerhalb der 52 Katalogrezepte; keine X-Texte übernommen):

~~~text
[MOTIV/REFERENZ] Eine einzige markenlose, aufladbare Fahrradlampe mit mattem graphitfarbenem Gehäuse und genau einem bernsteinfarbenen Schalter. Ein mögliches Referenzbild fixiert nur ihre Form.
[SZENE/KAMERA] Ruhige Fahrradwerkstatt in der Dämmerung. Eine durchgehende Nahaufnahme folgt von den Händen der Mechanikerin zur Lampe und zum Lenker. Natürliches Fensterlicht; kein Schnitt oder Teleport.
[0–4 s] Sie legt die ausgeschaltete Lampe neben den Lenker; beide Hände und die Halterung bleiben sichtbar.
[4–8 s] Sie rastet die Lampe ein. Erst nachdem ein deutliches Klickgeräusch die Befestigung bestätigt, drückt ihr Daumen den bernsteinfarbenen Schalter.
[8–12 s] Die Lampe leuchtet genau einmal auf und beleuchtet Vorderrad und einen kleinen Bodenbereich. Die Kamera gleitet seitlich und zeigt den Lichtkegel.
[12–15 s] Sie lässt den Lenker los; die Lampe bleibt fest. Ruhiges Schlussbild halten.
[TON/VORGABEN] Werkstattatmosphäre, ein Einrast- und ein Schalterklick; keine Sprache oder Musik. Form, Anzahl der Hände, Befestigung und Lichtrichtung bewahren. Keine Marke, zusätzliche Lampe oder unbegründete Schnittstelle.
~~~

Sowohl kurze als auch längere, klar strukturierte Briefings testen. Modus, Dauer, Referenzen und Ergebnis dokumentieren, bevor ein Rezept „getestet“ heißt. Eigene Beiträge sind über den [Beitragsleitfaden](CONTRIBUTING.md) willkommen.

## Kurzstruktur

```text
[AUSGABE] Dauer, Seitenverhältnis, One-Take/Mehrfachaufnahme, Look
[KONTINUITÄT] feste Merkmale von Person, Kleidung, Produkt und Requisiten
[RAUM] Ort, Zeit, Licht und Startpositionen
[ZEITLICHE SHOTS] eine Hauptaktion + eine Kameraabsicht pro Abschnitt
[SPIEL UND PHYSIK] Blick, Atmung, Kontakt, Gewicht und Trägheit
[AUDIO] Sprecher, Sprache, Ton, Atmosphäre, Geräusche und Musik
[EINSCHRÄNKUNGEN] Identität, Richtung, Licht, Text, Logos und Verformung
```

Deutsch ist eine Dokumentationssprache dieses Projekts, gehört aber nicht zur bestätigten Liste nativer Kling-3.0-Dialogsprachen. Deutsche Sprache bitte im Live-Modell testen oder nachträglich mit geprüfter Sprachaufnahme ergänzen.

## Empfehlungen

- [Mehrsprachiges Wiedersehen](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [Botanischer Produktfilm](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [Vier-Jahreszeiten-Modefilm](prompts/style-and-performance.md#2-four-seasons-one-coat)
- [Nahtlose Regenschirm-Schleife](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)

## Über FLAQ.AI

> Stand 29.09.2026 sind die FLAQ.AI-Seiten für 4.0 [Text-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) und [Image-to-Video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) mit „Coming Soon“ markiert. Der frühe Flash-Zugang bei Kling bedeutet nicht, dass die 4.0-API bei FLAQ.AI verfügbar ist.

[FLAQ.AI](https://flaq.ai/) ist eine Webplattform und ein einheitlicher API-Layer für Bild-, Video- und Sprachmodelle. Aktuell gibt es Seiten für [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) und [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/). Dieses Projekt behauptet keine Kling-4.0-Verfügbarkeit. Live-Einstellungen, Preise und API-Spezifikationen vor Produktion prüfen.
