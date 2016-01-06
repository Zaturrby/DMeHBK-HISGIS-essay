
## Methodologie 

### Kritiek

#### Data

##### Selectie 

{ Data is Capta }
{ Selectiecriteria en beschikbaarheid } 
{ Autoriteit }
{ C.A.R.S }
{ Gezond verstand }

Er zijn uiteraard ook specifieke kaders waarmee digitale gereedschappen moeten worden gemeten. Allereerst kan er terechte kritiek geuit worden op met welke eenheden de samenleving beschreven wordt. In tegenstelling tot traditionele bronnen die vaak zelf al rijk en divers zijn wordt de samenleving met data vaak aan de hand van enkele eenheiden beschreven. Data is geen gegeven, maar zij is genomen van de werkelijkheid: zij is ‘capta’.[^1]Deze eenheden moeten goed gewogen worden op hun waarde. Een goed voorbeeld van een enkele eenheid en het perspectief dat het biedt is de visualisatie van kunstenaarslevens in het blad Nature.[^2]

Daarnaast is een gezond verstand onontbeerlijk. Een kritische houding waarin je geloofwaardigheid, nauwkeurigheid en redelijkheid afweegt hoort bij al het geesteswetenschappelijke werk.[^3]

##### Opschoning

{ Dirty Data }
{ Harmonisatie en linkages }
{ Meta-data en ontologiën }
{ Geladenheid meta-data en ontologiën }

Het is duidelijk en vruchtbaar gebleken om data te digitaliseren en van meta-data te voorzien, het liefst met ontologiën. 

Dit probleem is goed zichtbaar in de rijkheid van de specifieke gebieden van de Digital Humanities. De historische geografische informatie wetenschappen zijn hier een van. De rijkheid van dit vakgebied wordt duidelijk wanneer je NASA-documentatie moet lezen om een relatief kleine taak uit te voeren. Er zitten oneindig veel lagen in een rijke historische kaart. Het begint bij de data, waarbij beschikbaarheid, harmonisatie en onzekerheid een grote rol spelen. Vervolgens moet de data gevisualiseerd worden met oog op de consequenties die dat heeft voor de lezer. Als laatste moet exploratie en verantwoord gebruik mogelijk gemaakt worden door interfaces. Aan elk van deze lagen kan eindeloos veel tijd worden besteed.

##### Hergebruik

{ Scheiding Data van Implementatie }
{ Hergebruik vanuit data perspectief: }
{ Beschikbaarheid }
{ Open Data }
{ API’s } 

 Deze scheiding tussen data en implementatie moet gewaarborgd blijven. Dit is een belangrijk criterium voor een reproduceerbaarheid van het onderzoek. Een applicatie mag niet in de kantlijn data veranderen of toevoegen en dat sluipt er heel snel in. Daarnaast is het hoogstwaarschijnlijk dat de implementatie in de toekomst niet meer werkt. De data heeft daarentegen een veel hogere levensspan. Open data is hierbij wel een belangrijke voorwaarde; van zowel gestructureerde data als teksten en afbeeldingen zoals kaarten en kunstwerken. De volledige data moet ten alle tijden los van de applicatie beschikbaar zijn. 

#### Implementatie

##### Transformaties 

{ Data transformaties }
{ Hergebruik vanuit implementatie perspectief: }
{ Reproduceerbaarheid: }
{ Scripts vs GUI }
{ Vrijheid van expressie }
{ Iedere knop is al geïnterpreteerd }
{ tools met onderwerp vs tools zonder onderwerp }
{ Progammeervaardigheden vs. GUI’s }
{ Beschikbaarheid en stabiliteit tools }

Daarnaast moeten de transformaties en toevoegingen aan data toegankelijk en reproduceerbaar zijn. Vastlegging van deze stappen in scripts is onontbeerlijk, beschrijvingen van de bediening van interfaces belemmeren reproductie. Het doel van interfaces is om stappen aan het oog van de gebruiker te onttrekken en die stappen zijn mogelijk waardebetrokkene. Het moet duidelijk zijn wat er onder de motorkap gebeurd en dat is bij interfaces vaak niet herleidbaar.

