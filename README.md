# ehealth-maken

<b>Proof of Concept onderzoeksverslag</b>

<b>Inleiding</b>

Om de design challenge van het project op te lossen heb ik samen met mijn team meerdere deelvragen bedacht. Ik ga mij focussen op deelvraag 1; “Hoe kan de app beter aansluiten bij de wensen en doelen van de gebruiker?”. Om dit op te lossen ga ik de homepagina van de app aanpassen. De gebruiker kan op dit moment alleen een foto opsturen van een activiteit. In de nieuwe app kunnen gebruikers meer delen met elkaar zoals positieve quotes, video’s, foto’s, muziek en artikelen (update: de gebruiker kan alleen foto's en video's delen). Zo ontstaat er een plek waar patiënten met BDD positieve ervaringen met elkaar kunnen delen, als een social media kanaal. De app is afgeschermd en de content is alleen beschikbaar voor mensen in dezelfde groep. 

De homepagina van de app is op dit moment statisch en niet vormgeven met de stijl die wij voor ogen hebben. Om de homepagina aantrekkelijker te maken wil ik de lay-out veranderen door inspiratie op te doen van Pinterest. Ik wil erachter komen hoe ik de homepagina technisch gezien kan maken. Zo wil ik onderzoeken of ik flexbox het beste kan gebruiken en hoe ik ervoor kan zorgen dat de gebruiker de verschillende soorten content kan inleveren. Op visueel gebied wil ik de homepagina opnieuw vormgeven in photoshop en verder uitwerken in Framer. 

<b>Aanpak onderzoek</b>

Om erachter te komen hoe ik de lay-out van de homepagina moet maken ga ik starten met desk-research. Zo wil ik onderzoeken of ik flexbox het beste kan gebruiken of dat er andere hulpmiddelen zijn wat mij verder kan helpen. Ik ga dus op zoek naar bestaande code. Ook ga ik kijken naar mijn bron van inspiratie; Pinterest zelf. Ik ga de lay-out van de app en de website onderzoeken. 

<b>Resultaten</b>

Als eerste heb ik gebruik gemaakt van een expert review. Emiel Zuurbier liet mij de Isotope zien. De manier waarop ik later in het project de lay-out kan coderen. Hij vertelde dat als ik flexbox gebruik de blokken waarin de content wordt weergegeven een vaste lengte hebben. De blokken content verschijnen niet vloeiend naast en onder elkaar. Maar door de code op http://isotope.metafizzy.co/faq.html te gebruiken wordt de lay-out soepeler en visueel aantrekkelijker. Isotope heeft meerdere licenties. Het is open source zolang je het voor persoonlijke projecten gebruikt. Stukjes code zijn op de website te vinden en onderverdeeld onder verschillende categorieën, zoals ‘Filtering’, ‘Sorting’, ‘Layout’, ‘Layout modes’, ‘Methods’ en ‘Events’. Onder het kopje layout worden meerdere oplossingen uitgelegd met code, met daarbij voorbeelden op CodePen.

Ten tweede heb ik deskresearch uitgevoerd. Ik zocht op google naar ‘Pinterest layout code’ en vond meteen een oplossing op CodePen. De oplossing heet de ‘Pure CSS Pinterest Columnar Layout’ en is gemaakt door Dudley Storey. Het is te vinden op https://codepen.io/dudleystorey/pen/yqrhw. Wat hij heeft gemaakt is precies wat ik in mijn hoofd had voor de layout. De afbeeldingen worden op een mooie manier naast en onder elkaar weergegeven terwijl de afbeeldingen dezelfde lengte en breedte hebben. Er geen Javascript nodig, alleen HTML en CSS.

<b>Conclusie</b>

De vraag die ik wilde beantwoorden was; 'Hoe los ik de homepagina van de BDD technisch op?'. Aan de hand van het onderzoek weet ik inmiddels dat er genoeg op het internet te vinden is om de Pinterest lay-out na te maken. De voorbeelden die ik heb gevonden geven duidelijk weer wat ik voor ogen heb. Als ik de eerste versie zou gebruiken dan moeten kosten daarvoor berekend worden. Maar er zijn meerdere gratis mogelijkheden te vinden online. 

<b>Bronnen</b>

1: http://isotope.metafizzy.co/faq.html
2: https://codepen.io/dudleystorey/pen/yqrhw


# Aanvulling

<b>Het prototype</b>

Tijdens project eHealth heb ik gewerkt aan een prototype voor de BDD MyHealthDiary app. In het project nam ik de rol aan van Visual Interface Designer daarom heb ik gelet op een nieuwe vormgeving van de app. Ik heb ook een gedeelte van de app onderzocht en opnieuw ontworpen, namelijk de homepagina en een chatfunctie. Het prototype bestaat uit de homepagina (deze is scrolbaar), een hamburgermenu, een chat en het openen van een gesprek. 
- Voor een link naar het Framer prototype zie: http://share.framerjs.com/daqwcadnz2rn/  

<b>Ontwerpbeslissingen</b>

1: De homepagina. De homepagina bestaat uit cards waarop content wordt weergegeven. In het POC hierboven had ik onderzocht hoe een Pinterest layout gecodeerd kan worden. De content types (video en afbeelding) verschijnen op cards in de homepagina. Het idee was dat indien de gebruiker een te klein scherm gebruikt voor twee kolommen de layout zal veranderen naar een single-column layout. 

