---
---
Färgschema kmom04
=========================

Tre tekniska utbildningars webbplats
=======================
I denna undersökning har jag valt att titta på tre webbsidor som representerar tekniska universitetsutbildningar i Sverige.
De tre sidorna ska analyseras med hjälp av ett röd-grön-blå-färghjul för att undersöka färgpalett, färgschema samt eventuell accentfärg. Det ska även göras en analys av deras typografiska val av rubriker och font.
Genom att sammanställa dessa analyser ska det gå att utläsa vilken profil de förmedlar och vilka gemensamma drag det finns.

Urval
--
Idag används dbwebb.se till stor del i studierna under utbildningen i webbutveckling på Blekinge Tekniska Högskola (BTH). Det är till största delen den sidan jag har kommit i kontakt med genom utbildningen på distans, och det är lätt att glömma att det faktiskt är bth.se som är skolans huvudsida.
dbwebb.se samt bth.se skiljer sig väsentligt åt i utformning, och jag funderade på hur andra skolor har lagt upp sina webbsidor.

Eftersom BTH är en teknisk högskola valde jag att söka på tekniska högskolor, och letade efter en gruppering av tre som krävdes för undersökningen.
På wikipedia.se finns en artikel, ”Teknisk högskola i Sverige”, där en gruppering av tre tekniska högskolor fanns med. Under titeln självständiga tekniska högskolor med universitetsstatus samt tekniska universitet fanns följande tre utbildningssäten:

-  Chalmers Tekniska Högskola (CTH)
-  Kungliga Tekniska Högskolan (KTH)
-  Luleå Tekniska Universitet (LTU)

Det är dessa tre skolors webbplatser som ska undersökas.

Metod
--
Startsidan utgör grunden för analysen, efter det att man har klickat bort alla eventuella pop-up-element.

Bilderna som är tagna av webbsidan har vidden 1536px samt bredden 737px. Bilden är redigerad där menyn från datorn samt där navigationen för webbfönstret syns har skurits bort i programmet Paint 3D och sedan sparad i formatet .jpg. Man bör ha detta i åtanke då jag har analyserat bilden, och inte hela webbplatsen, därför kan man hitta fler färger samt accentfärger på vissa sidor om man går in aktivt på webbplasten.

För färganalysen utgår jag ifrån de tre primära färgerna röd-grön-blå (RGB), och med hjälp av de tre ska jag analysera färgpalett, färgschema samt eventuell accentfärg. Jag har använt Eye Dropper som är ett tillägg till Chrome för att hämta färger på hemsidor med. Jag har valt den delen av bilden där färgen framkommer mest.

Val av typsnitt för H1-H3 (titel-element i HTML) samt brödtext kommer att analyseras med hjälp av utvecklingsverktyget i webbläsaren.

Undersökningen görs på en Dell Inspiron 5570 och Chrome är den webbläsaren som används.

Svårigheten med genomförandet av en färganalys är personliga inställningar på datorn, samt datorns egna inställningar. Även färger har olika betydelse beroende på kulturell status, vilket bör tas i beaktande.

Resultat
--
Varje webbsida ska undersökas i samma ordning som skolorna nämndes i urvalet. Undersökningen kommer att göras på de färger som syns på bilden.

I analysen förekommer termen sans-serif samt serif. Jag har valt att behålla den engelska stavningen på dessa två termer. Skillnaden dem emellan är att serif har en liten klack i slutet på bokstaven. Sans-serif saknar klacken.

###CTH
[FIGURE src=image/cth.jpg?width=100% alt="Chalmers Tekniska Högskolas startsida" caption="Chalmers Tekniska Högskolas startsida"]

Bakgrunden är ljust grå med vit meny med svart text samt en vit side-bar med cirkulära bilder och svart text. Själva innehållet är färgade div-element med vit text som är länkar.

Första övre bilden är väldigt ljus i mitten och mörkare mot sidorna och består mest av grå-blåa toner med gröngula inslag från buskarna/träden. Texten är vit med skugga.

Div-elementen består av följande färger:

