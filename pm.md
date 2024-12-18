# HissProjekt PM
Oliver Magnusson (2024-12-18)

## Inledning
Vi fick uppgiften att skapa en valfri hiss i grupp eller enskillt. Vi fick uppgiften för att lära oss implementera våra kunskaper i verkliga scenarion. Jag valde att göra en grupp med Daniel och Sebastian. Efter ett tag så slutade det upp med att bara jag och Daniel var kvar i gruppen. Vi valde att göra en 3D hiss i programet Unity som använder sig av programeringsspråket C#. Innan vi började med 3D-hissen gjorde vi en prototyp i python. Den prototypen är menad att visa hiss logiken. Alltså vilken våning den far till härnäst och system om hur man sparar kön till alla våningar.

Vi beslöt att jag skulle kolla in lite mer i Unity då jag har använt det förut och Daniel skulle börja på prototypen. Vi arbetade tillsammans på planeringen och hjälpe varandra då det behövdes.

## Bakgrund
Vi började med prototypen som Daniel har på sin dator så jag har inga bra bilder på den men tanken var att med text input och output generera en liten simulator där man väljer att lägga till våningar eller att fara till nästa tillagda våningen. Vi gjorde det genom några simpla loopar och funktioner. Själva Unity 3D-Hissen är lite svårare att göra då man måste referera objekt med varandra för att nå olika typer av data. T.ex, positionen och rotationen för olika objekt. Med hjälp av datan kan man uppdatera den och flytta på objekten. Vi skapade olika värden för alla tre dimensioner i positioner genom olika Vector3 vectorer. Vector3 skapar värden för alla tre dimensionerna (x,y,z) så man kan hålla koll på saker som position och rotation och mer. Vi skapade en Vector3 för varje våning som hissen kan fara mellan då programmet får rätt tangentbords-input.
![Våningarna](/images/HISS_BILD.PNG)

Bilden visar 10 olika våningar som är sparade som Vector3 data. Bilden visar också två olika listor som man använder för minnet till kön och en variabel som är hastigheten på hissen.

Alla inputs blir till våningar som läggs in i wait queue och när floor queuen är tom läggs första våningen i wait queuen in i floor queuen och tas bort från wait queuen.

### Positiva erfarenheter
Det mesta har gått bra då vi har en slutgiltig produkt som kan fara till alla våningar som vi vill den ska fara till och jag har lärt mig mycket om hur Unity fungerar och om hur olika kodspråk som C# och java skiljs åt.

### Negativa erfarenheter
Dem första lektionerna var det svårt att komma igång då man inte visste vart man skulle börja. Det vill säga att det var svårt att hoppa in i ett 3D program med en ny variant av position data. (Vector3) Det vill säga svårt att fatta vad som krävdes för att objekten skulle röra på sig.

## Sammanfattning
I helhet var det väldigt bra att ha gjort den här uppgiften då jag förstår Unity mycket bättre vilket är ett program som jag vill lära mig hantera ännu bättre. Det var lite jobbigt att jobba i grupp på ett sånt här arbete då man inte riktigt kan koda på samma sak. (position hanteraren)