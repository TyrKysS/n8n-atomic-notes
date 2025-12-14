---
{"dg-publish":true,"permalink":"/Smart home/Vícevrstvá architektura aplikací/","dgShowLocalGraph":true,"noteIcon":""}
---

tags: #vícevrstvá_architektura #prezentační_vrstva #datová_vrstva #JSON #XML
created: 2025-12-14T20:17:21.503Z

---
# 1. Popis
Aplikační software pro inteligentní domy by měl být navržen jako vícevrstvá architektura oddělující prezentační vrstvu (web, desktop, mobilní a dotykové panely), aplikační logiku (biznis pravidla, řídicí algoritmy) a datovou vrstvu (DBMS, historizační úložiště), což umožňuje opakované použití business logiky mezi různými klienty, zjednodušenou údržbu, nezávislý vývoj frontendu a škálovatelnost, přičemž komunikace mezi vrstvami používá standardní protokoly (HTTP/REST, TCP/IP, JDBC) a formáty (JSON, XML).
# 2. Reference


Originální soubor - [[INFORMATIKA INTELIGENTNÍCH DOMŮ.pdf]]