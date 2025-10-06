# flus_case
Svar på flus sine case oppgaver

## Oppgave 1
- Tegn eller beskriv steg-for-steg hvordan brukeren skal bevege seg i appen (onboarding → småjobber → CV → oppdrag)
- Forklar hvorfor dere har valgt akkurat denne flyten.

Først må brukeren opprette en konto, hvor man oppgir informasjon om hvem man er. Dette gjør det mulig for Flus å vite hvem som ønsker å bruke applikasjonen, samt koble data til riktig bruker. Brukeren kan opprette konto via Vipps, noe som sikrer at det er en ekte person med en gyldig Vipps-konto, i tråd med Vipps sine strenge krav.

Etter at kontoen er opprettet, kan brukeren se tilgjengelige småjobber, legge ut egne småjobber eller deltidsstillinger, og bygge en CV direkte i applikasjonen. CV-en kan brukes for å få oppdrag gjennom plattformen.

Vi har valgt denne flyten fordi den ligner på løsninger i flere andre apper, noe som gjør det enklere for brukeren å forstå og bruke applikasjonen. 

## Oppgave 2
- Lag en enkel skisse/wireframe for minst 3 skjermbilder (f.eks. onboarding, småjobber-oversikt, CV-bygger)
- Bruk gjerne papir, Figma eller annet verktøy.

## Oppgave 3
- Beskriv hvilke teknologier dere ville valgt (frontend, backend, database).
Jeg ville brukt React på frontend fordi det er mye brukt i utviklingsmiljøer og gjør det enkelt å lage komponenter som kan gjenbrukes. Det gjør koden mer ryddig og gjør det lettere å utvikle nye funksjoner uten å måtte skrive alt fra bunnen av.

På backend ville jeg brukt Java fordi det er open source, har mange ferdige biblioteker, og fungerer godt for apper som skal håndtere mye logikk og trafikk. Java er også stabilt og mye brukt i bransjen, noe som gjør det lettere å finne hjelp og ressurser når man trenger det.

Til lagring og behandling av data ville jeg valgt PostgreSQL fordi den er gratis å bruke, pålitelig og har mange funksjoner som gjør det enkelt å jobbe med databaser på en sikker og effektiv måte. Den støtter komplekse spørringer, transaksjoner og gir god kontroll over dataene.

For å få frontend og backend til å kommunisere, ville jeg brukt RESTful API-er. Dette gjør det enkelt å sende og hente data mellom de ulike delene av applikasjonen på en standardisert måte. Samlet sett gir denne løsningen en struktur som er fleksibel, oversiktlig og lett å bygge videre på når man utvikler flere funksjoner eller skalerer applikasjonen.

- Hvordan ville dere sørget for at data lagres sikkert (GDPR, personvern)?
Jeg tolket spørsmålet som at dere lurer på hvordan GDPR skal følges.

Jeg ville sørget for å ha full kontroll over all persondata som brukes i applikasjonen, og ha tydelige rutiner for å kunne slette data dersom det blir nødvendig. All data skal behandles på en trygg og sikker måte, slik at GDPR respekteres i alle ledd. Brukeren må også gi samtykke til at dataene deres behandles av oss, og vi skal tydelig informere om hva dataene brukes til.

I forhold til lagring og sikring ville jeg benyttet godt etablerte løsninger og metoder, som for eksempel kryptering av data i databasen, for å sikre at informasjonen behandles på en trygg og sikker måte.

## Oppgave 4 (Frivillig) 
- Hvordan ville dere lagt opp en Gründer-modul for en ungdom som ønsker å starte ENK eller AS? Hvilke steg ville dere lagt inn, og hvordan ville dere gjort det forståelig?
