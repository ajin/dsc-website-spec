# Onderzoek

Onderbouwend onderzoek voor de specificatie van de DSC-website. Deze map bevat
het bewijsmateriaal achter de menu- en navigatiekeuzes die zijn vastgelegd in
[`../docs/requirements.md`](../docs/requirements.md).

## Wat staat hier

| Bestand | Omschrijving |
|---------|--------------|
| `chess-menu-research.xlsx` | Ruwe onderzoeksdata: menustructuren van schaakclub-websites. |
| `findings-summary.md` | Belangrijkste bevindingen als leesbare tekst (optionele aanvulling op het spreadsheet). |

## Over de dataset

Het spreadsheet brengt de navigatiemenu's van **47 Nederlandse schaakclub-websites**
in kaart, waarvan er **44 leesbaar** waren. Per club is vastgelegd:

- Aantal hoofditems in het menu
- Maximale menudiepte
- Navigatiepatroon (plat, simpele dropdown, geneste dropdown, megamenu, …)
- Ordeningsprincipe (op doelgroep vs. op functie)
- Of er een splitsing jeugd/senioren is
- Opvallende observaties
- De volledige menuboom

## Belangrijkste bevindingen

Dit zijn de patronen die de menustructuur van DSC hebben bepaald:

- **De mediane club heeft 7 hoofditems** (gemiddeld 8,4, spreiding 4–22) en een
  **menudiepte van 3**. Een hoofdmenu met één submenuniveau zit precies op de
  bewezen norm.
- **Volledig platte menu's zijn zeldzaam** — slechts 5 van de 44 clubs gebruiken
  helemaal geen submenu's, en dat zijn vrijwel allemaal hele kleine of
  verouderde sites.
- **Geneste dropdowns zijn het meest voorkomende patroon** (19 van de 44), maar
  de overzichtelijkste, best scanbare sites houden het bij één submenuniveau.
- **Doelgroep-gestuurde hoofdnavigatie** (aparte items Senioren / Jeugd) wordt
  gebruikt door enkele van de overzichtelijkste sites (Moira-Domtoren, De Pion,
  SV Amsterdam West, WLC) — een goede match voor DSC, waarvan de content al
  doelgroep-gevormd is.
- **"Lid worden" is vaak een los hoofditem**, omdat het de belangrijkste
  conversielink is voor een wervende club.
- **Content rond sociale veiligheid** (gedragsregels, vertrouwenspersoon,
  privacy) staat doorgaans **onder een "Over ons"-hoofditem**, niet als een
  eigen hoofditem.

Zie `findings-summary.md` voor de volledige uitwerking.

## Opmerkingen & kanttekeningen

- Het `.xlsx`-bestand is **binair** en kan niet door Git ge-diff't worden. Het is
  toegevoegd als eenmalige onderzoeks-snapshot; de leesbare conclusies staan in
  `findings-summary.md`, zodat ze zichtbaar blijven zonder Excel te openen.
- De data weerspiegelt de onderzochte sites **op het moment van verzamelen** en
  komt mogelijk niet overeen met de huidige websites van die clubs.
- Clubnamen en menustructuren zijn uitsluitend vastgelegd voor vergelijkend
  onderzoek.

## Licentie

Dit onderzoek maakt deel uit van de DSC Website-specificatie en valt onder de
**CC BY 4.0**-licentie — zie [`../LICENSE.md`](../LICENSE.md). Je mag het
hergebruiken mits je passende naamsvermelding geeft en terugverwijst naar deze
repository.
