# Develop 2 – Antropometrische Studie
## Deel I: Analyse van Voetafmetingen – Dimensionering van Bakje
### 1 Onderzoeksdoel

Het doel van dit onderzoek is om de dimensies van het bakje van een nieuwe prototype iteratie (Figuur 1) te definiëren. Het prototype moet voor beide voeten twee knoppen bieden, die indrukbaar zijn door de linkse en rechtse uiterste punten van de voet. Een visuele weergave van dit concept, alsook de te bepalen afmetingen, zijn weergegeven in Figuur 2. Deze onbekende dimensies worden bepaald doormiddel van een antropometrische analyse, gebruikmakend van bestaande betrouwbare antropometrische gegevens.

![](/img/antro1/1.png)
*Figuur 1: Theoretisch model waarvan de afmetingen in dit onderzoek gedefinieerd worden*
![](/img/antro1/2.png)
*Figuur 2: Weergave algemeen concept, gekende dimensies en te bepalen dimensies van theoretisch model*

---
### 2 Motivatie

Voor deze toepassing wordt een antropometrische analyse als noodzakelijk beschouwd, enerzijds omwille van het feit dat het onderzoeksproces zich in de tweede deelfase van de ontwikkelingsfase bevindt, waardoor van “quick and dirty” prototyping meer overgegaan moet worden tot iets degelijkere, beter uitgewerkte ontwerpiteraties. Anderzijds omwille van het feit dat de positie van deze twee knoppen en de nodige grootte ervan om door (bijna) alle voeten bruikbaar te kunnen zijn, zeer moeilijk intuïtief te bepalen is. Deze data is ook nog verder in het proces bruikbaar, in het geval dat niet met dit concept verdergegaan wordt.

---
### 3 Data

Als belangrijkste bron aan antropometrische gegevens wordt DINBelg gebruikt. 

Om de dimensies van de grootste reële voeten te bepalen, worden de beschikbare relevante gegevens van mannen, tussen de 18 en 65 jaar, binnen het 99ste percentiel (P99) geëxtrapoleerd.

Om de dimensies van de kleinste reële voeten te bepalen, worden de beschikbare relevante gegevens van meisjes, van 6 jaar, binnen het 1ste percentiel (P1) geëxtrapoleerd.

DINBelg biedt enkel voetlengte en voetbreedte als bruikbare gegevens. Deze zijn verzameld in Tabel 1:

*Tabel 1: Antropometrische gegevens van voetdimensies uit DINBelg*

| Populatiebeschrijving | Voetlengte (mm) | Voetbreedte (mm) |
|----------------------|-----------------|------------------|
| Mannen, 18-65, P99  | 289             | 114              |
| Meisjes, 6, P1      | 157             | 60               |

(Deze gegevens waren ook reeds toegepast bij de conceptweergave in Figuur 2)

Enkel deze gegevens bieden niet genoeg informatie om alle nodige afmetingen te bepalen. (Aangeduid met “?” in Figuur 2)

Volgende afmetingen zijn nog nodig (zie Figuur 3):
-	Ballengte (Ball length, BL)
-	Balbreedte (Ball width, BW)
-	Voetlengte – ter referentie (Foot length, FL)
-	Voetbreedte – ter referentie (Foot width, FW)

![](/img/antro1/3.png)
*Figuur 3: Overzicht antropometrische gegevens van voetdimensies*

Deze gegevens worden verzameld uit een onderzoeksartikel, door Zhang et al.

---
#### 3.1 Berekeningen

In Figuur 4 staan alle antropometrische metingen uit de gekozen bron.

Van elk van de dimensies wordt het gemiddelde en de standaarddeviatie gegeven, en voor elk ook de waarde bij:
-	“NWB: Non-Weight Bearing”, voet zonder belasting (weinig tot geen contact met vloer)
-	“HWB: Half Weight Bearing”, voet onder belasting van 50% lichaamsgewicht
-	“80%WB: 80% Weight Bearing”, voet onder staande belasting

