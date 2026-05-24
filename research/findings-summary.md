# Bevindingen – menuonderzoek schaakclubs

Volledige uitwerking van het onderzoek naar de navigatiemenu's van Nederlandse
schaakclub-websites. Dit document is de leesbare tegenhanger van
`chess-menu-research.xlsx` en vormt de onderbouwing voor de menukeuzes in
[`../docs/requirements.md`](../docs/requirements.md).

## Opzet

Onderzocht zijn **47 Nederlandse schaakclub-websites**, waarvan er **44 leesbaar**
waren. De overige 3 tonen hun menu via JavaScript of waren niet toegankelijk en
zijn buiten de cijfers gelaten.

## Aantal hoofditems

De clubs gebruiken gemiddeld **8,4** hoofditems, met een **mediaan van 7** en een
spreiding van 4 tot 22.

| Aantal hoofditems | Aantal clubs |
|------------------:|-------------:|
| 4 | 2 |
| 5 | 2 |
| 6 | 6 |
| 7 | 13 |
| 8 | 9 |
| 9 | 2 |
| 10 | 1 |
| 11 | 3 |
| 12 | 2 |
| 13 | 2 |
| 20 | 1 |
| 22 | 1 |

De grote uitschieters (20 en 22) zijn sites die elke pagina als los menu-item
tonen — een patroon dat juist onoverzichtelijk wordt. Het zwaartepunt ligt
duidelijk rond de 6–8 items.

## Menudiepte

De **mediane menudiepte is 3** (hoofdmenu + submenu, soms één niveau dieper).

| Maximale diepte | Aantal clubs |
|----------------:|-------------:|
| 1 (plat) | 7 |
| 2 | 13 |
| 3 | 17 |
| 4 | 6 |
| 5 | 1 |

Een hoofdmenu met **één submenuniveau** dekt het overgrote deel van de clubs en
sluit aan bij de wens voor DSC: geen megamenu, geen submenu's onder submenu's.

## Navigatiepatroon

| Patroon | Aantal clubs |
|---------|-------------:|
| Geneste dropdown | 23 |
| Simpele dropdown | 13 |
| Plat (geen submenu) | 7 |
| Megamenu | 1 |

Geneste dropdowns zijn het meest voorkomend, maar de overzichtelijkste sites in
de set houden het bij één submenuniveau. Volledig platte menu's komen vooral voor
bij hele kleine of verouderde sites.

## Conclusies voor DSC

1. **Hoofdmenu + één submenuniveau** zit precies op de bewezen norm (mediaan 7
   items, diepte 3). De oorspronkelijke wens voor een volledig plat menu zou de
   vindbaarheid juist schaden.
2. **Doelgroep-gestuurde hoofdnavigatie** (Senioren / Jeugd als hoofditems) wordt
   door enkele van de overzichtelijkste sites gebruikt en past bij de al
   doelgroep-gevormde content van DSC. Senioren en Jeugd krijgen daarom een
   parallel opgebouwd submenu.
3. **"Lid worden" als los hoofditem** — een van de meest voorkomende losse
   hoofditems, en de belangrijkste conversielink voor een wervende club.
4. **Sociale veiligheid onder "Over DSC"** (plus een link in de footer), conform
   de gangbare praktijk om gedragsregels, vertrouwenspersoon en privacy onder een
   "Over"-item te plaatsen in plaats van als eigen hoofditem.
5. **Geen zoekfunctie nodig** bij een goed gestructureerd menu van deze omvang.

## Referentieclubs

Sites die qua opzet het dichtst bij de gekozen DSC-structuur liggen (heldere
doelgroepsplitsing, diepte 2–3, beheersbaar aantal hoofditems):
Moira-Domtoren, De Pion, SV Amsterdam West en WLC.

## Kanttekening

De data weerspiegelt de onderzochte sites op het moment van verzamelen en komt
mogelijk niet overeen met de huidige websites van die clubs.
