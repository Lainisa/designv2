---
---
Laddningstid kmom05
=========================
Tre skidanläggningars hemsida
=======================
I denna undersökning har jag valt att titta på tre webbsidor som alla är relaterade till mitt yrke.
De tre sidorna ska analyseras med Google PageSpeed så väl på dator som på mobil, samt låta sig undersökas av devTools i Chrome på datorn.
Genom att sammanställa dessa analyser ska det gå att utläsa vilken av de tre sidorna som är snabbast i laddningstid och de kommer att rangordnas utifrån deras mätvärden.

Urval
--
Jag har utgått från Kläppen i urvalet, eftersom det är här jag arbetar vintertid. Adderade Bjursås samt Branäs, då det är skidorter med tillhörande vintercamping som jag känner till genom mitt yrke och de ligger nära geografiskt sett.

Före undersökningen var det bara Kläppens webbplats som jag var bekant med, de andra två hade aldrig besökts tidigare men jag utgick från att de alla tre har gemensamma nämnare med camping samt skidåkning.

Jag har medvetet valt bort de eventuella skidorter med campingar som tillhör SkiStar, då deras sida är en stor med flera underliggande för de olika skidorterna.

Dagen då undersökningen görs (2018-12-10, kl 13-14)fungerar inte Bjursås hemsida. Jag väljer därför närmaste skidorten till Bjursås, vilket är Romme Alpin.


Metod
--
Jag kommer att mäta tre sidorna vardera på de tre valda sidorna med Google Pagespeed, både på dator och telefon. De tre undersidorna som ska undersökas är följande kategorier: ”Mat och Nöje” eller dylik kategori, ”Skidåkning” samt ”Om”.

De tre undersidor som ska undersökas är gemensamma för alla sidor. Vissa sidor har dock delat upp sina i underkategorier, vilket jag inte tar hänsyn till i analysen. Det är den översta länken i kategorin alternativ startsidan i kategorin som är den som undersöks.

För varje sida ska jag även med devtools networks notera laddningstiden samt antalet resurser och sidans totala storlek. Detta ska göras tre gånger och sedan tas det ut ett genomsnitt på varje sida.

På mitt andra jobb så har jag vad jag anser vara på gränsen för en trög hemsida. Den totala laddningstiden i devtoools är strax över sex sekunder. Aftonbladets hemsida ser jag som väldigt långsam och den laddar på 7, 27 sekunder. Gränsen för en alldeles för långsam sida går för min del på sju sekunder.
En snabb laddning är under tre sekunder.

För varje sida som jag går in på trycker jag CTRL + Alt + r, för att ladda om sidan med en hård omladdning.
Webbsidornas responsivitet kan även påverka resultatet. Jag noterar att rommes sida går in i ett responsivt läge med hamburgermeny när jag kör den storleken på fönstret som jag har använt (ca 900px i width).

Resultat
--
I resultatet är alla siffror i genomsnitt, om inget annat anges.

###Kläppen
[FIGURE src=image/klappen.jpg?width=100% alt="Kläppen ski Resort startsida" caption="Kläppen ski Resort startsida"]

PageSpeed data ligger på 22 för datorn och 21 för mobilen, vilket anses vara lågt. De åtgärder som föreslås från PageSpeed och som påverkar bilder mest är att använda bilder i rätt storleksformat samt att skicka bilder i modernare filformat.

Storleken på sidorna är mellan 1,9mb till 2,7mb och laddningstiden mellan 4,2s till 5,64 sekunder med antalet requester från 55st till 79st.

Skidåkningssidan är den som är tyngst att ladda men också har flest requests.

###Romme Alpin
[FIGURE src=image/romme.jpg?width=100% alt="Romme Alpin startsida" caption="Romme Alpin startsida"]

PageSpeed data ligger på 99 för datorn och 97 för mobilen, vilket anses vara riktigt bra. De åtgärder som föreslås från PageSpeed är att skicka bilder i modernare filformat.

Storleken på sidorna är mellan 273kb till 345kb och laddningstiden mellan 0,98s till 1,46 sekunder med antalet requester från 24st till 27st.

Skidåkningssidan är den som är tyngst att ladda men också har flest requests.