Voor deze toepassing is HWB de beste metriek, aangezien voor besturing de voet op de ondergrond wordt gedrukt in zekere mate, maar wel al zittend, dus niet met het volledige gewicht.

![](/img/antro1/4.png)
*Figuur 4: Antropometrische voetafmetingen bij verschillende belastingscondities, uit studie van Zhang et al. (2022)*

Volgende formule wordt voor de hierop volgende berekeningen gebruikt:
X_P=μ+Z_P*σ
XP: waarde van variabele bij percentiel P
μ: gemiddelde waarde
ZP: Z-score voor percentiel P
σ: standaarddeviatie

Ook volgende gegevens worden gebruikt (geëxtrapoleerd uit Figuur 5):
-	Z-score voor P1 = -2,3263
-	Z-score voor P99 = +2,3263

![](/img/antro1/5.png)
*Figuur 5: Z-score - percentieltabel voor normale distributie, uit Mathblog.com*
  
---
##### 3.1.1 Ballengte

_Mannen_

P99=182,6+2,3263*6,9=198,7mm

_Vrouwen_

P1=171,8-2,3263*8,0=153,2mm

---
##### 3.1.2 Balbreedte

_Mannen_

P99=96,9+2,3263*5,8=110,4mm

_Vrouwen_

P1=93,5-2,3263*6,2=79,1mm

---
##### 3.1.3 Voetlengte

_Mannen_

P99=246,1+2,3263*8,2=265,2mm

_Vrouwen_

P1=243,3-2,3263*10,1=219,8mm

---
##### 3.1.4 Voetbreedte

_Mannen_

P99=93,8+2,3263*5,9=107,5mm

_Vrouwen_

P1=90,7-2,3263*6,1=76,5mm


Deze gegevens zijn verzameld in Tabel 2:

*Tabel 2: Relevante percentielen uit antropometrische gegevens van Figuur 4*

| Populatiebeschrijving                          | Ballengte (mm) | Balbreedte (mm) | Voetlengte (mm) | Voetbreedte (mm) |
|------------------------------------------------|----------------|-----------------|-----------------|------------------|
| *Mannen, 66 ± 4 (60–72) jaar, P99*             | 198,7          | 110,4           | 265,2           | 107,5            |
| *Vrouwen, 64 ± 5 (56–75) jaar, P1*             | 153,2          | 79,1            | 219,8           | 76,5             |

De verhouding van de ballengte t.o.v. de voetlengte wordt bepaald voor zowel mannen als vrouwen, waarna deze fractie vermenigvuldigd worden met de Belgische voetlengte gegevens (Tabel 1), om zo een schatting te maken van de waarden van ballengtes voor mannen en vrouwen uit België:

_Mannen_

(198,7/265,2)*289=216,5mm

_Vrouwen_

(153,2/219,8)*157=109,4mm

Uit de balbreedte en voetbreedte kan de cosinus van de hoek tussen D4 en D5 (Figuur 3) en zo ook de hoek zelf bepaald worden, welke door combinatie met Belgische voetbreedte gegevens uit DINBelg gebruikt kunnen worden om de verticale afstand tussen de twee extrema van voetbreedtepunten in België te schatten. Ook dit gebeurt voor zowel mannen als vrouwen:

_Mannen_

sin⁡(cos^(-1)⁡〖107,5/110,4〗 )*114=25,8mm

_Vrouwen_

sin⁡(cos^(-1)⁡〖76,5/79,1〗 )*60=15,2mm

Alle relevante Belgische gegevens en schattingen worden verzameld in Tabel 3:

*Tabel 3: Belgische antropometrische gegevens en schattingen voor voetafmetingen, relevant voor dimensiebepaling binnen het concept*

| Populatiebeschrijving      | Ballengte (mm) | Verticale afstand tussen maximale breedtepunten v/d voet (mm) | Voetlengte (mm) | Voetbreedte (mm) |
|----------------------------|----------------|----------------------------------------------------------------|-----------------|------------------|
| *Mannen, 18-65, P99*       | 216,5*         | 25,8*                                                         | 289             | 114              |
| *Meisjes, 6, P1*           | 109,4*         | 15,2*                                                         | 157             | 60               |

