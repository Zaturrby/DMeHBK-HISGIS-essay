## ORBIS - The Stanford Geospatial Network Model of the Roman World

Orbis is een model en interface waarmee de Romeinse logistiek kan worden bestudeerd. Het is opgezet als een bron voor historici om betere inschatting te maken reistijden, afstanden en kosten. In Orbis is een routenetwerk geconstrueerd van wegen en zeebanen. Al deze routes krijgen afhankelijk van het vervoersmiddel, afstand, elevatie en weersomstandigheden een gewicht. Op basis van dit geospatiële model krijgt de gebruiker een schatting van de reistijd en de kosten te zien. Daarnaast zijn zijn er allerlei cartogrammen zoals Minard diagrammen en zijn er andere netwerkvisualisaties over de kaart heen gelegd. Zodoende is het Romeinse wegennetwerk op een hedendaagse manier begrijpbaar en navigeerbaar gemaakt.[^1]

### Data

De bronnen van Orbis zijn duidelijk gedocumenteerd. De geografie komt van het Ancient World Mapping Center. De coördinaten van de locaties komen uit het Pleiades project. Als laatste is het routenetwerk geconstrueerd door middel van gegeorefereerde kaarten uit de The Barrington Atlas of the Greek and Roman World. Daarnaast zijn er een aanvullende bronnen gebruikt die detail toevoegen waar dat ontbreekt in de Barrington Atlas. 

De selectie van deze bronnen lijkt sterk bepaald door de doelstelling van het project en het beschikbare materiaal. Een belangrijk punt in de selectie is dat alle bronnen van de Romeinse tijd als contemporain zijn beschouwd, een lange tijdsspan. In de selectie komt ook naar voren dat de onderzoekers geprobeerd hebben een enkele eenheid, namelijk het routenetwerk, in hoog detail weer te geven. Er zijn veel waarden geassocieerd met de lijnstukken. Zo is het de “Tetrarchische prijsbepaling van 301 v.Chr” belangrijk voor het bepalen van de kosten van de routes. De onderzoekers hebben ook veel werk gestopt in het controleren van hun modellen. Zo is de data genormaliseerd en gecontroleerd naar 200 bekende historische reizen. Al met al lijkt de data met zorg samengesteld te zijn om de eenheid van het routenetwerk zo betrouwbaar mogelijk weer te geven. 

Helaas zijn de construerende bronnen echter niet zichtbaar los van het eindresultaat en zodoende kan een gebruiker niet inschatten hoe de data getransformeerd is. Autoriteit aan de visualisatie toekennen is problematisch omdat de data niet goed gescheiden is van de implementatie. Er zijn ook geen links vindbaar naar een data archieven, geen API en geen losse datasets. Een polyline in SVG formaat van het routenetwerk is wel beschikbaar, maar deze bevat niet de gegevens van het model. 

### Implementatie

Hetzelfde bezwaar geld voor de broncode waar geen duidelijke link voor beschikbaar is. Gelukkig is het na een kleine zoektocht wél vindbaar op Github.[^2] Maar ook daar is maar een deel beschikbaar. Alle PHP code, waarin de data transformerende algoritmes staan, zijn bewust niet online gezet.[^3] Een goede peer review van de data transformaties is daardoor niet mogelijk. Bovendien is de beschikbare code niet gedocumenteerd en bevat het relatief weinig structuur om gemakkelijk waardebrokken onderdelen te kunnen ontrafelen zonder begeleiding. 

De bijvoegde academische documentatie is echter van hoge kwaliteit, daaruit is wel het een en ander over de transformatie af te leiden. De belangrijkste toevoeging van Orbis is dat de Barrington Atlas is gevectoriseerd en vervolgens geïnterpoleerd waar gegevens ontbraken. Gewicht is toegekend aan de hand van geografie. De zeeroutes en hun gewicht zijn algoritmisch bepaald met behulp van meteorologische data. Veel van deze keuzes zijn ook gecorreleerd met historische academische literatuur. Deze transformaties vormen samen het geospatiële model. 

De interface is beter beoordelen. De interface bied de gebruiker ruime mogelijkheden om het routenetwerk te verkennen. De routing werkt intuïtief, er zijn veel exploratieve mogelijkheden en de kaart laad snel. Daarnaast zijn er interessante verdiepende grafieken, hoewel weergegeven op een smal vlak op het scherm. Het is ook goed mogelijk om afbeeldingen te genereren over hoe een een stad of regio functioneerde in het wegennetwerk. De applicatie is echter geen handig publicatieplatform voor academische teksten. De teksten kunnen niet worden afgedrukt en ze hebben tevens geen zelfstandig webadres, digital object identifiër (DOI) of andere identificatie mogelijkheden. Dit maakt citatie lastig. De juxtapositie van documentatie en applicatie is wenselijk, maar iets meer scheiding is handiger.

### Interpretatie

Orbis is geen zelfstandig geesteswetenschappelijk product, de interpretatieve lagen zijn moeilijk te achterhalen zonder een diepe studie op de visualisatie. Scheidel en Meeks hebben beiden  ter ondersteuning artikelen geschreven. Vooral het artikel “The shape of the Roman world” schept ligt op de interpretatieve mogelijkheden.[^4] In de artikelen wordt continue benadrukt dat de nadruk op structuren ligt en niet op particulariteiten. Het model laat de condities en beperkingen zien waaronder gebeurtenissen plaatsvonden. Scheidel stelt aan de hand van Orbis dat een belangrijke determinant van het Romeinse verval de kosten voor connectiviteit zijn. De expansie naar onbereikbare gebieden legde grote druk op de economie en bespoedigden politieke transformatie waardoor het rijk uiteindelijk segmenteerde en verviel.

Deze deterministische interpretatie van het Romeinse Rijk roept vragen op. Contextualisatie met een perspectief met meer zorg voor agency zou wenselijk zijn. Want hoewel Scheidel de val verklaart aan de hand van kosten voor connectiviteit, zijn deze kosten wellicht ontstaan vanuit agency. De isolatie van de militaire macht en het politieke centrum in de Donau-regio, zoals Scheidel stelt, roept vragen op over de drijvende krachten daarachter. In hoeverre deze conclusies echter open deuren zijn is moeilijk te beoordelen zonder verdere literatuurstudie. In ieder geval heeft Orbis geopatiële model een ondersteunend perspectief weten toe te voegen aan deterministische verklaringen, waaruit nieuwe vragen ontstaan. Daarnaast is er opnieuw bruikbare data gecreëerd met het routenetwerk. 
---- 

[^1]:	Scheidel, Walter en Elijah Meeks. *ORBIS: The Stanford Geospatial Network Model of the Roman World.* Web. 16 Jan 2016. \<[http://orbis.stanford.edu/][1]\>

[^2]:	Meeks, Elijah.  *ORBIS v2.* Web. 16 Jan 2016. \<[https://github.com/emeeks/orbis\_v2][2]\>

[^3]:	Meeks, Elijah. *Git Ignore.* Web. 16 Jan 2016. \<[https://github.com/emeeks/orbis\_v2/blob/master/.gitignore][3]\>

[^4]:	Scheidel, Walter. “The Shape of the Roman World.” *Journal of Roman Archaeology* 27 (2014): 7:33. Print.

[1]:	http://orbis.stanford.edu/
[2]:	https://github.com/emeeks/orbis_v2
[3]:	https://github.com/emeeks/orbis_v2/blob/master/.gitignore