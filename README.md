# 🍪 Implementace správy cookies

- Pro správu cookies je implementován modifikovaný skript https://github.com/orestbida/cookieconsent v aktuální stabilní verzi
- Při zvolení souhlasu, nesouhlasu nebo změny souhlasu je tato informace zaznamenána do externí databáze pro možnou potřebu doložení souhlasu/nesouhlasu
- Cookies implementace podporuje jazykové mutace
- Cookies implementace podporuje Google Consent Mode a Facebook Pixel Consent Mode
- Cookies banner je vizuálně modifikován do podoby webu (fonty, barvy atp.)
- Cookies jsou kategorizovány zpravidla do:
  - Nezbytně nutné cookies (funkční cookies)
  - Výkonové a analytické cookies (typicky Google Analytics)
  - Reklamní a cílící cookies (typicky Google Ads a Facebook Pixel)
- Součástí implementace je informační stránka o cookies, ze které je možné cookies banner vyvolat
