# Testtömeg index számító mobil app készítése
## Új projekt létrehozása
Első lépésként be kell jelentkezni az Appinventor felületére, majd **Projects** menüből a **Start New Project**-et kell választani
![ujprojekt](newproj.JPG)

## Új képernyő (screen) hozzáadása
Azt szeretnénk, hogy az app egy kezdő képernyővel induljon, amiről gombnyomásra lehet továbbmenni a számításhoz. 
Az **Add Screen**-re kattintva adunk a projekthez új screent. Adjuk neki valami nevet, pl **tti_szamitas** 

![ns](newscreen.JPG)
![screenek](screenek.JPG)

A kezdő screen-en alakítsuk ki a következő felületet:

![felulet](felulet2.JPG)

Ehhez a **Layout**-ok közül válasszuk a **VerticalArrangement**-et, húzzuk a **Screen1**-re

A **Screen1**-en az **alignHorizontal** értékét állítsuk **Center**-re

A **VerticalArrangement**-re húzzunk két darab **Label**-t és alájuk egy **Button**-t.
A **Buttont** nevezzük át **tovabb**-ra.
Állítsuk be a **Screen1**-nek, valamint a **VerticalArrangement**-nek is tetszőleges háttérszínt.

A **Screen1**-nél váltsunk át **Blocks** nézetre (jobb felső sarok).

Válasszuk ki a **tovabb** nevű gombunkat. A **Click** eseményt kell megadnunk, ezt húzzuk át jobbra. A parancs amit az esemény bekövetkeztekor végre kell majd hajtania a progranak a **Control** alatt található **Open another screen...** lesz. Ezt húzzuk bele a kódblokkba. Ezt követően a **Text** elemek közül a legfelső kell, amelyben meg kell adni a megnyitni kívánt screen nevét. Ez most a **tti_szamitas** lesz.

## Az eredmény:
![screen1 kód](screen1_kod.JPG)
Ezzel az első képernyő kész.

Dolgozzuk ki a számítást végző programrész képernyőjét is.

A **tti_szamitas** nevű screen vízszintes igazítását állítsuk be **Center**-re.

A **Layout**-ok közül válasszuk a **TableArrangement**-et, húzzuk a screen-re. Álljon 2 oszlopból és két sorból.
A bal oldali cellákba kerüljön 2 **Label**, a jobb oldalra pedig 2 **TextBox**





