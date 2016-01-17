# - Presentatie -

{ Introductie }
{ Historische Geografische Interfaces want eigen interface }
{ drie tools, drie dimensies }
{ Data, implementatie, interpretatie }
{ Kwaliteit }

Ik heb historische geografische interfaces gekozen als mijn onderwerp voor het essay en de presentatie. Dit onderwerp vind ik interessant omdat ik zelf in een historische geografische interface probeer te ontwerpen en ik graag mijn kader rondom dit onderwerp wou verdiepen. In deze korte presentatie ga ik jullie kort door vier tools lopen aan de hand van drie dimensies. Ik zal elk van deze tools belichten vanuit drie perspectieven. Hun data, hun implementatie en hun interpretatie. Om een succesvolle digitaal historisch product te zijn vind ik dat al deze dimensies goed verzorgd moeten zijn, want uiteindelijk is het de academische kwaliteit die hun apart zet van videogames waar historie verdraaid wordt om het zo vermakelijk en goedkoop mogelijk te maken. De eerste drie tools heb ik gekozen omdat ze hoog van kwaliteit zijn, de laatste heb ik gekozen omdat het mijn eigen project is. 

## Geography of the Post

{ Introductie }
{ Geography of the Post: Blevins en Heppler }
{ Postkantoren -\> Expansie Anglo Amerikaanse cultuur }

Ik ga beginnen met de tool die qua kwaliteit van uitvoering de anderen ver achter zich laat. Dit is het Geography of the Post project door Cameron Blevins en Jason Heppler. In dit project worden postkantoren gevisualiseerd op een kaart om zo een nieuw perspectief op de expansie van de Anglo Amerikaanse cultuur westwaarts te geven. 

{ Data }
{ United States Post Offices Helbrock: Plaatsen en datums }
{ GNIS: coördinaten }

Maar voordat ik verder in de interpretatie duik wil ik graag kijken naar de data die het product in gaat. Dit begint bij een gigantisch karwij met de collectie van de data door de posthistoricus Richard Helbrock. Aan de hand van postzegels heeft hij bepaald wanneer er postkantoren in een bepaalde regio zijn. Deze dataset is het begin van de visualisatie. Blevins en Heppler hebben deze dataset voorzien van geografische coördinaten door middel van het Geographic Names Information System. Dit is een database van de Amerikaanse overheid die zorgt dat namen en plaatsen met elkaar overeenkomen. Dit is min of meer de data die de applicatie verbruikt.

{ Implementatie }
{ Code: Github }
{ Goed gearchiveerd en gedocumenteerd}
{ Transformatie script ontbreekt helaas }
{ Lokale versie en aanpassingen snel mogelijk door documentatie }
{ Controle goed mogelijk }
{ Design en Interactie}
{ Verschillende visualisatie mogelijkheden }
{ Selectie van tijdvakken }
{ Identificatie punten }
{ Goede implementatie }

Blevins en Heppler hebben vervolgens deze data gebruikt om de visualisatie op te zetten. Dit hebben ze heel goed gearchiveerd en gedocumenteerd gedaan. De data is beschikbaar, de code is dat ook en daarnaast is het allemaal beschreven. Ik kon zelf gemakkelijk een lokale versie van de site draaien en eventueel dingen aanpassen. Mocht ik enige twijfel hebben over hun werk, dan kon ik het goed nalopen. Maar dit is aan de achterkant. De voorkant lijkt interessanter. Het ziet er goed ontworpen en interactief uit. Je kan tijdvakken selecteren en postkanten op twee verschillende manieren zien wanneer ze geopend en gesloten zijn. De interface doet goed wat hij moet doen. 

{ Interpretatie }
{ Wat betekenen de stipjes? Narratief? }
{ Interface betekenisloos en ontoegankelijk zonder interpretatie }
{ Context is belangrijk, particulariteiten moeten gekend }
{ Narratief met geesteswetenschappelijke kennisdoelen }
{ 287 pagina’s tellende dissertatie } 

Maar wat is er te zien? Dit is eigenlijk heel problematisch in deze interface. Je ziet een hoop stipjes op een kaart een een grafiekje die zegt wanneer dit stipjes zijn ontstaan. Er is geen narratief verbonden met de visualiserende interface. Hier kom je ook gelijk uit bij de interpretatie van een dergelijke interface. Hoewel het er fantastisch uitziet is het eigenlijk helemaal niet toegankelijk voor leken en zelf niet voor academici. Je moet fatsoenlijk context rondom de visualisatie hebben om het te kunnen interpreteren. Je moét kennis hebben van particulariteiten. Je moet de visualisatie verweven met een perspectief of narratief waarin geesteswetenschappelijke kennisdoelen zijn verwerkt om hier iets mee te kunnen. Pas dan kun je zeggen: ja, dit een interessante tool. Blevins heeft hier gelukkig een 287 pagina’s tellende dissertatie over geschreven. 


{ Specifieke interpretatie }
{ Contextualisatie punten met particulariteit }
{ Simultane natuur verhaal }
{ Goudzoeker }
{ Spoorwegarbeider }
{ Indianen en Leger }
{ Agrarier }
{ Postkantoren -\> Gebalanceerd narratief }
{ Blogpost Blevins } 

