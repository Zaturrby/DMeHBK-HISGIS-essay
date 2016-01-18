## Implementatie

### Transformatie

Zodra de data verzamelt is begint de transformatie van die data voor visualisatie. Volgens het stappenplan van Ben Fry zijn de eerste stappen nu achter de rug. De data is nu verzameld en enigszins geparset. Nu moeten de betekenisvolle elementen daarin gefilterd en de betekenis, al dan niet met behulp van statistiek, toegankelijk gemaakt worden.[^1] Kortom er moeten algoritmes naast de data worden gelegd. Er zijn eindeloos veel methoden om dit te doen en elk van deze methoden kent zijn eigen krachten en zwakheden. 

Een grof onderscheid kan worden gemaakt tussen transformatie gemaakt door grafische interfaces (GUI’s) en programmatische interfaces. Het doel van grafische interfaces is vaak om stappen aan het oog van de gebruiker te onttrekken. Bij het gebruik van GUI’s is extra zorg nodig voor academische verantwoording. Code heeft automatisch voordelen voor de reproduceerbaarheid van een onderzoek. De algoritmische natuur staat een controlerende onderzoeker gemakkelijk toe om na te lopen welke transformaties hebben plaatsgevonden. Daarnaast biedt code eindeloos meer expressiemogelijkheden dan grafische interfaces. 

### Design en User Experience

De laatste stappen in Fry’s proces van visualisatie zijn representatie, verfijning en interactie. Ook hier zijn eindeloos veel mogelijkheden zoals zichtbaar is in ‘The Periodic Table of Visualization Methods’.[^2] Alleen de basisvormen bieden al eindeloos veel mogelijkheden. Daarnaast beïnvloeden het design en de interactiemogelijkheden de betekenis enorm. De beslissing om bepaalde elementen dikker of kleurrijker te maken heeft effect. Kaarten zijn al sterk geabstraheerd van de werkelijkheid. De metrokaart van Londen is hier een goed voorbeeld van.[^3] Ook de User Experience bepaald veel van de betekenis. Schaalknoppen zijn hier een goed voorbeeld van. Schaal en detail hebben grote invloed op de betekenis. Hoewel technisch vrijwel geen moeite gespendeerd hoeft te worden kan de vergroting de beeldvorming bepalen.

Voor kaarten zijn er bovendien domein gerelateerde problemen. Projecties en oriëntatie van kaarten bepalen de beeldvorming enorm. Dit was al bekend toen Franse historicus Braudel de wereld omdraaide waardoor Africa veel machtiger lijkt.[^4] Monmonier verdiept de problemen met cartografische projecties in zijn boek ‘Lying with Maps’.[^5] Maar er zijn ondertussen ook veel visualisaties waarin je de problemen interactief kunt verkennen. In een visualisatie van Jason Davies zijn de overgangen tussen projecties geanimeerd waardoor goed waarneembaar is hoe deze zich tot elkaar verhouden.[^6] Talmage en Maneice hebben voor de Mercator projectie uitgewerkt wat voor een effect dit heeft op de grootte van naties.[^7] Het laatste waarvoor gewaakt moet worden is de verweving van kaarten een taal. In welke taal moeten plaatsnamen geschreven worden en hoe moet er met geschiedenis worden omgegaan: Schrijven we Batavia of Jakarta? De keuze heeft een performatief effect en we moeten hierbij waken voor post-kolonialisme. 

In de literatuur valt de term ‘Deep Map’ vaak. Mia Ridge, Don Lafreniere en Scott Nesbit hebben en piramide voorgesteld voorgesteld met het universum aan data, een ‘deep map’ en vervolgens een ‘spatial narrative’.[^8] Een kaart is echter altijd een gesloten systeem waarin de vragen, waarden, middelen en vaardigheden van de betrokken onderzoekers uitdrukking in vinden. Een “deep map” met vrije exploratie is altijd hierdoor begrenst. Daarnaast is er teveel data om in één kaart te visualiseren. In plaats van te streven naar een ‘Deep Map’ is het slimmer om te streven naar een goede opslag van historische geografische data zodat onderzoekers hun eigen kaarten gemakkelijk en bewust kunnen creëren. 