Tools waarin geen onderwerp besloten ligt zijn daarom betekenisvoller. Wij zullen als geesteswetenschappers niet zulke gereedschappen moeten willen ontwerpen. De computerwetenschappen  en het bedrijfsleven hebben dit grotendeels voor ons gedaan. Maar wij moeten ze wel kunnen gebruiken, vooral ook als ze geen grafische interface hebben. De vrijheid van expressie is vele malen groter in programmeertalen dan in de beste GUI. Maar daarvoor zijn technische vaardigheden wel noodzakelijk. Veel van de programma’s zijn bewust zonder onderwerp ontworpen en gemaakt voor hergebruik. Ze worden geoptimaliseerd en onderhouden door bedrijven met commerciële doelstellingen. De taak voor geesteswetenschappers is om deze multidimensionale tools te voorzien van rijkere narratieven waarin meerdere stemmen hun uiting in vinden en er ruimte is voor ambiguïteit en onzekerheid.

##### Design en User Experience

{ Exploratieve mogelijkheid vs Begeleiding }

Kaarten zijn daarnaast sterk geabstraheerd van de werkelijkheid. De metrokaart van Londen is hier een goed voorbeeld van.[^4] De beslissing om bepaalde elementen dikker of kleurrijker te maken heeft effect. Het design heeft effect op lezen, zowel visueel als in User Experience Design (UX-Design). Schaalknoppen zijn hier een goed voorbeeld van. Schaal en detail hebben grote invloed op de betekenis. Technisch is elke vergroting mogelijk, maar als het mogelijk is om voorbij het detail van de data in te zoomen dan ontstaat er een grote leegte. Voor gebruikers die het bereik van de data niet kennen kan deze leegte beeldbepalend zijn.

##### Voorbeelden van tools zonder onderwerp voor de Spatial Humanities

{ Mapnik }
{ GDAL }
{ PostgreSQL, PostGIS, pgRouting, PL/pgSQL }		
{ Leaflet }
{ D3 }
{ HTML, CSS, Javascript } 
{ Datastructuren }
{ Shell Scripting }

Voor kaarten zijn er grafische tools zoals Quantum GIS of de kaartlagen generator Tilemill, maar juist de tools zonder interfaces zoals Leaflet, PostGIS en D3 zijn van groot belang. Leaflet is een online mapping tool die het mogelijk maakt geografische data in de browser te visualiseren. PostGIS is een collectie van geografische formules voor de database PostgreSQL, waarmee ruimtelijke analyse algoritmisch kan worden uitgevoerd. Het heeft tevens een implementatie voor routing met pgRouting. Daarnaast is het algemenere D3 als visualisatie tool niet te vergeten. Eventueel zijn onderliggende programma’s zoals Mapnik of GDAL interessant als een interface zoals Tilemill niet voldoende mogelijkheden biedt. Hiervoor is wel aardig wat voorkennis of een stevige portie ingenuïteit gewenst, maar dat is uiteindelijk onontkoombaar. Postgis veronderstelt kennis van SQL of PL/pgSQL en Leaflet en D3 van HTML, CSS en Javascript. Een beetje shell scripting, versie controle, en kennis van datastructuren is tevens gewenst omdat geografische varianten daarop door bouwen.

##### Voorbeelden van tools met onderwerp voor de Spatial Humanities

{ ErfGeo: Toponiemendata }
{ Geotagging }
{ Digital Atlas o/t Roman Empire: Basiskaarten } 
{ Georeferencing }
{ Vectorising }

Specifiek voor historische geografie zijn toponiemen-data en  basiskaarten per tijdperiode zeer wenselijk. Onderzoek naar toponiemen kan een grote bijdrage leven aan de koppeling tussen teksten en kaarten. In een zekere zin wordt hier een ontologie van hedendaagse plaatsnamen toegepast op historische: een alternatieve vorm van distant reading.[^5] Het ErfGeo project is een mooi voorbeeld hiervoor.[^6] Basiskaarten zijn een ander opnieuw bruikbaar fenomeen. De selectie of constructie van correcte geografie en bebouwing kost veel tijd; terwijl een onderzoeker juist een abstracter verhaal binnen het kader van een tijd wil vertellen. Het georefereren van oude kaarten is een mooi begin, maar idealiter worden deze kaarten gevectoriseerd zodat ze algoritmisch vergelijkbaar worden. Binnen deze data kan een onderzoeker dan een abstracter narratief opzetten. De Romeinse kaart van Pelagius project is hier een goed voorbeeld van.[^7] In vergelijking met Orbis wordt ook al zichtbaar dat in deze kaarten een nieuw consensus gevonden moet worden. De kaart van Orbis verschilt namelijk aanzienlijk van Pelagius door de verschillende doelstellingen.[^8] Hoewel de kaartlagen een interessante opnieuw bruikbare tussenstap zijn, zijn ze waardebetrokken en ook hier moet de construerende data altijd beschikbaar zijn.

##### Voorwaarden voor hergebruik

