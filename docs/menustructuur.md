# DSC Website – Voorstel menustructuur

**Uitgangspunt:** hoofdmenu + maximaal 1 niveau submenu. Geen mega-menu, geen submenu's onder submenu's. Gebaseerd op een analyse van 44 leesbare schaakclub-sites (mediaan: 7 hoofditems, menudiepte 3) en de specifieke wensen voor DSC.

---

## Hoofdmenu (7 items)

Home – Senioren – Jeugd – Toernooien – Lid worden? – Over DSC – Contact

Home, Lid worden? en Contact zijn losse pagina's zonder dropdown. De overige vier hebben één niveau submenu.

---

## Senioren
- Interne competitie
- Externe competitie *(KNSB, HSB, e.a. als content op de pagina)*
- Damesteam
- Stand & uitslagen
- Reglement
- Kalender

## Jeugd
- Informatie en inschrijving
- Training en examens
- Stand & uitslagen
- Reglement
- Kalender

## Toernooien
- OGD
- OPK
- Kroeglopen
- Grand Prix Rapid

## Over DSC
- Over de club / bestuur
- Sociale veiligheid
- Huisregels
- Vertrouwenspersoon
- Privacy

---

## Wat hier niet staat

- **Footer.** De footer is geen menu maar wel overal zichtbaar — zie
  [`requirements.md`](requirements.md#footer).
- **Technische uitwerking van toernooien** (post-categorieën, plugins) — zie
  [`requirements.md`](requirements.md#toernooien).

---

## Toelichting bij de keuzes

**Waarom niet volledig plat.** Van de 44 leesbare clubsites zijn er maar 5 volledig plat zonder submenu's; dat zijn vrijwel allemaal hele kleine of verouderde sites. De mediaan is 7 hoofditems met menudiepte 3. Een hoofdmenu + 1 submenuniveau zit precies op het bewezen punt: overzichtelijk én vindbaar.

**Waarom audience-gestuurd (Senioren / Jeugd).** Acht clubs zetten doelgroep expliciet als hoofditem, en de overzichtelijkste sites in de set (Moira-Domtoren, De Pion, SV Amsterdam West, WLC) doen dat ook. De content van DSC is al doelgroep-gevormd, dus dit sluit naadloos aan. Senioren en Jeugd hebben grotendeels hetzelfde patroon (intern / extern / stand / reglement / kalender), zodat een ouder en een volwassen speler in "hun" sectie dezelfde soort pagina's in dezelfde volgorde vinden.

**Lid worden? als eigen hoofditem.** Dit is een van de meest voorkomende losse hoofditems bij clubs, omdat het de belangrijkste conversielink is voor het werven van leden. Daarom verplaatst van onder "Over DSC" naar het hoofdmenu.

**Damesteam onder Senioren.** Het damesteam staat als submenu-item onder Senioren: zichtbaar en vindbaar, zonder een volledig hoofditem te claimen. Mocht het werven van damesspelers een expliciet strategisch doel worden, dan kan "Dames" later in één regel gepromoveerd worden tot hoofditem.

**Toernooien als losse menu-items.** De terugkerende toernooien (OGD, OPK, Kroeglopen, Grand Prix Rapid) krijgen elk een eigen submenu-item, omdat ze elk een eigen herkenbare identiteit hebben. Elke toernooipagina bevat de eigen aanmeldinfo (geen apart "aanmelden" menu-item nodig). Externe competities (KNSB, HSB en eventueel meer) horen niet bij Toernooien maar bij Senioren → Externe competitie, want dat is teamcompetitie; de losse competities staan als content op die pagina, niet in het menu-label. De technische uitwerking als post-categorie staat in [`requirements.md`](requirements.md#toernooien).

**Consistente menu-labels.** De labels zijn kort en parallel gehouden: binnen Senioren en Jeugd heten de gedeelde items in beide secties exact hetzelfde ("Stand & uitslagen", "Reglement", "Kalender") en staan in dezelfde volgorde. De doelgroep-toevoeging ("senioren" / "jeugd") is uit de labels gehaald omdat het bovenliggende menu-item die al aangeeft. De volledige paginatitels mogen uitgebreider zijn — bijvoorbeeld het label "Reglement" onder Jeugd kan als paginatitel "Reglement interne competitie DSC jeugd" hebben.

**Geen zoekfunctie nodig.** Bij een goed gestructureerd menu van 7 items met telkens één submenuniveau is een site van deze omvang prima te navigeren zonder zoekfunctie.

## Aandachtspunt

De Senioren-dropdown is met 6 items de langste. Dat is nog comfortabel, maar als het te vol voelt kan "Stand & uitslagen" op de pagina Interne competitie worden opgenomen in plaats van als los submenu-item.