*(Schattingen van waarden, niet werkelijk gemeten)*

**Opmerking**

De vermenging van vrouwelijke kindergegevens met volwassen gegevens leidt tot een zekere graad van onnauwkeurigheid. Deze berekening is een schatting. Ook deze tussen volwassen mannen is minder betrouwbaar dan werkelijke antropometrische metingen.

Om deze onnauwkeurigheden op te vangen wordt genoeg marge genomen bij de dimensies van het uit te werken concept.

---
### 4 Data analyse

Het is de bedoeling dat de voet tot helemaal achteraan in het bakje geplaatst wordt bij gebruik (zie Figuur 2), dus voor de dimensiebepaling wordt van bovenuit gerekend. Ook zoals te zien in Figuur 2 (blauw aangeduid) en zoals als nodig gevonden bij de berekeningen (zie 4.1.: Opmerking), zal op de aangeduide plaatsen een zekere extra uitsparing voorzien worden.

---
#### 4.1 Minimale en maximale maten, zonder toegevoegde marges

Met behulp van de waarden uit Tabel 3, kunnen binnenin het theoretische bakje al de aanrakingspunten aangeduid worden van de maximale breedtepunten van de voet, van zowel de grootste mannelijke voet, als de kleinste vrouwelijke voet. Deze zijn de punten op de voet die contact moeten maken met de drukknoppen (zie Figuur 2). 

Deze contactpunten zijn de extrema langs beide kanten, dus vormen ook de theoretische range, zonder toegevoegde marges, waartussen contacten van zo goed als alle soorten voeten kunnen liggen, als de tip van de voet het einde van het bakje raakt zoals bedoeld.

De grafische combinatie van gegevens uit Tabel 3 worden gevisualiseerd in Figuur 6. De bekomen contactrange als gevolg, wordt gevisualiseerd in Figuur 7:

![](/img/antro1/6.png)
*Figuur 6: Grafische voorstelling van antropometrische gegevens van voetafmetingen, uit Tabel 3*
![](/img/antro1/7.png)
*Figuur 7: Contact-/Inputranges bekomen uit antropometrische gegevens van voetafmetingen uit Tabel 3*

---
#### 4.2 Marge toevoeging aan contactranges

Aangezien er voor deze schattingen geen manier is om de “mate van onnauwkeurigheid” eenduidig te bepalen, wordt voor elke range een arbitraire, grotere maat gekozen.

Beide maten worden met ~5mm vergroot:
-	24,9mm -> 30mm
-	35,5mm -> 40mm
---
#### 4.3 Hoogtebepaling

Aangezien de maximale breedtepunten van de voet tot zeer laag richting de voetzool lopen met een quasi constante uitwijking, is de hoogte waarop het contact (knop) ligt een factor die vrij te kiezen is, grotendeels onafhankelijk van antropometrie. Hierbij wordt dan rekening gehouden met volgende factoren

-	Compactheid: Hoe minder hoog, hoe beter, voor bergbaarheid, combinatiemogelijkheid met piano pedalen,
  gewicht, etc., zolang dit niet (te veel) ten koste gaat van een andere belangrijke requirement.

-	Comfort: Aangezien de knop waarschijnlijk een grote weerstand zal hebben, om verkeerde inputs te vermijden,
  zou een zeer dunne, lange knop bij langdurig gebruik tot last kunnen leiden. Een dikkere knop is dus beter.

-	Containment: Als de rand te laag ligt, kan het optreden dat de voet niet goed genoeg begrensd wordt, waardoor
  die er bij gebruik uit kan vliegen.

Rekening houdend met deze factoren, wordt voorlopig voor een wandhoogte van 3cm gekozen, met knoppen die 2cm hoog zijn, startend vanaf de basis.

---
#### 4.4 Dimensionering van concept

Alle gezochte maten van dit onderzoek zijn bepaald, welke tot een eerste volledig gedimensioneerd concept leiden.

