# Develop phase 1
## Wat weten we al? 

Dat is de vraag die gesteld wordt om de ontwikkelingsfase van start te laten gaan. 

Er zijn al een reeks aan inzichten bekomen (zie Definition), welke zich uiten als streefpunten voor volgende prototype iteraties en al een preciezer beeld schetsen van het uiteindelijke prototype.

![COW](/img/DEV1.png)

Aan de hand hiervan worden enkele zaken schematisch voorgesteld om te dienen als referentie, grond om op verder te werken, manier om ideeën te visualiseren en algemene hulp tijdens het proces: 

### User Flow

![UF](/img/DEV2.png)

### Human-Product Interactions

![HPI](/img/DEV3.png)

### Informatiearchitectuur

De informatiearchitectuur dient bestudeerd te worden voor zowel de app als mogelijke controllers:

**App**

![IAA](/img/DEV4.png)

**Controller principe 1**

![IAC1](/img/DEV5.png)

**Controller principe 2**

![IAC2](/img/DEV6.png)

### Customer Journey

![CJ](/img/DEV7.png)

### Storyboard

De storyboard wordt verder verfijnd om meer aan te sluiten bij de huidige visie van context en gebruik van het product.

![SB](/img/storyboard.jpg)

### Hiërarchische taakanalyse

**app**

![app](/img/Develop_1_-_HTA_-_App.png)

**prototype**

![Prototype]()

### Morfologische matrix

![MM](/img/Morfomatrix.jpeg)

---
## Hoe bouwen we hierop voort?

Echter resteren er nog veel vragen, welke meer onderzoek nodig hebben om beantwoord te worden. Deze onderzoeksvragen worden gerangschikt op mate van urgentie en ook in diezelfde volgorde getest. 

![COW](/img/DEV9.png)

Het bepalen van de beste input-methode wordt als meest kritisch genomen, aangezien door deze te testen ook enige mate van inzicht bekomen kan worden op de andere vragen en deze de grootste vormbepalende factor heeft. 

Welke functionaliteit noodzakelijk is, welke _nice to have_ en welke _elimineerbaar_ is, kan in enige zin bepaald worden doormiddel van **card sorting**, zonder dat deze functionaliteit al effectief aanwezig dient te zijn in de prototypes. Dit betekent dat ook deze vraag geïntegreerd kan worden in de eerste testfase. 

Voor een volledige beschrijving van de eerste testfase, zie Develop 1 – User Test Protocol.

Dit leidt tot de volgende vraag, namelijk wat de **MVP** _(Minimal Viable Product)_ van de prototypes is, om deze onderzoeksvragen te beantwoorden: 

![COW](/img/DEV10.png)

Twee inputopties worden overwogen op dit punt: 
- Pedalen
- Side Buttons 

Beide van deze worden uitgewerkt tot een prototype, voldoet aan de bekomen MVP:

---
## Prototype 1 - Pedalen:

**Cenceptualisatie**

![COW](/img/DEV11.png)

Bij de conceptualisatie van de pedalen wordt een antropometrische analyse uitgevoerd van het voetbereik in neutrale zitstand, welke ook bruikbaar kan zijn bij volgende iteraties/onderzoeken/...: 

De keuze van pedalen komt reeds uit vorige testen, waarbij dit een intuïtieve manier is om met de voet inputs te geven. De reden hierdoor is da bijvoorbeeld pianospelers dit kennen van de piano pedalen, dit is dus een metafoor van hun omgeving. 

Anderzijds wordt deze keuze gemaakt vanuit de design requierments. Het bied een lage cognitieve belasting omdat een pedaal gekend is bij de meeste mensen. Het idee is om 2 hoofd pedalen te ontwerpen die hoofdfuncties zullen uitvoeren. Dit is echter niet genoeg om alle functies te kunnen uitvoeren. Hierdoor ontstond het idee om een “CTRL” knop te maken net zoals bij een toetsenbord, waar combinaties worden gemaakt voor meer functies te verkrijgen.  

![COW](/img/DEV12.png)

