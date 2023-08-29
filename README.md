# Roadmap for Digdir

Veikart for alle produktene til Digdir samlet på ett sted:

**https://github.com/orgs/digdir/projects/8/**

Det er [produkteier](https://github.com/orgs/digdir/teams/team-product-owners) sitt ansvar at [alle visninger](https://github.com/digdir/roadmap#layouts) til envher tid er oppdatert for sine produkter. Feltet `Progresjon (prosent)` skal vurderes ukentlig, mens gjennomførte oppgaver skal oppdateres fortløpende.

| Produkt            | Visning            |
| :----------------- | :----------------- |
| Altinn Formidling  | [Roadmap](https://github.com/orgs/digdir/projects/8/views/20?layout=roadmap) • [Table](https://github.com/orgs/digdir/projects/8/views/20?layout=table) • [Board](https://github.com/orgs/digdir/projects/8/views/20?layout=board)
| Altinn Melding     | [Roadmap](https://github.com/orgs/digdir/projects/8/views/21?layout=roadmap) • [Table](https://github.com/orgs/digdir/projects/8/views/21?layout=table) • [Board](https://github.com/orgs/digdir/projects/8/views/21?layout=board)
| Altinn Studio      | [Roadmap](https://github.com/orgs/digdir/projects/8/views/2?layout=roadmap)  • [Table](https://github.com/orgs/digdir/projects/8/views/2?layout=table)  • [Board](https://github.com/orgs/digdir/projects/8/views/2?layout=board)
| Autorisasjon       | [Roadmap](https://github.com/orgs/digdir/projects/8/views/5?layout=roadmap)  • [Table](https://github.com/orgs/digdir/projects/8/views/5?layout=table)  • [Board](https://github.com/orgs/digdir/projects/8/views/5?layout=board)
| Dialogporten       | [Roadmap](https://github.com/orgs/digdir/projects/8/views/25?layout=roadmap) • [Table](https://github.com/orgs/digdir/projects/8/views/25?layout=table) • [Board](https://github.com/orgs/digdir/projects/8/views/25?layout=board)
| Dialogporten.js    | [Roadmap](https://github.com/orgs/digdir/projects/8/views/28?layout=roadmap) • [Table](https://github.com/orgs/digdir/projects/8/views/28?layout=table) • [Board](https://github.com/orgs/digdir/projects/8/views/28?layout=board)

## Effekter

- [Ett sted](https://github.com/orgs/digdir/projects/8/) for å få overordnet oversikt over hva som planlegges for Digdir sine produkter
- Gjøre det enklere å koordinere på tvers, **både** internt på tvers av teams i Digdir og eksternt mot de som benytter produktene
- Økt gjennomsiktighet ved at man kan
   - Forstå leveransene som kommer
   - Drille ned videre til konkrete epos/brukerhistorier i produktteamenes backlogs
   - Følge med på status, fremdrift og avhengigheter

## Nivå

Elementene i roadmap skal beskrives kort og presist, på et helt overordnet nivå:

- Overordnet beskrivelse
- Forventet resultat
- Hvordan skal det fungere?
- Gjennomføring
  - Avhengigheter (en tasklist med avhengigheter til andre produkter)
  - Tasks (en eller flere tasklists med epos som skal leveres)

Tittel skal være kort og konsis, men gi mening også på tvers av produkter i ulike visninger.  
Avhengigheter og Tasks **skal** legges inn som [tasklists](https://github.com/digdir/roadmap#tasklists).

Se [eksempel på ønsket nivå](https://github.com/digdir/roadmap/issues/78) fra roadmap for Altinn Studio.

## Struktur

### En fane pr. produkt.

![En fane per produkt](https://user-images.githubusercontent.com/6088624/245439117-c38b0ca1-4390-4198-bef5-39e454465598.png "Produktvisninger, en fane per produkt")

Hvert produkt har sin egen fane, og fanene skal ligge i alfabetisk rekkefølge.  
Hver fane filtreres på [label for produkt](https://github.com/digdir/roadmap#labels), og roadmap-elementene **skal** ligge i [roadmap-repo](https://github.com/digdir/roadmap/issues).

### Layouts

Hver produkt har tre ulike layouts for visning av leveransene. Du kan [selv velge](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view#changing-the-project-layout) hvilken du ønsker å se.

- [Roadmap](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view#about-the-roadmap-layout) - leveransene lagt ut i tid. Dette betyr at hver leveranse **skal** ha satt dato i felter for `Start` og `End`.
- [Tabell](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view#about-the-table-layout) - leveransene vist som et regneark. Feltene `Estimert ukesverk` og `Progresjon (prosent)` skal være satt.
- [Board](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view#about-the-board-layout) - leveransene vist i tavle (Kanban) basert på overordnet status `Til vurdering`, `Backlog`, `Under arbeid`eller `Levert`.

Uavhengig av hvilken layout som benyttes, så kan du alltid se på den enkelte leveranse ved å trykke på den.

### Tasklists

For at veikart skal kunne gi de ønskede effektene så **skal** koblinger mot epos i underliggende backlogs legges inn.

Hvert element i roadmap skal inneholde en eller flere [tasklist](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-tasklists) som lenker ned mot ett eller flere epos i produktbacklog.  
Når alle lenkede epos er lukket så kan roadmap-elementet også lukkes.

MERK: Det er viktig at tasklist med avhengigheter har tittel `Avhengigheter`, da dette benyttes ifbm. rapportering. Se også [nivå](https://github.com/digdir/roadmap#niv%C3%A5) for mer info.

Se [eksempel](https://github.com/orgs/digdir/projects/8/views/2?pane=issue&itemId=24019705) fra roadmap for Altinn Studio:

![image](https://github.com/digdir/roadmap/assets/6088624/a1e61139-5d6f-4056-8c6f-be13956677a9)

### Tracks
Bruk av [tasklist](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-tasklists) gjør at man i tabell-layout for et produkt kan følge med på status på tvers av underliggende epos med en ["Tracks"-kolonne](https://docs.github.com/en/issues/planning-and-tracking-with-projects/understanding-fields/about-tracks-and-tracked-by-fields#enabling-the-tracks-field).

Se [eksempel](https://github.com/orgs/digdir/projects/8/views/5?layout=table) fra roadmap for Autorisasjon:

![Image](https://user-images.githubusercontent.com/6088624/245457571-d7aa1d58-5d28-48a6-ba31-864435e055f9.png)

### Labels
Hvert produkt har sin egen label, og hvert element i roadmap skal ha kun ha en produktlabel.  
Komplett oversikt finnes her: https://github.com/digdir/roadmap/labels

For større tiltak som går på tvers av flere produkter, og som krever spesiell oppfølging, så kan det finnes en egen label.  
Et eksempel på en slik label er https://github.com/digdir/roadmap/labels/program%2Fnye-altinn.
