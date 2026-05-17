# Develop 2 – Antropometrische Studie
## Deel II: Analyse van Heup– en Beenafmetingen - Plaatsing van Bakjes
### 1 Onderzoeksdoel

Het doel van dit onderzoek is om de afstand(en) tussen de bakjes van een nieuwe prototype iteratie (aangeduid met rood op Figuur 1) te definiëren. Zie Deel I: Analyse van Voetafmetingen – Dimensionering van Bakje voor een beschrijving en conceptuele weergave van de verwachte functionaliteiten van dit prototype. Deze onbekende dimensie(s) wordt/worden bepaald doormiddel van een antropometrische analyse, gebruikmakend van bestaande betrouwbare antropometrische gegevens.

![](/img/antro2/Ant1.png)

*Figuur 1: Theoretisch model waarvan de afmeting(en) in het rood in dit onderzoek gedefinieerd worden*

---
### 2 Motivatie

Voor deze toepassing wordt een antropometrische analyse als noodzakelijk beschouwd, enerzijds omwille van het feit dat het onderzoeksproces zich in de tweede deelfase van de ontwikkelingsfase bevindt, waardoor van “quick and dirty” prototyping meer overgegaan moet worden tot iets degelijkere, beter uitgewerkte ontwerpiteraties. Anderzijds omwille van het feit dat de afstand tussen de bakjes om door (bijna) alle mensen bruikbaar te kunnen zijn, zeer moeilijk intuïtief te bepalen is. Deze data zijn ook nog verder in het proces bruikbaar, in het geval dat niet met dit concept verdergegaan wordt.

---
### 3 Data
Als bron aan antropometrische gegevens wordt DINBelg gebruikt. 

DINBelg biedt geen eenduidige gegevens voor de voet-tot-voetafstand in ruststand.

Als gevolg wordt deze afstand op basis van de heupbreedte geschat, met een factor 0,6 à 0,7 als verhoudingscoëfficiënt (zie Figuur 2 ter illustratie).

![](/img/antro2/Ant2.png)

*Figuur 2: Benadering van voet-tot-voetlengte in rustende zitstand doormiddel van de heupbreedte*

De afname van nauwkeurigheid die deze aanname introduceert, dient weggewerkt te worden door genoeg speling op beide extrema te voorzien.

Voor de grootste voet-tot-voetafstand worden de maximale heupbreedtes van beide geslachten tussen 18 tot 65 jaar, binnen het 99ste percentiel (P99) vergeleken. De afstand wordt dan geschat door de grootste maat met de factor 0,7 te vermenigvuldigen.

Hetzelfde gebeurt voor de kleinste voet-tot-voetafstand, maar dan voor kinderen van 6 jaar, binnen het 1ste percentiel (P1). De afstand wordt dan geschat door de kleinste maat met de factor 0,6 te vermenigvuldigen.

De verzameling aan gegevens, alsook de overeenstemmende benaderde voet-tot-voetlengtes, zijn verzameld in Tabel 1.

*Tabel 1: Antropometrische gegevens van voetdimensies uit DINBelg*

| Populatiebeschrijving | Heupbreedte (mm) | Benaderde voet-tot-voetlengte (mm) |
|---|---:|---:|
| Mannen, 18-65, P99 | 430 |  |
| Vrouwen, 18-65, P99 | 483 | 338,1 ≈ 340 |
| Jongens, 6, P1 | 175 | 105 |
| Meisjes, 6, P1 | 180 |  |

---
### 4 Data analyse

De benadering van de voet-tot-voetafstand varieert tussen 105mm en 340mm voor de gekozen extremumgroepen. 

---
#### 4.1 Dimensionering van concept

De onnauwkeurigheid door de benadering wordt weggewerkt door beide verder in de richting van hun resp. extremum af te ronden:
-	Minimum: 105mm -> 100mm  
-	Maximum: 340 -> 350mm

De dimensies van de bakjes zijn te vinden in Deel I: Analyse van Voetafmetingen – Dimensionering van Bakje. Deze nieuwe waarden vormen de afstanden tussen de middens van de bakjes, zoals geïllustreerd in Figuur 1.

---
#### 4.2 Analyse van dimensionering

Beide edge cases: tall en small, worden geanalyseerd.

---
##### 4.2.1 Edge case: Design for the small

Bij de kleinste genomen voet-tot-voetafstand duikt mogelijks een probleem op. De bakjes zijn zodanig breed als gevolg van de vereiste om de grootste voeten (man, 18 - 65 jaar, P99) te kunnen accommoderen, dat deze kleinste afstand, bepaald in 4.1., niet bereikt kan worden. De bakjes overlappen deels.

Deze situatie wordt in Figuur 3 weergegeven, met de overlapping in het rood:

![](/img/antro2/Ant3.png)

*Figuur 3: Analyse van edge case MIN waarin een potentieel probleem wordt aangetroffen*

Als de bakjes met huidige afmetingen zouden uitgewerkt worden in vaste vorm, zou de minimale toegelaten voet-tot-voetafstand vergroten tot 130mm tegenover de gewenste 100mm, wat een zeker deel van de groep zou “uitsluiten” (zie Figuur 4). 

ALS dit een probleem vormt, kan er op enkele manieren mee omgegaan worden:

  1.	Accepteer de “uitsluiting” van het betroffen deel van de groep en ga verder met huidige         ontwerpvisie.
  2.	Maak de vereisten minder streng.
  3.	Verander het ontwerp om dit deel van de groep toch niet uit te sluiten.

![](/img/antro2/Ant4.png)

*Figuur 4: Minimale voet-tot-voetafstand voor de bakjes, toegelaten door het huidig ontwerp*

Om te kunnen beslissen of deze limiet aan minimale afstand effectief een probleem vormt, moet bepaald worden of er effectief sprake is van een uitsluiting of niet. De genomen voet-tot-voetafstanden zijn namelijk referenties maar niet bindend voor gebruik. Hierop wordt verder dieper ingegaan:

De afstand tussen de bakjes is tot nog toe bepaald doormiddel van de voet-tot-voetafstand van een persoon in rustende zithouding. Dit betekent met de benen naar voor staand, zoals afgebeeld in Figuur 5:

