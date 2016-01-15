## HDAT - Historical Dutch Asiatic Trade

De Historical Dutch Asiatic Trade is een visualisatie die tracht de Boekhouding van de Boekhouder Generaal Batavia (BGB) toegankelijk te maken door deze geografisch te ontsluiten. Daarnaast wordt geprobeerd de rijkheid van de data toegankelijk te maken met gelaagde visualisaties. De visualisatie is opgezet door Erik van Zummeren en mijzelf. Hierdoor is dit deel van dit essay een bevooroordeeld perspectief en dus is vooral geschreven als tussentijdse evaluatie dan uiteindelijke beoordeling. 

### Data

De bronnen voor de huidige versie van deze visualisatie zijn allereerst de boekhouding van de Boekhouder Generaal van Batavia. Deze boekhouding is door het Huygens/ING gedigitaliseerd.[^1] De database bevat onder andere datums van vertrek en aankomst met bijbehorende locaties en de vervoerde goederen met hun waarde. Deze gegevens worden aangevuld met coördinaten uit de Atlas of Mutual Heritage.[^2] Met behulp van CLIWOC en historische kaarten is vervolgens een routenetwerk geconstrueerd waardoor mogelijk wordt schepen gesimuleerd van Nederland naar Azië te laten varen. De kaartlaag is geconstrueerd uit moderne geografie, bruin gestileerd, met een additionele laag historische namen daaroverheen. Alle data is in ruwe vorm beschikbaar op Github.[^3] De data zal in de toekomst wellicht ook toegankelijk zijn door middel van een API, want de applicatie zal deze zelf gaan gebruiken.

Er zijn nog vele extra bronnen beschikbaar die waardevolle verdiepende perspectieven kunnen bieden. Er zijn een groot aantal missieven beschikbaar bij het Huygens/ING die een waardevol een rijk interpreteerbaar perspectief bieden door hun tekstuele natuur.[^4] Daarnaast kan meer data uit het AMH worden gebruikt om de locaties verder te voorzien van informatie. Het is ook onze wens om bepalende gebeurtenissen bij te voegen in een laag om de app gemakkelijker begrijpbaar te maken. Er zijn tevens mogelijkheden tot verbreding van de data. Er is een digitalisatie project gaande om de Ommelandsvaart te digitaliseren en deze kan met weinig moeite worden toegevoegd aan de data. Ook is er data beschikbaar voor reizen gemaakt door slavenhandelaren.[^5] Deze data kan gemakkelijk in deze kaart worden ingevoegd, of een kopie daarvan. Ongetwijfeld zullen er meer scheepsdatabases zijn of ontstaan waaraan een ruimtelijk perspectief waarde kan toevoegen.  

### Implementatie

De code van deze applicatie is eveneens beschikbaar op Github. Alle transformaties zijn vastgezet in scripts en kunnen gedraaid worden op elk UNIX-systeem mits de gebruiker de juiste software heeft geïnstalleerd. Deze scripts legen de database elke keer en installeren een schone versie. Vervolgens worden alle transformaties algoritmisch toegepast. Eén uitzondering hierop de data van het AMH, waarbij sommige toponiemen handmatig corresponderend zijn gemaakt. Deze data wordt vervolgens verder in de online applicatie weer algoritmisch van meer detail voorzien om animaties vloeiend te laten verlopen. Enkele stappen in de transformatie zijn hoogst speculatief en behoeven verdere analyse. Zo is er gekozen voor een basissnelheid van 5km/u voor de schepen. Dit simpele getal bepaald grote delen van de visualisatie en moet beter verantwoord worden.

Een ander belangrijk punt van de applicatie is dat hij sterk in ontwikkeling is. Ondertussen zijn drie versie van de applicatie beschikbaar geweest. Al deze versies zijn nog beschikbaar door middel van het versie controle systeem van Git. In de huidige versie zijn we ons aan het oriënteren op interface lagen die de basisvisualisatie van de schepen met meer betekenis moeten gaan voorzien. Hieronder vallen bijvoorbeeld de Minard Diagrammen voor de goederen, maar we zijn ons hierbij al bewust van de relatief slechte leesbaarheid hiervan. Hoewel het design al enige aandacht heeft gekregen zijn is er nog steeds veel te verbeteren. Al met al zijn nog oneindig veel mogelijkheden om deze applicatie betekenisvoller te maken.

### Interpretatie

Deze applicatie is vrijwel nog niet geïnterpreteerd. Erik is op dit moment bezig met een scriptie over dit onderwerp te schrijven. De evaluatie van database en interface nemen daarbinnen een plek in. Onze verwachting is dat metname de goederen meer inzicht zullen gaan bieden. Het routenetwerk is relatief simpel zodat een netwerkanalyse vooral open deuren gaat opleveren. Wellicht zit hierin voor de interne Aziatische handel wel betekenis. Uitbreiding van de visualisatie methoden en fatsoenlijk literatuur onderzoek zijn noodzakelijk om meer hierover te zeggen. Interne relaties tussen schepen zijn al wel goed zichtbaar door de focus op een dynamische visualisatie, maar hun betekenis behoeft verder onderzoek. De bron kan al wel binnen enkele minuten op waarde worden geschat en met de interface wordt er een interessante ingang voor exploratie geboden.
---- 

[^1]:	Huygens/ING. *Boekhouder-Generaal Batavia. 2013.* Web. 16 Jan 2016. 
	\<[http://bgb.huygens.knaw.nl/][1]\>

[^2]:	AMH Projectgroep. *Atlas of Mutual Herritage.* Web. 16 Jan 2016. \<[http://www.atlasofmutualheritage.nl/en/][2]\>

[^3]:	Zummeren, Erik en Robert-Jan Korteschiel. Historical Dutch Asiatic Trade. 2016. Web. 16 Jan 2016. \<[https://github.com/hdat][3]\>

[^4]:	Huygens/ING. *Generale Missiven van Gouverneurs-Generaal en Raden aan Heren XVII der Verenigde Oostindische Compagnie.* Web. 16 Jan 2016. \<[http://resources.huygens.knaw.nl/vocgeneralemissiven][4]\>

[^5]:	Emory University. The Transatlantic Slave Trade Database. Web. 16 Jan 2016. \<[http://www.slate.com/articles/life/the\_history\_of\_american\_slavery/2015/06/animated\_interactive\_of\_the\_history\_of\_the\_atlantic\_slave\_trade.html][5]\>\<[http://www.slavevoyages.org/]()\>

[1]:	http://bgb.huygens.knaw.nl/
[2]:	http://www.atlasofmutualheritage.nl/en/
[3]:	https://github.com/hdat
[4]:	http://resources.huygens.knaw.nl/vocgeneralemissiven
[5]:	http://www.slate.com/articles/life/the_history_of_american_slavery/2015/06/animated_interactive_of_the_history_of_the_atlantic_slave_trade.html
