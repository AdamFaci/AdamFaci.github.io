---
title: "RAG pour l'exploration de corpus en GLAM"
collection: talks
type: "Conference talk"
permalink: /talks/2024-10-14-coldoc-rag-glam
venue: "ColDoc 2024 — « La linguistique dans une ère nouvelle : discours, méthodes et technologies dans le paysage contemporain »"
date: 2024-10-14
location: "Nanterre, France"
---

With Antoine Silvestre de Sacy.

With GLAMs in mind, and in the context of corpus exploration with a search engine, for example to build up a state of the art and explore it, several strategies using RAG can be implemented. One obstacle remains: to establish sub-corpora from the same set of documents, in order to have different contexts to be provided to the RAG.

Our proposal is to combine community detection techniques (around influential authors and around themes) and classification of these communities to describe them upstream. Coupling this community detection to the use of RAG allows us to pre-select and display an initial filtering of the corpus to the user, on which the RAG can operate with greater relevance. During their search, the user can see communities and networks emerging between the results, which they can then extract and use the RAG to question, without ever losing control of that constitution. We also offer other processing chains that enable you to interactively compose different communities in a corpus, characterising them according to specific criteria: cluster theme, lexical richness, level of technicality, etc.

[Read on HAL](https://hal.science/hal-04829841v1)
