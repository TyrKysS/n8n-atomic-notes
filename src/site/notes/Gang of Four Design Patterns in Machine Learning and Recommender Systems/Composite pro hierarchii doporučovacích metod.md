---
{"dg-publish":true,"permalink":"/Gang of Four Design Patterns in Machine Learning and Recommender Systems/Composite pro hierarchii doporučovacích metod/","dgShowLocalGraph":true,"noteIcon":""}
---

tags: #composite_pattern #hybrid_recommender #cold_start #algorithm_ensemble
created: 2025-12-14T20:43:41.834Z

---
# 1. Popis
Composite pattern je vhodný pro skládání více doporučovacích strategií do stromové hierarchie, kde například vrchol rozhoduje mezi větvemi pro cold_user a warm_user a jednotlivé listy obsahují konkrétní algoritmy (popularity, content_based, collaborative, hybrid), což umožní flexibilně kombinovat metody podle segmentu uživatele nebo kontextu.
# 2. Reference
- [[Gang of Four Design Patterns in Machine Learning and Recommender Systems/Strategie pro runtime přepínání algoritmů\|Strategie pro runtime přepínání algoritmů]] (85%)
- [[Factory/Abstract Factory v recommender systémech\|Factory/Abstract Factory v recommender systémech]] (82%)
- [[Gang of Four Design Patterns in Machine Learning and Recommender Systems/Decorator pro postprocessing a pravidla byznysu\|Decorator pro postprocessing a pravidla byznysu]] (81%)


Originální soubor - [[gof-and-recommenders.docx-2.pdf]]