### Hergebruik

Voor hergebruik kun je een grof onderscheid maken tussen tools met historisch onderwerp en zonder. Tools zonder historisch onderwerp, zoals PostGIS of D3, zijn over het algemeen waardevoller om bekend mee te zijn door de veelzijdigheid van inzetbaarheid. Voor specifieke interfaces, zoals Orbis of Geography of the Post, geld over het algemeen dat iedere knop al door de maker geïnterpreteerd is. Algemenere GUI’s, zoals QGIS, zijn lastig om wetenschappelijk te verantwoorden hoewel in sommige gevallen wel wenselijk. Ieder onderwerp en dataset is anders en vraagt vaak zijn eigen statistiek of visualisatiemethode. De vrijheid van expressie hierin is uiteindelijk ongeëvenaard in programmeertalen. Met regelmaat opnieuw bruikbare tools bevinden zich dan ook vaak op dit niveau. 

Deze gereedschappen worden vaak ook geoptimaliseerd en ingezet door het bedrijfsleven en Open Source tools op dit niveau zijn door deze commerciële belangen vaak ook stabieler. Als geesteswetenschappers hoeven wij niet zozeer deze tools te bouwen en zeker niet te optimaliseren. Maar wij moeten wel zelf onze visualisaties en interfaces hiermee kunnen opzetten. Onze taak moet liggen in deze multidimensionale tools te voorzien van rijke narratieven waarin meerdere stemmen hun uiting vinden en er ruimte is voor ambiguïteit en onzekerheid.

Als laatste zijn documentatie en gesystematiseerde versie controle van groot belang. Het is van belangrijk om te kunnen achterhalen wie veranderingen maakt en op welke versie van een tool of kaart een onderzoek is geschreven. De scripts van die versie moeten worden gebruikt ter beoordeling, want latere versies kunnen scripts verwijderd hebben omdat de doelstelling van de interface bijvoorbeeld is veranderd. De tool Git is hier een goed voorbeeld voor.[^9] Documentatie van de code is ook essentieel. Een korte introductie om de code te installeren en comments bij sterk waardebetrokken delen maakt de code veel toegankelijker. 
---- 

[^1]:	Fry, Ben. *Visualizing Data.* Sebastopol: O'Reilly Media, 2008. Print.

[^2]:	Lengler, Ralph and Martin J. Eppler. *Towards A Periodic Table of Visualization Methods for Management.* IASTED Proceedings of the Conference on Graphics and Visualization in Engineering. 2007, Clearwater, Florida, USA. Web. \<[http://www.visual-literacy.org/periodic\_table/periodic\_table.pdf]()\>

[^3]:	Cartwright, William. *Beck's representation of London's Underground system: map or diagram?* Proceedings of the Geospatial Science Research 2 Symposium. Dec. 10-12 2012, Melbourne, Australia. Web. \<[http://ceur-ws.org/Vol-1328/GSR2\_Cartwright.pdf]()\>

[^4]:	Owens, J. B. *What Historians Want from GIS.* Web. 8-11-2015. \<[http://www.esri.com/news/arcnews/summer07articles/what-historians-want.html]()\>

[^5]:	Mark Monmonier. *Lying with Maps.* Chicago: The University of Chicago Press, 1996. Print.

[^6]:	Davies, Jason. *Map Projection Transitions.* Web. 14 Jan. 2016. \<[https://www.jasondavies.com/maps/transition/][4]\>

[^7]:	Talmage, James and Damon Maneice. *The True Size … .* Web. 16 Jan. 2016.\<[http://thetruesize.com][5]\>

[^8]:	Ridge, Mia, Don Lafreniere en Scott Nesbit. “Creating Deep Maps and Spatial Narratives Through Design.” *International Journal of Humanities and Arts Computing* 7.1-2 (2013): 176–189. Print.

[^9]:	*Git:  A Free And Open Source Distributed Version Control System.* 16 Jan. 2016. \<[https://git-scm.com/][6]\>

[4]:	https://www.jasondavies.com/maps/transition/
[5]:	http://thetruesize.com/ "http://thetruesize.com"
[6]:	https://git-scm.com/