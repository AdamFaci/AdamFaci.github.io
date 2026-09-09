---
title: "Segmentation automatique d'images en histoire de l'art : nouvelles méthodes et réflexion épistémologique"
authors:
  - "Faci, Adam"
  - "Maronet, Léa"
collection: talks
type: "Invited seminar talk"
permalink: /talks/2026-06-01-vhs-segmentation-histoire-art
venue: "Séminaire international VHS — « Étude de la circulation du savoir scientifique par l'image lors des périodes médiévale et moderne »"
date: 2026-06-02
location: "Paris, France"
---

Invited talk with Léa Maronet.

Computer vision methods are now powerful tools for exploring and analysing large iconographic collections: automatic classification, object recognition and semantic segmentation make it possible to identify recurrent motifs and visual elements across substantial image corpora. While they open new perspectives for the study of stylistic trends, figuration practices and the circulation of images, they run into a persistent limit — they produce descriptions that are often too poor for the requirements of the social sciences and humanities, while more precise approaches remain costly, hard to parameterise and poorly reproducible outside specialised contexts.

We propose an approach combining two reproducible axes, using recent models in zero-shot mode, that is without retraining. Segmentation of visual elements is handled by SAM (Segment Anything Model), adapted to heritage images through an interactive interface that produces annotations in a few clicks. This interactive approach drastically reduces the laborious side of the task while maintaining a high level of precision, making segmentation accessible to researchers who are not image-processing specialists. The identified segments are then described with the vision-language model SigLIP2, instructed to produce categorisations grounded in a taxonomy rather than the generic labels the models propose on their own. This semantic enrichment yields finer, contextualised descriptions that are directly usable for historical and iconographic analysis.

[Read on HAL](https://hal.science/hal-05655872v1)
