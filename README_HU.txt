EDZI · Teljes PWA csomag (2026-11-03)

FELTÖLTÉS GITHUB PAGES-RE:
1. Nyisd meg a GitHubon a meglévő benjamyn72/edzi repositoryt.
2. Az alkalmazás minden fájlját közvetlenül a repository főkönyvtárába töltsd fel.
   Az index.html és a main.js NE kerüljön külön mappába!
3. Ha azonos nevű fájlokat már tartalmaz a tárhely, a GitHubon cseréld/felülírd őket.
4. Settings > Pages > Deploy from a branch > main > /(root).
5. Webcím: https://benjamyn72.github.io/edzi/
6. iPhone Safariban Megosztás > Hozzáadás a Főképernyőhöz.

TARTALOM:
- index.html: teljes felület és iPhone safe-area javítás
- main.js: napló, gyakorlatok, 24 recept, 34 kártya, Smart Workout Assistant,
  Gym RPG XP/szint alapverzió, gyakorlatonkénti PR Hall of Fame (becsült 1RM)
- sw.js: offline PWA gyorsítótár, új cache-v5
- manifest.webmanifest: telepítési adatok
- icon.svg, icon-180.png, icon-192.png, icon-512.png: EDZI ikonok
- EDZI_offline_demo.html: önálló HTML kipróbáláshoz, nem szükséges a PWA működéséhez
- README_HU.txt: ez az útmutató

FONTOS:
- Az app ugyanazt a helyi adattárolót használja (edzi_app_v2); a frissítésnek
  meg kell őriznie a meglévő edzéseket és kártyákat, ha ugyanazon a webcímen fut.
- Feltöltés előtt az app Beállítások menüjében készíts JSON biztonsági mentést.
- Az adatok nem szinkronizálódnak a felhőbe.
- A kártyák ebben a verzióban stilizált, emojialapú grafikákkal jelennek meg,
  nem különálló fotókkal vagy generált illusztrációfájlokkal.
- A Gym RPG jelenleg XP + szint, nem avatár. A PR becslés nem valódi 1RM mérés.
- iPhone fájlelőnézetben a HTML JavaScriptje korlátozott lehet. A teljes PWA-t
  GitHub Pages-en, Safariban érdemes használni.


EDZI v7 - KARTYA JAVITAS (2026.11.04.)
A kartyakepek teruletenek nulla szelessegre zsugorodasa megszuntetve.
A figurak CSS/emoji-alapuak, nem kulso kepfajlok; Safari alatt is lathatok.
Animalt fenyeffekt es lebego ikonok megmaradnak.
Telepites: a ZIP osszes gyokerfajljat toltsd fel a GitHub edzi repoba a korabbiak helyere;
a regi fajlok atirasat/commitolasat a GitHubon erositsd meg.
Adatok: a bongeszo localStorage-jat ne torold, mert az edzesnaplo ott tarolodik.
Ha a regi verzio maradt meg, teljesen zard be a Safari lapot, es nyisd ujra.