![](/img/antro2/Ant5.png)

*Figuur 5: Weergave van hetgeen bedoeld wordt met “neutrale zitpositie”*

Het gebruik van deze neutrale zitpositie als gegeven voor een groep is zinvol voor de maximale afstandsmaat, om te bepalen hoe klein het mag zijn, zodat het nog steeds comfortabel bedienbaar is door de personen met de grootste voeten (maximale compactheid bereiken). Dit is echter niet bindend in de zin dat het product enkel bedienbaar is in deze positie.

De benen kunnen uitwijken langs de zijkant en tot op een bepaalde uitwijking is dit theoretisch gezien nog steeds comfortabel bedienbaar.

Om te bepalen wat deze maximale comfortabele uitwijking is, wordt de Comfort Analysis van Dreyfuss 3D uitgevoerd, ook binnen het Human Body Toolpakket van NX. De relevante resultaten hiervan zijn weergegeven in Figuur 6:

![](/img/antro2/Ant6.png)

*Figuur 6: Resultaten van comfort analyse, betreffende de maximale comfortabele uitwijking van benen in rustende zitpositie*

Opmerkingen: 
  1.	Met de Human Body tool kunnen geen mensen jonger dan 18 jaar gegenereerd worden. Ook is
     geen Belgische data bruikbaar (Duitse data komt wel sterk overeen). Deze analyse geeft een
    	goed idee maar is dus geen analyse die 100% overeenstemt met de onderzochte groepen (6
    	tot 11 à 12-jarige Belgen).
  3.	Comfort van de enkels bij draaien van de voet is geen metriek die door de comfortanalyse
     onderzocht wordt. Echter is een uitwijking zo klein als 11 graden al genoeg voor bediening
    	en hiervan wordt verondersteld dat het geen discomfort zal bieden.

Zonder specifieke berekeningen uit te voeren, kan al gesteld worden dat de voeten comfortabel plaatsbaar zijn, met een voet-tot-voetafstand die op zijn minst overeenstemt met de heupbreedte.

De P1 heupbreedtes van jongens en meisjes van 6 jaar zijn resp. 175mm en 180mm (zie Tabel 1). Dit terwijl de nieuwe kritische afstand slechts 130mm bedraagt (Figuur 4).

**Met deze gegevens is het dus zeer veilig om te stellen dat deze geometrische beperking geen problemen zal bieden bij gebruik voor de kleinere groepen. Er worden geen nieuwe groepen uitgesloten.**

---
##### 4.2.2 Edge case: Design for the Tall

Figuur 7 biedt een weergave van de grootst genomen voet-tot-voetafstand, toegepast op het ontwerp:

![](/img/antro2/Ant7.png)

*Figuur 7: Maximale voet-tot-voetafstand voor de bakjes*

---
##### 4.2.3 Vergelijking van edge cases

Als basis om te bepalen welke implicaties deze uiterste afstanden hebben op het ontwerp, worden ze bij elkaar gevoegd om te vergelijken. Dit is afgebeeld in Figuur 8:

![](/img/antro2/Ant8.png)

*Figuur 8: Vergelijking van maximale en minimale voet-tot-voetafstand voor de bakjes*

---
##### 4.2.4 Implicaties van edge cases op ontwerp
###### 4.2.4.1 Design strategie

Het interval waarbinnen de voet-tot-voetafstanden liggen is [130, 350]. De ideale afstand voor de gemiddelde persoon binnen de groep waarvoor ontworpen wordt, ligt gezien ergens op een punt hierbinnen.

Het ontwerp moet dus niet enkel deze uiterste afstanden kunnen bieden, maar ook deze hiertussen, al dan niet met zekere intervallen.

Het is vanzelfsprekend dat in deze situatie gekozen wordt voor de design strategie design for adjustability. Anders zou immers design for the tall de enige overblijvende keuze zijn welke de hele groep includeert en dit zou tot veel te brede, onbruikbare en onhandige pedalen leiden, zoals geïllustreerd in Figuur 9:

![](/img/antro2/Ant9.png)

*Figuur 9: Redeneringsproces en illustratie, welke de designstrategie design for the tall verwerpen en design for adjustability als beste keuze selecteren*

---
###### 4.2.4.2 Implicaties van design strategie

Design for adjustability als designstrategie kiezen voor dit ontwerp houdt in dat het instelbaar moet gemaakt worden binnenin het interval van extrema. De plaats waar de voeten komen moet hiertussen ingesteld kunnen worden.

Constraints hierbij om functionaliteit van het product te behouden:

1.	De knoppen moeten (de optie bieden) om op eender welke instellocatie even makkelijk
    bereikbaar te blijven door de voet(en).
->	De knoppen bewegen mee met de instelling of bieden in ieder geval deze optie. 

2.	De muren moeten (de optie bieden) om op eender welke instellocatie de voet(en) te
    begrenzen/constrainen/vasthouden, en de knoppen blijven behuizen.
->	Muren bewegen mee met de instelling of bieden in ieder geval de optie en zijn bij deze
  	instelling vast genoeg om de voet vast te blijven houden en tegen een stootje te kunnen,
  	bijvoorbeeld wanneer het kracht ondervindt als een knop wordt ingedrukt.

---
#### 4.3 Conceptgeneratie

Het conceptualisatieproces en de resultaten, gebruikmakend van de bekomen designimplicaties en dimensionering worden hier beschreven.

---
##### 4.3.1 Algemene principes

De constraints leggen vast dat de muren en de knoppen mee ingesteld moeten kunnen worden met de instelling van voetplaatsing en dat de muren in elk van de mogelijke instellingen vast genoeg moet staan zodat ze de voeten kunnen vasthouden en niet bewegen tijdens bijvoorbeeld het indrukken van de knoppen.

Met dit in gedachten wordt geopteerd voor een interval schuifsysteem. Een intervalsysteem heeft namelijk enkele voordelen boven continue instellingen:

-	Het instelstuk kan beter geborgd worden, met name zijwaartse borging, welke met continue
  instelling moeilijker te bereiken is. Dit is een groot pluspunt omdat praktisch enkel
 	horizontale krachten moeten opgevangen worden en de horizontale borging dus de belangrijkste
 	is.

