### iOS instalace beta-verze
1. Nainstaluj si poslední verzi aplikace z [TestFlight](https://developer.apple.com/testflight/)
   - je nutné být přidán jako beta-tester v App Store Connect, v případě, že aplikaci nevidíš kontaktuj Nasťu nebo Ľuboše

### Android instalace beta-verze
1. Na [Google Play](https://play.google.com/store/games?hl=en&gl=US) vyhledej aplikaci `Virtual Breviary`
2. Na stránce aplikace zoskroluj dole a zaklikni tlačítko `Join` v sekci `Join the beta`
3. Nainstaluj si poslední verzi aplikace

### Login do aplikace
1. Po otevření tě aplikace vyzve k vybrání organizace. Klikni na tlačítko `Přidat vlastní`.
2. Do pole `Název organizace` napiš `stg` (ale může to být cokoliv)
3. Do pole `Adresa serveru` napiš `https://breviary.stg.mild.blue/` (adresu stagingu)
4. Vyber organizaci `stg` a klikni na `Pokračovat do organizace stg`
5. Po úspěšném připojení klikni na `Přihlásit se`. Pokud nedošlo k úspěšnému připojení byla buď chybně zadaná adresa nebo stg neběží. Vyzkoušej zadáním adresy do tvého oblíbeného prohlížeče.
6. Zadej uživatelské jméno a heslo pro `stg`. (najdeš v bitwardenu)
7. Vyber hospitalizační jednotku default
8. Vyber typ léku `Heparin`

### Testování notifikací
Notifikace je potřeba testovat v 3 režimech
- v otevřené aplikaci
- v minimalizované aplikaci (jenom klasiky zavřít)
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