## Toepassing

### Orbis

Orbis is een model met een interface waarin de Romeinse logistiek kan worden bestudeerd. Het is opgezet als een bron voor historici om betere inschatting te maken reistijden, afstanden en kosten. In Orbis is een routenetwerk geconstrueerd van wegen en zeebanen. Al deze routes krijgen afhankelijk van het vervoersmiddel, afstand, elevatie en weersomstandigheden een gewicht. Op basis van dit ‘geospatial model’ krijgt de gebruiker een schatting van de reistijd en de kosten te zien. Daarnaast zijn zijn er allerlei cartogrammen zoals Minard diagrammen en andere netwerkvisualisaties over de kaart heen gelegd. Zodoende is het Romeinse wegennetwerk op een hedendaagse manier begrijpbaar en navigeerbaar gemaakt. 

#### Data

De bronnen van Orbis zijn duidelijk gedocumenteerd. De geografie komt van het Ancient World Mapping Center. De coördinaten van de locaties komen uit het Pleiades project. Als laatste is het routenetwerk geconstrueerd uit gegeorefereerde kaarten uit de The Barrington Atlas of the Greek and Roman World. Daarnaast zijn er een aanvullende bronnen die detail toevoegen. 

De selectie van deze bronnen lijkt sterk bepaald door de doelstelling van het project en het beschikbare materiaal. Een belangrijk punt in de selectie is dat alle bronnen van de Romeinse tijd als contemporain zijn beschouwd, een lange tijdsspan. In de selectie komt ook naar voren dat de onderzoekers geprobeerd hebben een enkele eenheid, namelijk het routenetwerk, in hoog detail weer te geven. Er zijn veel waarden geassocieerd met de lijnstukken. Zo is het de “tetrarchic price edict of 301 CE” belangrijk voor het bepalen van de kosten van de routes. De onderzoekers hebben veel werk gestopt in het controleren van hun modellen. Zo is de data genormaliseerd en gecontroleerd naar 200 bekende historische reizen. De data lijkt met zorg samengesteld te zijn om de eenheid van het routenetwerk zo betrouwbaar mogelijk weer te geven. 

Helaas zijn echter de construerende bronnen niet zichtbaar los van het eindresultaat en zodoende kan een gebruiker niet inschatten hoe de data getransformeerd is. Autoriteit aan de visualisatie toekennis is daarom problematisch. Daarnaast is de data niet goed gescheiden van de implementatie. De construerende data en de resulterende data is niet beschikbaar, althans, zonder communicatie met de onderzoekers. Er zijn geen links vindbaar naar een data archieven, geen API en geen losse datasets. Een polyline in SVG formaat van het routenetwerk is wel beschikbaar, maar deze bevat niet de gegevens van het model. 

### Implementatie

Helaas is de link naar de broncode niet duidelijk weergegeven, maar na een kleine zoektocht is deze vindbaar op Github. [^1]Het is echter maar deels beschikbaar. Alle PHP code, waarin de data transformerende algoritmes staan zijn bewust niet online gezet.[^2] Een goede peer review van de data transformaties is daardoor niet mogelijk. De beschikbare code is niet gedocumenteerd en bevat bovendien relatief weinig structuur om gemakkelijk waardebrokken onderdelen te kunnen ontrafelen zonder begeleiding. Uit de bijvoegde academische documentatie is echter wel het een en ander over de transformatie af te leiden. De belangrijkste toevoeging van Orbis is dat de Barrington Atlas is gevectoriseerd en vervolgens geïnterpoleerd waar gegevens ontbraken. De zeeroutes en hun gewicht zijn algoritmisch bepaald met behulp van meteorologische data. Veel van deze keuzes zijn ook gecorreleerd met historische academische literatuur. 

De interface is beter beoordelen. De interface bied de gebruiker ruime mogelijkheden om het routenetwerk te verkennen. De routing werkt intuïtief en bied veel mogelijkheden en de kaart laad snel. Daarnaast zijn er interessante verdiepende grafieken, hoewel weergegeven op een smal vlak op het scherm. Het is ook goed mogelijk om afbeeldingen te genereren hoe een bijvoorbeeld een stad functioneerde in het wegennetwerk. De applicatie is echter geen handig publicatieplatform voor academische teksten. De teksten kunnen niet worden afgedrukt en ze hebben tevens geen zelfstandig webadres, digital object identifiër (DOI) of andere identificatie mogelijkheden. Dit maakt citatie lastig. De juxtapositie van documentatie en applicatie is wenselijk, maar iets meer scheiding is handiger.

