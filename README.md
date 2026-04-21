# Model boulderovky pro 3D tisk (metoda reliéfu)

## Popis projektu
Projekt zmenšeného modelu lezecké haly optimalizovaný pro 3D tisk bez podpěr. Využívá metodu reliéfního tisku pro dosažení vysokých detailů stěn a modularitu pro snadné sestavení a měnění lezeckých cest pomocí systému výměnných chytů.

## Technické řešení
### Metoda reliéfu
Stěny jsou modelovány se zadní plochou stranou a lícovým reliéfem (výběžky, hrany, prohlubně). Všechny tvary jsou navrženy pod úhly (nad 45°), které umožňují tisk lícem nahoru bez nutnosti generovat podpěry.

### Spojovací mechanismus
Podlaha obsahuje vodicí drážky, do kterých se hotové stěny zasouvají. Toto řešení zajišťuje stabilitu bez nutnosti lepení a umožňuje model snadno rozebrat.

### Interaktivní chyty
Součástí je sada miniaturních chytů s čepy. Tyto chyty se zasouvají do rastru otvorů v panelech, což umožňuje simulovat reálné lezecké cesty.

## Hlavní komponenty
* **Základová deska:** Podlaha s integrovanými drážkami pro stěny a otvory pro umístění volně stojících bloků.
* **Reliéfní panely:** Zadní a boční stěna s 3D strukturou a rastrem pro piny chytů.
* **Vnitřní bloky:** Samostatně stojící balvany tištěné jako uzavřené objekty se zarovnanou základnou.
* **Sada chytů:** Různé tvary (lišty, stisky, obliny) vybavené fixačními piny pro snadné zasouvání.

## Pokyny pro 3D tisk
* **Orientace:** Stěny jsou tisknuty naležato, zadní stranou k podložce. Tím se dosáhne nejvyšší kvality otvorů.
* **Materiál:** PLA. Pro hlavní stěny matné barvy (bílá, šedá), pro chyty pestré barvy dle obtížnosti.
* **Nastavení:** Pro detailní reliéfy je vhodné použít funkci variabilní výšky vrstvy v sliceru.

## To-do list (Kroky projektu)
- [ ] Namodelovat základovou desku s drážkami pro stěny
- [ ] Navrhnout reliéfní stěny s rastrem otvorů (úhly nad 45°)
- [ ] Modelovat vnitřní balvany jako samostatné objekty
- [ ] Vytvořit sadu chytů s piny pro zasouvání
- [ ] Exportovat STL soubory a připravit G-code (slicing)
- [ ] Vytisknout hlavní konstrukci z matného PLA
- [ ] Vytisknout sady chytů v různých barvách
- [ ] Sestavit model a vytvořit první cesty
