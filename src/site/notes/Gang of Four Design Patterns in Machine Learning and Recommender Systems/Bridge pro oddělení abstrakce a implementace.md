---
{"dg-publish":true,"permalink":"/Gang of Four Design Patterns in Machine Learning and Recommender Systems/Bridge pro oddělení abstrakce a implementace/","dgShowLocalGraph":true,"noteIcon":""}
---

tags: #bridge_pattern #abstraction_implementation #recommendation_engine #data_access
created: 2025-12-14T20:43:41.834Z

---
# 1. Popis
Bridge pattern odděluje abstrakci (např. RecommendationEngine) od konkrétní implementace (např. RecommendationAlgorithm nebo Model) a tím umožňuje nezávislé rozšiřování obou stran, dynamické přepínání implementací při běhu a lepší organizaci přístupu k datům (např. různé adaptory pro offline nebo online datové zdroje).
# 2. Reference


Originální soubor - [[gof-and-recommenders.docx-2.pdf]]