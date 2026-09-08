---
title: "SegmentArt"
excerpt: "A SAM2-based tool for fast image annotation in art history, developed with Léa Maronet. Version 4 demonstrated publicly."
collection: portfolio
permalink: /projects/segmentart/
---

**SegmentArt** is an annotation aid built on SAM2, developed with Léa Maronet: the model proposes masks, the researcher keeps every interpretive decision, and the cost of annotating an image drops far enough to make large art-historical corpora workable.

The motivation is a methodological contradiction rather than a throughput problem. An expert description — *a winged elephant in right profile, trunk raised, in procession around a lotus* — is slow, dense, contextual and interpretive. A computational annotation reading *elephant* is fast, standardised, decontextualised and reductive. Hours of invisible labour, spent on ambiguous boundaries and nested objects, produce a single word and erase the complexity that motivated the study. SegmentArt is an attempt to lower that cost without accepting the reduction as final.

Assisted image annotation combines manual prompts (box, positive and negative points) with automatic segmentation by SAM 2, followed by semantic grouping and structured, Visual Genome style description. It is designed to reduce the time and number of interactions required for dense annotation, with fine-grained interaction telemetry for comparing annotation strategies.

Source code: [github.com/AdamFaci/segmentart](https://github.com/AdamFaci/segmentart) &mdash; software deposit: [hal-05742614](https://hal.science/hal-05742614v1).