Dit wordt afgebeeld in Figuur 8:

![](/img/antro1/8.png)
*Figuur 8: Voorlopig finaal gedimensioneerd concept*

**Opmerking**

Dit is slechts een veralgemeende voorstelling. Zaken als bedrading, behuizing voor elektronica, etc., worden beïnvloed door onder andere technische specificaties en vallen buiten de scope van dit onderzoek.

---
#### 4.5Analyse van dimensionering
##### 4.5.1 Edge case - "MIN"

Door de keuze van “design for the tall” als designstrategie, is het bakje zeer groot in verhouding tot de kleinste voeten waarvoor ontworpen wordt.

De knoppen gaan alsmaar verder weg staan des te kleiner de voet wordt en dit betekent dat kleinere voeten meer afstand zullen moeten afleggen om de knoppen te kunnen bereiken, zijnde dit rotatie (draaien), translatie (horizontaal schuiven) of een combinatie van beide.

Hoe dit is bij de kleinste voet, wordt met voorbeeld zuivere rotatie weergegeven in Figuur 9:

![](/img/antro1/9.png)
*Figuur 9: Nodige rotatie van kleinste voet waarvoor ontworpen wordt, om de linker- en rechterknop te bereiken*

Aangezien de Comfort Analysis uit CAD Siemens NX (“Human Body” tool, antropometrie) voetrotatie niet registreert als invloedfactor op comfort, kan deze tool niet gebruikt worden om al snel een eerste idee van de impact op comfort te scheppen.

Als gevolg zal voor het bepalen van comfort bij voetrotatie meteen moeten overgegaan worden naar user tests, met proefpersonen met variërende voetgroottes, die de voeten binnen een 1:1 schaalmodel van de prototype bakjes roteren/schuiven zoals bij gebruik.

De proefpersonen hoeven noch slechtziend, noch muzikaal opgeleid te zijn om te kwalificeren voor deze test.
---
##### 4.5.2 Edge case - "MAX"

Anderzijds, is het bakje vrij nauw voor de grootste voeten waarvoor ontworpen wordt (zie Figuur 8). 

Dit introduceert het potentieel risico op ongewenste inputs (“mis-inputs”) bij grotere voeten, indien hier geen rekening mee wordt gehouden met het design.

Om dit te vermijden zijn er 3 opties:
1.	De bakjes breder maken
2.	Grote weerstand aanbrengen op de knopjes
3.	Andere vorm van input
---
###### 4.5.2.1 Uitwerkingsvorm - bredere bakjes

De eenvoudigste uitwerking van deze ontwerpoptie is simpelweg de bakjes breder maken in hun vaste dimensionering.

Een tweede optie is om de bakjes instelbaar te maken in breedte. 

De voor- en nadelen voor beide opties worden hieronder opgelijst.

**Algemeen voordeel (t.o.v. weerstandstoevoeging)**
-	Sluit nog minder mensen uit:
  *	Mensen met nog bredere voeten dan mannen, 18-65 jaar, P99
  *	Mensen met brede schoenen
  *	(Combinatie van beide)

**Vaste verbreding**
*Voordelen*
-	Eenvoudig
*Nadelen*
-	Verlies aan compactheid
-	Vergroting van Edge Case – “MIN” probleem(?): kleine voeten moeten nog meer uitwijken om knoppen te bereiken
  Merk op: er is nog niet bepaald of dit effectief een probleem is, deze conclusie volgt uit opkomend onderzoek

**Instelbaar**
*Voordelen*
-	Bakje kan ingesteld worden op maat van (bijna) elke voet
  ->	Kan probleem(?) van Edge Case – “MIN” elimineren
-	Nog steeds quasi even compact (minus extra mechanisme dat extra plaats inneemt), mogelijks zelfs compacter,
  dan origineel (niet verbreed) concept
*Nadelen*
-	Verhoogde complexiteit:
  *	Extra mechanisme om breder te maken = extra onderdeel dat kan falen/verkeerd begrepen kan worden
  *	Extra mechanisme betekent extra kost
