---
{"dg-publish":true,"permalink":"/Gang of Four Design Patterns in Machine Learning and Recommender Systems/Builder pro komplexní pipeline/","dgShowLocalGraph":true,"noteIcon":""}
---

tags: #builder_pattern #pipeline_construction #recommender_systems #modular_design
created: 2025-12-14T20:43:41.834Z

---
# 1. Popis
Vzor Builder je užitečný při sestavování složitých recommender pipeline sestávajících z mnoha kroků (např. načítání dat, feature_extractor, preprocessory, model, postprocessing), protože umožňuje konstruovat varianty systému krok po kroku, zjednodušuje klientský kód a snižuje riziko přetížených konstruktorů s velkým počtem parametrů.
# 2. Reference
- [[Factory/Abstract Factory v recommender systémech\|Factory/Abstract Factory v recommender systémech]] (89%)


Originální soubor - [[gof-and-recommenders.docx-2.pdf]]