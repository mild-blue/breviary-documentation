### iOS instalace beta-verze
1. Nainstaluj si poslední verzi aplikace z [TestFlight](https://developer.apple.com/testflight/)
    - je nutné být přidán jako beta-tester v App Store Connect, v případě, že aplikaci nevidíš kontaktuj Nasťu nebo Ľuboše

### Android instalace beta-verze
1. Na [Google Play](https://play.google.com/) vyhledej aplikaci `Virtual Breviary`
2. Na stránce aplikace zoskroluj dole a zaklikni tlačítko `Join` v sekci `Join the beta`
    - občas se stane, že trvá pár (desítek) minut než se objaví tlačítko update, v tom připade je možné zajít do `manage apps & devices` skryté pod profilovou ikonkou kde by se po kliknutí na `Virtual Breviary` mnělo ukázat tlačítko update
3. Odinstaluj si produkční verzi aplikace
4. Nainstaluj si poslední beta verzi aplikace

### Login do aplikace
1. Po otevření tě aplikace vyzve k vybrání organizace. Klikni na tlačítko `Přidat vlastní`.
2. Do pole `Název organizace` napiš `stg` (ale může to být cokoliv)
3. Do pole `Adresa serveru` napiš `https://breviary.stg.mild.blue/` (adresu stagingu)
4. Vyber organizaci `stg` a klikni na `Pokračovat do organizace stg`
5. Po úspěšném připojení klikni na `Přihlásit se`. Pokud nedošlo k úspěšnému připojení byla buď chybně zadaná adresa nebo stg neběží. Vyzkoušej zadáním adresy do tvého oblíbeného prohlížeče.
6. Zadej uživatelské jméno a heslo pro `stg`. (najdeš v bitwardenu)
7. Vyber hospitalizační jednotku default
8. Vyber typ léku `Heparin`

### Testovaci scenare
#### Heparin:
1. [Testovani vypisu pacientu.](patient_list.md)
2. [Testovani notifikací.](notification.md)
3. [Testovani hlasek "Není možné doporučit dávku, protože pacientovo cílové aPTT ratio je mimo rozsah nomogramu" a "Není možné doporučit dávku, protože pacientova hmotnost je mimo rozsah nomogramu".](weight_aptt.md)
4. [Testovani nouzoveho zastaveni.](emergency_stop.md)
5. [Testovani nizkeho aptt ratio.](low_aptt.md)
6. [Testovani pri rychlosti pumpy 0.](pump_speed0.md)
#### Inzulin:
1. [Testovani hlasky "Včera nebyla aplikována žádná dávka inzulínu".](no_insulin_yesterday.md)
2. [Testovani pridani noveho vysledku testu.](test_result.md)
3. [Testovani hlasky "Riziko hypoglykemie".](risk_of_hypoglycemia.md)
4. [Edge case.](edgecase.md)
5. [Real life case.](real_life_case.md)