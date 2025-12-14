---
{"dg-publish":true,"permalink":"/Gang of Four Design Patterns in Machine Learning and Recommender Systems/Strategie pro runtime přepínání algoritmů/","dgShowLocalGraph":true,"noteIcon":""}
---

tags: #strategy_pattern #runtime_switching #algorithm_selection #cold_start
created: 2025-12-14T20:43:41.835Z

---
# 1. Popis
Strategy pattern definuje rodinu algoritmů a umožňuje jejich zapouzdření a zaměnitelnost v běhu, což je v doporučovacích systémech užitečné pro dynamické přepínání mezi metodami podle dostupnosti dat, segmentu uživatele nebo obchodních metrik a tím podporuje flexibilitu nasazení bez zásahu do kontextu volajícího kódu.
# 2. Reference
- [[Gang of Four Design Patterns in Machine Learning and Recommender Systems/Composite pro hierarchii doporučovacích metod\|Composite pro hierarchii doporučovacích metod]] (85%)
- [[Gang of Four Design Patterns in Machine Learning and Recommender Systems/Adapter pro kompatibilitu knihoven\|Adapter pro kompatibilitu knihoven]] (82%)
- [[Gang of Four Design Patterns in Machine Learning and Recommender Systems/Template Method pro sdílené kroky výpočtu\|Template Method pro sdílené kroky výpočtu]] (88%)


Originální soubor - [[gof-and-recommenders.docx-2.pdf]]