“Goed design is zo weinig mogelijk design” (eigen vertaling van Rams, z.d.).
---
###### 4.5.2.2 Uitwerkingsvormen - Grotere knopweerstand

Hierin zijn twee mogelijke weerstandsprincipes te onderscheiden. 

Enerzijds is er de mogelijkheid om een algemene/constante middelgrote indrukweerstand te hebben, waarbij je met een grote weerstand de knop over een zekere afstand moet indrukken tot je het elektrisch contact bereikt en de input geregistreerd wordt. 

Anderzijds kan geopteerd worden voor een doorbreekweerstand: bij een te lage kracht vertoont de knop geen beweging, maar eens een zekere vereiste kracht overbrugd wordt, wordt het contact onmiddellijk gemaakt. Dit principe is vergelijkbaar met bijvoorbeeld de knopjes op gsm’s, maar ook veel andere drukknoppen.

Een vergelijking van deze twee principes wordt geïllustreerd in Figuur 10:

![](/img/antro1/10.png)
*Figuur 10: Illustratie van de twee werkingsopties voor de knoppen in functie van weerstandstoevoeging*

De voordelen en nadelen voor elk van deze opties liggen veel genuanceerder dan bij de bakjesverbreding, aangezien het hier bijvoorbeeld onder andere gaat over indrukcomfort en indruksensatie. Welke voor minder mis-inputs zal zorgen valt reëel gezien ook niet theoretisch te bepalen.

Om te kunnen beslissen welke van de twee een betere optie zou zijn, zouden beide opties moeten getest worden, met een prototype met functionerende contacten zodat de hoeveelheid mis-inputs kwantitatief kunnen gemeten vergeleken worden en via gelaatsanalyse en een QAP kan bepaald worden welke comfortabeler/aangenamer is.

---
###### 4.4.2.3 Uitwerkingsvormen - andere vorm van input

Dit is de worstcasescenario optie, in het geval beide opties geen aanvaardbaar resultaat leveren. Dit vergt dan ook zijn eigen onderzoek en valt buiten de scope van dit onderzoek.

---
###### 4.5.2.4 Vergelijking van uitwerkingsvormen

Een van de voordelen die de bakjesverbreding heeft t.o.v. de knopweerstand is dat het de doelgroep verruimt.

De niet-instelbare, “vaste” verbreding zou het (ongewenst) effect van de nodige uitwijking bij kleine voeten (5.5.1.) versterken.

Als de nodige uitwijking voor kleinere voeten bij het huidige concept al als (bijna) te groot wordt vastgesteld, wordt deze vaste optie dan ook uitgesloten.

Het verruimen van de groep van mensen waarvoor het product bruikbaar is, is een van de hoofddoelen als ontwerper en dus positief. Er moet echter ook rekening gehouden worden met de “law of diminishing returns” (Figuur 11). 

Het principe van “diminishing returns” of afnemende meeropbrengsten kan worden omschreven als “de afname van de marginale output van een productieproces wanneer de hoeveelheid van één productiefactor wordt verhoogd, terwijl andere factoren constant blijven” (eigen vertaling van Wikipedia, z.d.).

![](/img/antro1/11.png)
*Figuur 11: Verloop van afnemende meeropbrengsten*

Dit betekent dat de verruiming van doelgroep goed meegenomen zou zijn, maar het niet-verbreed concept in principe al voor een groot deel van de voetmaten bruikbaar is, dus dit voordeel zelf geen determinerende factor is voor een ontwerpkeuze, tenzij alle andere factoren onderling gelijk zouden zijn.

Een voordeel dat specifiek de instelbare bakjesverbreding heeft, is dat deze instelbaarheid toelaat voor de gebruiker om de bakjes in te stellen op de breedte die hij/zij als het meest comfortabel ervaren. Hier zou dan de designstrategie design for adjustability (Molenbroek & de Bruin, 2005) toegepast worden.