Hierin contextualiseert hij het ontstaan van puntjes op de kaart met particulariteiten, of juist het niét ontstaan van punten. Zowel positieve als negatieve ruimte wordt belicht. Het blijkt dat de postkantoren een geweldige manier vormen om de simultane natuur van de verhalen van de goudzoeker, spoorwegarbeider, indianen en de agrariërs te vertellen. Zo breid hij er een gebalanceerd narratief uit de verhalen die anders in isolatie worden vertelt. Maar als je meer wilt weten: lees de blogpost van Blevins erover, hij legt het vele malen beter uit dan ik. Hoewel de tool ontoegankelijk is voor ons, is hij dat zeker niet voor iemand die de particulariteiten van het onderwerp kent.  

## Orbis

{ Introductie }
{ The Stanford Geospatial Model of the Roman World } 
{ Wegennetwerk toont functioneren van het rijk }

Tot zover de Geography of the Post. ORBIS. Weer een project van Stanford. Elijah Meeks en Walter Scheidel zitten achter dit project. De subtitel spreekt boekdelen hier: “The Stanford Geospatial Model of the Roman World”. In dit project hebben ze een model van het wegennetwerk van de Romeinen gemaakt en dat geprobeerd om meer duidelijkheid te geven over het functioneren van het rijk.

{ Data }
{ Inputdata model: hypothetisch of gefundeerd } 
{ Pleiades: coördinaten }
{ Barrington Atlas: wegen + QGIS snap }
{ Klimatologische data en algoritme: Zeenetwerk }
{ Ancient World Mapping Center: Kaart }
{ 200 historische reizen: Controle en normalisatie }

Allereerst ben ik natuurlijk weer geïnteresseerd in welke data erin gaat. Als ik dat niet weer kan je me nog meer vertellen, maar ik moet weten wat hypothetisch is en wat niet, zeker bij een ‘model’. Het blijkt dat hier gebruik is gemaakt van het Pleiades project voor de coördinaten en de Barrington atlas voor de wegen. Het schijnt dat ze deze zelf hebben gevectoriseerd. Deze altas lijkt min of meer de bron voor alle datasets rondom de Romeinse tijd te zijn. Hiermee hadden ze een wegennetwerk die van een gewicht hebben voorzien aan de hand van geografie. Het zeenetwerk echter hebben ze algoritmisch geconstrueerd en van gewichten voorzien aan de hand van hedendaagse meteorologische data. Hiermee hadden ze een model, wat ze vervolgens hebben gecontroleerd en genormaliseerd aan de hand van tweehonderd bekende historische reizen. Redelijk degelijke dataselectie lijkt me zo. 

{ Implementatie } 
{ Cartogrammen, flow diagrammen, Routing }
{ Design en Interactie }
{ Geen archivering en documentatie code }
{ Online documentatie onhandig -\> Routing } 

Orbis heeft dit model vervolgens gevisualiseerd met een online interface. Hierin zijn rijke mogelijkheden om de data op andere manieren weer te geven. Cartogrammen die de afstanden transformeren naar kosten en Minard Diagrammen waarin kruispunten duidelijk zichtbaar worden. Ook kun je een route plannen door het rijk en een idee krijgen van hoe lang het duurt om ergens te komen. Het ziet er allemaal ook weer goed uit. Maar  nu het probleem. Ik heb alleen geen idee wat er op de achtergrond allemaal gaande is. Er is geen link naar de code, en de datasets zijn niet los beschikbaar. Gelukkig ben ik een ervaren Google fanaticus en vond ik een deel van de broncode op Github. Maar de code was niet gedocumenteerd, noch gemakkelijk leesbaar. In mijn vrije tijd lees ik niet eventjes bestanden van 2700 regels door, dit is slecht management van complexiteit. In de interface is zelf wel documentatie, zogenaamd een academische publicaties platform, maar wel een slechte. Je kan niet linken naar artikelen of dergelijke. Ze hebben de routing goed verknald: koppel het dan liever los.

{ Interpretatie }
{ Middelmatige implementatie, goede interpretatie }
{ Expansie van Romeinse Rijk en kosten voor connectiviteit }  
{ Mediterrane kern vs Syrie en Donau regio -\> Extremiteit }
{ Economische en politieke transformatie }
{ Deterministische toepassing geospatieel model }

Nu ik even mijn gram kwijt ben over de slordige backend implementatie, de interpretatie door Scheidel is wel weer heel goed. De interface geeft je zelf geen verhaal, maar de gepubliceerde tekst is best heel interessant. Het schetst goed welke kosten het Romeinse rijk gehad moet hebben om hun expansies in de Donau regio, Syrië en Egypte te betalen. Want hoewel deze regio’s geografisch niet zo heel ver verwijderd lijken te zijn van de mediterrane kern van het rijk, zijn ze qua kosten absolute uithoeken. Scheepvaart was onder de Pax Romana erg goedkoop. Scheidel stelt iets of wat deterministisch dat de kosten uiteindelijk grote impact hebben gehad op de economische verhoudingen en politieke transformatie vereisen. De concentratie van militaire en politieke macht in de Trier en de Donau regio plaatst het hele mediterrane centrum op gigantische afstand van het bestuur. Het geospatiële model lijkt heel dienstbaar aan deze interpretatie. Zodoende vind ik het een erg geslaagd onderzoeksproject. 