**Prototyping**

![COW](/img/DEV13.png)

**Resultaat**

![COW](/img/DEV14.png)

---
## Prototype 2 - Side Buttons:

**Conceptualisatie**

![COW](/img/DEV15.png)

Dit prototype is gebaseerd op de rust positie van de gebruiker, hiermee wordt verwacht dat wanneer er geen input moet gegeven worden, de voeten niet van de controller moeten gehaald worden. Ook moet de voet zich niet verplaatsen naar een alternatieve input, want per voet zijn er twee inputs. 

Dit hangt vast aan de design requirement die stelt dat het product een lage cognitieve belasting moet hebben tijdens het gebruik. Doordat de voet niet constant op en af een input moet gezet worden, is dit zowel voor inputs geven als ergonomische rust positie een aangenamere keuze. Het constant moeten verplaatsen van de voeten kan een drempel zijn bij het pedalen prototype. Aan de hand van dit prototype is het de bedoeling om te testen welk van de twee principes het best zal zijn om als finaal input principe te nemen.

**Prototyping**

![COW](/img/DEV16.png)

**Resultaat**


![COW](/img/DEV17.png)

---
# Test resultaten

## App

De app is in deze fase grotendeels hetzelfde in vergelijking met de vorige fase. Uit de test zijn deze conclusies getrokken: 
- Eliminatie van bevestigingsschermen heeft geen negatieve invloed op taakvoltooiing, maar
  reduceert tijd om taak te voltooien in significante mate. Deze aanpassing blijft behouden.
- Partituur scanfunctie in app integreren. Er bestaan hier al voorbeelden van zoals
  https://scan-score.com/en/  
- Mogelijke verwarring van lijstopdeling in achterhoofd houden dit oplossen aan de hand van
  tabbladen. 
- Een geschreven handleiding toevoegen over alle nodige besturingsinfo van het product.

---
## Prototype 1

Uit de test van het opstellen bleek dat een aanhangsel niet zo intuïtief is. Alle respondenten konden de hoofddoos correct plaatsen maar wisten niet wat men met het aanhangsel (“ctlr” pedaal) moest doen. 

**Respondent 1**

![Foto](/img/RES1.png)

**Respondent 2**

![Foto](/img/RES2.png)

**Respondent 3**

![Foto](/img/RES3.png)

Uit de test voor het plaatsen van de voeten voor een algemene input ging dit algemeen vlot. Alle respondenten konden de pedalen indrukken zoals gewenst. Alleen is de rust positie van de voeten niet zoals verwacht. Twee van de respondenten plaatsen de voeten op de grond in plaats van op het pedaal en één respondent zweefde over het pedaal. 

**Respondent 1**

![Foto](/img/RES4.png)

**Respondent 2**

![Foto](/img/RES5.png)

**Respondent 3**

![Foto](/img/RES6.png)

Uit de test van de controle input werd meer informatie verzameld. Niet alle respondenten wisten hoe ze een speciale input moesten geven (combinatie input). Hieruit bleek dat het beter is om alles als één samenhangend geheel te behouden en mogelijk andere textuur voor het “ctrl” pedaal te gebruiken. 

**Respondent 1**

![Foto](/img/RES7.png)

**Respondent 2**

![Foto](/img/RES8.png)

**Respondent 3**

![Foto](/img/RES9.png)

Tijdens het analyseren van het gebruik van het prototype na onze uitleg en na dat de respondenten zelf al eens getest hebben, was er geen twijfel of onzekerheid bij de proefpersonen. 

---
## Prototype 2

Bij dit prototype is het de bedoeling dat men de boog van zich weg plaatst om zo de inputs te kunnen bedienen. Echter voor niemand was dit intuïtief, want de affordances waren niet goed genoeg bij dit prototype.  

**Voetplaatsingstest (ruststand) & bedieningstest** 

_Opmerking:_
Omdat de rustpositie plaats vindt op het prototype speelt deze automatisch een rol in het besturen van het prototype. 

**Respondent 1**

