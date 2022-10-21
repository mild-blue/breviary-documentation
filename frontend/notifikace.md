### Testování notifikací
Notifikace je potřeba testovat v 3 režimech
- v otevřené aplikaci
- v minimalizované aplikaci (jenom klasicky zavřít)
- po force quit

1. Otevři si `https://breviary.stg.mild.blue/` na počítači
2. Přihlas se pod stejným účtem a do stejné jednotky (`default`) jako na mobilu (nebo tabletu)
    - webová aplikace tě nevyzve k vybrání organizace, ta je vybrána automaticky podle url s kterou se do aplikace dostaneš
3. Vyber typ léku `Heparin`
4. Otevři pacienta
5. Zeskroluj dole a klikni na `Přidat výsledek appt testu`
6. Zadej jakoukoliv hodnotu v zadaném rozmezí do pole `Výsledek aPTT testu`
7. Klikni na `Přidat`
8. Notifikace by se mněla zobrazit na telefonu (nebo tabletu)

#### Notifikace mi nechodí
- ujisti se, že máš povolené notifikace pro breviary v nastaveních telefonu
- na některých LG mobiloch byl potřebný restart telefonu (spíš vypadá na problém os)
