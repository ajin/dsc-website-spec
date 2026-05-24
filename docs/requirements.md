# DSC Website – Requirements

Functionele en inhoudelijke uitgangspunten voor de nieuwe website van
schaakvereniging DSC (WordPress). Dit document wordt stap voor stap uitgebouwd.

---

## Techniek & uitgangspunten

Algemene technische randvoorwaarden waarbinnen de site moet werken. Doel:
beperk het aantal externe afhankelijkheden en houd het beheer eenvoudig.

- **Minimaliseer plugins.** De site draait standaard op zo min mogelijk
  plugins. De volgende plugins worden gebruikt:
  - RGB Chessboard
  - The Events Calendar
  - Een formulierplugin (bijv. Contact Form 7)
- **Geen ledenlogin (vooralsnog).** De site is volledig publiek; er komt
  geen account- of ledengedeelte. Kan later heroverwogen worden.
- **Geen zoekfunctie.** Het hoofdmenu is de enige navigatie; een zoekbalk
  wordt niet ingebouwd. Onderbouwing in
  [`../research/findings-summary.md`](../research/findings-summary.md).
- **Onderscheid tussen pages en posts.** WordPress kent twee soorten
  content; kies bewust om verwarring te voorkomen.
  - **Pages** = vaste, hiërarchische pagina's die in het menu staan (Home,
    Senioren, Jeugd, Toernooien, Over DSC, Contact en hun subpagina's). Niet chronologisch.
  - **Posts** = chronologische berichten in een categorie (toernooi­verslagen,
    uitslagen, nieuws). Verschijnen in feeds en op de bijbehorende
    categorie-pagina.

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
Toernooien
├── OGD                  ┐
├── OPK                  │  elk een pagina met toernooi-info
├── Kroeglopen           │  + alle posts in die categorie
└── Grand Prix Rapid     ┘
Lid worden?
Over DSC
├── Over de club / bestuur
├── Sociale veiligheid
├── Huisregels
├── Vertrouwenspersoon
└── Privacy
Contact
```

- **Externe competitie staat onder Senioren, niet onder Toernooien.** De
  losse competities (KNSB, HSB e.a.) zijn teamcompetitie en staan als content
  op die pagina, niet als menu-label.
- **Toernooien.** Elk submenu-item (eg. OGD, OPK, Kroeglopen, Grand Prix
  Rapid, blitz-/rapidformats (10 en 3 minuten)) is een eigen pagina met (a)
  een beschrijving van het toernooi, en (b) een overzicht van alle posts in
  de bijbehorende categorie. De lijst is uitbreidbaar: nieuwe terugkerende
  toernooien die de club gaat organiseren kunnen op dezelfde manier als
  submenu-item worden toegevoegd.

- **Damesteam onder Senioren.** Als het werven van damesspelers expliciet
  strategisch wordt, kan "Dames" gepromoveerd worden tot hoofditem.

De analyse achter deze structuur — waarom niet volledig plat, waarom
doelgroep-gestuurd (Senioren / Jeugd), "Lid worden?" als hoofditem, sociale
veiligheid onder "Over DSC" en geen zoekfunctie — staat in
[`../research/findings-summary.md`](../research/findings-summary.md).

---

## Footer

De footer staat onderaan elke pagina en is daarmee vanaf elke plek op de site
bereikbaar. 

- Adres en speellocatie.
- Link naar sociale veiligheid, met o.a. huisregels. Sociale veiligheid staat
  bewust op twee plekken: als menu-item onder "Over DSC" én als link in de
  footer.
- Privacy.
- Agenda-abonneerlinks (Tribe Events).
- Social links.
- Lid worden.
- Alle overige belangrijke links.
