
## GotP - Geography of the Post

Geography of the Post is een project dat de expansie van de VS in westelijke richting probeert te verklaren aan de hand van postkantoren. Hierdoor wordt een nieuw perspectief verschaft aan een verhaal dat anders gedomineerd wordt door goudzoekers, spoorwegarbeiders en indianen.[^1]

### Data

Deze interface gebruikt een dataset dat gecompileerd is vanuit de ‘United States Post Offices, Volumes 1-8’ door Richard Helbrock. Deze data is vervolgens verbonden met het ‘Geographic Names Information System (GNIS)’ waar hoogst waarschijnlijk de coördinaten vandaan komen.[^2] De selectie van de data lijkt daarmee vooral pragmatisch van natuur. Hoewel de auteurs graag lagen aan de kaart willen toevoegen is dat tot op heden niet gebeurd. De gevisualiseerde eenheid is daardoor relatief simpel en vooral door de aggregatie interessant.

De datasets zijn in ruwe vorm online beschikbaar. Dit maakt controle daarvan relatief simpel. Het is een ruwe CSV met voor ieder postkantoor de naam, jaartallen en coördinaten. Het is goed gezien welke record verbonden kon worden met het GNIS en welke niet doordat beide bestanden leesbaar zijn. Er zijn helaas geen links naar duurzame opslag van deze data. Helaas is er ook geen contextualisatie met de context waaruit de data is geconstrueerd. Waarschijnlijk bied het werk van Helbrock dit, maar een korte beschrijving hiervan zou wenselijk toevoegend zijn.

### Implementatie

De code is beschikbaar op Github en voorzien van een korte documentatie. Helaas is ook hier de code niet modulair opgezet en daardoor niet goed begrijpbaar op het eerste gezicht, maar aangezien er relatief weinig code is, is dit te overzien. Daarnaast is de code voorzien van inline documentatie. Het script dat de verbinding met het GNIS heeft uitgevoerd is echter niet vindbaar; hierdoor ontstaan vraagtekens of de postkantoren wel werkelijk op hun correcte coördinaten liggen. De auteurs vermelden ook dat hun implementatie bepaalde zaken zoals naamsveranderingen, en meerdere sluiting en openingen op dezelfde locatie niet in acht heeft genomen. Interessant aan de interface is de keuze voor het westen van de VS, de data voor het oosten lijkt immers ook beschikbaar. Dit is logisch vanuit de onderzoeksvraag, maar de interface zou met kleine moeite ook het oosten kunnen weergeven.

Het design heeft voldoende aandacht gekregen. De interface voelt   intuïtief aan en er zijn ook reflecties beschikbaar over de gemaakte keuzes. Zo zijn andere modi van visualisatie beschreven en de redenen waarom deze uiteindelijk zijn gekozen. Hieraan heeft een kan een volgende onderzoeker, die wellicht wil verder bouwen aan dit onderzoekgebied steun. De interface laad iets of wat traag, maar dit was onvermijdelijk aangezien het grote aantal punten dat de onderzoekers wouden weergeven. De kaart maakt slim gebruik van kleur, interface elementen, lagen en meerdere views. Interactiviteit tussen de elementen is slim met hovers geregeld. Al met al is dit een goed uitgewerkte interface, waaraan weinig aan op te merken valt.[^3]

## Interpretatie

De project is verwerkt in een 287 pagina’s tellende dissertatie. [^4]Aangezien dit doorlezen ver buiten het bereik van dit essay valt volsta ik met een blogpost die de auteur rondom die project heeft geschreven.[^5] Hierin gebruikt hij de data van de postkantoren om een alternatief perspectief te geven op expansie van de Anglo-Amerikaanse cultuur westwaarts. De postkantoren zijn de eerste institutie die in afgelegen gebieden werd opgezet en laat zo duidelijk de vraag vanuit de gebieden zien en de reactie van de overheid daarop. De postkantoren bieden de ruimte om de simultane natuur van de verhalen van de goudzoeker, spoorwegen, soldaat en agrariër te vertellen. 

Maar ook de contextualisatie met de evenementen die ter grondslag liggen aan de postkantoren krijgen aandacht met dit essay. Het ontstaan clusters van postkantoren in de Black Hills zegt op zichzelf niks van geweld dat hieraan vooraf is gegaan. South Dakota was een slagveld tussen de VS en de Lakota’s en Cheyennes. De postkantoren creëren ook negatieve ruimte wat vragen oproept. In de dissertatie zal dit ongetwijfeld uitgebreid onder de aandacht zijn gekomen. Hoewel de visualisatie moeilijk is te interpreteren door een leek, is het een bron van vragen die onderzoeker 287 pagina’s lang bezig kan houden.
---- 

[^1]:	[http://cameronblevins.org/gotp/][1]

[^2]:	[http://geonames.usgs.gov/][2]

[^3]:	[http://jasonheppler.org/2014/10/30/research-design-in-geography-of-the-post/][3]

[^4]:	dissertatie

[^5]:	[http://www.cameronblevins.org/posts/postal-geography-and-the-golden-west/][4]

[1]:	http://cameronblevins.org/gotp/
[2]:	http://geonames.usgs.gov/
[3]:	http://jasonheppler.org/2014/10/30/research-design-in-geography-of-the-post/
[4]:	http://www.cameronblevins.org/posts/postal-geography-and-the-golden-west/