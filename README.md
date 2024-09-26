# Pug-it
Grattis. Du har lyckats klona hem repot eller så arbetar du till och med i ett Codespace. Oavsett så jobbar vi vidare med uppgifterna!

Du lämnar in genom **commit + sync**



## Resurser
- https://expressjs.com/en/starter/installing.html 
- https://expressjs.com/en/starter/basic-routing.html 
- https://expressjs.com/en/starter/static-files.html 
- https://expressjs.com/en/guide/using-template-engines.html
- https://www.youtube.com/watch?v=Ad2ngx6CT0M
- https://pugjs.org/api/getting-started.html
- https://pugjs.org/language/iteration.html 


## 3.2.1 Setup
Initiera ett projekt och installera express
Skapa en server och rutten / och testa att den är igång

## 3.2.2 HelloWorld med templating
Skapa /views
Installera pug och ställ in servern på pug som templating-motor
Skapa /views/hello.pug och använd pug och url för att skriva ut namnet så att när en surfar till /hello/Johan så skrivs en trevlig hälsning till Johan ut på sidan som en h1

## 3.2.3 Tid
Skapa funktionalitet så att aktuell dag, månad och år skrivs ut när en surfar till /time. Använd pug.

## 3.2.4 Statiska filer
Se till att bilderna och css-filerna finns tillgängliga i en mapp om en surfar direkt till dem, ex om man surfar till /css/style.css så ska man få upp css-filen

## 3.2.5 Gör om index.html med pug
Gör en lämplig fil i /views och trigga den med /
Återskapa index.html som ligger i mappen assets med pug. Du ska inte ändra i style.css förutom att du måste fixa till en bakgrundsbild med rätt sökväg.

## 3.2.6 Använd each och data för tjejerna (valfri)
Gör om 3.2.5 så att delen med de tre tjejerna loopas ut med en each utifrån ett objekt du skapat i din js-fil. Vi kommer i del 4 att hämta data från databaser och göra precis det här. 