2: Het hamburgermenu. Ik had een klein onderzoekje uitgevoerd naar het wel of niet toevoegen van een hamburgermenu. Er zitten meerdere nadelen aan het gebruiken van een hamburgermenu. Zo staan de opties van de navigatie verborgen en bestaat er een kans dat de gebruiker de opties niet kan vinden. Ik had toch besloten om een hamburgermenu toe te voegen omdat een andere optie het toevoegen van een tapbar was, een menu onderaan het scherm zoals bij IOS. Bij Android telefoons is al standaard een menu onderaan toegevoegd. Omdat wij dubbele menu's wilden voorkomen hadden wij gekozen voor een hamburgermenu. 

3: Chatfunctie. Als de gebruiker op het chaticoon klikt opent het chatmenu. Hierin kan de gebruiker andere patiënten vinden die online of offline zijn (wordt aangegeven met een rood of groen rondje). Onderaan de chat staat een icoon waarop staat 'mis je nog iemand?'. Als de gebruiker daarop klikt gaat hij/zij naar 'groepen'. Hierin kan hij/zij een ander persoon aan de groep toevoegen. 

4: Openen van chat. Als de gebruiker op een andere gebruiker klikt opent een Modal. Dit is een scherm wat bovenop de andere schermen verschijnt. Als de gebruiker dit scherm weg klikt is nog steeds het chatmenu geopend. Dit zorgt voor een betere interactie flow voor de gebruiker. In de chat krijgt de gebruiker een waarschuwing dat de chat wordt gecontroleerd door een woordfilter. Dit woordfilter (zie Rowenna's project) filtert negatieve woorden uit de chat. 

<b>Nice to haves/Must haves</b>

Er zijn meerdere onderdelen in het prototype wat toegevoegd of veranderd zou kunnen worden.

1: De layout. Ik heb in het prototype een Pinterest layout laten zien met twee kolommen. Wat er nog toegevoegd zou moeten worden is dat als het scherm smal is de layout zal veranderen naar een single-column layout. 

2: Het hamburgermenu. Ik had nog een animatie willen toevoegen dat als de gebruiker op het icoon van het hamburgermenu klikt, het icoon in een vloeiende beweging veranderd naar een kruis icoon. 

3: Chatfunctie. In de chatfunctie staat onderaan "Mis je iemand? Voeg iemand toe". Dit had ik toegevoegd met de bedoeling dat de gebruiker meteen naar groepen gaat en iemand kan toevoegen door iemands email in te voeren. Nu was er verwarring ontstaan over de groepen. Het was niet helemaal duidelijk of er van tevoren een groep wordt aangemaakt met vaste leden of dat je zelf mensen toevoegt in jou groep. Ook zou je daaruit weer kunnen selecteren wie er dan in de chatfunctie verschijnt. Ik had bedacht dat alle leden in de chatfunctie komen en dat je handmatig nog iemand zou kunnen toevoegen. Dit gedeelte was niet helemaal duidelijk.

4: Openen van chat. Na de presentaties bleek dat de chatfunctie nog steeds niet gewenst was, zelfs nadat het gereguleerd zou worden. Ook al wordt er een woordfilter op gezet, ook al zijn er waarschuwingen, een chat zou niet zo snel toegevoegd worden. Voor meer uitleg over de chat en het commentaar van het AMC, zie het onderzoeksverslag. 

<b>Progressie</b>

Tijdens dit project heb ik mij gefocust op de rol van Visual Interface Designer. Daarom had ik als doel opgesteld om Framer te leren kennen en met deze tool mijn eindopdracht te maken. Ik heb wel in de POC uitgezocht hoe de Pinterest layout gemaakt zou kunnen worden maar ik had besloten om daar zelf niet mee verder te gaan. Ik wilde namelijk mijn doel behalen om beter te worden met Framer. Ik denk namelijk dat Framer mij erg kan gaan helpen als ontwerper. Ik werk mijn ontwerpen eerst uit in Photoshop, dat blijft statisch. Dankzij Framer komen mijn ideeën en interacties veel beter over dan in een statisch afbeelding. Ik verwacht dat ik in aankomende projecten eerder mijn ontwerpen zal uitwerken in Framer dan bijvoorbeeld in Invision omdat er veel meer mogelijkheden zijn voor bijvoorbeeld animaties. 

Het was voor mij even uitzoeken hoe ik Framer precies moest gebruiken. Ik had namelijk eerder interacties uitgewerkt in Framer met één scherm. Dat was veel makkelijker omdat er geen flow bestond van meerdere schermen. Met dit prototype moest ik rekening houden met meerdere schermen in mijn photoshop bestand. Framer zet namelijk het linkerscherm als standaard scherm in het prototype. Omdat daar mijn hamburgermenu stond was het voor mij uitzoeken hoe ik het scherm van de homepagina in het midden kon krijgen. Dit heb ik opgelost door te werken met states. Er ging veel tijd zitten in het uitzoeken hoe ik Framer moest gebruiken, daarbij heb ik ook gekeken naar hun handleidingen. Omdat ik nu weet hoe het werkt zal ik de volgende keer sneller een prototype kunnen maken. 