-	Minder cognitieve belasting: als aan de gebruikers de mogelijkheid wordt gegeven om het
  product op eender welk punt in te stellen, is de kans groter dat hij/zij lang bezig zit aan
 	kleine tweaks om het “perfect” te krijgen, terwijl instelmogelijkheid constrainen tot enkele
 	punten ervoor zorgt dat de gebruiker slechts een van deze punten dient uit te kiezen en er
 	dan niet meer over hoeft te denken. 

*Dus ja, er wordt vrijheid van personalisatie ontnomen van de gebruiker, maar met voldoende klein genomen intervallen zouden alle gebruikers nog steeds een gepast instelpunt moeten kunnen vinden.*

-	Dit gaat verder op het vorige punt, irritaties zoals per ongeluk het stuk te ver verschuiven,
  zodat je de “sweet spot” weer terug moet gaan zoeken, worden grotendeels geëlimineerd met dit
 	systeem, aangezien het minder makkelijk per ongeluk verschuift door de zijwaartse borging,
 	maar ook omdat zo’n intervalpunt makkelijker terug te vinden is.

Het conceptueel behuizingstuk van het interval schuifsysteem: “Rail”, wordt in Figuur 10 weergegeven:

![](/img/antro2/Ant10.png)

*Figuur 10: Conceptuele illustratie van het behuizingonderdeel van het schuifsysteem: “Rail”*

Zoals zichtbaar wordt gekozen voor een dubbele rij. Dit heeft als doelen extra zijwaartse borging toe te voegen, waardoor het sterker wordt en om het schuifstuk recht verticaal te houden.

De volgende stap is om te bepalen **wat** er verschuift wordt.

Hier zijn 2 opties:
    -	Bakjes verschuiven ten opzichte van elkaar
    -	Muren verschuiven ten opzichte van elkaar
Beide opties worden geanalyseerd op hun eigen voor- en nadelen:

---
###### 4.3.1.1 Bakjes Verschuiven

-	**Voordelen**
  - Minder cognitieve belasting en tijdsinname dan muurverschuiving, want minder te verschuiven
    onderdelen
  - Wordt beschouwd als een intuïtievere optie
  -  Minder complex
-	**Nadelen**
  - Vaste breedte van bakjes

---
###### 4.3.1.2 Muren verschuiven

-	Voordelen
  - Instelbare breedte van bakjes
-	Nadelen
  - Meer cognitieve belasting en tijdsinname dan muurverschuiving, want meer te verschuiven
    onderdelen
  - Wordt beschouwd als minder intuïtief
  - Complexer
  - 
Hier is 1 aspect zeer interessant: muurinstelling biedt de mogelijkheid om niet enkel de positie van voetplaatsing in te stellen, maar ook de breedte van de bakjes. Dit gaat dan wel ten koste van extra complexiteit en mogelijks een minder intuïtief geheel.

Dit is interessant, omdat in Deel I: Analyse van Voetafmetingen – Dimensionering van Bakje het grote verschil in voetgroottes binnen de groep leidt tot een zeer groot bakje voor relatief kleine voeten, bij een deel van de groep. Er is echter momenteel nog geen test uitgevoerd om te bepalen of dit effectief een probleem is of niet.

Een algemene zijwaartse denkroute toepasbaar op beide opties, is de vraag hoeveel stukken er verschoven worden.

Hier zijn ook twee mogelijkheden:

-	Alles verschuifbaar maken
  -	Bakjesverschuiving: 2 verschuifbare onderdelen
  -	Muurverschuiving: 4 verschuifbare onderdelen
-	1 stuk vastzetten aan de rail, welke dient als referentiepunt*
  -	Bakjesverschuiving: 1 verschuifbaar onderdeel
  -	Muurverschuiving: 3 verschuifbare onderdelen
  -	
Hierbij wordt gekozen voor de tweede optie: een vast referentiestuk integreren. Hiervoor geldt volgende redenering: het verhoogt intuïtiviteit en vermindert complexiteit, zowel qua onderdelen als het instelproces.

*_referentiepunt, bedoeld als zijnde vergelijkbaar met het opmeten met een schuifmaat: het ene uiteinde blijft vast, terwijl de meter kan verschoven worden._

---
###### 4.3.1.3 Beslissing van verschuifstuk

De muurinstelling biedt een volledige personalisatie aan de gebruiker. De breedte-instelling van de bakjes lijkt hoe dan ook een voordeel. Sommige gebruikers willen mogelijks een bakje dat ruimer zit, andere wat meer spannend. Dit zou er ook voor zorgen dat bij kleine voeten, de afstand tussen de bakjes onder de 130mm kan gebracht worden, wat de limiet van de vaste bakjes is (Figuur 4). 

Er wordt voor deze optie gekozen om verder te gaan in het proces, gebruikmakend van een referentiemuur.

Uit tests zal blijken of dit al dan niet te veel vrijheid biedt aan de gebruiker, de keuze van muurinstelling in plaats van bakjesinstelling niet voldoende intuïtief blijkt, of de referentiemuur het product makkelijk bruikbaar maakt en of ook dit intuïtief is.

---
##### 4.3.2 Vormbepaling en dimensionering
###### 4.3.2.1 Bodemplaat

Gezien besloten is dat de verschuifbare componenten muren worden in plaats van vaste bakjes, kunnen de bodems van de voorgaande bakjes nu samengevoegd worden tot één bodemplaat, waarover de muren zullen verschuiven.

---
####### 4.3.2.1.1 Breedte

De breedte ervan wordt bepaald door de maximale genomen instelafstand van de voorgaande bakjes te nemen (Figuur 7) en hierbij twee helften - oftewel één gehele – maximale voetbreedte bij op te tellen (Tabel 2):

*Tabel 2: Antropometrische gegevens van voetdimensies uit DINBelg*

| Populatiebeschrijving | Voetlengte (mm) | Voetbreedte (mm) |
|---|---:|---:|
| Mannen, 18-65, P99 | 289 | 114 |
| Meisjes, 6, P1 | 157 | 60 |

350 + 114 = **464mm**

---
####### 4.3.2.1.1 Lengte

De lengte wordt bepaald door de maximale voetlengte binnen de groep te nemen (Tabel 2).

