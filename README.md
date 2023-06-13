# Roadmap for Digdir

Veikart for alle produktene til Digdir samlet på ett sted:

**https://github.com/orgs/digdir/projects/8/**

Veikartet har som mål å gi følgende effekter:
- Ett sted for å få overordnet oversikt over hva som planlegges for produktene i Digdir
- Gjøre det enklere å koordinere på tvers, både internt i Digdir og eksternt mot de som benytter produktene
- Økt transparens ved at man kan
   - Forstå leveransene som kommer
   - Drille ned videre til konkrete epos/brukerhistorier i teamenes backlogs
   - Følge med på status og fremdrift
   

## En fane pr. produkt.

![En fane per produkt](https://user-images.githubusercontent.com/6088624/245439117-c38b0ca1-4390-4198-bef5-39e454465598.png "Produktvisninger, en fane per produkt")

Hver produkt har tre ulike layouts for visning av leveransene. Du kan [selv velge](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view#changing-the-project-layout) hvilken du ønsker å se.

- [Roadmap](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view#about-the-roadmap-layout) - leveransene lagt ut i tid.
- [Tabell](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view#about-the-table-layout) - leveransene vist som et regneark.
- [Board](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view#about-the-board-layout) - leveransene vist i tavle basert på status.

Uavhengig av hvilken layout som benyttes, så kan du alltid se på den enkelte leveranse ved å trykke på den.


## Kobling mot underliggende backlogs

For at veikart skal kunne gi de ønskede effektene så må koblinger mot underliggende backlogs legges inn.

### Tasklists

Hvert element i roadmap bør inneholde en eller flere [tasklist](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-tasklists) som lenker ned mot en eller flere epics/issues som må lukkes for at roadmap-elementet er ferdigstilt.

[Eksempel](https://github.com/orgs/digdir/projects/8/views/5?layout=table&pane=issue&itemId=30168409) fra roadmap for Autorisasjon:

![Image](https://user-images.githubusercontent.com/6088624/245456940-f997fe3a-9b1d-425b-8873-b0afff4f7b24.png)

### Tracks
Bruk av [tasklist](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-tasklists) gjør også at man i tabell-layout for et produkt kan følge med på status på tvers av underliggende elementer ved å legge til en ["Tracks"-kolonne](https://docs.github.com/en/issues/planning-and-tracking-with-projects/understanding-fields/about-tracks-and-tracked-by-fields#enabling-the-tracks-field).

[Eksempel](https://github.com/orgs/digdir/projects/8/views/5?layout=table) fra roadmap for Autorisasjon:

![Image](https://user-images.githubusercontent.com/6088624/245457571-d7aa1d58-5d28-48a6-ba31-864435e055f9.png)
