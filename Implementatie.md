## Implementatie

### Transformatie

Zodra de data verzamelt is begint de transformatie van die data voor een visualisatie. Volgens het stappenplan van Ben Fry zijn de eerste stappen nu achter de rug. De data is nu verzameld en enigszins geparset. Nu moeten de betekenisvolle elementen daarin gefilterd en de betekenis, al dan niet met behulp van statistiek, toegankelijk gemaakt worden.[^1] Kortom er moeten algoritmes naast de data worden gelegd. Er zijn eindeloos veel methoden om dit te doen en elk van deze methoden kent zijn eigen krachten en zwakheden. 

Een grof onderscheid kan worden gemaakt tussen transformatie gemaakt door grafische interfaces (GUI’s) en wederom door API’s. Het doel van grafische interfaces is om stappen aan het oog van de gebruiker te onttrekken. Deze stappen zijn mogelijk waardebetrokken zijn. Het moet duidelijk zijn wat er onder de motorkap gebeurd en dat is bij deze interfaces vaak niet herleidbaar. Voor de reproduceerbaarheid van het onderzoek is het essentieel dat de transformatie door middel van code gebeurd. Een controlerende onderzoeker heeft dan een veel beter zicht op welke transformaties hebben plaatsgevonden dan met een beschrijving van het gebruik van een GUI. Daarnaast bieden transformaties door middel van code eindeloos meer expressiemogelijkheden dan grafische interfaces. 

### Design en User Experience

De laatste stappen in Fry’s proces van visualisatie zijn representatie, verfijning en interactie. Ook hier zijn eindeloos veel mogelijkheden zoals zichtbaar is in ‘The Periodic Table of Visualization Methods’.[^2] Alleen de basisvormen bieden al eindeloos veel mogelijkheden. Daarnaast beïnvloeden het design en de interactiemogelijkheden de betekenis enorm. De beslissing om bepaalde elementen dikker of kleurrijker te maken heeft effect. Kaarten zijn al sterk geabstraheerd van de werkelijkheid. De metrokaart van Londen is hier een goed voorbeeld van.[^3] Ook de User Experience bepaald veel van de betekenis. Schaalknoppen zijn hier een goed voorbeeld van. Schaal en detail hebben grote invloed op de betekenis. Hoewel technisch vrijwel geen moeite gespendeerd hoeft te worden kan de vergroting de beeldvorming bepalen.

Voor kaarten zijn er bovendien domein gerelateerde problemen. Projecties en oriëntatie van kaarten bepalen de beeldvorming enorm. Dit was al bekend toen Braudel de wereld omdraaide waardoor Africa veel machtiger lijkt.[^4] Mark S. Monmonier gaat hier een stap verder mee in zijn boek ‘Lying with Maps’.[^5] Er zijn ondertussen ook veel visualisaties waarin je de problemen interactief kunt verkennen. In een visualisatie van Jason Davies zijn de overgangen tussen projecties geanimeerd waardoor goed waarneembaar is hoe deze zich tot elkaar verhouden.[^6] Talmage en Maneice hebben voor de Mercator projectie uitgewerkt wat voor een effect dit heeft op de grootte van naties.[^7]Het laatste waarvoor gewaakt moet worden is de verweving van kaarten een taal. In welke taal moeten plaatsnamen geschreven worden en hoe moet er met geschiedenis worden omgegaan: Schrijven we Batavia of Jakarta? De keuze heeft een performatief effect en we moeten hierbij waken voor post-kolonialisme. 

In de literatuur valt de term ‘Deep Map’ vaak. Mia Ridge, Don Lafreniere en Scott Nesbit hebben en piramide voorgesteld voorgesteld met het universum aan data, een ‘deep map’ en vervolgens een ‘spatial narrative’.[^8] Een kaart is echter altijd een gesloten systeem waarin de vragen, waarden, middelen en vaardigheden van de betrokken onderzoekers uitdrukking in vinden. Een “deep map” met vrije exploratie is altijd hierdoor begrenst. Daarnaast is er teveel data om in één kaart te visualiseren. In plaats van te streven naar een ‘Deep Map’ is het slimmer om te streven naar een goede opslag van historische geografische data zodat onderzoekers hun eigen kaarten gemakkelijk en bewust kunnen creëren. 

### Hergebruik

Voor hergebruik kun je een grof onderscheid maken tussen tools met onderwerp en zonder. Tools zonder historisch onderwerp zijn over het algemeen waardevoller om bekend mee te zijn door de veelzijdigheid van inzetbaarheid. Bij specifieke interfaces geld over het algemeen dat de maker iedere knop daarin al heeft geïnterpreteerd. Algemenere GUI’s zijn wetenschappelijk beperkend, hoewel in sommige gevallen wel wenselijk. Om werkelijk nieuwe inzichten uit data te halen zullen nieuwe statistische methoden of originele visualisatietechnieken moeten worden toegepast. Uiteindelijk is de vrijheid van expressie ongeëvenaard in programmeertalen. Met regelmaat opnieuw bruikbare tools bevinden zich dan ook vaak op dit niveau. 

Deze worden vaak ook geoptimaliseerd en ingezet in het bedrijfsleven en Open Source tools op dit niveau zijn door commerciële belangen vaak ook stabieler. Als geesteswetenschappers hoeven wij niet zozeer deze tools te bouwen en ook optimalisatie hiervan is een taak voor ICT’ers. Maar wij moeten wel zelf onze visualisaties en interfaces opzetten. Onze taak moet liggen in deze multidimensionale tools te voorzien van rijke narratieven waarin meerdere stemmen hun uiting in vinden en er ruimte is voor ambiguïteit en onzekerheid.

Als laatste zijn documentatie en gesystematiseerde versie controle van groot belang. Het is van belangrijk om te kunnen achterhalen wie veranderingen maakt en op welke versie van een tool of kaart een onderzoek is geschreven. De scripts van die versie moeten worden gebruikt ter beoordeling, latere versies kunnen scripts verwijderd hebben omdat bijvoorbeeld de doelstelling van de interface is veranderd. De tool Git is hier een goed voorbeeld voor.[^9]Documentatie van de code is ook essentieel. Een korte introductie om de code te installeren en comments bij sterk waardebetrokken delen maakt de code veel toegankelijker. 
---- 

[^1]:	Ben Fry -\> Proces

[^2]:	[http://www.visual-literacy.org/periodic\_table/periodic\_table.html][1]

[^3]:	Metrokaart Londen

[^4]:	Africa auteur

[^5]:	Lying with Maps

[^6]:	[https://www.jasondavies.com/maps/transition/][2]

[^7]:	[http://thetruesize.com][3]

[^8]:	deep maps en design

[^9]:	Git

[1]:	http://www.visual-literacy.org/periodic_table/periodic_table.html
[2]:	https://www.jasondavies.com/maps/transition/
[3]:	http://thetruesize.com/ "http://thetruesize.com"