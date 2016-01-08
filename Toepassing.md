## Toepassing

### Orbis

Orbis is een model met een interface waarin de Romeinse logistiek kan worden bestudeerd. Het is opgezet als een bron voor historici om betere inschatting te maken reistijden, afstanden en kosten. In Orbis is een routenetwerk geconstrueerd van wegen en zeebanen. Al deze routes krijgen afhankelijk van het vervoersmiddel, afstand, elevatie en weersomstandigheden een gewicht. Op basis hiervan krijgt de gebruiker een schatting van de reistijd en de kosten te zien. Daarnaast zijn zijn er allerlei cartogrammen, Minard diagrammen en andere netwerkvisualisaties over de kaart heen gelegd. Zodoende is het Romeinse wegennetwerk op een hedendaagse manier begrijpbaar en navigeerbaar gemaakt. 

#### Data

De bronnen van Orbis zijn duidelijk gedocumenteerd. De geografie komt van het Ancient World Mapping Center. De coördinaten van de locaties komen uit het Pleiades project. Als laatste is het routenetwerk geconstrueerd uit gegeorefereerde kaarten uit de The Barrington Atlas of the Greek and Roman World. Daarnaast zijn er een aanvullende bronnen die detail toevoegen. 

De selectie van deze bronnen lijkt sterk bepaald door de doelstelling van het project en het beschikbare materiaal. Een belangrijk punt in de selectie is dat alle bronnen van de Romeinse tijd als contemporain zijn beschouwd, een lange tijdsspan. In de selectie komt ook naar voren dat de onderzoekers geprobeerd hebben een enkele eenheid, namelijk het routenetwerk, in hoog detail weer te geven. Er zijn veel waarden geassocieerd met de lijnstukken. Zo is het de “tetrarchic price edict of 301 CE” belangrijk voor het bepalen van de kosten van de routes. De onderzoekers hebben veel werk gestopt in het controleren van hun modellen. Zo is de data genormaliseerd en gecontroleerd naar 200 bekende historische reizen. De data lijkt met zorg samengesteld te zijn om de eenheid van het routenetwerk zo betrouwbaar mogelijk weer te geven. 

Helaas zijn echter de construerende bronnen niet zichtbaar los van het eindresultaat en zodoende kan een gebruiker niet inschatten hoe de data getransformeerd is. Autoriteit aan de visualisatie toekennis is daarom problematisch. Daarnaast is de data niet goed gescheiden van de implementatie. De construerende data en de resulterende data is niet beschikbaar, althans, zonder communicatie met de onderzoekers. Er zijn geen links vindbaar naar een data archieven, geen API en geen losse datasets. Een polyline in SVG formaat van het routenetwerk is wel beschikbaar, maar deze bevat niet de gegevens van het model. 

### Implementatie

Helaas is de link naar de broncode niet duidelijk weergegeven, maar na een kleine zoektocht is deze vindbaar op Github. [^1]Het is echter maar deels beschikbaar. Alle PHP code, waarin de data transformerende algoritmes staan zijn bewust niet online gezet.[^2] Een goede peer review van de data transformatie is dus niet mogelijk. Helaas is de code ook niet los gedocumenteerd. Daarnaast is er relatief weinig structuur in de code. Herstructurering van de code is nodig voordat de interface echt opnieuw bruikbaar is. 

Uit de bijvoegde academische documentatie is wel het een en ander over de transformatie af te leiden. De belangrijkste toevoeging van Orbis is dat ze de Barrington Atlas hebben gevectoriseerd en vervolgens geïnterpoleerd waar gegevens ontbraken. De zeeroutes en hun gewicht zijn algorimatisch routes bepaald met behulp van meteorologische data. Pragmatisch redenen hebben de auteurs gedwongen om veel te specificeren wat anders niet beschreven zou worden. Veel van deze keuzes zijn ook gefundeerd in academische literatuur. De resulterende routenetwerken hebben potentieel.

De interface is beter beoordelen. De interface bied de gebruiker ruime mogelijkheden om het routenetwerk te verkennen.  De routing werkt redelijk intuïtief en bied veel mogelijkheden. Daarnaast zijn er interessante verdiepende grafieken, hoewel weergegeven op een smal vlak op het scherm. Het is ook goed mogelijk om afbeeldingen te genereren hoe een bijvoorbeeld een stad functioneerde in het wegennetwerk. De applicatie is echter geen handig publicatieplatform voor teksten. De teksten kunnen niet worden afgedrukt en ze hebben tevens geen zelfstandig webadres. Dit maakt citatie problematisch. Het idee van de juxtapositie van documentatie en applicatie is goed, maar iets meer scheiding is wenselijk.

#### Interpretatie

Het grootste probleem met Orbis wordt zichtbaar in hun eigen vergelijking met Google Maps. Google Maps is waarschijnlijk veel accurater dan Orbis, maar desalniettemin duurt een reis regelmatig langer dan weergegeven. Particulariteiten, vooral ongebruikelijke en narratief bepalende, zijn niet goed uitgedrukt aan de hand van een model. De auteurs erkennen dat dit ook niet hun bedoeling is. In hoeverre Orbis in de huidige staat echter kan bijdragen aan ons begrip van de Romeinse tijd is twijfelachtig. Aangezien particulariteiten toch niet accuraat beschreven kunnen worden aan de hand van een model is het de vraag welke verhouding tussen accuraatheid en tijdsinvestering wenselijk is. De auteurs hebben buitengewoon veel aandacht besteed aan het onderbouwen van hun model in plaats van deze te gebruiken om hun model interpretatief interessanter te maken. 

Van groot belang is dat de interface geen zelfstandig geesteswetenschappelijk product is, zelfs niet met de bijgevoegde documentatie. Het werkelijke product is het 

Dit probleem is verbonden met de data


Er is weinig over te zeggen. Er is een artikel dat kort vermeld dat Orbis gebruik kan worden om de groei van het Romeinse rijk te beschrijven. Maar dat is nog niet verder uitgewerkt. Het potentieel voor interpretatie lijkt laag, als er al ooit potentieel was. Een visuele kaart is kwantificeerbaar gemaakt, waar vervolgens hypothetisch detail aan toegevoegd is. Patronen zijn wellicht waarneembaar, maar die scheppen dan wel een heel deterministisch wereldbeeld. Als gesteld zou kunnen worden vanuit Orbis dat het routenetwerk bepalend is geweest voor de groei van het Romeinse Rijk is het alsnog de vraag of historie op deze schaal wel interessant is. 











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

Je komt er snel achter dat het onbegonnen werk is om de autoriteit van de data te achterhalen. In principe kun je er alleen maar op vertrouwen dat het goede data is.

[^1]:	[https://github.com/emeeks/orbis\_v2][1]

[^2]:	.gitIgnore: regel 530

[1]:	https://github.com/emeeks/orbis_v2