---
{"dg-publish":true,"permalink":"/Gang of Four Design Patterns in Machine Learning and Recommender Systems/Template Method pro sdílené kroky výpočtu/","dgShowLocalGraph":true,"noteIcon":""}
---

tags: #template_method #pipeline_template #code_reuse #recommendation_workflow
created: 2025-12-14T20:43:41.835Z

---
# 1. Popis
Template Method definuje kostru procesu doporučování (např. načtení dat, sestavení profilu, extrakce rysů, výpočet skóre, řazení) v abstraktní třídě a umožňuje podsystémům předefinovat konkrétní kroky, takže se dosahuje opakovaného využití společných operací a konzistence pipeline napříč různými typy doporučovacích metod.
# 2. Reference
- [[Gang of Four Design Patterns in Machine Learning and Recommender Systems/Strategie pro runtime přepínání algoritmů\|Strategie pro runtime přepínání algoritmů]] (89%)


Originální soubor - [[gof-and-recommenders.docx-2.pdf]]