## HDAT

{ Introductie }
{ Concretisering en verdiepend perspectief }
{ Verlevendiging en exploratie van BGB } 

The Historical Dutch Asiatic Trade. Dit is een interface van mijzelf en vriend van mij, waar we aan begonnen zijn om te leren hoe het allemaal in de praktijk nou gaat. Het zelf maken van een dergelijk project heeft ons enorm geholpen om de abstracte materie te concretiseren en wie weet krijgen we het ook nog eens af. Het perspectief dat ik op de vorige app had is grotendeels ontstaan doordat we er zelf met HDAT tegenaan gelopen zijn. HDAT is een interface die probeert de boekhouding van de boekhouder generaal van Batavia te visualiseren. Hierin staan reizen van Nederland naar Azië droog als record in een register. Deze hebben we geprobeerd tot leven te brengen door ze op een kaart te visualiseren.

{ Data }
{ BGB: reizen en producten}
{ AMH: coördinaten }
{ CLIWOC + Kaarten: Routes }
{ OSM-data: Geografie voor kaart }

Om dezelfde structuur als de rest van de presentatie aan te houden ga ik eerst in op de data. Allereerst dus de Boekhouding van de Boekhouder Generaal van Batavia, welke dus reizen maar ook producten bevat. Maar daar stopt het niet, we hadden ook geografische coördinaten nodig. Daarvoor hebben we de Atlas of Mutual Heritage geplunderd, eerst zonder en later met toestemming uiteraard. Daarnaast hebben we een historische klimatologisch project over de oceanen geraadpleegd voor routes van de reizen. Hieruit konden we al duidelijker een route netwerk construeren, welke we gecorreleerd hebben met historische kaarten. Zo zijn we aan onze reizen, locaties en routes gekomen. De kaart zijn is een laag geconstrueerd uit OSM data, met een bruin kleurtje en wat historische namen. We willen nog eindeloos veel meer data toevoegen, maar de realiteit is dat wel al meer als genoeg te behappen hebben aan deze data. We moeten nog flinke technologische obstakels over willen we het verder uitbreiden. Maar we hebben plannen genoeg, nu alleen nog tijd. 

{ Implementatie }
{ Postgis en visualisatie lib: Leaflet }
{ Versiecontrole }
{ Animaties + Minard } 

Onze implementatie is sterk vergelijkbaar met de implementatie van ORBIS en Geography of the Post. Alleen gebruiken wij een andere visualisatie bibliotheek. Zij gebruiken vooral D3, wij richten ons op Leaflet, omdat het georiënteerd op kaarten is terwijl D3 een algemenere tool is met kaart functionaliteit. Al onze code is vanaf het eerste begin beschikbaar online en gearchiveerd. Zonder een goed versie controle systeem hadden we nooit zover kunnen komen als we nu zijn. Uiteindelijk hebben we een basis interface klaar: Je kan de schepen zien varen en er zijn enigszins bruikbare Minard grafieken van de goederen.

{ Interpretatie }
{ Patronen betekenisloos zonder kennis van particulariteiten }
{ Behoefte aan literatuur onderzoek }
{ Tijdsintensief, moeilijk haalbaar, maar waardevol }
{ Essentiële vaardigheden: Samenwerken, programmeren }
{ Methodologische vraagstukken }
{ Valorisatie }

Maar dit is hoever we zijn. Er is nog geen goede documentatie en bovenal: er is geen goede interpretatie. Erik en ik hebben daar nog stop discussies over. Wat zit erin en wat zit er niét in. Het is Overduidelijk voor ons geworden dat het grotendeels betekenisloos is zonder kennis van particulariteiten. Je moet een narratief construeren en particulariteiten en patronen met elkaar verweven. Het kan super interessant zijn, maar zonder degelijk literatuur onderzoek zegt het niks. Daardoor zijn we enigszins tegen een muur opgelopen. De data analyseren, een degelijke implementatie bouwen en een goede interpretatie schrijven met een literatuur onderzoek op de achtergrond is een megalomaan project om op een namiddag te doen. Zeker zonder studiepunten of andere financiering. We hebben beide meerdere vakken geofferd om tot dit punt te komen en willen we meer sneuvelen er nog een hoop. Dit roept wel interessante vragen op over de haalbaarheid van dergelijke onderzoeken. Maar persoonlijk geloof ik dat het de kosten meer dan ook waard zijn.   Meeks heeft een baantje bij Netflix en dat betaalt volgens mij wel lekker. Geesteswetenschappelijke kennis vind zo zijn ingang bij technologie bedrijven die het hard nodig hebben. We houden de moed er dus nog maar even in!




