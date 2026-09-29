<div align="center">

# Awesome Kling 4.0 Prompts — Guide français

52 prompts vidéo originaux pour le cinéma, la publicité, l’UGC, le dialogue, les VFX, l’animation, la cuisine, le voyage, l’éducation et les réseaux sociaux.

[English](README.md) · [简体中文](README.zh-CN.md) · [Español](README.es-ES.md) · **Français** · [15 langues](docs/LANGUAGES.md)

[Catalogue](prompts/README.md) · [Méthode complète](docs/PROMPT-GUIDE.md) · [Audio multilingue](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **État du modèle — 29/09/2026 :** Kling 4.0 Flash est accessible en avant-première depuis le 28 septembre aux abonnés Ultra annuels. Selon l’[annonce officielle de Kling AI](https://sg.linkedin.com/company/kling-ai-api), la version complète de Kling 4.0 et l’accès API sont prévus pour octobre 2026, sans date précise. La génération native jusqu’à **30 secondes** est annoncée pour la version complète ; cette durée n’est pas une limite vérifiée pour Flash. Les prompts actuels durent 5 à 15 secondes.

## Kling 4.0 : nouveautés et disponibilité

Selon [l’annonce officielle de Kling AI sur X](https://x.com/Kling_ai/status/2104596718067257458), Flash est en accès anticipé pour les abonnés Ultra annuels ; la version complète 4.0 et l’API sont prévues pour octobre 2026. La version complète annonce jusqu’à 30 secondes par génération, 10 images clés, 15 références multimodales, une sortie jusqu’en 4K/10-bit HDR, un son stéréo et davantage de langues et d’accents. **Ces chiffres ne sont pas des limites Flash vérifiées.** Les 52 prompts existants restent conçus pour 5 à 15 secondes. Sur FLAQ.AI, les pages 4.0 [texte-vers-vidéo](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) et [image-vers-vidéo](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) portent encore la mention « Coming Soon » : il ne s’agit pas d’une API 4.0 active.

## Vidéos et prompts partagés sur X

**Vérifié le 29/09/2026.** La [vidéo officielle](https://x.com/Kling_ai/status/2104596718067257458) est un montage promotionnel de la famille 4.0 ; sa durée totale ne prouve pas qu’un seul rendu Flash puisse être aussi long. Les exemples ci-dessous sont des essais déclarés par leurs auteurs, ni des benchmarks officiels ni des reproductions indépendantes du projet. Regardez les vidéos et les prompts complets dans les publications d’origine ; nous ne les recopions pas.

| Publication originale | Piste de travail |
|---|---|
| [Umesh : poursuite nocturne d’un chat, 20 s](https://x.com/umesh_ai/status/2104595267794460949) · [prompt d’origine](https://x.com/umesh_ai/status/2104595270671724936) | Garder un seul sujet, un trajet continu et une action physique par lieu ; la caméra suit sans coupe. |
| [OscarAI : concert animé, 20 s et prompt](https://x.com/Artedeingenio/status/2104829034299351079) | L’auteur préfère, dans ses premiers essais, des consignes courtes et directes, tout en signalant une fidélité imparfaite. Tester sujet → changement → caméra → fin. |
| [とすくん : changement de météo, 15 s](https://x.com/tokyo_Valentine/status/2104810060811833710) · [prompt d’origine](https://x.com/tokyo_Valentine/status/2104810064750239987) | Limiter la fiche personnage à l’identité et à la tenue ; dater séparément les changements de météo, de lumière et de jeu. |
| [Alexandra Dekimpe : essais de production](https://x.com/HadesDesign/status/2104878440889417957) | Décrire des microgestes observables plutôt qu’une émotion abstraite ; écrire « seulement après » pour la causalité ; fournir le dialogue exact ou demander le silence. Ce sont ses observations. |
| [Aswin Aji Raj : UGC en hindi, 20 s](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | Le prompt complet n’est pas publié. Préciser locuteur et phrase exacte ; contrôler prononciation, synchronisation labiale et allégations produit. |
| [@plasm0 : comparaison 3.0/Flash à prompt identique](https://x.com/plasm0/status/2104597949485629557) | Garder prompt et références identiques pour un test A/B, noter les réglages ; une seule paire ne constitue pas une évaluation formelle. |

**Exercice vertical original de 15 s, non testé** (en dehors des 52 recettes ; aucun texte de X n’est recopié) :

~~~text
[SUJET/RÉFÉRENCE] Une seule lampe rechargeable de vélo, sans marque, boîtier graphite mat et un unique interrupteur ambré. Une image éventuelle ne fixe que sa forme.
[SCÈNE/CAMÉRA] Atelier de vélo calme au crépuscule. Plan rapproché continu des mains de la mécanicienne vers la lampe puis le guidon. Lumière naturelle de fenêtre ; aucune coupe ni téléportation.
[0–4 s] Elle pose la lampe éteinte près du guidon ; montrer ses deux mains et la fixation.
[4–8 s] Elle clipse la lampe. Ce n’est qu’après le clic confirmant la fixation que son pouce appuie sur l’interrupteur ambré.
[8–12 s] La lampe s’allume une seule fois et éclaire la roue avant et une petite zone du sol. La caméra glisse latéralement pour révéler le faisceau.
[12–15 s] Elle lâche le guidon ; la lampe reste fixée. Tenir un cadre final stable.
[SON/CONTRAINTES] Ambiance d’atelier, un clic de fixation et un clic d’interrupteur ; ni dialogue ni musique. Conserver forme, nombre de mains, position et direction lumineuse. Pas de marque, de lampe supplémentaire ou de coupe injustifiée.
~~~

Tester aussi bien un brief court qu’un brief plus long mais structuré. Noter mode, durée, références et résultat avant de qualifier une recette de « testée ». Les créations originales peuvent être soumises via le [guide de contribution](CONTRIBUTING.md).

## Structure rapide

```text
[SORTIE] durée, format, plan-séquence/multiplan, rendu
[CONTINUITÉ] personnage, costume, produit et accessoires invariants
[ESPACE] lieu, heure, lumière et positions initiales
[PLANS CHRONOMÉTRÉS] une action principale + une intention caméra par segment
[JEU ET PHYSIQUE] regard, respiration, contact, poids et inertie
[AUDIO] locuteur, langue, ton, ambiance, bruitage et musique
[CONTRAINTES] identité, direction, lumière, texte, logos et déformations
```

Le français est une langue de documentation de ce projet, mais ne figure pas dans la liste vérifiée des langues de dialogue natif de Kling 3.0. Pour une voix française, testez le modèle en direct ou ajoutez une voix contrôlée en postproduction.

## Sélection

- [Retrouvailles multilingues](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [Publicité de boisson botanique](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [Poursuite de science-fantasy](prompts/action-and-vfx.md#1-the-glass-manta-pursuit)
- [Boucle comique du parapluie](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)

## À propos de FLAQ.AI

> Au 29/09/2026, les pages FLAQ.AI 4.0 [texte-vers-vidéo](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) et [image-vers-vidéo](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) affichent « Coming Soon ». L’accès anticipé à Flash chez Kling ne signifie pas que l’API 4.0 de FLAQ.AI est ouverte.

[FLAQ.AI](https://flaq.ai/) est une plateforme web et une couche API unifiée pour les modèles d’image, de vidéo et de langage. Elle propose actuellement des pages [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) et [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/). Ce dépôt n’affirme pas que Kling 4.0 y est disponible. Vérifiez les paramètres et tarifs en direct avant toute production.

Tous les prompts et visuels locaux ont été créés pour ce projet. Vérifiez les droits liés aux personnes, voix, marques, musiques et lieux.