{ Documentatie }
{ Optimalisatie }
{ Wrap in tests }
{ Toolbuilding }
{ Versiecontrole }
{ Git, SVN, Mercurial } 
{ Archivering } 

Als laatste is het gebruik van gesystematiseerde versie controle van belang. Een onderzoek is gegenereerd op een bepaalde versie van een kaart of tool. De scripts van die versie moeten worden gebruikt ter beoordeling, latere versies kunnen bijvoorbeeld scripts verwijderd hebben omdat de doelstelling van de interface is veranderd. De tool Git is hier een goed voorbeeld voor.[^9]

Er zijn wel mogelijkheden tot hergebruik van sommige tools met een onderwerp daarin, maar er moet zorgvuldig afgewogen worden wat opnieuw bruikbaar is. 

#### Wetenschappelijk 

##### Doelstelling en bereik

{ Deep Map }

Een kaart is altijd een gesloten systeem waarin de vragen, waarden, middelen en vaardigheden van de betrokken onderzoekers uitdrukking in vind. Een “deep map” met vrije exploratie is altijd hierdoor begrenst.[^10] Het is hierdoor twijfelachtig of er opnieuw bruikbare humanistische digitale tools gecreëerd kunnen worden waarin een onderwerp besloten ligt. De waardebetrokkenheid van de onderwerpen en de adaptatie-problemen inherent aan digitale producten maken hergebruik van kaarten, tools en interfaces problematisch. Iedere knop in een tool is bewust neergezet en in grote mate geïnterpreteerd door de ontwerpende onderzoeker. Archivering is daarnaast ook nog een groot probleem. Er zijn eindeloos veel implementaties mogelijk van rijke data en deze zullen niet allemaal onderhouden kunnen worden. 

##### Kaartenkritiek en traditionele ruimtelijke interpretaties

{ Spatial Humanities }
{ Beeldvorming }
{ Namen en postkolonialisme }

Voor kaarten zijn er bovendien domein gerelateerde problemen. Projecties en oriëntatie van kaarten bepalen de beeldvorming enorm. Zoals … liet zien met Africa en … met India in vergelijking tot Europa.[^11][^12] Daarnaast zijn kaarten en taal verweven, in welke taal zet je plaatsnamen neer: Spreken we van Batavia of Jakarta? De keuze heeft een performatief effect en we moeten hierbij waken voor post-kolonialisme. 

##### Hergebruik

{ Onzekerheid, ambiguïteit }

##### Traditionele kritieken: anachronismen

{ Anachronisme }

Daarnaast geven GIS-tools ons per definitie een anachronistisch perspectief op de tijd. Er is een illusie van grip op een wereld die in werkelijkheid ver van ons af staat met een perspectief dat in de tijd zelf niet beschikbaar was.

### Meta-Kritiek

#### Proces

{ Data-driven onderzoek vs Question-driven }
{ Thinking through making }
{ Consensusvorming } 
{ Prototyping }

#### Digitaal vs Traditioneel

{ Toevoeging statistiek, visualisatie en interfaces }
{ Tools en patronen vs. Narratief }
{ Visualisatie vs beschrijving -\> Taal }
{ Voorbeeld }
{ Architectuur }

Het uiteindelijke doel van een onderzoek moet uiteindelijk echter niet een visualisatie of interface zijn. Dit wordt vaak geopperd doordat het proces zo aanzienlijk verschilt in vergelijking met de talige traditionele methodologieën. Het is intensiever en collectiever. Maar het achterliggende probleem heeft veel meer te maken met het veronderstelde kennisdoel van de geesteswetenschap. Is het een positivistisch doel in het vinden van patronen of hebben de geesteswetenschappen een meer romantisch doel in het verrijken en diversificeren van de samenleving? Het onderzoek wordt in de traditionele methoden vaak ingestoken met een onderzoeksvraag. Bij de digitale methoden is het startpunt intuïtief de bron of data. Het reflexieve proces tussen bron en onderzoeker dat er is bij ieder type onderzoek is wordt duidelijk gewonnen door de bron bij digitale methoden. De nadruk ligt daardoor bij voorbaat al op patronen. Terwijl het in de traditionele methoden meer beginnen bij de vraag en maatschappijkritische representaties die daarmee worden gecreëerd. 