![Foto](/img/RES10.png)

**Respondent 2**

![Foto](/img/RES11.png)

**Respondent 3**

![Foto](/img/RES12.png)

Tijdens het gebruiken van het prototype werd er eerst bij de respondenten een twijfel of onzekere gelaatsuitdrukking waar genomen. Pas na dat men geholpen werd liep het vlotter. Uit de test van dit prototype ontstond een brainstorm, hierdoor ontstond een nieuw theoretisch concept. Wat voor hen beter leek voor deze potentieel hebbende input methode. Bij dit model is er geen draaiend pedaal maar draaien de voeten gewoon op de grond om zo wand knoppen te activeren. 

![Foto](/img/RES13.png)

In de achteraf gestelde vragen die de prototypes vergeleek. Was duidelijk dat beide principes potentieel hadden en beter scoorden dan de andere op verschillende vlakken. Door deze samen te voegen was het mogelijk om nieuwe conclusies te vormen over de prototypes. 
- Constrainen is de effectiefst waargenomen methode van behavioral design.
- Bij informatie architectuur moet opgelet worden dat wanneer je zaken wilt onderscheiden, je ze nog steeds onderdeel laat uitmaken van eenzelfde groot geheel, zodat
  waargenomen connectie tussen de twee, nodig bij gebruik, niet verloren gaat. 
- Indrukken van pedalen in verticale richting is intuïtiever dan indrukken in horizontale richting.
- Beide prototype varianten zijn in huidige staat niet combineerbaar met piano pedalen.
- Een horizontaal schuifcontactvlak in de lucht is niet comfortabel bij gebruik, voorkeur gaat naar schuin contact.
- Nieuw theoretisch model vertoont voldoende potentieel om mee verder te werken in het proces.
- Constrainen kan ook nadelen hebben in specifieke situaties, waarmee rekening moet gehouden worden.

---
## Mental card sorting - resultaten

![Foto](/img/RES14.png)

Conclusies:  
- Pauzeren, hervatten en terugspoelen wordt gezien als absoluut noodzakelijk gecategoriseerd, wat betekent dat deze sowieso moeten blijven.
- Geen enkele functie werd als niet zinvol gecategoriseerd. Volgens deze 3 personen zijn dus geen redundante, weglaatbare functies aanwezig.
- Sneller en trager functies (zeker trager) zijn interessant om verder op in te gaan. Om gebruikersfundamentalisme tegen te gaan, zullen hier pas definitieve conclusies rond
  genomen worden na deze als toegevoegde functies te laten categoriseren bij de volgende test.
  Switching wordt als algemeen zinvol, maar minst noodzakelijk uit de selectie beschreven. Wat betekend dat het interessanter is om in de app een mogelijkheid te bieden om
  één van de twee te selecteren. 

---
## Design requirements

Uit alle verkregen data kunnen nieuwe design requirements gevormd worden die zich zullen aansluiten bij de huidige [requirements](/docs/design_requirements.md).

- De controller signaleert enkel naar bedoelde affordances.
- De controller elimineert zoveel mogelijk ongewenste nuance in interpretatie van gebruik.
- De controller heeft een bediening die zo simpel is als haalbaar.
- De controller heeft een zo snel mogelijke bediening.
- De controller minimaliseert het risico van verkeerde inputs.
- De controller geeft een nauwkeurige response op inputs.
- De controller biedt zelf een merkbare vorm van tril feedback op inputs.
- De controller heeft een bediening die zo min mogelijk voetverplaatsing vereist.
- De controller heeft een bediening die natuurlijk aanvoelt.
- De controller heeft na langdurig gebruik geen negatieve lichamelijke gevolgen zoals krampen of pijn.
- De controller is zo compact als mogelijk, met een voorkeur naar verticale compactheid, boven horizontale.
- De app biedt aan de gebruiker de optie om uitleg te krijgen over hoe de pedalen werken.
- De app biedt een manier van navigeren door de muziekcatalogus, die intuïtief en verstaanbaar is voor de gebruiker. 
