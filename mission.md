
### 12 januari

Hej David!
God fortsättning på det nya året, hoppas att allt är väl med dig. Läste nyss med stor behållning din artikel på skolappar.nu om CAS-appar. Pedagogiskt och grundligt!

Vi har under en tid funderat på vilken typ av matteverktyg vi skulle kunna ha i våra interaktiva böcker. Som du vet sedan tidigare är våra interaktiva böcker webbaserade, responsiva och plattformsoberoende (funkar åtminstone för iOS, Win, Mac och Android). Vi skulle vilja ha t.ex. kalkylator, grafritare, möjlighet att skriva matematisk text, samt ev. CAS-verktyg. För att ta reda på vad som finns redan, och vad vi skulle behöva utveckla själva, behövs någon som är expert på området. Då tänker jag förstås på dig!

Skulle du ha tid och lust att på uppdrag av oss göra en sådan undersökning? Vi skulle i så fall behöva träffas ett par timmar för att speca uppdraget. Hör av dig så stämmer vi möte, om du vill och kan.

Hälsningar
Marcus Ander


### 9 februari

Hej David!
Så gick ett par veckor, utan att jag återkom till dig. Beklagar min försummelse. 

Här är lite tankar för dig att jobba vidare med. Vi vill alltså att du sonderar marknaden (kod, färdiga tjänster eller produkter) efter lite olika matteverktyg som vi vill kunna implementera i vår plattform för interaktiva böcker. Detta för att förstå om det är enkelt eller svårt, om vi behöver köpa in något, be någon programmera något eller om våra egna utvecklare kan implementera färdig kod.

De olika behoven vi har är
Kalkylator. Enkel, dock med rätt prioriteringsregler, och även en mer avancerad funktionsräknare (brukar vara två lägen i samma applikation). Denna applikation ska finnas med i menyn "Verktyg" och ska kunna "sväva fritt" medan jag räknar i boken. Gärna med möjligheten att spara historik över gjorda beräkningar, ungefär som i Desmos.
Grafritare. Till en början räcker det med den funktionalitet som finns i Desmos, dvs. att kunna rita, zooma in/ut, hitta intersection, zero, min/max etc.
Statistik-motor, dvs. tabell med diagram och enkel analys (detta är inte prio jämfört med de två föregående, men kan vara värt att undersöka)
Editor för att skriva MathML online, både med knappar och kortkommandon. Förutom i e-Math, har jag sett att mathspace.co.uk använder sig av en enkel editor (säkerligen Mathquill skulle jag tro). Dessutom såg jag att de kommande PISA-testerna kommer att göras med dator, där en enkel matteeditor kommer att ingå.
Enkel CAS-motor, dels för bokstavsuttryck, men också för potenser och annat som du nämnde.
När man kan skriva matte, och rita grafer, skulle man förstås vilja kunna spara ett resultat av en gjord redovisning, ungefär som i e-Math, där text, matteuttryck, graf, och enkla ritade figurer, kunde sparas som en komplett redovisning (tänk högstadium och Gy i första hand).
Kommer du på mer verktyg och features som du tror skulle kunna vara relevanta för högstadie- och gymnasieelever?

Allt detta ska kunna fungera i vår nuvarande plattform, med följande systemkrav hos användaren: https://www.gleerups.se/kontakta-oss/tekniska_krav/tekniska_krav_for_interaktiva_bocker-och-webbar

"Skriva matte-funktionen" skulle kunna bli en egen applikation, men kanske också kunna användas i QuestBox som är vår motor för interaktiva övningar. Om du behöver veta mer om den, eller om annan teknik i vår plattform, hör av dig till mig. Har du kvar inloggningar till böckerna?

Återkom när du läst detta, och ge ett estimat på hur lång tid du kan behöva i en första vända, så får du ok för att sätta igång. 
Marcus Ander



### 3 mars

2 nya spår

...apropå CAS och digitala verktyg, som du kanske redan känner till.
Våra danska kollegor Systime i Århus har sedan en tid arbetat med en spansk CAS-motor, som jag just nu glömt namnet på. Här är deras första färdiga produkt. Säg till om du behöver mer info. Vi kan säkert få full access till materialet om det skulle behövas. http://cas.systime.dk/
Idag var jag i Köpenhamn på en dansk skolmässa, och pratade då med skoledu.dk som gjort alla geometri- och algebra-övningar genom GeoGebras API. Pratade i förra veckan med ett tyskt förlag som hade gjort detsamma. Så kanske är GeoGebra ett lika intressant spår som Desmos?
Hörs!
Marcus Ander



### 11 mars

Hej!
Du tänker säkert för mycket, och det är bra. Det försöker vi göra också. Alltså på helheten, dit vi vill komma. Såklart, även i helheten kommer vi ha behov av befintlig (eller egenutvecklad) teknik för att kunna skriva bråk, rita en graf, göra numeriska beräkningar etc, oavsett applikation. Senare kommer man förstås till frågor om vilka vägar man ska gå.

Utöver din rapport om delarna, tar jag förstås gärna del av dina funderingar kring helheten, om LMS-vägval m.m. Även efter att rapporten är klar kan vi förstås ha en fortsatt dialog, det dröjer nog ett tag innan vi är i hamn med allt!

Helt rätt att Danmark och Sverige (t.ex.) skiljer sig en del åt, bl.a. när det gäller användandet av CAS-verktyg. Men också i marknadens mognad för digitala läromedel i allmänhet. Danska staten har pyntat in 500 MDKK under en femårsperiod för att stimulera användandet av digitala verktyg i skolan. Köper du digitala läromedel för 20 000 kr betalar du själv 10 000 kr, resten betalar staten. I samband med detta har staten satt upp kriterier som måste vara uppfyllda för att läromedlet (eller lms:en, eller vadsomhelst) ska kunna subventioneras. Det har lett till en viss uppstramning och styrning när det gäller funktioner i plattformar och läromedel. Mest bra tror jag, men också en del som inte har varit helt styrt utifrån marknadens egentliga behov, utan mer utifrån tänkta behov.

Ska fixa en Questboxinloggning till dig. Återkommer!

Hälsningar Marcus
