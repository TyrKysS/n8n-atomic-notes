---
{"dg-publish":true,"permalink":"/Gang of Four Design Patterns in Machine Learning and Recommender Systems/Flyweight pro úsporu paměti u velkých datasetů/","dgShowLocalGraph":true,"noteIcon":""}
---

tags: #flyweight_pattern #memory_optimization #shared_state #large_scale_systems
created: 2025-12-14T20:43:41.835Z

---
# 1. Popis
Flyweight pattern minimalizuje spotřebu paměti tím, že sdílí společný stav objektů (např. metadata položek jako title, genre, year) mezi mnoha uživatelskými referencemi a odděluje proměnný stav vztahující se k uživateli (rating, timestamp), což je obzvlášť efektivní v systémech s miliony uživatelů a velkým počtem opakovaných entit.
# 2. Reference


Originální soubor - [[gof-and-recommenders.docx-2.pdf]]