#### Interpretatie

Orbis is geen zelfstandig geesteswetenschappelijk product. Scheidel en Meeks hebben beiden artikelen ter ondersteuning geschreven. Vooral het artikel “The shape of the Roman world” schept ligt op de interpretatieve mogelijkheden. In de artikelen wordt continue benadrukt dat de nadruk op structuren ligt en niet op particulariteiten. Het model laat de condities en beperkingen zien waaronder gebeurtenissen plaatsvonden. Scheidel stelt aan de hand van Orbis dat een belangrijke determinant van het Romeinse verval de kosten voor connectiviteit zijn. De expansie naar onbereikbare gebieden legde grote druk op de economie en bespoedigden politieke transformatie waardoor het rijk uiteindelijk segmenteerde en verviel.

Deze deterministische interpretatie van het Romeinse Rijk roept vragen op. Contextualisatie met een perspectief met meer zorg voor agency zou wenselijk zijn. Want hoewel Scheidel de val naar de expansie verklaart aan de hand vanuit de kosten van connectiviteit, zijn deze kosten wellicht ontstaan vanuit agency. De beslissing om militaire macht en het politieke centrum te verplaatsen naar de Donau, zoals Scheidel stelt, roept vragen op over de drijvende krachten daarachter. 

In het geval van Orbis is het model duidelijk waardevoller dan de interface. Het model is niet verantwoord te bestuderen vanuit de interface zonder toegang tot de construerende data. Daarnaast lokt de analogie met Google Maps uit dat men juist particulariteiten aan de hand van de interface gaat beschrijven.    Vanuit dit perspectief lijkt het detail dat het model bevat overdadig en 

















### Pelagios





### Een vergelijking van drie tools

Orbis -\> Hypothetische resultaten
HISGIS -\> Illusie van algemeniteit door georeferencing
BGB -\> Administratieve data geotagged
HDAT -\> Narratief en specificiteit
Pelagios/Peripleo -\> Kaartlaag
Nature visualisatie -\> Visualisatie aan de hand van één eenheid
TANAP -\> Missieven? 
AMH -\> Toponiemen
Erfgeo -\> Toponiemen

Dit perspectief levert een sterk diachrone weergave op waarbij interne relaties goed zichtbaar worden. De bron kan nu binnen enkele minuten op waarde worden geschat. Extern levert het ook perspectieven op. Om de visualisatie mogelijk te maken moesten al vele bronnen worden gecombineerd. Scheepskaarten zijn gebruikt om routes te construeren en de Atlas of Mutual Heritage is gebruikt om plaatsnamen met coördinaten te verbinden. Daarnaast genereert de visualisatie haar eigen data door extrapolatie. 


## Hisgis

 HISGIS positioneert zichzelf als algemene historische geografische tool en vermijdt narratief compleet. ORBIS is interactiever doormiddel van de historische routing en in de rijkheid van visualisatietechnieken. De juxtapositie van documentatie en visualisatie geeft de gebruiker al veel steun. 

### HDAT

Onze eigen tool HDAT heeft een hogere specificiteit, heeft zich gericht op dynamiek en is daardoor meer geneigd naar narratief. Het tijdselement vertelt zijn eigen diachrone verhaal. Daarentegen ontbreekt in de laatste tool zowel autoriteit als verantwoording en is goed zichtbaar dat deze tool nog in aanbouw is. 


---- 

### Subconclusie

Er is een cumulatief effect binnen de Digital Humanities dat moeilijk zichtbaar is elders in de geesteswetenschap. Waar traditionele geesteswetenschappen natuurlijk neigen om de breedte in te gaan, gaan de Digital Humanities de diepte in. Dit leidt in sommige gevallen tot positivistische of deterministische interpretaties. Aan de andere kant kunnen particulariteiten voorzien worden contextualisatie die voorheen onmogelijk was. Maar interpretatie die zich richten op literatuur en traditioneel bronnen onderzoek zijn tevens van groot belangrijk om de resultaten van deze digitale onderzoeken op waarde te schatten.

Je komt er snel achter dat het onbegonnen werk is om de autoriteit van de data te achterhalen. In principe kun je er alleen maar op vertrouwen dat het goede data is.

[^1]:	[https://github.com/emeeks/orbis\_v2][1]

[^2]:	.gitIgnore: regel 530

[1]:	https://github.com/emeeks/orbis_v2