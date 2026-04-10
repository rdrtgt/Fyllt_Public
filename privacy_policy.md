# Personvernerklæring — Fylt

*Sist oppdatert: 10. april 2026*

## 1. Behandlingsansvarlig

Fylt er utviklet og driftet av Younas (privatperson). For spørsmål om personvern, kontakt oss på: [younas171996@gmail.com](mailto:younas171996@gmail.com)

## 2. Hvilke data vi samler inn

### 2.1 Kontodata
| Data | Formål | Rettslig grunnlag |
|------|--------|-------------------|
| E-postadresse (valgfritt) | Autentisering og kontogjenoppretting | Samtykke (GDPR art. 6(1)(a)) |
| Anonym bruker-ID | Automatisk opprettet ved første bruk for identifisering uten personlig informasjon | Berettiget interesse (GDPR art. 6(1)(f)) |
| Visningsnavn (valgfritt) | Vises på topplisten i stedet for kontokode. Du velger selv hva som vises. | Samtykke (GDPR art. 6(1)(a)) |

### 2.2 Posisjonsdata
| Data | Formål | Rettslig grunnlag |
|------|--------|-------------------|
| GPS-posisjon (ved prisrapportering) | Verifisere at du er nær stasjonen (innen 10 km) | Samtykke (GDPR art. 6(1)(a)) |
| GPS-posisjon (ved stasjonssøk) | Finne stasjoner i nærheten | Samtykke (GDPR art. 6(1)(a)) |
| GPS-posisjon (ved prisvarsel) | Definere søkeområde for prisvarsler du oppretter | Samtykke (GDPR art. 6(1)(a)) |

**Viktig:** Posisjonen din lagres kun når du aktivt sender inn en prisrapport eller oppretter et prisvarsel. Vi sporer ikke posisjonen din i bakgrunnen.

### 2.3 Brukeraktivitet
| Data | Formål | Rettslig grunnlag |
|------|--------|-------------------|
| Prisrapporter | Oppdatere drivstoffpriser for andre brukere | Berettiget interesse (GDPR art. 6(1)(f)) |
| Endringsforslag | Forbedre stasjonsinformasjon | Berettiget interesse (GDPR art. 6(1)(f)) |
| Tillitsscore | Anti-spam og kvalitetssikring | Berettiget interesse (GDPR art. 6(1)(f)) |
| Antall innsendinger | Hastighetsbegrensning og misbruksforebygging | Berettiget interesse (GDPR art. 6(1)(f)) |
| IP-adresse | Hastighetsbegrensning og sikkerhetslogging | Berettiget interesse (GDPR art. 6(1)(f)) |
| Teknisk informasjon (appversjon, OS, plattform) | Feilsøking ved tilbakemeldinger | Berettiget interesse (GDPR art. 6(1)(f)) |
| Krasjrapporter og feillogger | Automatisk feilrapportering via Sentry for å forbedre app-stabilitet | Berettiget interesse (GDPR art. 6(1)(f)) |
| Favorittstasjoner | Synkronisert til serveren for å sende push-varsler ved prisoppdatering | Samtykke (GDPR art. 6(1)(a)) |
| Prisvarsler | Drivstofftype, målpris og søkeradius du definerer. Brukes til å sende push-varsler. | Samtykke (GDPR art. 6(1)(a)) |
| Varselhistorikk | Logg over utløste varsler (tittel, innhold, tidspunkt). Kun synlig for deg. | Berettiget interesse (GDPR art. 6(1)(f)) |

### 2.4 Push-varsler og enhetsidentifikator
| Data | Formål | Rettslig grunnlag |
|------|--------|-------------------|
| FCM-token (Firebase Cloud Messaging) | En enhetsidentifikator som brukes utelukkende til å levere push-varsler til din enhet. | Samtykke (GDPR art. 6(1)(a)) |

**Om FCM-token:** Tokenet genereres av Google Firebase og identifiserer din enhet for levering av push-varsler. Det roteres periodisk av Google. Vi bruker det **kun** til å sende prisvarsler og favorittoppdateringer — aldri for sporing, analyse eller reklame. Du kan når som helst deaktivere push-varsler i enhetens innstillinger, og tokenet vil da ikke lenger lagres.

### 2.5 Automatiserte beslutninger
Vi bruker automatisert vurdering av brukerbidrag for kvalitetssikring (se Vilkår for bruk, § 5). Systemet kan automatisk advare eller suspendere kontoer basert på bidragshistorikk. Du kan kontakte oss for manuell gjennomgang av eventuelle automatiserte beslutninger som påvirker kontoen din (GDPR art. 22).

### 2.6 Data vi IKKE samler inn
- Vi samler ikke inn navn, telefonnummer eller fysisk adresse.
- Vi bruker ikke sporingsteknologi (cookies, fingeravtrykk) for reklame.
- Vi selger ikke data til tredjeparter.

## 3. Databehandlere (tredjeparter)

