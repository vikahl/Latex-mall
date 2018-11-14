Den här mallen är arkiverad, kommer inte längre att uppdateras och eventuella användare bör kontrollera och reflektera om det finns bättre paket eller inställningar för att lösa problemen.

# En LaTeX-mall

Efter att blivit tillfrågad flera gånger om jag hade någon lämplig LaTeX-mall att utgå ifrån och efter att mallen jag brukade använda blivit hopplöst utdaterad så bestämde jag mig för att göra en mall där jag ansträngde mig lite mer med att kommentera de olika paketen och inställningarna samt att använda versionshantering.
Det är inte ett dokument som försöker vara täcka alla möjliga kombinationer, utan snarare ett enkelt dokument man kan utgå ifrån när man ska skriva inlämningar eller liknande.

Repositoryn innehåller tre mallar:

* Exempeldokument-minimal, ett minimalt dokument med bara det man ”måste” ha
* Exempeldokument-article, ett större dokument med alla filer man bör ha
* Exempeldokument-KOMA, ett större dokument som använder KOMA-Script klasserna. Inte klart än.

## Kompatibilitet

Mallen är framförallt tänkt att användas med LuaTeX men fungerar även med XeTeX. Den fungerar dock inte med pdfTeX, då den innehåller en del paket som kräver LuaTeX/XeTeX. Tar man bort dessa paket fungerar den givetvis.

## Installation

Det är inte särskilt mycket att installera, det är bara en .tex-fil med exempel.

## Licens

Exempeltext är taget ifrån August Strindbergs Röda rummet, som inte längre omfattas av upphovsrätt utan är *allmängods*.


För mer Latex kan du besöka [TeXempelvis](http://www.texempelvis.se)