Dit biedt het nadeel dat het minder compact is dan als bijvoorbeeld enkel de lengte van een bovenste helft van een voet genomen zou worden, maar er wordt hiervoor gekozen omwille van volgende redeneringen: 

-	Met een voet niet volledig op de plaat, zou de hiel stationair blijven tijdens de bediening
  van een knop langs deze kant. Dit zou aanleiding geven tot het meedraaien van het prototype
 	langs deze kant, welke dan ook voor een misinput langs de andere kant zou kunnen zorgen. Dit
 	wordt geschetst in Figuur 11:

![](/img/antro2/Ant11.png)

*Figuur 11: Illustratie van geanticipeerd probleem dat zou kunnen optreden bij korte bodemplaat: verschuiving van product welke op zichzelf een annoyance is en mogelijks voor misinputs kan zorgen*

Het is de hoop dat als de volledige voet op de bodemplaat rust, in combinatie met goede grip onderaan de plaat, dit effect verminderd zou worden. Dit dient a.d.h.v. verdere tests gevalideerd te worden.

-	Het zou het product intuïtiever kunnen maken:
  Als de gebruiker voelt dat de muren met knoppen aan de rail vooraan hangen en er nog een plat
 	stuk vanachter is overgelaten, is het de hoop dat dit een extra indicatie geeft dat het de
 	bedoeling is om de voeten te plaatsen op de bodemplaat, elk binnen 2 muren, gericht naar de
 	rail.

-	Als de bodemplaat vervaardigd zou worden uit een comfortabel materiaal (wordt verder bepaald
  onder CMF), zou dit prototype met een plaat, waar de volledige voet op past, ook gebruikt
 	kunnen worden op harde/koude/ruwe/vuile… vloeren, terwijl de voeten volledig van de comfort
 	van de bodemplaat kunnen blijven genieten. 

Om het nadeel dat de plaat lomper en minder makkelijk transporteerbaar en opbergbaar zou worden als gevolg van deze gekozen lengte te verhelpen, zal deze opgedeeld worden in twee delen: een onderhelft en een bovenhelft.

Deze zal dan inklapbaar zijn (compacter en beter opbergbaar) en ook uitgerust worden met handvaten, waardoor de gebruiker deze in ingeklapte stand eenvoudig kan ronddragen.

De inklap- en ronddraagprincipes worden in Figuren 12 en 13 afgebeeld:

![](/img/antro2/Ant12.png)

*Figuur 12: Illustratie van het inklapproces, doormiddel van gelijke verdeling van de bodemplaat in twee helften*

![](/img/antro2/Ant13.png)

*Figuur 13: Illustratie van het draagproces, doormiddel van voorziene handvaten*

De lengte van het geheel is dus 289mm (twee helften van 144,5mm)(zie tabel 2)

*Deze dienen elk als richtwaarden. De maten dienen bij voorkeur niet lager dan deze waarden genomen te worden om te vermijden dat mensen worden buitengesloten (vooral bij de breedte) en ook niet onnodig veel groter omdat dit de compactheid vermindert, maar een lichte toename in functie van andere component(en) is toegelaten.*

---
###### 4.3.2.2 Rail (interval schuifsysteem)
####### 4.3.2.2.1 Vormbepaling

Achteraan de bodemplaat komt de rail terecht, met de inkeping/gleuf naar achteren gericht. Op deze manier kunnen de muren zich rond de rail klemmen.

Dit principe wordt geïllustreerd in Figuur 14:

![](/img/antro2/Ant14.png)

*Figuur 14: Plaatsing van de rail, muur en bodemplaatcomponenten en contactpunten tussen de muur en de rail*

De verschuifbare muur beweegt door zijn geometrie vrij in de bovenste rijen. Dit is de schuifstand.

Wanneer de muur op een beschikbaar punt naar beneden geschoven wordt, is deze (met enige speling) horizontaal geborgd. Dit is de vaste stand.

Eens de vaste stand bereikt is, zijn er twee bouten voorzien die de gebruiker dient in te drukken. 

Eentje zit in de muur, aan de kant van de gleuf in de rail, zodanig dat bij indrukken de muur ook (met enige speling) verticaal geborgd is.

De andere zit aan het andere uiteinde van de muur, aan de kant van de gebruiker. Deze dient in het overeenstemmende voorziene gat in de bodemplaat geduwd te worden. Dit zorgt ervoor dat de muur niet (merkbaar) zijwaarts kan wiebelen aan dit uiteinde tijdens gebruik.

Op dit moment is de muur dus langs alle richtingen geborgd, van alle vrijheidsgraden ontnomen.

Het gehele schuif- en borgingsproces wordt in Figuur 15 afgebeeld en in Figuur 16 worden de twee borgingen meer gedetailleerd weergegeven:

![](/img/antro2/Ant15.gif)

*Figuur 15: Werkingsprincipe van het instelproces van de muur, waaronder verschuiving en borging*

![](/img/antro2/Ant16.png)

*Figuur 16: Borgingsprincipes van het instelproces van de muur*

---
####### 4.3.2.2.2 Dimensionering
######## 4.3.2.2.2.1 Breedte van geheel

De breedte van de rail stemt overeen met de breedte van de bodemplaat. 
Deze bedraagt dus (voorlopig) 464mm.

---
######## 4.3.2.2.2.2 Breedtes van intervallen en tussenintervallen

Omdat zowel de gekozen voet-tot-voetafstand en de “bakjes”-breedte vrij te kiezen is, is het zinloos om hiervoor meer- en minder voorkomende instelpunten te bepalen om een variantie in hoeveelheid intervalpunten in zekere regio’s te voorzien.

In werkelijkheid zullen zo goed als alle punten over de gehele lengte wel door iemand binnen de groep gebruikt worden, behalve over de lengte van de minimale voetbreedte, genomen vanaf het referentiepunt, zie Figuur 14. Deze minimale voetbreedte bedraagt 60mm. (Tabel 2)

![](/img/antro2/Ant17.png)

*Figuur 17: Ongebruikt deel van interval door de gekozen gebruikersgroep*