<table style="border-spacing: 4px; border-collapse: separate">
    <tr>
        <td style="height: 50px; width: 50px; background-color: #056963">
        <td style="height: 50px; width: 50px; background-color: #8b879e">
        <td style="height: 50px; width: 50px; background-color: #4a80aa">
        <td style="height: 50px; width: 50px; background-color: #5d8b01">
    </tr>
</table>

Färgschemat är analogt med fokus på blått och grönt.
Ingen accentfärg har använts då man har använt flera olika färger som får lika stort utrymme.

####Typografi
På första sidan finns varken h1 , h2 eller h3. Den första typ av header som dyker upp i htmlkod är h4 och det är en sans-serif.  I övrigt har de använt div-element för att formatera header-text men även de är sans-serif.

Första sidan består mest av länkar och bilder, men även om man klickar sig vidare så är brödtexten även den en sans-serif (https://www.chalmers.se/sv/styrkeomraden/energi/nyheter/Sidor/Ett-steg-n%C3%A4rmare-solcellsutmaningen-.aspx).

###KTH
[FIGURE src=image/kth.jpg? width=100% alt="Kungliga Tekniska Högskolans startsida"caption="Kungliga Tekniska Högskolans startsida"]

Bakgrunden är ljust grå med vit body, och en mörkt grå login-meny längst upp. Svart text på vit bakgrund, med en blå logga och ett div-element i färg för att fokusera nyheter. I övrigt har man bilder kopplade till artiklarna för att ge färg.

KTH:s logga är i färgen dark slate blue, och består av lite mer grönt än rött i grunden.

Nyheter-elementet består av färgen crimson, en röd ton med lite mer blått än grönt.

<table style="border-spacing: 4px; border-collapse: separate">
    <tr>
        <td style="height: 50px; width: 50px; background-color: #2258a5">
        <td style="height: 50px; width: 50px; background-color: #e4363e">
    </tr>
</table>

Tittar man på bilden är det ett analogt färgschema, där man har valt närliggande röd och blå, med olika nyanser, med fokus på vitt och svart. Jag anser att crimson är en accentfärg på webbplatsen.

####Typografi
Det finns inga h1-element utan det är h2 som är första elementet. Det används som rubriker i ”KTH gästas av Netflix” samt ”Hur är det att plugga på KTH?”. h2 är en tydlig serif med klackar på K, T samt H som sticker ut. H3 som ligger ovanför rubriken med texten ”Nyheter” har de valt att sätta som san-serif, likaså brödtexten är sans-serif.

###LTU
[FIGURE src=image/ltu.jpg? width=100% alt="Luleås Tekniska Universitets startsida"caption="Luleås Tekniska Universitets startsida"]

En dominerande färg i djupt blått med vit eller blå textfärg, små inslag av gult som i de dubbla vinkelcitationstecken.

Accentfärgen heter orange och har inget blått i grunden. Den blåa färgen har inte särskilt mycket rött i sig.

<table style="border-spacing: 4px; border-collapse: separate">
    <tr>
        <td style="height: 50px; width: 50px; background-color: #053159">
        <td style="height: 50px; width: 50px; background-color: #ff9d00">
    </tr>
</table>


####Typografi
Den h1 som finns är inte synlig, men tillhör fontfamiljen sans-serif. h2-elementen är de mörkblåa som ligger som rubriker på artiklarna. All text på sidan är sans-serif.

Analys
-----------------------

###CTH
Färgschema med fokus på blått och grönt.
Tyvärr den vita textens kontrast dålig på stora första bilden, trots skuggningen som jag tror är där för att utmärka texten snarare än att ge ett djup. Jag tror man hade vunnit på att göra bakgrundsbilden mer enhetlig i färg, och därför lyft de under div-elementen mer. Även läsbarheten hade förstärkts.

De ger ett intryck av en modern webbsida, med inslag av lekfullhet i sina cirkulära bilder, och nyttjande av färger.  Bra läsbarhet på fonten, och fina öglor på deras gammaldags g:n.

###KTH
Jag anser att man har använt crimson som en accentfärg, då den är den enda och det görs för att markera en nyhet. Man vill att blickarna dras dit direkt.

I övrigt är webbsidan färglös, och man har valt att fokusera på färgrika bilder till artiklarna.

KTH låter vissa rubriker vara serif, och andra sans-serif. Brödtexten är sans-serif, och kanske är det det som gör att jag upplever det som rörigt, tillsammans med blandningen av färger.

Fonten som används som brödtext har för litet mellanrum under g:t för att det ska bli bra. Det saknas luft i själva fonten.

I side-baren har man valt att ha svart som bakgrund och vitt som font i rubriken, förmodligen för att markera att det tillhör en annan sida (KTHmagazine) men resultatet blir rörigt.

Första anblicken ger ett rörigt intryck av sidan. Det händer för mycket, och det saknas en röd tråd i fontvalet. Man har dessutom valt att blanda sans-serif med serif i headings, vilket gör att det upplevs som ostrukturerat. Kanske är KTH:s lekfullhet av fonter ett sätt att försöka vara innovativa, men helhetsintrycket blir inte bra.

###LTU
LTU:s webbplats har två färger och ett genomgående färgtema som anspelar på kall vinter med blått och vitt och bilder av snö och skidåkning. En gulare accentfärg som är sparsamt använd lyfter layouten.

Enda bristen är rubriken på artiklarna. De är väldigt tjocka och kompakta, och jag ser i mina verktyg att de dessutom har valt att minska utrymmet mellan bokstäverna.
I övrigt ger de ett stilrent och lekfullt inslag med sina anspelningar på snö och norrland.

Sammanfattning
--
De tre sidorna representerar de tre tekniska universiteten i Sverige. KTH samt CTH har flera färger på sin webbsida, där CTH lyckas bättre med sina färgval än KTH. LTU har sparsamt med färg och känns därför lite mer kompakt.

Gällande fonter så lyckas CTH bäst med läsbarheten på brödtext samt rubriker. En lite fin detalj är öglan på g:t som talar för lite tradition mitt i det moderna. KTH blandar sans-serif och serif, och blandar dessutom i rubrikerna vilket ger ett osammanhängande intryck. LTU är kompakt men sammanhållande.

Alla tre talar för att webbplatserna är medvetna om sin användargrupp, i olika mått. Det finns en vilja att inte vara för minimalistisk, slätstruken och enkel. Kanske att LTU:s layout hade passat bättre på en skiResort, än på ett tekniskt universitet men det är lockande med all snö och sol. CTH är den som känns mest traditionell, och hade det inte varit för färgvalen hade det nog upplevts på gränsen till tråkigt.

De representerar ett visst mått av seriositet, även om den kan ifrågasättas på KTH:s webbplats, och de slåss om sina kunder som alla andra webbplatser. Webbplatsen är det första som studenterna möter idag när de söker utbildningar. Och ska jag sammanställa de tre känslorna som webbplatserna förmedlar blir det på följande sätt:
- CTH är ett traditionellt men inte genomtråkigt ställe att studera på
- KTH är ett rörigt, ostrukturerat utbildningssäte
- LTH är ett lekfullt, aktivt universitet i norr

Referenser
--
###Internetkällor
_”Teknisk högskola i Sverige”_, Wikipedia, https://sv.wikipedia.org/wiki/Teknisk_h%C3%B6gskola_i_Sverige , 2018-11-29, (20:13)

_”Kungliga Tekniska Högskolan”_, https://kth.se, 2018-11-29, (20:42)

_”Chalmers Tekniska Högskola”_, https://cth.se, 2018-11-29, (20:47)

_”Luleås Tekniska Universitetet”_, https://ltu.se, 2018-11-29, (20:49)

_”Tvärsöver kontinenten på bara solkraft”_,
https://www.chalmers.se/sv/styrkeomraden/energi/nyheter/Sidor/Ett-steg-n%C3%A4rmare-solcellsutmaningen-.aspx, 2018-11-30, (13:25)
