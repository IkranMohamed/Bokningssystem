# Bokningssystem
Detta projektide handlar om att skapa ett bokningssystem där användare kan boka tider för tjänster (exempelvis gympass, frisörer och tandläkartider etc.).
Systemet ska hantera bokningar, visa lediga tider och skicka bekräftelser till användare och administratörer.

## Designmönster: Singleton
Singleton-mönstret för att hantera databasanslutningar. Detta säkerställer att det bara finns en instans av databasanslutningen, vilket förbättrar prestanda och minskar risken för fel.

### Use Case
Namn: Skapa bokning
Aktör: Inloggad användare
Beskrivning: När en användare gör en bokning, hämtas lediga tider från databasen. Singleton garanterar att samma instans används varje gång systemet kommunicerar med databasen.

### User story
Som utvecklare
vill jag att systemet alltid använder samma databasinstans
så att vi slipper prestandaproblem och undviker att flera anslutningar öppnas samtidigt.

# Bakgrund & Syfte
 Syftet är att förenkla bokningsprocessen och minska dubbelbokningar. företag. Eftersom många företag eller tjänsteleverantörer behöver ett digitalt sätt att hantera sina bokningar. 

#  Vision & Mål
Systemet ska effektivisera bokningshantering och minska den manuella administrationen. Det ska vara enkelt att använda för både kunder och administratörer.

# Tydliga mål 
1. Att ge användare möjlighet att avboka, ändra och boka tider online.
2. Systemet ska skicka automatiska bokningsbekräftelsen antingen via mejl eller SMS.
3. Administratörer ska kunna se statistik samt hantera bokningar.
4. Man ska kunna använda sin mobil och enkelt att navigera.

# Intressentkartläggning
Slutanvändare: De som använder systemet för att boka tider. De är den primära målgruppen och systemet ska vara enkelt och smidigt för dem att använda.

Administratörer: Ansvariga för att hantera bokningar, se statistik och eventuellt göra manuella justeringar i systemet.

Företagsägare: Bestämmer hur systemet ska implementeras och vilka funktioner som är viktigast. De har ett affärsperspektiv och vill ha ett system som underlättar verksamheten.

Utvecklare: Bygger och underhåller systemet. De ser till att alla funktioner fungerar och att kraven uppfylls.

Testare: Ansvariga för att kontrollera att systemet fungerar som förväntat och att inga buggar påverkar användarupplevelsen negativt.

# Funktionella krav:
1. Användare ska kunna registrera och logga in på systemet.

2. Användare ska kunna söka efter lediga tider och boka en tjänst.

3. Administratörer ska kunna hantera (lägga till, ändra, ta bort) bokningar.

4. Systemet ska skicka bokningsbekräftelsen till användaren via e-post/SMS.

5. Användare ska kunna avboka en bokad tid.

6. Systemet ska visa en översikt över alla bokningar för administratörer.

7. Systemet ska förhindra dubbelbokningar.

# Icke-funktionella krav:
1. Prestanda: Systemet ska kunna hantera minst 100 samtidiga användare.
2. Säkerhet: Användardata ska vara krypterad och inloggning sker via en säker autentiseringsprocess.
3. Användbarhet: Systemet ska ha en intuitiv design och fungera på både desktop och mobil.
4. Tillgänglighet: Systemet ska vara tillgängligt 24/7 med minimala driftstopp.
5. Skalbarhet: Systemet ska enkelt kunna utökas med fler funktioner i framtiden.

# Prioritering av krav (MoSCoW-metoden)

# MUST (MUST HAVE)
De mest kritiska funktionerna som systemet måste ha för att fungera. Användare ska kunna boka tider, registrera sig och logga in på systemet. Administratörer måste kunna hantera bokningar och se en översikt av dessa.


# SHOULD (SHOULD HAVE)
Funktioner som är viktiga men inte absolut nödvändiga för första versionen. Exempelvis bör systemet ha en sökfunktion för bokningar och möjlighet att skicka notifikationer via SMS och e-post.


# COULD (COULD HAVE)
Funktioner som är trevliga att ha men inte avgörande för systemets grundfunktionalitet. Exempelvis kan användare ges möjlighet att betygsätta tjänster efter genomförd bokning.

# User Stories:
Som användare vill jag kunna söka efter lediga tider så att jag kan boka en tid som passar mig.

Som administratör vill jag kunna se alla bokningar i ett kalenderformat så att jag enkelt kan hantera dem.

Som användare vill jag kunna få en bekräftelse på min bokning så att jag vet att den är registrerad.

Som administratör vill jag kunna avboka en tid åt en kund om det behövs.

Som användare vill jag kunna logga in och se mina bokningar så att jag kan ändra eller avboka vid behov.

# Sammanfattning av bokningssystemet : 
Bokningssystemet ska erbjuda användare möjligheten att registrera sig, logga in och boka tider för olika tjänster.

Systemet ska hantera bokningar, möjliggöra avbokningar och skicka automatiska bekräftelser via e-post eller SMS.

Administratörer ska kunna hantera bokningar, se statistik och få en översikt över alla bokade tider.

Systemet ska vara responsivt, säkert och kunna hantera minst 100 samtidiga användare. Användardata ska krypteras, och autentisering ska ske via en säker process. Systemet ska minimera dubbelbokningar och vara tillgängligt 24/7.