| Tjeneste | Formål | Plassering | Databehandleravtale |
|----------|--------|------------|---------------------|
| Supabase (supabase.com) | Database, autentisering, serverløse funksjoner | EU (Frankfurt) | Ja — Supabase DPA |
| Sentry (sentry.io) | Feilrapportering og krasjovervåking | EU (Tyskland) | Ja — Sentry DPA |
| OpenStreetMap | Kartdata og stasjonsinformasjon | Global | Offentlig data (ODbL) |
| Nominatim (OSM) | Adresseoppslag (kun server-side) | Global | Ingen persondata sendes |
| Firebase Cloud Messaging (Google) | Levering av push-varsler til enheten | EU/USA | Google Cloud DPA |
| Discord (discord.com) | Videresending av tilbakemeldinger fra brukere | USA | Discord Privacy Policy |

## 4. Lagring og oppbevaring

### 4.1 Oppbevaringsperioder
| Datatype | Oppbevaringstid | Begrunnelse |
|----------|-----------------|-------------|
| Kontoinformasjon | Til kontoen slettes | Nødvendig for tjenesten |
| Prisrapporter | 12 måneder | Historisk prisdata og trendanalyse |
| Endringsforslag | 6 måneder etter behandling | Revisjonsspor |
| Posisjonsdata (fra rapporter) | 12 måneder | Verifisering og misbruksforebygging |
| Tillitsscore | Til kontoen slettes | Kvalitetssikring |
| IP-adresser (hastighetsbegrensning) | 24 timer | Misbruksforebygging |
| IP-adresser (sikkerhetslogger) | 12 måneder | Revisjonsspor og sikkerhetsovervåking |
| Teknisk informasjon (tilbakemeldinger) | 12 måneder | Feilsøking |
| FCM-token | Til kontoen slettes eller varsler deaktiveres | Push-varsler |
| Prisvarsler | Til brukeren sletter varselet | Brukerstyrt |
| Favorittstasjoner | Til brukeren fjerner favoritten | Brukerstyrt |
| Varselhistorikk | 6 måneder | Brukerens varseloversikt |
| Visningsnavn | Til kontoen slettes eller brukeren endrer det | Brukerstyrt |

### 4.2 Automatisk sletting
- Prisrapporter eldre enn 12 måneder slettes automatisk.
- Behandlede endringsforslag slettes etter 6 måneder.
- Inaktive anonyme kontoer slettes etter 24 måneder.

## 5. Dine rettigheter (GDPR)

Som bruker i EU/EØS har du følgende rettigheter:

| Rettighet | Beskrivelse | Slik utøver du den |
|-----------|-------------|-------------------|
| **Innsyn** (art. 15) | Se hvilke data vi har om deg | Kontakt oss på e-post |
| **Retting** (art. 16) | Korrigere feilaktige data | Kontakt oss på e-post |
| **Sletting** (art. 17) | Be om sletting av dine data | Kontakt oss eller slett kontoen i appen |
| **Begrensning** (art. 18) | Begrense behandlingen av dine data | Kontakt oss på e-post |
| **Dataportabilitet** (art. 20) | Motta dine data i maskinlesbart format | Kontakt oss på e-post |
| **Innsigelse** (art. 21) | Protestere mot behandling | Kontakt oss på e-post |
| **Klage** (art. 77) | Klage til tilsynsmyndighet | Datatilsynet (datatilsynet.no) |

Vi svarer på henvendelser innen 30 dager.

## 6. Sikkerhet

- All kommunikasjon mellom appen og serverne er kryptert med TLS/HTTPS.
- Passord (hvis brukt) lagres som salted hashes — vi kan aldri se passordet ditt.
- Tilgangskontroll (Row Level Security) sikrer at brukere kun ser egne data.
- Servere driftes av Supabase i EU-regionen.

## 7. Barn

Tjenesten er ikke rettet mot barn under 13 år. Vi samler ikke bevisst inn data fra barn under 13. Dersom vi oppdager at vi har samlet inn data fra et barn under 13, vil vi slette dataene umiddelbart.

## 8. Internasjonale overføringer

Dine data behandles primært innenfor EU/EØS (Supabase EU-region). Push-varsler leveres via Firebase Cloud Messaging (Google) — Google er underlagt EUs standardkontraktsklausuler (SCC) og EU-US Data Privacy Framework. Kartdata fra OpenStreetMap er offentlig tilgjengelig globalt. Tilbakemeldinger kan bli videresendt til Discord (USA) — Discord er underlagt EUs standardkontraktsklausuler (SCC). Ingen andre persondata overføres til land utenfor EU/EØS uten tilstrekkelig beskyttelsesnivå.

## 9. Endringer i personvernerklæringen

Vi kan oppdatere denne erklæringen fra tid til annen. Vesentlige endringer vil bli varslet i appen. Den nyeste versjonen er alltid tilgjengelig i appen under Innstillinger.

## 10. Kontakt og klage

- **E-post:** [younas171996@gmail.com](mailto:younas171996@gmail.com)
- **Tilsynsmyndighet:** Datatilsynet, postboks 458 Sentrum, 0105 Oslo — [www.datatilsynet.no](https://www.datatilsynet.no)
