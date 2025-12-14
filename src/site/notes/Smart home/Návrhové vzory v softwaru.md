---
{"dg-publish":true,"permalink":"/Smart home/Návrhové vzory v softwaru/","dgShowLocalGraph":true,"noteIcon":""}
---

tags: #návrhové_vzory #singleton #observer #software_design
created: 2025-12-14T20:17:21.503Z

---
# 1. Popis
Použití návrhových vzorů usnadňuje tvorbu robustního softwaru pro chytré domácnosti: vzor Singleton omezuje počet vytvářených instancí (např. pool připojení k databázi) a zamezuje nadměrnému otevírání spojení, zatímco Observer umožňuje efektivní notifikace a aktualizace více prezentačních klientů (tablet, dotykový panel, desktop) při změně dat modelu bez neefektivního periodického dotazování, čímž se snižuje zatížení sítě a zvyšuje citlivost uživatelského rozhraní na reálné události.
# 2. Reference
- [[Smart home/Pět oblastí platformy\|Pět oblastí platformy]] (84%)


Originální soubor - [[INFORMATIKA INTELIGENTNÍCH DOMŮ.pdf]]