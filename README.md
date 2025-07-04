# Skylife

Jednoduchá webová aplikace pro evidenci služeb záchranáře a odesílání zpráv vedení.

## Spuštění

Stačí otevřít soubor `index.html` v libovolném moderním prohlížeči. Není potřeba žádná instalace ani backend.

## Použití aplikace

### Režim služby
1. Klikněte na **Začít službu**. Pole *Datum* a *Od* se automaticky vyplní aktuálním datem a časem, objeví se pole pro zadání použitých vozidel a tlačítko **Ukončit službu**.
2. Během služby můžete průběžně vyplňovat pole *Použitá vozidla* (např. `AMB01, RZP03`).
3. Po ukončení směny stiskněte **Ukončit službu**. Pole *Do* se vyplní aktuálním časem, vypočítá se délka služby a přičte se k týdennímu součtu. V seznamu služeb se zobrazí textový výpis, který lze jedním kliknutím zkopírovat.
4. Pokud služba probíhá přes půlnoc, rozdělí se automaticky na dvě samostatné položky pro každý den zvlášť.
5. Celkový počet hodin se v pondělí automaticky začne počítat od nuly.

Veškeré zadané služby se ukládají do `localStorage`, takže po znovuotevření stránky zůstanou zobrazené stejně jako dříve odeslané zprávy.

Veškeré zadané služby se ukládají do `localStorage`, takže po znovuotevření stránky zůstanou zobrazené stejně jako dříve odeslané zprávy.

### Zpráva vedení
Ve spodní části stránky je formulář pro odeslání zprávy vedení. Po odeslání se text uloží do `localStorage` a zůstane tak dostupný i po opětovném otevření stránky.