Binnenin dit interval geen borgingspunten voorzien in de rail en de bodemplaat, zou ook kunnen serveren als extra indicatie van hoe het product gebruikt moet worden. Het eerste punt waar de gebruiker de linkse verschuifbare muur zou kunnen vastzetten zou al een zekere ruimte overlaten tot de referentiemuur, waarbinnen 2 knoppen aan weerskanten beschikbaar staan, wat aan de gebruiker duidelijk kan maken dat hier de voet tussen zou moeten komen om de knoppen te bedienen. 

Hierdoor zou hij/zij hopelijk ook kunnen achterhalen dat de twee overblijvende verschuifbare muren dezelfde functie bieden, voor de andere voet.

Of dit effectief zo is, wordt duidelijk uit volgende tests.

Over de rest van de lengte van de rail zijn de instelpunten gelijkmatig verdeeld. Om de breedtes van de intervallen en tussenintervallen te bepalen, worden de doelen ervan overlopen.

  -	Genoeg instelopties bieden aan de gebruiker, maar niet overweldigend veel.
  -	Breedte van intervallen moet breed genoeg zijn om de muren te behuizen, zonder dat de
    instelpunten van de muren breken of losschieten bij horizontale kracht.
  -	Breedte van tussenintervallen moet breed en sterk genoeg zijn om de krachten van de muur op
    de rail op te vangen. 

Dit in rekening gehouden, wordt gekozen voor zowel een interval- als een tussenintervalbreedte van 5mm. Dit wordt weergegeven in Figuur 15:

![](/img/antro2/Ant18.png)

*Figuur 18: Breedtes van intervallen en tussenintervallen*

---
######## 4.3.2.2.2.3 Dikte

De rail moet dik genoeg zijn om in de groefgedeeltes zowel de muur goed in te klemmen (mag niet loskomen) en ook met de overblijvende dikte nog sterk genoeg is. (Zie Figuur 14)

Met dit rekening houdend wordt gekozen voor een dikte van 15mm, met een gleufverhouding van 1/3, wat betekent dat de gleuf 5mm diep is en in de gleuf zo nog 10mm wand overblijft.
Dit wordt afgebeeld in Figuur 19:

![](/img/antro2/Ant19.png)

*Figuur 19: Diktedimensies van de rail*

---
######## 4.3.2.2.2.4 Hoogte van het geheel

Voor de hoogte geldt hetzelfde principe als bij de breedtes van de intervallen en tussenintervallen, namelijk dat moet gekozen worden voor een maat die groot genoeg is om nog steeds voldoende sterk te zijn en de functionaliteiten te volbrengen, maar ook niet te groot, om compactheid te maximaliseren.

Hierbij gaat het om de volgende constraints:

-	Er moeten twee gleuven boven elkaar staan met genoeg ruimte tussen de gleuven zodat bij
  gebruik deze grens niet kan breken.
-	De gleuven zelf moeten een hoogte hebben, groot genoeg zodanig dat de stukken van de muur die
  erin komen (de klemmingsuitsteeksels, te zien in alle Figuren die de muren afbeelden) groot
 	genoeg kunnen zijn zodat deze niet breken bij gebruik en er een bout in kan passen die kan
 	ingeschoven worden bij de borging (zie Figuur 16, het eerste afgebeelde borgingsprincipe).

In functie van deze constraints, gecombineerd met de hoogte van de muren (4.3.2.3.2.2), wordt gekozen voor de dimensies afgebeeld in Figuur 20:

![](/img/antro2/Ant20.png)

*Figuur 20: Hoogtedimensies van de rail*

---
####### 4.3.2.2.3 Gehele dimensionering van rail

Al de aparte designbeslissingen binnen de dimensionering van de rail leiden tot een allesomvattende dimensionering, waarvan de technische tekening in Figuur 21 afgebeeld staat.

Enkele opmerkingen:

-	De afstand waarover de gleuf is weggenomen uit de rail, is gereduceerd van 60mm
  (4.3.2.2.2.2.) tot 55mm aangezien de voornaamste functie ervan is om functionaliteit te
 	indiceren en op deze manier wordt vermeden dat onnodig mensen worden uitgesloten.

-	De breedte van de bodemplaat is verhoogd van 464mm (4.3.2.1.1.) naar 485mm, om de toegevoegde
  breedte door de muren (4.3.2.3.2.1.) op te vangen en ook zodat de gleuf eindigt op een
 	borgingspunt, waarbinnen bij instelling de grootste neutrale voet-tot-voetafstand alsook de
 	grootste voetbreedte kan bereikt worden.

-	De muur, vast inbegrepen aan de rail, volgt de dimensionering van de muren (4.3.2.3.), minus
  het klemstuk.

-	Aan elke verschuifbare muur is een behuizingsstuk voor de geïntegreerde drukknoppen
  (Schneider Electric Harmony Series Contact Block, 600V, 1 NO, zie Bill of Materials)

![](/img/antro2/Ant21.png)

*Figuur 21: Gehele vormgeving en dimensionering van de rail*

---
###### 4.3.2.3 Muren
####### 4.3.2.3.1 Vormbepaling

De muren dienen de voeten op hun plek te houden, tegen een stoot te kunnen en verschuifbaar en borgbaar te zijn binnenin het schuifsysteem.

Dit leidt tot een algemene vorm zoals weergegeven in Figuur 14, met een klemvormig uiteinde welke over de rail loopt en zo in de gleuf terechtkomt.

De hoogte van het muurgedeelte moet groot genoeg zijn om tegen te houden dat de voet erover vliegt bij gebruik en er een knop van de gewenste grootte (4.3.2.5.) in kan geïntegreerd worden. 

De breedte moet groot genoeg zijn zodanig dat de borgingsstukken redelijk goed horizontaal geborgd blijven in de rail en zodanig dat de twee extra borgingsstaven erin geïntegreerd kunnen worden, welke dik genoeg zijn om niet te breken bij gebruik, zoals afgebeeld in Figuren 15 en 16. Ook moet de breedte groot genoeg zijn om voldoende schuifafstand te voorzien voor de knoppen (4.3.2.5.2.4.).

Zowel de hoogte als de breedte moeten groot genoeg zijn om voldoende kracht te kunnen opvangen.

