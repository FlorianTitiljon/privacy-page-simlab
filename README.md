# Privacybeleid VIVES SimLab

**Laatst bijgewerkt:** 14 november 2025

## 1. Introductie

Welkom bij VIVES SimLab. Wij respecteren uw privacy en zetten ons in voor de bescherming van uw persoonlijke gegevens. Dit privacybeleid beschrijft hoe wij omgaan met uw informatie wanneer u onze mobiele applicatie gebruikt.

VIVES SimLab is een educatieve applicatie ontwikkeld voor het beheren en monitoren van IoT medische apparaten zoals bladderscans en glucometers.

## 2. Informatie die wij verzamelen

### 2.1 Apparaatgegevens
Wij verzamelen de volgende informatie die u invoert via de app:
- **Bladderscan metingen**: Volume metingen (in ml) die u handmatig invoert
- **Glucometer metingen**: Glucose waarden (in mg/dL) die u handmatig invoert
- **Apparaat selectie**: Welk apparaat (Device 1, 2, of 3) u gebruikt

### 2.2 App-instellingen
De app slaat lokaal de volgende instellingen op:
- **Firebase configuratie**: Database URL, API key, en project instellingen
- **Notificatie voorkeuren**: Of u push notificaties wilt ontvangen

### 2.3 Push notificatie tokens
Wanneer u push notificaties inschakelt, wordt er een unieke notificatie token gegenereerd en verzonden naar Azure Notification Hub om u berichten te kunnen sturen.

### 2.4 Technische gegevens
- **IP-adres**: Voor communicatie met Firebase en Azure services
- **Tijdstempels**: Wanneer u metingen verstuurt

## 3. Hoe wij uw informatie gebruiken

Wij gebruiken uw gegevens voor de volgende doeleinden:

### 3.1 Kernfunctionaliteit
- Het versturen van uw apparaatmetingen naar Firebase Realtime Database
- Het weergeven van uw instellingen en voorkeuren
- Het verzenden van push notificaties (indien ingeschakeld)

### 3.2 Educatieve doeleinden
Alle gegevens worden gebruikt binnen een educatieve context voor het leren werken met IoT medische apparaten.

### 3.3 Verbetering van de app
Wij kunnen geanonimiseerde gegevens gebruiken om de app te verbeteren en fouten op te lossen.

## 4. Opslag van gegevens

### 4.1 Lokale opslag (op uw apparaat)
De volgende gegevens worden **alleen op uw apparaat** opgeslagen via IndexedDB:
- Firebase instellingen (database URL, API key, project ID)
- Notificatie voorkeuren
- App configuratie

**Deze gegevens worden NIET verzonden naar onze servers en blijven privé op uw apparaat.**

### 4.2 Firebase Realtime Database
Apparaatmetingen die u verstuurt worden opgeslagen in Firebase Realtime Database:
- Bladderscan volumes per apparaat
- Glucometer waarden per apparaat
- Tijdstempels van metingen

**Beveiliging:** Firebase data is beveiligd met authenticatie en toegangsregels.

### 4.3 Azure Notification Hub
Wanneer u notificaties inschakelt:
- Uw notificatie token wordt opgeslagen in Azure Notification Hub
- Een unieke installatie-ID wordt gegenereerd
- Deze gegevens worden alleen gebruikt om u push berichten te sturen

## 5. Delen van gegevens met derden

### 5.1 Serviceproviders
Wij delen uw gegevens met de volgende serviceproviders:

**Google Firebase** (Firebase Realtime Database)
- **Doel**: Opslag van apparaatmetingen
- **Locatie**: Servers binnen de EU of VS (afhankelijk van uw Firebase configuratie)
- **Privacybeleid**: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

