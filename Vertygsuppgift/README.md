# Vertygsuppgift - Introduktion till modern utvecklarroll 
I denna övning tränar jag på att använda terminalen, Git/github och VS code. Syftet är att lära mig grunderna i filsystem och dokumentation. Jag har förstått att en readme.md är bra att ha med i varje projekt för att beskriva vad det gör och varför det finns. Om något behöver installeras kan man också skriva enkla steg hur man ska göra det. 

Vet inte hur mycket som skall skrivas i denna uppgift men hoppas att detta räcker.

## Git kommandon jag använt

- `git init` – skapar ett nytt tomt Git repository i mappen
- `git add .` – lägger till alla filer i mappen som redo för nästa commit
- `git remote add origin <url>` – kopplar det lokala repot till ett repository på GitHub
- `git branch -M main` – byter namn på nuvarande branch till main
- `git config --global user.email "din@mail.com"` – ställer in vilken e-postadress som ska kopplas till ens commits
- `git config --global user.name "Ditt Namn"` – ställer in vilket namn som ska kopplas till ens commits
- `git commit -m "meddelande"` – sparar en ny commit med ett förklarande meddelande
- `git push -u origin main` – skickar upp branchen main till GitHub och kopplar dem ihop, så framtida `git push` räcker utan `-u origin main`
- `git log` – visar historiken över alla commits som gjorts i repot

# Vad är ett repository, en commit och versionshistorik
Ett repository (repo) är en mapp som git håller koll på och som
innehåller alla filer i projektet plus hela historiken av ändringar.
En commit är typ som en "sparpunkt" i den historiken alltså en samling ändringar
med ett meddelande som beskriver vad som gjordes. Versionshistorik
är listan av alla commits i tidsordning, vilket gör att man kan se
och gå tillbaka till tidigare versioner av projekte
