# I. Betartandó fejlesztési folyamat:
1. **Issue létrehozása** - Hozz létre egy issue-t. Az issue-ban leírt feladat legyen elég részletesen leírva, hogy bárki elvégezhesse. A leírt feladat mérete maximum 1-2 órás legyen, de lehetőleg kisebb.
2. **Létező issue kiválasztása** - Válassz ki egy issue-t és végezd el.
3. **Felhasználó hozzárendelése** - A munkacsoport vezető felelőssége, hogy minden issue időben elkészüljön, ennek érdekében hozzárendelhet feladatot a csoport tagjaihoz. Mindig mindenkinek legyen feladata. Próbáljátok úgy osztani, hogy mindenki azt a részét végezze, amihez a legjobban ért és ahol a legtöbb hozzáadott értékkel tudja támogatni a csapatot.
4. **Feladat elvégzésének elkezdése:** A kiválasztott issue ToDo-ból planning vagy in progress-be mozgatása. E nélkül nem kezdhető el feladat. Csak leírt issue végezhető el. Az elszámolásnak ez az alapja.
5. **Feladat befejezése:** Amikor a kiválasztott feladat elkészült, akkor a következő lépéseket hajtsd végre:
    * *commit* - változtatásokra add ki a commit-ot. , amelynek a szövege minden esetben így kezdődjön: #X, ahol X egyenlő az issue számával. Ezután írj egy rövid leírást is! Issue sorszám belinkeléséről bővebb infó itt:
    [https://help.github.com/en/github/writing-on-github/autolinked-references-and-urls](https://help.github.com/en/github/writing-on-github/autolinked-references-and-urls)
    Példa issue a helyes commit-hoz: [https://github.com/gitjuzer/EGER_2019_2_Lev_A/issues/20](https://github.com/gitjuzer/EGER_2019_2_Lev_A/issues/20)
    * *Push* - Módosítások feltöltése.
    * *Done* - Kártya átmozgatása Done oszlopba.

> Megjegyzés: Ne zárd le az issue-t, azt a code review után megtesszük.

# II. Git munkafolyamat:

A projekt sikere érdekében, [az itt található](https://nvie.com/posts/a-successful-git-branching-model/), 
jól bevált munkafolyamat egyszerűsített változatát fogjuk alkalmazni.

**A lépések betartása kiemelten fontos.** Elhagyásuk esetén már egy nálunk kisebb létszámú, és jóval tapasztaltabb fejlesztői csapat 
is komoly problémákba ütközhet. A lépések végrehajtásáról részletesen olvashatsz a [Git alapok fejezetben](git_tutorial.md) fejezetben.


A folyamat:

1. Ne kezdd el a fejlesztést, **még egy fájnevet se írj át, egy mappát se hozz létre**, amíg az adott pont nem ad rá utasítást!
2. Git repó klónozása.
3. Váltás a develop branchre. **NE FEJLESSZ A MASTER BRANCH-BEN!**
4. Adj nevet a fejlesztendő feladatnak, és hozz létre hozzá egy feature branch-et! Hogy mi számít elkülöníthető feladatnak, és az elnevezéssel kapcsolatos konvenciókat beszéljétek meg a csoportotok vezetőjével!
5. **Most kezdheted a fejlesztést!** 
6. Ha úgy gondolod, hogy a munkád publikálható (commitálható), akkor hajts végre egy **commit**-ot!
7. Válts vissza a develop branch-re, mergeld vissza a feature branchedet, majd töröld azt! Ne aggódj, a munkád nem fog elveszni, csak az ágak elkülönítése szűnik meg ilyenkor. (Természetesen van lehetőség teljes törlésre is, de ez nem ide tartozik)
8. A develop branche-t pushold a GitHub repóba (szükség esetén pull és konfliktus feloldás)!
9. Minden egyes jól elkülöníthető feladatra ismételd a 4-8 pontokat!

A fenti szabályok talán szigorúnak tűnnek, de mindenképp megéri betartani őket. Ha ezt a 9 pontot következetesen, 
algoritmikus módon alkalmazod, akkor nagyon hamar belejösz, és nem fog nehézséget okozni.

Egy újabb fontos szabály: **Ne pusholj, amíg nem ellenőrzöd meg a repód állapotát!** (A részletes leírásban megtalálod a módját is)

Mit tegyek, ha mégis kihagytam valamit?

1. Don't Panic :) A commitált módosításaid nem vesznek el, és amíg lokális környezetben dolgozol, másnak sem tudsz gondot okozni.
2. Ha nem a megfelelő branchben kezdtél el dolgozni, akkor egyszerűen válts át a helyes branchre, és folytasd a munkát! **De a váltás előtt NE COMMIT-OLJ**
3. Csak akkor commit-olj, amikor biztos vagy abban, hoyg minden a helyén van. Ilyenkor viszont azonnal!!!

## Git Branch Naming Rules and Conventions
[https://www.youtube.com/watch?v=n0w4oL4bJo8](https://www.youtube.com/watch?v=n0w4oL4bJo8)
