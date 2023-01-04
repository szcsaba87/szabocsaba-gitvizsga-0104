git init
Initializáltam egy üres Git repositoryt

README.md létrehozása

git pull git@github.com:szabopeter92/git-vizsga0104.git
Lehúztam a githubról a vizsgaanyagot.

.gitignore létrehozása, benne *.txt, *.doc stb. beírása, hogy azokat ne vegye figyelembe majd a commit

git branch console - új ág létrehozása

git checkout console - ágra váltok

git add . - minden fájl hozzáadása (kivéve ami a gitignoreban van)

git commit -m "Eredeti verzió gitignore-ral, readme-vel, teszt txt-vel (javítva)"

app.js mókolása

git add . - ezzel hozzá is adtuk a következő verzióhoz

git commit -m "App js-be bekerült a betöltodött oldal kiíratása" - eltároltuk ezt a verziót

style.css mókolása

git add . - ezzel hozzá is adtuk a következő kiadáshoz

git commit -m "Style.css módosítva - háttér" - már kiírja a console-ba, ami a feladatban szerepel

git remote add origin git@github.com:szcsaba87/szabocsaba-gitvizsga-0104.git - hozzákapcsolom a githubot

git push -u origin console - feltöltöm a githubra