---
####### 4.3.2.3.2 Dimensionering
######## 4.3.2.3.2.1 Breedtes

Voor de twee borgingsbouten wordt gekozen voor diameters van 5mm en 2,8mm, respectievelijk voor de verticale bout en de horizontale bout, aangezien de verticale bout meer kracht zal moeten opvangen omdat het het enige element is dat de muur vasthoudt aan die kant. 

In functie van toleranties worden de gaten voor deze bouten vergroot tot respectievelijk 5,1mm en 3mm.

Om genoeg wanddikte aan het verticale gat te voorzien (2,45mm), sterkte te bieden en voldoende schuifstand voor de knoppen te voorzien, wordt voor een muurbreedte van 10mm gekozen.

De breedtes van de klemstukjes aan de muur dienen ongeveer overeen te komen met de intervalbreedtes (4.3.2.2.2.2.), minus een speling/tolerantie van 0,2mm langs weerskanten, welke leidt tot een breedte van 4,6mm hiervoor.

Deze dimensies worden afgebeeld in Figuur 22: 

![](/img/antro2/Ant22.png)

*Figuur 19: Breedtedimensies van de verschuifbare muren*

---
######## 4.3.2.3.2.2 Hoogtes

De hoogte wordt enerzijds bepaald door de knophoogte (4.3.2.5.2.2.), anderzijds in functie van het begrenzend vermogen dat het heeft voor de voeten.

Als referentie wordt de instaphoogte (“instep height”, aangeduid in Figuur 20) benaderd* voor het 99ste percentiel van mannen tussen de 18 en 65 jaar.

Volgende afmetingen zijn nodig (zie Figuur 23):
  -	Instaphoogte (Instep height, IH)
  -	Voetlengte – ter referentie (Foot length, FL)

![](/img/antro2/Ant23.png)

*Figuur 23: Overzicht antropometrische gegevens van voetdimensies*

Deze gegevens worden verzameld uit een onderzoeksartikel, door Zhang et al.

* _Benaderd, aangezien niet-Belgische antropometrische gegevens worden gebruikt en doormiddel van verhouding tot voetlengte worden omgerekend naar de equivalent voor de grootste Belgische voeten (man, P99, 18-65 jaar)._

Als tweede bron van antropometrische gegevens wordt DINBelg geraadpleegd, met name de voetlengte van mannen, P99, 18-65 jaar. Zie Tabel 3:

*Tabel 3: Antropometrische gegevens van voetdimensies uit DINBelg*

| Populatiebeschrijving | Voetlengte (mm) |
|---|---:|
| Mannen, 18-65, P99 | 289 |

In Figuur 24 staan alle antropometrische metingen uit de gekozen bron.

Van elk van de dimensies wordt het gemiddelde en de standaarddeviatie gegeven, en voor elk ook de waarde bij:

  -	“NWB: Non-Weight Bearing”, voet zonder belasting (weinig tot geen contact met vloer)
  -	“HWB: Half Weight Bearing”, voet onder belasting van 50% lichaamsgewicht
  -	“80%WB: 80% Weight Bearing”, voet onder staande belasting
  -	
Voor deze toepassing is HWB de beste metriek, aangezien voor besturing de voet op de ondergrond wordt gedrukt in zekere mate, maar wel al zittend, dus niet met het volledige gewicht.

![](/img/antro2/Ant24.png)

*Figuur 21: Antropometrische voetafmetingen bij verschillende belastingscondities, uit studie van Zhang et al. (2022)*

Volgende formule wordt voor de hierop volgende berekeningen gebruikt:

X_P = μ + Z_P * σ

XP: waarde van variabele bij percentiel P
μ: gemiddelde waarde
ZP: Z-score voor percentiel P
σ: standaarddeviatie

Ook volgende gegevens worden gebruikt (geëxtrapoleerd uit Figuur 25):
-	Z-score voor P1 = -2,3263
-	Z-score voor P99 = +2,3263

![](/img/antro2/Ant25.png)

*Figuur 22: Z-score - percentieltabel voor normale distributie, uit Mathblog.com*

P99 = 58,5 + 2,3263 * 5,1 = 70,4mm

De verhouding van de instaphoogte t.o.v. de voetlengte wordt bepaald, waarna deze fractie vermenigvuldigd worden met de Belgische voetlengte (Tabel 4), om zo een schatting te maken van de waarde van de grootste voethoogte voor mannen uit België:

(70,36413/265,2) *289 = **76,68mm**

Dit gecombineerd met de hoogte van de knoppen, welke 19,5mm bedraagt (4.3.2.5.2.2.), maakt een muurhoogte van 30mm een veilige keuze. Het biedt ruim genoeg plaats om de knoppen in de muren te bergen en een verhouding van 30/76,68 is voldoende groot om de voeten zelfs bij harde tikken op hun plaats te houden (intuïtief, niet op basis van cijfers).

Dit houdt in dat er boven de knopholte nog 5mm overblijft. Deze waarde wordt behouden voor de hoogte/dikte van het klemstukgedeelte boven de rail en verdubbeld aan het klemstukgedeelte achter de rail, om meer gewicht aan deze kant te plaatsen (minder de neiging om te wiebelen of te bewegen) en ook om de horizontale borgingsstaaf goed te kunnen behuizen.

De borgingsstukken aan de klem volgen in hun hoogte dezelfde speling/tolerantie als bij de breedte ervan (4.3.2.3.2.1.) en hierdoor wordt ook voor hun hoogte voor 4,6mm gekozen. Op deze manier kan de muur in schuifstand soepel door de groeven bewegen, zonder dat deze klemstukken tegen de randen wrijven.

---
######## 4.3.2.3.2.3 Lengtes

De lengte van de muur dient lang genoeg te zijn om deze goed en stevig achteraan de rail te kunnen inklemmen, om de knoppen te kunnen behuizen en de voeten goed op hun plaats te kunnen houden.

Aangezien het idee is om de bodemplaat in twee helften op te delen, welke inklapbaar zal zijn op de manier afgebeeld in Figuren 15 en 16, wordt gekozen om de plaathelft aan de kant van de rail volledig te laten overspannen door de muren in lengterichting. Dit biedt namelijk het voordeel dat de afstand van de verticale borgingstaaf tot de borging aan de rail (Figuur 16) gemaximaliseerd wordt, wat ervoor zal zorgen dat de neiging voor de muren om te wiebelen bij bediening geminimaliseerd wordt. Kortom, dit biedt de beste algehele horizontale borging aan de muren.

