# git-vizsga
GIT vizsga feladat

git config user.name    // Felhasználónév beállítás ellenőrzése - rendben van, régebben beállításra került
git config user.email    // E-mail cím beállítás ellenőrzése - rendben van, régebben beállításra került
git init    // Git hozzáadása a projekthez
git clone https://github.com/szabopeter92/git-vizsga    // Letölti a megadott remote repository-ból a local repository-ra a komplett project könyvtárat
README.md fájl létrehozása
.gitignore fájl létrehozása
git add .    // A fájlok hozzáadása a staging areahoz
git commit -m ".README.md és .gitignore fájl létrehozása és fájlok hozzáadása a staging areahoz"    // Verzió rögzítés
git branch console    // console nevű ág létrehozása
git checkout console    // console ágra váltás
git add .    // A fájlok hozzáadása a staging areahoz
git commit -m "app.js fájl módosítása: Betöltődéskor kiírja, hogy az oldal sikeresen betöltődött"    // Verzió rögzítés
git add .    // A fájlok hozzáadása a staging areahoz
git commit -m "style.css fájl módosítása: Háttér színátmenet megváltoztatása"
git remote set-url origin https://github.com/hatamas/git-vizsga.git
