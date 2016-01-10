
## GP - Geography of Post

Geography of the Post is een project dat de expansie van de VS in westelijke richting probeert te verklaren aan de hand van postkantoren.

### Data

Deze interface gebruikt een dataset dat gecompileerd is vanuit de ‘United States Post Offices, Volumes 1-8’ door Richard Helbrock. Deze data is vervolgens verbonden met het ‘Geographic Names Information System (GNIS)’ waar hoogst waarschijnlijk de coördinaten vandaan komen. De selectie van de data lijkt daarmee vooral pragmatisch van natuur. Hoewel de auteurs graag lagen aan de kaart willen toevoegen is dat tot op heden niet gebeurd. De gevisualiseerde eenheid is daardoor relatief simpel en vooral door de aggregatie interessant.

De datasets zijn in ruwe vorm online beschikbaar. Dit maakt controle daarvan relatief simpel. Het is een ruwe CSV met voor ieder postkantoor de naam, jaartallen en coördinaten. Het is goed gezien welke record verbonden kon worden met het GNIS en welke niet doordat beide bestanden leesbaar zijn. Er zijn helaas geen links naar duurzame opslag van deze data. Github is een degelijke site, maar kan uiteindelijk ook zomaar weggeschoven worden zoals SourceForge. Helaas is er ook geen contextualisatie met de context waaruit de data is geconstrueerd. Waarschijnlijk bied het werk van Helbrock dit, maar dit is niet gemakkelijk vindbaar. 

### Implementatie

Een grot 