Het is belangrijk om te realiseren dat ondanks de moeite die in digitale methoden gaan zitten het eindresultaat uiteindelijk onder dezelfde voorwaarden gewogen moet worden. Visualisaties en interfaces zijn slechts een tussenstap tussen de bron of data en de onderzoekstekst. Als we bijvoorbeeld willen uitzoeken wie of wat het meest bepalend is geweest voor de Amsterdamse architectuur in de 16e eeuw is het zeer voordelig dat we een kaart van Amsterdam omstreeks 1500 en 1600 op het scherm tevoorschijn kunnen halen, en die met elkaar kunnen vergelijken. Het liefst algoritmisch om ons oog al te leiden naar de verschillen. Vervolgens moet de technologie losgelaten worden en de disciplinaire bril opgezet worden. In de vergelijking zijn redeneringen van agency en ongelijkheden mogelijk zoals sociaal-economische, feministische of post-kolonialistische. Eveneens perspectieven zoals het semiotische zijn erbij gediend, want de veranderingen in de objecten zijn symptomen van de contemporaine discussie en betekenis.[^13] Dit narratief, deze tekst, is het uiteindelijke onderzoeksresultaat, niet de visualisatie of interface.

#### Kennisdoelen

{ Maatschappelijke impact vs Geesteswetenschappelijke }
{ Maatschappelijk relevante vaardigheden vs Maatschappijkritische theorieën }
{ Investering in onderwijs en bildung }
{ Maatschappelijke impact betaald investering: Haalbaarheid }
{ Hybriditeit }
{ Stoppen met schrijven beginnen met doen }

Digitale geesteswetenschappen worden vaak gepositioneerd als anders dan de traditionele geesteswetenschappen. Niets is minder waar: Een getal of visualisatie zonder narratief of beschrijvende taal is vrijwel betekenisloos. Juist de versmelting van de talige traditionele methoden en de kwantitatief of visueel georiënteerde digitale methodologieën creëren het onderscheid tussen de Digital Humanities en de computerwetenschappen. Traditionele methoden hebben een sterke wisselwerking met de specifiek bestudeerde objecten maar ook met verdiepende filosofieën. Maar de implementatie was meestal uniform: een narratief uitgezet in taal. Digital Humanities voegt hier complexe dimensies aan toe met statistiek, visualisaties en interfaces. Dat deze methoden kunnen toevoegen aan de vakgebieden is niet in twijfel, het grootste probleem is de benodigdheden voor succesvol resultaat. Wat is haalbaar?

Hoewel onderzoeken op dezelfde manier moeten worden gewogen is daarentegen wel heel gemakkelijk om Digitale Humanisten de grond onder de voeten weg te schieten vanuit geesteswetenschappelijk perspectief. Zij hebben vele malen minder tijd voor hun studies en schrijfvaardigheden dan traditionele humanisten. Ook hun onderzoeksprojecten zijn vele malen omvangrijker. Maar hoewel het geesteswetenschappelijk resultaat vergelijkbaar zal zijn, is de maatschappelijke impact van digitale humanisten vele malen groter. De visualisaties en tools zijn gemakkelijk te valoriseren. Traditionele geesteswetenschappers isoleren zich doordat zij zichzelf en hun standpunten niet effectief autonoom kunnen profileren in moderne media als het internet. Daarnaast vechten traditionele humanisten vechten voor een sterk beperkte hoeveelheid banen terwijl goed opgeleide digitale humanisten overal inzetbaar zijn. Technologie is een belangrijk onderdeel van de moderne samenleving.

De vraag die daarmee opborrelt is of de geesteswetenschap wel naar universele kennis streeft of maatschappelijke impact. Digitale humanisten hebben goud in de handen met hun maatschappelijk relevante vaardigheden, traditionele wetenschappers met hun maatschappijkritische theorieën. Nu nog samen in één pakket: De waarde ligt in hybriditeit.[^14] We moeten stoppen met ons te richten op de legitimatie van digitale methoden, maar ons richten op de uitvoering daarvan en de resultaten die ze kunnen genereren.[^15]De investering in de digitale methoden betaalt zich ruimschoots terug in maatschappelijke impact en inzetbaarheid. Dit rechtvaardigt de investering en maakt de Digital Humanities haalbaar.

----  

[^1]:	Tekst over capta

[^2]:	nature vis

[^3]:	CARS

[^4]:	Metrokaart Londen

[^5]:	Morelli

[^6]:	Erfgeo site of artikel -\> het toponiemen onderdeel

[^7]:	Pelagius artikel

[^8]:	Orbis artikel

[^9]:	Git

[^10]:	deep maps en design

[^11]:	Africa auteur

[^12]:	India auteur

[^13]:	Hier leun ik sterk op het boek van Benaderingen

[^14]:	Tekstje aan het begin van het college noemt deze term

[^15]:	Boonstra.