**Microsoft Azure** (Azure Notification Hub)
- **Doel**: Verzenden van push notificaties
- **Locatie**: Azure datacenters (afhankelijk van configuratie)
- **Privacybeleid**: [https://privacy.microsoft.com/](https://privacy.microsoft.com/)

### 5.2 Geen verkoop van gegevens
Wij verkopen, verhuren of verhandelen NOOIT uw persoonlijke gegevens aan derden.

### 5.3 Wettelijke verplichting
Wij kunnen uw gegevens delen als dit wettelijk verplicht is of om:
- Te voldoen aan een gerechtelijk bevel of juridisch proces
- Onze rechten, eigendom of veiligheid te beschermen
- Fraude of beveiligingsincidenten te onderzoeken

## 6. Beveiliging van uw gegevens

Wij nemen de beveiliging van uw gegevens serieus en implementeren passende beveiligingsmaatregelen:

### 6.1 Technische maatregelen
- **HTTPS versleuteling**: Alle communicatie met Firebase en Azure gebruikt SSL/TLS encryptie
- **Firebase Security Rules**: Toegang tot de database is beveiligd met authenticatieregels
- **Lokale encryptie**: App-instellingen worden veilig opgeslagen in IndexedDB

### 6.2 Toegangscontrole
- Alleen geautoriseerde systemen kunnen toegang krijgen tot Firebase en Azure services
- Notificatie tokens zijn uniek en kunnen niet gebruikt worden om u te identificeren

### 6.3 Geen garantie
Hoewel wij alle redelijke maatregelen nemen, kunnen wij geen absolute beveiliging garanderen. Gebruik de app op eigen risico.

## 7. Uw rechten (AVG/GDPR)

Als gebruiker heeft u de volgende rechten onder de Algemene Verordening Gegevensbescherming (AVG):

### 7.1 Recht op inzage
U heeft het recht om te weten welke gegevens wij over u hebben opgeslagen.

### 7.2 Recht op correctie
U kunt uw gegevens te allen tijde aanpassen via de app-instellingen.

### 7.3 Recht op verwijdering ("recht om vergeten te worden")
U kunt uw gegevens op elk moment verwijderen:
- **Lokale gegevens**: De-installeer de app of wis de app-data in uw Android instellingen
- **Firebase data**: Contacteer ons om uw data uit de database te verwijderen
- **Notificatie tokens**: Schakel notificaties uit in de app-instellingen

### 7.4 Recht op dataportabiliteit
U kunt een kopie van uw gegevens opvragen in een leesbaar formaat.

### 7.5 Recht op bezwaar
U kunt bezwaar maken tegen bepaalde vormen van gegevensverwerking.

### 7.6 Rechten uitoefenen
Om deze rechten uit te oefenen, neem contact met ons op via de contactgegevens onderaan dit document.

## 8. Kinderen en privacy

Onze app is bedoeld voor educatieve doeleinden en kan door studenten gebruikt worden. Wij verzamelen niet bewust persoonlijke gegevens van kinderen onder de 13 jaar zonder toestemming van ouders of voogden.

Als u een ouder of voogd bent en ontdekt dat uw kind persoonlijke gegevens heeft verstrekt, neem dan contact met ons op.

## 9. Internationale gegevensoverdracht

Uw gegevens kunnen worden overgedragen naar en opgeslagen op servers buiten uw land of regio:
- **Firebase**: Kan servers in de VS of EU gebruiken
- **Azure**: Wereldwijde datacenters (afhankelijk van configuratie)

Wij zorgen ervoor dat passende beveiligingsmaatregelen worden genomen bij internationale overdrachten, in overeenstemming met de AVG.

## 10. Cookies en tracking

### 10.1 Geen cookies
Onze app gebruikt **geen cookies** omdat het een native mobiele applicatie is.

### 10.2 Geen analytics
Wij gebruiken momenteel **geen analytics** of tracking tools (zoals Google Analytics).

### 10.3 Push notificaties
Push notificaties worden alleen verzonden als u deze expliciet inschakelt in de app-instellingen.

## 11. Wijzigingen in dit privacybeleid

Wij kunnen dit privacybeleid van tijd tot tijd bijwerken. Wijzigingen worden van kracht zodra het bijgewerkte beleid in de app wordt gepubliceerd.

**Belangrijke wijzigingen** zullen worden gecommuniceerd via:
- Een notificatie in de app
- Een update van de "Laatst bijgewerkt" datum bovenaan dit document

Wij adviseren u om dit privacybeleid regelmatig te controleren op wijzigingen.

## 12. Bewaartermijn

### 12.1 Lokale gegevens
Blijven op uw apparaat totdat u:
- De app verwijdert
- De app-data wist
- Handmatig instellingen verwijdert

### 12.2 Firebase data
Blijft in de database totdat:
- U ons vraagt deze te verwijderen
- Het Firebase project wordt verwijderd
- Automatische cleanup regels (indien geconfigureerd)

### 12.3 Notificatie tokens
Blijven actief totdat:
- U notificaties uitschakelt
- De app wordt verwijderd
- Het token verloopt (automatisch na lange inactiviteit)

## 14. Toestemming

Door VIVES SimLab te gebruiken, stemt u in met dit privacybeleid en de verwerking van uw gegevens zoals hierin beschreven.

Als u niet akkoord gaat met dit beleid, gelieve de app niet te gebruiken.

---

**Versie:** 1.0  
**Datum:** 14 november 2025  
**Taal:** Nederlands

*Dit privacybeleid is opgesteld in overeenstemming met de Algemene Verordening Gegevensbescherming (AVG/GDPR) en de Belgische privacywetgeving.*
