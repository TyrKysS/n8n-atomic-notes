---
{"dg-publish":true,"permalink":"/Smart home/Kódování a datová reprezentace/","dgShowLocalGraph":true,"noteIcon":""}
---

tags: #unicode #kódování #XML #JSON #hex
created: 2025-12-14T20:17:21.503Z

---
# 1. Popis
Správná reprezentace znaků a dat je v propojených systémech zásadní: moderní řešení preferují Unicode (UTF‑8) kvůli univerzálnosti, zatímco starší zařízení mohou používat platformně specifická kódování (windows‑1250, cp852 apod.), a nízkoúrovňová zařízení často komunikují v binárních nebo hex formátech; navíc pro strukturovaný přenos se používají XML (s XSD validací) nebo JSON podle potřeb, přičemž pro komunikaci se senzory či legacy protokoly se běžně převádějí hex/byte sekvence a je potřeba ošetřit konverzi i endianitu.
# 2. Reference


Originální soubor - [[INFORMATIKA INTELIGENTNÍCH DOMŮ.pdf]]