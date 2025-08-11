# MINESWEEPER 2025

Moderní konzolová verze hry Mínolov s úrovnìmi, statistikami a vícejazyènou podporou.

## Funkce
- Hraj a 100 úrovní s rostoucí obtíností
- Ukládání a naèítání prùbìhu hry
- TOP 5 ebøíèek
- Statistiky (odehrané hry, vıhry, prohry, prùmìrná úroveò)
- Více jazykù (angliètina, nìmèina, polština, ukrajinština, francouzština, španìlština)
- Svìtlı a tmavı motiv

## Ovládání
- W/A/S/D nebo šipky: Pohyb kurzoru
- Enter: Odhalit pole
- F: Oznaèit minou
- H: Nápovìda
- Esc: Návrat do menu
- U: Uloit hru
- L: Naèíst hru

## Jak zmìnit jazyk
V hlavním menu zvolte 'Jazyk' a vyberte preferovanı jazyk. Aplikace si volbu zapamatuje.

## Jak spustit
1. Otevøete øešení ve Visual Studiu nebo spuste pøíkazem `dotnet run`.
2. Hrajte pøímo v konzoli.

## Technickı pøehled & Best practices

### Pouité technologie
- **C# 12.0**: Moderní jazykové prvky pro pøehlednı kód
- **.NET 8**: Rychlé, multiplatformní prostøedí
- **System.Text.Json**: Efektivní serializace nastavení, uloenıch her a statistik
- **Console API**: Interaktivní uivatelské rozhraní a barevnı vıstup
- **LINQ**: Tøídìní, filtrování a práce s kolekcemi
- **File I/O**: Trvalé ukládání her, nastavení, statistik a ebøíèku

### Programátorské postupy
- **Oddìlení logiky**: Herní logika (Minefield) a UI (Program) jsou oddìlené
- **Silná typovost**: Pouití enumù, tøíd a vlastností pro pøehlednost a bezpeènost
- **Vícejazyèná podpora**: Slovníkovı systém pro snadnou lokalizaci
- **Ukládání nastavení**: Jazyk a motiv se ukládají v JSON pro pohodlí uivatele
- **Jednotkové testy**: (viz ConsoleApp3.Tests) pro logiku minového pole
- **Ošetøení chyb**: Kontrola existence souborù a validních dat
- **Moderní C# prvky**: Inicializátory objektù, pattern matching, interpolované øetìzce
- **Èitelnost kódu**: Konzistentní formátování, smysluplné názvy, komentáøe

### Jak pøispívat
- Forknìte repozitáø na GitHubu
- Pouívejte pull requesty pro zmìny
- Dodrujte best practices pro .NET a C#
- Pište jednotkové testy pro nové funkce

## Autor & Licence
Vytvoøil DevBrain © www.devbrain.cz
MIT Licence
