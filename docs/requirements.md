# DSC Website – Requirements

Functionele en inhoudelijke uitgangspunten voor de nieuwe website van
schaakvereniging DSC (WordPress). Dit document wordt stap voor stap uitgebouwd.

---

## Menustructuur

**Uitgangspunt:** hoofdmenu + maximaal 1 niveau submenu. Geen mega-menu, geen submenu's onder submenu's. Gebaseerd op een analyse van 44 leesbare schaakclub-sites (mediaan: 7 hoofditems, menudiepte 3) en de specifieke wensen voor DSC.

### Menu

Zeven hoofditems. Home, Lid worden? en Contact zijn losse pagina's zonder
dropdown; de overige vier hebben één niveau submenu.

```text
Home
Senioren
├── Interne competitie
├── Externe competitie   (KNSB, HSB, e.a. als content op de pagina)
├── Damesteam
├── Stand & uitslagen
├── Reglement
└── Kalender
Jeugd
├── Informatie en inschrijving
├── Training en examens
├── Stand & uitslagen
├── Reglement
└── Kalender
Toernooien (post-categorieën met beschrijving)
├── OGD
├── OPK
├── Kroeglopen
└── Grand Prix Rapid
Lid worden?
Over DSC
├── Over de club / bestuur
├── Sociale veiligheid
├── Huisregels
├── Vertrouwenspersoon
└── Privacy
Contact
```

---

### Regels

- **Consistente labels.** Binnen Senioren en Jeugd heten de gedeelde items
  exact hetzelfde ("Stand & uitslagen", "Reglement", "Kalender") en staan in
  dezelfde volgorde. De doelgroep ("senioren" / "jeugd") zit in het
  bovenliggende menu-item, niet in het label. Paginatitels mogen uitgebreider
  zijn — bijv. "Reglement interne competitie DSC jeugd" achter het label
  "Reglement" onder Jeugd.
- **Externe competitie staat onder Senioren, niet onder Toernooien.** De
  losse competities (KNSB, HSB e.a.) zijn teamcompetitie en staan als content
  op die pagina, niet als menu-label.
- **Toernooien.** Elke toernooipagina bevat de eigen aanmeldinfo; geen apart
  "aanmelden" menu-item nodig.
- **Damesteam onder Senioren.** Als het werven van damesspelers expliciet
  strategisch wordt, kan "Dames" gepromoveerd worden tot hoofditem.

### Aandachtspunt

De Senioren-dropdown is met 6 items de langste. Dat is nog comfortabel, maar
als het te vol voelt kan "Stand & uitslagen" op de pagina Interne competitie
worden opgenomen in plaats van als los submenu-item.

### Onderbouwing

De analyse achter deze structuur — waarom niet volledig plat, waarom
doelgroep-gestuurd (Senioren / Jeugd), "Lid worden?" als hoofditem, sociale
veiligheid onder "Over DSC" en geen zoekfunctie — staat in
[`../research/findings-summary.md`](../research/findings-summary.md).
