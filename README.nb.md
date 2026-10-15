# SRAGI® Skills

**Åpne instruksjonsfiler som gir AI-en du allerede bruker, en regenerativ retning.**

SRAGI® står for Systemic Regenerative Artificially Guided Insight. Se [Hva er SRAGI](WHAT-IS-SRAGI.nb.md) for hva det er, hvordan det tar standpunkt og hva det aldri gjør.

[English version](README.md)

## Hva er SRAGI?

SRAGI er et åpent rammeverk for **regenerativ intelligens**. Det er en måte å arbeide med AI på der menneskelig dømmekraft, levende systemer og langsiktige konsekvenser er med i den samme beslutningsprosessen.

SRAGI er ikke en ny AI-modell, og det påstår ikke at en maskin har blitt klok. SRAGI er et sett instruksjoner du gir til en AI du allerede bruker, for eksempel ChatGPT, Claude eller Gemini. Instruksjonene styrer hvordan AI-en svarer. Når SRAGI er aktiv, skal AI-en:

- svare på det du faktisk spør om
- holde fakta, antakelser og usikkerhet fra hverandre, og aldri finne på fakta eller kilder
- la den endelige avgjørelsen være din
- vise skjulte kostnader og hvem som bærer dem
- utfordre svak argumentasjon på en respektfull måte i stedet for å smigre deg
- foreslå ett realistisk neste steg når det er nyttig, i stedet for en stor plan
- unngå å gjøre deg avhengig av den

> **Mennesket setter retningen. AI utvider synsfeltet. Regenerative prinsipper er kompasset.**

SRAGI oppsummeres som **R > 1: gi mer enn du tar.** Et svar skal etterlate mer klarhet, handlekraft og muligheter enn det bruker opp. Det er en designtest, ikke en vitenskapelig formel.

## Dette kan du laste ned

Alle fire profilene har utgivelsesdato 1. oktober 2026.

| Profil | Versjon | Bruksområde |
| --- | --- | --- |
| **SRAGI® Ultra Lite** | 1.0.0 | Den minste profilen, for daglig bruk: refleksjon, læring, skriving, planlegging, kreativitet og lette beslutninger. **Begynn her.** |
| **SRAGI® Lite** | 1.0.0 | En kompakt profil med litt mer struktur: forklaring, prioritering, lett strategi, idéutvikling og regenerativ gjennomgang. |
| **SRAGI® Beliefs** | 4.0.0 | Fri utforskning av tro, mening, spiritualitet, identitet og bevissthet. *Go cosmic. Keep one instrument on reality.* |
| **SRAGI® Core Fullstack** | 4.2.0 | Hele rammeverket i fem komponenter: Activate 2.0.0, AI-BIOS 4.2.0, Core AI-OS 3.2.0, Blueprint Engine 4.2.0 og Twin 3.2.0. |

Ultra Lite, Lite og Beliefs ligger i [`releases/standalones/2026-10-01`](releases/standalones/2026-10-01/). Hver av dem er én `.yaml`-fil med instruksjonene, pluss en `.md`-fil som forklarer dem med enkle ord. Core Fullstack er fem `.yaml`-filer i [`releases/core-fullstack/4.2.0`](releases/core-fullstack/4.2.0/). Vil du ha alt på én gang, velger du **Code → Download ZIP** øverst på siden.