###Branäs
[FIGURE src=image/romme.jpg?width=100% alt="Romme Alpin startsida" caption="Romme Alpin startsida"]

PageSpeed data ligger på 51 för datorn och 50 för mobilen, vilket anses vara relativt bra. De åtgärder som föreslås från PageSpeed är att skicka bilder i modernare filformat samt koda bilder mer effektivt och använda bilder med rätt storlek.

Storleken på sidorna är mellan 1,4mb till 2,1mb och laddningstiden mellan 3,87s till 5,71 sekunder med antalet requester från 86 till 96st. Det ligger dock ett script i bakgrunden som skickar request som syns i consolen. Detta ökar på antalet requests och gör att finish-tiden aldrig riktigt avslutas.

Mat och nöje  är den som är tyngst att ladda men också har flest requests.

Analys
-----------------------
###Kläppen SkiResort
PageSpeed gillar inte kläppens hemsida. Det är många requester och det tar tid att ladda sidan. Den ligger på gränsen för vad jag anser är trög, men med tanke på hur mediatät sidan är så är den ändå relativt snabb. De kan förbättra laddningstiden och mätvärdet genom att använda bilder i rätt storleksformat, samt skicka bilder i ett modernare format.

Tittar man på antalet bilder av de requests som skickas, så är mat och nöje den sidan som har flest requests av bilder.
Genomgående är det toppbilderna, de som ligger som flashbilder som väger mest.

###Romme Alpin
Det här är en snabb webbsida, genomgående i alla kategorier.
Man kan förbättra resultatet genom att skicka bilderna i modernare bildformat, men med tanke på hur snabba sidorna är så är det inte nödvändigt.
Det är relativit mediatäta sidor, men bilderna är små i storleken och de flesta ligger under 50kb. Däremot är bilderna grynigare, de har inte samma skärpa som kläppen.

###Branäs
PageSpeed är relativt OK, men sidorna skulle vinna på att skicka bilderna i modernare format och koda bilder bättre.  Det är överlag stora bilder med storlek över 100kb på restaurang-sidan. Sidan ligger mellan trög och snabb, och är hanterbar i laddningstid.

Sammanfattning
--
Kläppen har förbättringsmöjligheter. Genom att skicka bilderna i bättre bildformat så skulle de minska laddningstiden. Det som tar mest tid att ladda är oftast flashbilden, som också är störst storleksmässigt sett.

Romme Alpin har grynigare bilder, de har inte samma skärpa som Kläppens bilder. Och kanske hade de vunnit lite på att behålla flashbilden i bättre format. Men Romme är de som är snabbast på laddningen och som kräver minst resurser.

Branäs sida skulle vinna på att koda bilderna bättre, och skicka i modernare bildformat. Branäs sida har en annan layout än de andra sidorna, där jag har fått använda länkar i underkategorier som avläsningspunkt. Huruvida detta har påverkat laddningstiden eller inte kan jag inte avgöra.

Alla skulle bli bättre genom att skicka upp bilderna i ett mer modernt bildformat, koda bilder mer effektivt samt skicka bilder med rätt storlek.

Den sida som genomgående gjort bäst i analysen är Romme Alpin, men de har också sämst upplösning på vissa bilder. De saknar skärpa, men tekniskt sett är de klart bäst av de tre.

På andra plats kommer Branäs, och sist kommer Kläppen. Trots den stora skillnaden i PageSpeed de två emellan, så känns Kläppen lika snabb som Branäs. Detta är konstigt, om man tittar på Branäs sida är de inte ens i närheten av antalet bilder kontra Kläppens hemsida.

Så tekniskt sett kommer Kläppen sist, men bildmässigt så tycker jag de har bäst bilder i skärpa, och skulle då hamna på första plats.

Referenser
--
###Underlag
[Google document med underlag för siffrorna](https://docs.google.com/spreadsheets/d/19NHLhJRdB6ALAyqWbUCSWmzPXPBCa8Wks1jBG4OS4So/edit?usp=sharing)

###Internetkällor
[Branäs](https://www.branas.se/) https://www.branas.se/, 2018-12-10

[Kläppen](https://www.klappen.se) https://www.klappen.se, 2018-12-10

[Romme Alpin](https://www.rommealpin.se/sv) https://www.rommealpin.se/sv, 2018-12-10