De originele bodemplaatlengte bedroeg 289mm (4.3.2.1.2.), maar aangezien de rail 20mm dik zal zijn (4.3.2.2.2.3.), wordt deze dikte eraan toegevoegd en aangezien de voet niet altijd tot helemaal aan de rail zal rijken wordt deze nog verder tot 320mm verhoogd, welke twee helften van 160mm overhoudt. Hierdoor zal het “muurgedeelte” (minus klemgedeelte) ook 160mm bedragen.

Voor de lengte van het klemstukgedeelte achter de rail wordt een waarde van 15mm gekozen om meer gewicht aan deze kant te plaatsen (minder de neiging om te wiebelen of te bewegen) en ook om de horizontale borgingsstaaf goed te kunnen behuizen. Voor de lengte van het gehele klemstukgedeelte (boven en achter de rail) wordt hierbij nog de dikte van de rail  (15mm, zie Figuur 19) plus een speling van een millimeter toegevoegd, waaruit een totale lengte van 31mm bekomen wordt.

De lengte van de klemstukken zullen zoals in hun andere dimensies ook 4,6mm bedragen in functie van spelingruimte. Hierdoor zullen ook in deze richting de muren niet haperen en blijven hangen bij het instellen.

De dimensies van zowel de hoogtes en lengtes worden in Figuur 26 weergegeven:

![](/img/antro2/Ant26.png)

*Figuur 26: Hoogte- en lengtedimensies van de verschuifbare muren*

---
###### 4.3.2.4 Bodemplaat - aanpassing

De dimensies van de bodemplaat worden aangepast als gevolg van de ontwerpkeuzes van de verschuifbare muren en de rail. De aanpassing van lengte is reeds toegelicht in 4.3.2.3.2.3., maar ook de breedte wordt aangepast. Deze was origineel 464mm (4.3.2.1.1.), maar moet vergroot worden naar een breedte die overeenstemt met de rail (4.3.2.2.3.). Dit verhoogt dus naar 485mm.

Deze nieuwe dimensies worden in Figuur 27 afgebeeld:

![](/img/antro2/Ant27.png)

*Figuur 27: Nieuwe dimensies van de bodemplaat*

_Opmerking: de handvaten zijn nog niet bemaat, omdat de dimensies hiervan in de volgende- en laatste antropometrische analyse: Deel III: Analyse van Handafmetingen – Dimensionering van Handvat, zullen bepaald worden._

---
###### 4.3.2.5 knoppen
####### 4.3.2.5.1 Vormbepaling

De knoppen zullen een eenvoudige rechthoekige vorm hebben met een verticaal grippatroon, aangezien een complexere knopvorm overbodig is voor deze toepassing (enkel praktisch).

Voor het mechanisme wordt gekozen voor “een algemene/constante middelgrote indrukweerstand, waarbij je met een middelgrote weerstand de knop over een zekere afstand moet indrukken tot je het elektrisch contact bereikt en de input geregistreerd wordt.”, zie Figuur 28 en verdere uitleg in Deel I: Analyse van Voetafmetingen – Dimensionering van Bakje.

![](/img/antro2/Ant28.png)

*Figuur 28: Keuze van de werkingsoptie voor de knoppen in functie van weerstandstoevoeging*

Hiervoor wordt gekozen omdat de Schneider Electric Harmony Series Contact Block, 600V, 1 NO drukknop die we gebruiken handig is in het opzicht van prototyping omdat je er eenvoudig kabels aan kan vast- en losmaken en deze ook zeer robuust is, wat noodzakelijk is bij voetbediening in deze gebruikscontext. Deze knop biedt de tweede opgelijste werkingsoptie in Figuur 28 niet als mogelijkheid, dus zal voor de externe knop een zeker schuifsysteem moeten geïntegreerd worden, binnenin de verschuifbare muur, welke acteert als een afstand die overbrugt moet worden tot je aan het effectief drukcontact terechtkomt.

---
####### 4.3.2.5.2 Dimensionering
####### 4.3.2.5.2.1 Lengte

De lengte van de knoppen is reeds bepaald in Deel I: Analyse van Voetafmetingen – Dimensionering van Bakje, namelijk een kleine knop van 30mm lang en een grote knop van 40mm lang per voet.

---
####### 4.3.2.5.2.2 Hoogte

De hoogte is nog onbepaald. Het belangrijkste hierbij is dat de knop niet ongemakkelijk aanvoelt aan de voet en vermeden wordt dat deze niet gemakkelijk meegaat bij induwen. Beide treden op bij een te kleine hoogte-tot-lengte verhouding. Echter mag hier ook niet in overdreven worden in functie van compactheid. Ook is deze afhankelijk van de gebruikte drukknop: Schneider Electric Harmony Series Contact Block, 600V, 1 NO.

Er wordt gekozen voor een hoogte van 20mm, omdat
-	20/76,68 = 0,26
->	Meer dan een kwart van de grootste voeten, zal niet ongemakkelijk aanvoelen

-	20/40 = 0,50
->	Deze hoogte-tot-lengte verhouding is voldoende zodanig dat deze makkelijk meegaat met het duwen

-	20 > 7,5
  7,5mm is de hoogte van het drukknopcontact, welke met ruime overschrijding bedekt zal worden
 	bij indrukking en een goed contact zou moeten garanderen.

---
####### 4.3.2.5.2.3 Dikte

De knop moet genoeg uitsteken om voelbaar en makkelijk bedienbaar te zijn. Hier wordt gekozen voor een dikte van 10mm, waarvan 7,7mm effectief uit de muur zal steken bij niet-ingedrukte stand.

---
####### 4.3.2.5.2.4 Mechanisme

Er wordt gekozen voor een inwendig schuifmechanisme binnenin de muren, op de manier zoals afgebeeld in Figuur 29:

![](/img/antro2/Ant29.png)

*Figuur 29: Schuifmechanisme van de knoppen, geïntegreerd in de muren*

