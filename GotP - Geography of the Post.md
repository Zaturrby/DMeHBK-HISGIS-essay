## GotP - Geography of the Post

Geography of the Post is een project dat de expansie van de VS in westelijke richting probeert te verklaren aan de hand van postkantoren. Hierdoor wordt een nieuw perspectief verschaft aan een verhaal dat anders gedomineerd wordt door goudzoekers, spoorwegarbeiders en indianen.[^1]

### Data

Deze interface gebruikt een dataset dat gecompileerd is vanuit de ‘United States Post Offices, Volumes 1-8’ door Richard Helbrock. Deze data is vervolgens verbonden met het ‘Geographic Names Information System (GNIS)’ waar hoogst waarschijnlijk de coördinaten vandaan komen. De selectie van de data lijkt daarmee vooral weer pragmatisch van natuur. Hoewel de auteurs graag lagen aan de kaart willen toevoegen is dat tot op heden niet gebeurd. De gevisualiseerde eenheid is daardoor relatief simpel en vooral door de aggregatie interessant. Interessant aan de is keuze voor het westen van de VS, de data voor het oosten lijkt immers ook beschikbaar. Hier neemt de onderzoeksvraag precedent op de data en wellicht het idee van de ‘deep map’.

De datasets zijn in ruwe vorm online beschikbaar. Dit maakt controle daarvan relatief simpel. Het zijn CSV-bestanden met voor ieder postkantoor de naam, jaartallen en coördinaten. Het is goed gezien welke records verbonden konden worden met het GNIS en welke niet doordat beide bestanden leesbaar zijn. Er zijn helaas geen links naar duurzame opslag van deze data. Ook is er ook geen contextualisatie met de context waaruit de data is geconstrueerd. Waarschijnlijk bied het werk van Helbrock dit, maar een korte beschrijving hiervan zou toevoegend zijn.

### Implementatie

De code is beschikbaar op Github en voorzien van een korte documentatie. Helaas is ook hier de code niet modulair opgezet en daardoor niet direct begrijpbaar, maar dit is te overzien. Daarnaast is de code voorzien van inline documentatie. Het script dat de verbinding met het GNIS heeft uitgevoerd is echter niet vindbaar; hierdoor ontstaan vraagtekens of de postkantoren wel werkelijk op hun correcte coördinaten liggen. De auteurs vermelden ook dat hun implementatie bepaalde zaken zoals naamsveranderingen en meerdere sluitingen en/of openingen op dezelfde locatie niet in acht zijn genomen. 

Het design heeft voldoende aandacht gekregen. De interface voelt   intuïtief aan en er zijn ook reflecties beschikbaar over de gemaakte keuzes. Zo zijn andere modi van visualisatie beschreven en de redenen waarom deze uiteindelijk zijn gekozen. Hieraan heeft een latere onderzoeker steun. De interface laad iets of wat traag, maar dit was onvermijdelijk aangezien het grote aantal punten dat de onderzoekers wouden weergeven. Qua design  maakt de applicatie slim gebruik van kleur, interface elementen, lagen en meerdere views. Interactiviteit tussen de elementen is slim met hovers geregeld en bied de gebruiker extra informatie. Al met al is dit een goed uitgewerkte interface, waar weinig aan op te merken valt.[^2]

### Interpretatie

Dit project is verwerkt in een 287 pagina’s tellende dissertatie.[^3] Aangezien dit doorlezen ver buiten het bereik van dit essay valt volsta ik met een blogpost die de auteur rondom dit project heeft geschreven.[^4] Hierin gebruikt hij de data van de postkantoren om een alternatief perspectief te geven op expansie van de Anglo-Amerikaanse cultuur westwaarts. De postkantoren zijn de eerste institutie die in afgelegen gebieden werd opgezet. Ze laten zo duidelijk de vraag naar post vanuit de gebieden zien en de reactie van de overheid daarop. De postkantoren bieden de ruimte om de simultane natuur van het verhaal van de agrariër met de verhalen van de goudzoeker, spoorwegen en soldaat te vertellen.

De contextualisatie met particulariteiten is bijzonder waardevol. De gebeurtenissen die ter grondslag liggen aan de postkantoren krijgen aandacht met dit essay. Het ontstaan clusters van postkantoren in de Black Hills zegt op zichzelf niks van geweld dat hieraan vooraf is gegaan. South Dakota was een groot slagveld tussen de VS en de inheemse bevolking. Deze dimensie wordt aangeboord door literatuurstudies en in een groter perspectief geplaatst door de visualisatie. De postkantoren creëren ook negatieve ruimte. De vraag van ‘Waarom hier en elders niet?’ wordt hierdoor opgeroepen. In de dissertatie zal dit ongetwijfeld uitgebreid onder de aandacht zijn gekomen. 

In eerste instantie leek de visualisatie weinig diepgang te bevatten. Maar hoewel de visualisatie moeilijk is te interpreteren door een leek, is het een bron van vragen die onderzoeker 287 pagina’s lang bezig kan houden.
---- 

[^1]:	Blevins, Cameron en Jason Heppler. *Geography of the Post: U.S. Post Offices in the Nineteenth-Century West.* Web. 16 Jan 2016. \<[http://cameronblevins.org/gotp/][1]\>

[^2]:	Heppler, Jason. *Research and Design in Geography of the Post.* 10 okt 2014. Web. 16 Jan 2016. \<[http://jasonheppler.org/2014/10/30/research-design-in-geography-of-the-post/][2]\>

[^3]:	Blevins, Cameron. *The Postal West: Spatial Integration and the American West, 1865-1902.* Juni 2015. Dissertatie. 

[^4]:	Blevins, Cameron. *Postal Geography and the Golden West.* 30 okt 2014. Web. 16 Juni 2016. \<[http://www.cameronblevins.org/posts/postal-geography-and-the-golden-west/][3]\>

[1]:	http://cameronblevins.org/gotp/
[2]:	http://jasonheppler.org/2014/10/30/research-design-in-geography-of-the-post/
[3]:	http://www.cameronblevins.org/posts/postal-geography-and-the-golden-west/