# Individuellt projekt: PWA
## Progressive Web App

1. [Uppdragsbeskrivning](#1-uppdragsbeskrivning)
1. [Inlämning](#2-inlämning)
1. [Bedömning](#3-bedömning)


---
### 1. Uppdragsbeskrivning
Du ska bygga en PWA som kombinerar de tekniker vi har gått igenom i kursen.

Appen ska publiceras online med https://surge.sh/ som vi använde i kursen. Den ska använda React.


#### Kompabilitet
Eftersom PWA är en relativt ny teknik, med ofullständigt stöd i olika webbläsare och på olika plattformar; är det svårt att uppnå 100% stöd för alla funktioner. Inlämningarna kommer att testas på Windows-dator med Chrome och Firefox. Om du känner dig osäker på om din app kommer att fungera, kan du redovisa de svajiga bitarna på lektionstid för läraren.


#### Appen: Instablam
*Detta är kraven som din app ska uppfylla.*

Instablam ska vara en PWA, som användaren kan använda för att ta bilder med sin mobil, eller dator med kamera. När man tar en bild så ska den sparas i ett galleri i appen. Tillsammans med bilden ska du spara information om när den togs, samt på vilken plats. Om inte användaren tillåter platsinformation ska det framgå tydligt på bilden, att appen inte vet var den är tagen.

Användaren ska kunna bläddra i galleriet, ta bort enskilda bilder, ladda ner en bild. Det ska finnas minst två bilder i galleriet när appen startar.

**VG**: Försök använda reverse geocoding för att visa närmaste orten, istället för latitud och longitud.

**VG**: Funktion för att appen ska vänta 3 sekunder och sedan ta en bild. När bilden är tagen ska en notifiering visas.

**VG**: Appens filer och tagna bilder sparas i cache, så att användaren kan titta på dem även i offline-läge.


#### Testa din app
Använd fler än en webbläsare när du testar din app. Samarbeta gärna med klasskamrater så att ni kan testa era appar i så många olika miljöer som möjligt.

Kom ihåg att du även kan testa appen med Lighthouse - inställningen Progressive Web App.


---
### 2. Inlämning
Ditt projekt ska vara ett GitHub-repo. Skriv länken till både GitHub-repot och den publicerade appen som en kommentar till inlämningen.
Berätta kort om din app och de viktigaste funktionerna. Zippa hela repot (utom `node_modules/` och `.git/`) och ladda upp på LearnPoint.

**Tips!** Du ska använda zip-formatet för att komprimera filerna. Enklast är att ladda ner ett zip-arkiv från GitHub.


---
### 3. Bedömning
**För godkänt** på projektet ska appen
1. Vara inlämnad på rätt sätt (publicerad online, publikt repo på GitHub, zippas och laddas upp på LearnPoint)
1. Vara en installerbar PWA, som använder Geolocation och MediaDevices
1. Appen uppfyller specen under rubriken "Appen: Instablam"

**För väl godkänt** på projektet ska appen
1. Använda Notification API
1. Kunna gå att använda offline, med hjälp av en service worker
1. hänsyn tagen till tillgänglighet



---

*Lycka till!*

[Toppen av sidan](#1-introduktion)