Bijkomend zou dit dus ook het (ongewenst) effect van de nodige uitwijking bij kleine voeten (5.5.1.) verzwakken of zelfs volledig elimineren indien het klein genoeg kan ingesteld worden.

Deze optie verhoogt echter wel de complexiteit van het product.

De voordelen die de knopweerstand dan heeft zijn dat dit een zeer eenvoudig uit te voeren verandering is tegenover instelbaarheid, het geen compactheid afneemt en het (ongewenst) effect van de nodige uitwijking bij kleine voeten (5.5.1.) niet versterkt zoals wel bij de vaste verbreding.

---
### 5 Conclusies

Een voorlopige dimensionering die voeten zou moeten kunnen dienen van meisjes, 6 jaar, P1 tot mannen, 18-65 jaar, P99 is vastgesteld (Figuur 8).

Beide edge cases (minimum- en maximum voetgrootte, resp. 5.5.1. & 5.5.2.) brengen elk (mogelijke) problemen met zich mee, van welke zowel de mate waarin ze een probleem vormen alsook de mogelijke oplossingen moeten onderzocht worden in volgende tests:

#### 5.1 Comfort van voetuitwijking - indrukken van knoppen in bakjes

Een 1:1 geschaald (niet noodzakelijk functioneel) prototype van het huidig concept (Figuur 8) wordt met een variatie van voetgroottes getest op eenvoud van indrukking van knoppen. 

#### 5.2 Uitwerkingsdefinitie van bakjes - verbreding en knopweerstand

Een 1:1 geschaald prototype met knoppen die feedback geven (bv. buzzer) wordt voorzien van instelbaarheid in verbreding, alsook knoppen met weinig weerstand, algemene/constante middelgrote indrukweerstand over afstand en een grote doorbreekweerstand. Deze worden elk apart getest en beoordeeld op hoeveelheid misinputs, comfort van gebruik en bruikbaarheid.

---
Elk van de benoemde uitwerkingsvormen biedt zijn eigen voor- en nadelen, voor zover theoretisch bepaald kan worden.

Het bepalen van de mate waarin de grote uitwijking van kleine voeten een probleem is, is in grote mate determinerend voor de keuze van uitwerkingsvorm (de eerste test beïnvloedt de tweede test).

Een tweede studie: Deel II: Analyse van Heup- en Beenafmetingen – Plaatsing van Bakjes, zal moeten uitgevoerd worden om te bepalen hoe ver de twee bakjes uit elkaar moeten staan, of instelbaarheid nodig is en in welke mate, etc., vooraleer de hiervoor vernoemde tests uitgevoerd kunnen worden.

---
### 6 Literatuurlijst
#### 6.1 Internetpagina's

DINBelg. (2005). DINBelg. https://www.dinbelg.be 

Zhang, L., Yick, K.-L., Li, P.-L., Yip, J., & Ng, S.-P. (2022). Foot deformation analysis with different load-bearing conditions to enhance diabetic footwear designs. PLOS ONE, 17(3), e0264233. https://doi.org/10.1371/journal.pone.0264233 

MathBlog. (2024, 7 maart). Z-score – Percentile table for normal distribution. https://mathblog.com/statistics/definitions/z-score/percentile-to-z-table/ 

Wikipedia. (z.d.). Diminishing returns. Geraadpleegd op 22 maart 2026, van https://en.wikipedia.org/wiki/Diminishing_returns

Heurio. (z.d.). Dieter Rams: 10 principles of good design. Geraadpleegd op 22 maart 2026, van https://www.heurio.co/dieter-rams-10-principles-of-good-design 

#### 6.2 Boeken

Molenbroek, J., & de Bruin, R. (2005). Enhancing
the use of anthropometric data. Human Factors
in Design, Safety, and Management, 289-297.

#### 6.3 Generatieve AI

Generatieve AI (ChatGPT, OpenAI) is gebruikt ter ondersteuning bij het toepassen van APA-richtlijnen, waaronder het correct formatteren van bronvermeldingen en het verwijzen naar figuren en citaten. De output is gecontroleerd en waar nodig aangepast door de auteur.



