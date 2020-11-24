# Individuellt projekt: PWA
## Progressive Web App

1. [Uppdragsbeskrivning](#1-uppdragsbeskrivning)
1. [Inlämning](#2-inlämning)
1. [Bedömning](#3-bedömning)


---
### 1. Uppdragsbeskrivning
Du ska bygga en PWA som kombinerar de tekniker vi har gått igenom i kursen.

Appen ska publiceras online, till exempel med https://surge.sh/ som vi använde i kursen.

#### Appen: Instablam
Instablam ska vara en PWA som användaren kan använda för att ta bilder med sin mobil eller dator med kamera. När man tar en bild så ska den sparas i ett galleri i appen. Tillsammans med bilden ska du spara information om när den togs och på vilken plats.

Användaren ska kunna bläddra i galleriet, ta bort enskilda bilder, ladda ner en bild. Det ska finnas minst två bilder i galleriet när appen startar.

När man tagit en bild kan en notifiering visas, som innehåller bilden.


#### Testa din app - webbläsare
Använd så många olika webbläsare som möjligt när du testar din app. Du kan till exempel svara med en tabell, med emojis eller text. Samarbeta gärna med klasskamrater så att ni kan testa era appar i så många olika miljöer som möjligt.
Testa gärna i fler webbläsare och miljöer än de som står här. Exempel på tabell:

|Webbläsare      |Geolocation |MediaDevices |Notification |Offline |Push |
|----------------|--------|-|-|-|-|
|Desktop Chrome  |✔️| Ja |
|Mobil Chrome    |⛔| Nej |
|Desktop Firefox |✔️| Ja |
|Mobil   Firefox |✔️| Ja |
|Desktop Safari  |❔|Inte testat|
|Mobil   Safari  |❔|Inte testat|
|Desktop Edge    |❔|Inte testat|
|Mobil   Edge    |❔|Inte testat|

#### Testa din app - Lighthouse
Testa appen med Lighthouse (inställningen Progressive Web App) och skriv ner resultatet:

|Kategori |Poäng |
|-|-|
|Fast and reliable | 0 / 3 |
|Installable | 0 / 3 |
|PWA Optimized | 0 / 8 |

*Båda rapporterna ska göras på den publicerade appen.*


---
### 2. Inlämning
Ditt projekt ska vara ett GitHub-repo. Det ska innehålla en README.md fil som innehåller ditt namn och länken till din publicerade app. Berätta kort om din app och de viktigaste funktionerna. Glöm inte att ta med testrapporterna. Zippa hela repot (utom `node_modules/` och `.git/`) och ladda upp på LearnPoint.

**Obs!** Du ska använda zip-formatet för att komprimera filerna och GitHub markdown för readme-filen. Läs mer här: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet


---
### 3. Bedömning
**För godkänt** på projektet ska appen
1. Vara publicerad online
1. Finnas i ett publikt repo på GitHub och innehålla en README.md
1. Ha en Lighthouse-rapport i README.md som du har skrivit
1. Zippas och laddas upp på LearnPoint
1. Vara en installerbar PWA (manifestfil och ikoner)
1. Använda Geolocation API
1. Använda MediaDevices API
1. Offline first: gå att använda så mycket som möjligt även utan internet

**För väl godkänt** på projektet ska du demonstrera att du behärskar kursens innehåll på en djupare nivå. Det gör du genom att göra en bättre och mer professionell app. Till exempel:
+ testa i många webbläsare och miljöer
+ användarvänlig hantering av felmeddelanden
+ hänsyn tagen till tillgänglighet
+ egenproducerade ikoner och eventuella bilder
+ Notification API
+ Push API eller Safaris motsvarighet


Tips: du kan använda https://push-notifications-admin.surge.sh/ för att skicka push-notiser.


---
#### FAQ
*Deadline för inlämning är 2020-12-04 kl 17:00.*

**Q**: Måste jag göra alla punkter på VG-listan? Hur många måste man göra?<br>
**A**: Nej, man måste inte göra alla punkter för att få VG. Satsa på att göra de du väljer så bra som möjligt.

**Q**: Vad händer om jag glömmer skriva README.md? Eller inte tar med länk till publicerade appen? <br>
**A**: Din inlämning är inte fullständig och kommer inte att bedömas.


*Lycka till!*

[Toppen av sidan](#1-introduktion)
