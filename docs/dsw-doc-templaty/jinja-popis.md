# Jinja - popis a základy

- Jinja, přesněji Jinja2 je templatovací engine
- Jeho primární použití je pro webové apliace, napsané v Pythonu
- Jak ale ukazuje FAIR Wizard, dá se velice dobře adaptovat i na jiná použití

## Co znamená templatovací engine
- Templatovací engine slouží k tomu, abyste si mohli napsat HTML dokument, aniž byste předtím znali jeho obsah
- Představte si následující situaci: máte HTML stránku, která má spoustu formulářů `<form>`
- Vy chcete, aby si uživatel po vyplnění mohl zobrazit, co napsal. Třeba i nějak hezky, formátovaně (to zní dost jako Data Stewardship Wizard, co?)
- V prostém HTML tohle udělat nejde. Tradiční cesta je ukládat obsah těch formulářů do nějaké databáze na serveru a pak ta data tam odtud zase načíst
- Jinja nám umožňuje tohle všechno udělat ve (skoro) prostém HTML

### Základní příklad