Les [ansvarsfraskrivelsen](#ansvarsfraskrivelse) før du bruker SRAGI.

Profilene er skrevet på engelsk, og AI-en svarer på språket du skriver på. Hver profil står på egne ben og aktiverer ikke de andre. Hver utgivelsesmappe har en README på engelsk. De opprinnelige utgivelsesnotatene på norsk ligger ved siden av som `README.nb.md`. De nevner et internt arkiv og en plugin som ikke er en del av dette repoet.

## Prøv på to minutter

1. Åpne [`SRAGI-Ultra-Lite-1.0.0-EN.yaml`](releases/standalones/2026-10-01/SRAGI-Ultra-Lite-1.0.0-EN.yaml). Klikk **Download raw file**, eller **Copy raw file** for å kopiere hele teksten. Bruk `.yaml`-filen. `.md`-filen er til å lese.
2. Start en ny samtale med AI-en din og legg ved filen. Godtar ikke appen filen, limer du inn den kopierte teksten i stedet. I et prosjekt legger du den inn som prosjektfil, ikke i et kort instruksjonsfelt.
3. Skriv **Activate SRAGI Ultra Lite** i den samme meldingen og send. For Lite skriver du **Activate SRAGI Lite**.
4. AI-en bekrefter kort at profilen er aktiv.
5. **Ta med et ekte spørsmål.** Beskriv situasjonen slik den er: hva du vil endre, hvem som er involvert og hvilke begrensninger som er reelle.

Det er ikke nok å nevne profilen eller legge ved filen til gjennomlesning.

**Beliefs og Core Fullstack** har ingen fast setning. Legg ved filene og si at du vil aktivere SRAGI Beliefs eller SRAGI Core Fullstack. Core Fullstack krever alle de fem `.yaml`-filene i samme samtale. Skriv `SRAGI:STATUS` for å se hvilke komponenter AI-en faktisk har lest inn.

**Den beste testen er en sammenligning.** Still det samme spørsmålet i en ny samtale *uten* SRAGI, og sammenlign svarene.

**Eller bruk en lenke.** Kan AI-en din åpne nettlenker, trenger du ikke laste ned noe. Se [`online/`](online/) (på engelsk).

## Dette bør du se etter

En god SRAGI-samtale skal gjøre deg **sterkere, ikke bare mer imponert.** Vær på vakt når AI-en, med eller uten SRAGI:

- blir skråsikker uten belegg
- er for raskt enig med deg
- finner på kilder eller fakta
- lager et komplisert rammeverk der en enkel handling holder
- oppmuntrer deg til å overlate dømmekraft du bør beholde selv

Skjer dette mens SRAGI er aktiv, vil vi gjerne vite det.

## Fortell oss hvordan det gikk

[Gi tilbakemelding i skjemaet Test feedback](https://github.com/Project2040/sragi-skills/issues/new?template=test-feedback.yml). Det krever en gratis GitHub-konto. Fortell hvilken profil og AI du brukte, hva du spurte om og hva som skjedde. Sakene er offentlige, så ikke ta med personlige eller fortrolige opplysninger. Du kan også sende e-post til [contact@sragi.org](mailto:contact@sragi.org).

Vi leser alle tilbakemeldinger, men kan ikke svare på alt. Pull requests tas ikke imot ennå. Se [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Sjekk en fil

Hver instruksjonsfil (`.yaml`) og følgedokument (`.md`) i `releases/` har en tilhørende `.sha256`-fil. Legg begge i samme mappe og kjør:

```sh
sha256sum -c SRAGI-Ultra-Lite-1.0.0-EN.yaml.sha256          # Linux
shasum -a 256 -c SRAGI-Ultra-Lite-1.0.0-EN.yaml.sha256      # macOS
Get-FileHash SRAGI-Ultra-Lite-1.0.0-EN.yaml                  # Windows PowerShell
```

På Windows sammenligner du verdien som skrives ut, med teksten i `.sha256`-filen. For å sjekke en hel utgivelsesmappe kjører du `sha256sum -c SHA256SUMS` i mappen.

## Lisens

- **De åtte YAML-instruksjonsfilene** er lisensiert under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Du kan dele, endre og bruke dem kommersielt hvis du navngir opphavspersonen, merker endringer og deler bearbeidelser videre under samme lisens. Andre vilkår kan avtales skriftlig. Vil du bygge SRAGI inn i et produkt eller en tjeneste, se [Building with SRAGI](BUILDING-WITH-SRAGI.md) (på engelsk).
- **Følgedokumentasjonen og metadataene** i `releases/` tilhører Neptunia Media AS. Du kan laste dem ned, lese og bruke dem gratis, og dele komplette, uendrede kopier gratis, for eksempel som en del av dette repoet eller ZIP-nedlastingen. Å endre, oversette eller selge dem, eller bygge dem inn i et produkt eller en tjeneste, krever en egen skriftlig avtale. Se [`LICENSE`](LICENSE).

Eksempel på navngivelse: *SRAGI® Ultra Lite 1.0.0, created by Rune Solberg and published by Neptunia Media AS. Licensed under CC BY-SA 4.0. Source: sragi.org*

SRAGI® er et registrert varemerke i Norge som tilhører Neptunia Media AS (reg.nr. 342880). Lisensen gir ingen rett til merket eller til å kalle noe offisielt SRAGI. Se [`LICENSE`](LICENSE).

## Ansvarsfraskrivelse

SRAGI leveres «som det er», gratis og uten noen form for garanti. Så langt loven tillater, er Neptunia Media AS ikke ansvarlig for tap eller skade som følge av bruk av SRAGI eller av svar fra en AI som bruker det.

- **AI-en er fortsatt en AI.** SRAGI styrer hvordan en AI svarer, men kan ikke garantere det. En AI kan overse, misforstå eller bare delvis følge instruksjonene, og den kan fortsatt ta feil. Sjekk alt som er viktig, før du handler på det.
- **Ikke rådgivning.** SRAGI er et eksperimentelt rammeverk for informasjon, refleksjon og beslutningsstøtte. Det er ikke faglig rådgivning eller sertifisering. Det erstatter heller ikke medisinske, juridiske, økonomiske eller psykologiske vurderinger, eller din egen dømmekraft.
- **I en krise: kontakt mennesker, ikke AI.** Er du eller noen andre i fare, kontakter du nødtjenestene der du er. I Norge ringer du 113 (medisinsk nødhjelp) eller 112 (politi).
- **Vilkårene til AI-tjenesten gjelder.** Samtalene dine behandles av AI-tjenesten du bruker, etter tjenestens vilkår og personvernerklæring.
- **Ingen tilknytning.** ChatGPT, Claude, Gemini og andre produktnavn er varemerker som tilhører sine eiere. SRAGI har ingen tilknytning til dem og er ikke godkjent av dem.

Ansvarsfraskrivelsen står også i [`DISCLAIMER`](DISCLAIMER), på engelsk og norsk.

## Tidligere materiale

Materiale fra 2025 (BIOS 2.22 og Core AI-OS 1.0) ligger uendret i [`archive/2025-12`](archive/2025-12/).

## Kontakt

Generelt: [contact@sragi.org](mailto:contact@sragi.org) · Kommersiell lisens: [commercial@sragi.org](mailto:commercial@sragi.org) · [sragi.org](https://sragi.org)

Rune Solberg, Neptunia Media AS (org.nr. 932 481 375), Norge.