Hierdoor moet dus een uitsparing gelaten worden in de muren waarin de knop met een extra schuifstuk voortbeweegt. Voor dit schuifstuk wordt een hoogte van 9,8mm gekozen zodat deze er bij gebruik (muren op- en neer heffen), niet uitvallen. Deze zijn langs weerskanten 15mm lang om wiebelen van de knoppen te vermijden.

Er wordt bepaald hoever het drukknopcontact in de muur komt wanneer deze in de behuizing ligt zoals in Figuur 26. Dit is het punt waar de knop dient terecht te komen in “uit”-stand. De “in”-stand van de knop rijkt tot aan de rand van de drukknop, zodat bij bediening van de knop altijd een contact doorgegeven wordt.

Dit in rekening gebracht met het feit dat de muren 10mm zijn, constraint dit de dikte van het schuifstuk tot 1,8mm.

De dimensies relevant voor het schuifmechanisme worden in Figuur 30 weergegeven:

![](/img/antro2/Ant30.png)

*Figuur 30: Dimensies voor het schuifmechanisme van de knoppen*

---
### 5 Conclusies
#### 5.1 Algemene conclusies

De benadering van de voet-tot-voetafstand varieert bij tussen 105mm en 340mm voor de gekozen extremumgroepen. 

De onnauwkeurigheid door de benadering wordt weggewerkt door beide verder in de richting van hun resp. extremum af te ronden:
-	Minimum: 105mm -> 100mm  
-	Maximum: 340 -> 350mm

Het origineel bakjesontwerp, bekomen in Deel I: Analyse van Voetafmetingen – Dimensionering van Bakje, wordt verworpen en in de plaats wordt verder gewerkt met een aaneengesloten, inklapbare bodemplaat met 4 muren. Zie Figuur 31:

![](/img/antro2/Ant31.png)

*Figuur 31: Bekomen geïntegreerd ontwerp als resultaat van de beslissingen genomen in de analyse*

Deze dienen elk een kant van een voet te begrenzen en 3 van de 4 muren kunnen over de plaat verschoven worden (rode muren in Figuur 28). De overblijvende staat vast aan de rand en serveert als vast referentie-/meetpunt en reduceert de complexiteit.

Het verschuiven van de muren gaat via het “rail”-systeem, zoals weergegeven in Figuur 29:

![](/img/antro2/Ant32.gif)

*Figuur 32: Werkingsprincipe van het instelproces van de muur, waaronder verschuiving en borging*

Vastklemmen van de muren gebeurt door deze aan weerszijden te borgen, zoals weergegeven in Figuur 33:

![](/img/antro2/Ant33.png)

*Figuur 33: Borgingsprincipes van het instelproces van de muur*

De inklapbaarheid van de bodemplaat biedt extra compactheid bij het opbergen, maar gecombineerd met handvaten aan weerskanten, zorgt het er ook voor dat zal kunnen gedragen worden zoals een koffer. De inklappings- en draagprincipes worden respectievelijk in Figuren 34 en 35 afgebeeld:

![](/img/antro2/Ant34.png)

*Figuur 34: Illustratie van het inklapproces, doormiddel van gelijke verdeling van de bodemplaat in twee helften*

![](/img/antro2/Ant35.png)

*Figuur 35: Illustratie van het draagproces, doormiddel van voorziene handvaten*

De dimensies van de handvaten dienen nog bepaald te worden in een volgende antropometrische analyse: Deel III: Analyse van Handafmetingen – Dimensionering van Handvat

De knoppen hebben een werkingsprincipe zoals geïllustreerd in Figuur 36:

![](/img/antro2/Ant36.png)

*Figuur 36: Schuifmechanisme van de knoppen, geïntegreerd in de muren*

---
#### 5.2 Conclusies van Dimensionering
#### 5.2.1 Bodemplaat

De afmetingen van de bodemplaat zijn in Figuur 37 weergegeven:

![](/img/antro2/Ant37.png)

*Figuur 34: Nieuwe dimensies van de bodemplaat*

De dikte is afhankelijk van de gebruikte houtplaat, aangezien het productieproces lasercutten zal zijn. Dit zal gebruikelijk 4mm bedragen.

---
#### 5.2.2 Rail

De afmetingen van de rail zijn in Figuur 38 weergegeven:

![](/img/antro2/Ant38.png)

*Figuur 38: Gehele vormgeving en dimensionering van de rail*

De aanhangende muur volgt de dimensionering van de verschuifbare muren (4.3.2.3.2. of 5.2.3.) minus de klem.

---
#### 5.2.3 Muren

De afmetingen van de muren zijn in Figuur 39 weergegeven:

![](/img/antro2/Ant39.png)

*Figuur 39: Gehele vormgeving en dimensionering van de muren*

---
#### 5.2.4 Knoppen

De afmetingen van de knoppen en hun mechanisme binnenin de muren zijn in Figuur 37 weergegeven:

![](/img/antro2/Ant40.png)

*Figuur 40: Gehele vormgeving en dimensionering van de knoppen en hun schuifmechanisme*

---
### 6 Literatuurlijst
#### 6.1 Internetpagina's

DINBelg. (2005). DINBelg. https://www.dinbelg.be 

Zhang, L., Yick, K.-L., Li, P.-L., Yip, J., & Ng, S.-P. (2022). Foot deformation analysis with different load-bearing conditions to enhance diabetic footwear designs. PLOS ONE, 17(3), e0264233. https://doi.org/10.1371/journal.pone.0264233 

MathBlog. (2024, 7 maart). Z-score – Percentile table for normal distribution. https://mathblog.com/statistics/definitions/z-score/percentile-to-z-table/ 

---
#### 6.2 Boeken

Molenbroek, J., & de Bruin, R. (2005). Enhancing
the use of anthropometric data. Human Factors
in Design, Safety, and Management, 289-297.

---
#### 6.3 Generatieve AI

Generatieve AI (ChatGPT, OpenAI) is gebruikt ter ondersteuning bij het toepassen van APA-richtlijnen, waaronder het correct formatteren van bronvermeldingen en het verwijzen naar figuren en citaten. De output is gecontroleerd en waar nodig aangepast door de auteur.


