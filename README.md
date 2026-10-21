# Crypto Hack – Economie klas 2 basis & kader

Een zelfstandig speelbaar klassenspel voor Chromebooks, gebaseerd op de aangeleverde leerstof hoofdstuk 1 en 2 (paragrafen 1.1 t/m 2.4).

## Inhoud
- 50 meerkeuzevragen (vier antwoorden), in willekeurige volgorde; na 50 vragen begint een nieuwe geschudde ronde.
- Alleen eenvoudige optel- en aftreksommen, bijvoorbeeld saldo. Geen procenten, gemiddelden, verhoudingstabellen, vermenigvuldigen of delen.
- Speeltijd instelbaar van 1 tot 15 minuten. Leerlingen spelen op eigen tempo.
- Bij een fout antwoord 7 seconden freeze en geen cadeau.
- Bij een goed antwoord +500 crypto en keuze uit vier gesloten vakjes: hack, +1000, dubbel of driedubbel crypto.
- Bij hacken wordt willekeurig een andere leerling toegewezen; iedere leerling heeft drie unieke codes.
- Leerlingen kiezen hun voornaam en een dierenemoji.

## Online zetten met GitHub en Render
1. Maak een **nieuwe GitHub-repository** voor deze klas-2-versie. Zet de uitgepakte bestanden in de hoofdmap: `server.js`, `package.json`, `questions.json`, en de map `public` met `index.html`.
2. Maak in Render een **nieuwe Web Service** met runtime **Node**, build command `npm install` en start command `npm start`.
3. Deel de nieuwe Render-link met leerlingen. De docent maakt een gamecode, leerlingen vullen code, voornaam en dier in.

**Gebruik niet dezelfde Render-service/repository als de vorige klasversie als je beide spellen apart wilt houden.**

## Testadvies
Test eerst met twee browsers/apparaten: aanmelden, docentstart, goed/fout antwoord, freeze, cadeau, hack en einde speeltijd.

## Technisch
Node.js + Express. Spelkamers worden alleen in servergeheugen opgeslagen en verdwijnen bij een herstart of slaapstand van de server. Voor een volledige les: start tijdig op en test vooraf.
