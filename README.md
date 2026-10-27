# VFC Teamplanner

Webapp voor de jeugdteams van VFC Vlaardingen. Een trainer voert zijn team één keer in; de club activeert het team, maakt eerlijke roosters (training begeleiden, shirts wassen, ballen, rijden, bardienst, siroop) en het teamdashboard toont uitslagen, stand, programma, topscorers, teamtaken en het wisselschema.

- Inloggen met een e-maillink (Firebase Authentication), geen wachtwoord.
- Gegevens in Firestore (europe-west4). De toegang regelt `firestore.rules`: een trainer ziet alleen zijn eigen team, alleen de clubbeheerder ziet alles.
- De Firebase-configuratie in `index.html` is bedoeld om openbaar te zijn; de beveiliging zit in de regels.

Alles staat in één bestand: `index.html`.
