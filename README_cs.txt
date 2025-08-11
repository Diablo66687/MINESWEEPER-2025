# MINESWEEPER 2025

Modern� konzolov� verze hry M�nolov s �rovn�mi, statistikami a v�cejazy�nou podporou.

## Funkce
- Hraj a� 100 �rovn� s rostouc� obt�nost�
- Ukl�d�n� a na��t�n� pr�b�hu hry
- TOP 5 �eb���ek
- Statistiky (odehran� hry, v�hry, prohry, pr�m�rn� �rove�)
- V�ce jazyk� (angli�tina, n�m�ina, pol�tina, ukrajin�tina, francouz�tina, �pan�l�tina)
- Sv�tl� a tmav� motiv

## Ovl�d�n�
- W/A/S/D nebo �ipky: Pohyb kurzoru
- Enter: Odhalit pole
- F: Ozna�it minou
- H: N�pov�da
- Esc: N�vrat do menu
- U: Ulo�it hru
- L: Na��st hru

## Jak zm�nit jazyk
V hlavn�m menu zvolte 'Jazyk' a vyberte preferovan� jazyk. Aplikace si volbu zapamatuje.

## Jak spustit
1. Otev�ete �e�en� ve Visual Studiu nebo spus�te p��kazem `dotnet run`.
2. Hrajte p��mo v konzoli.

## Technick� p�ehled & Best practices

### Pou�it� technologie
- **C# 12.0**: Modern� jazykov� prvky pro p�ehledn� k�d
- **.NET 8**: Rychl�, multiplatformn� prost�ed�
- **System.Text.Json**: Efektivn� serializace nastaven�, ulo�en�ch her a statistik
- **Console API**: Interaktivn� u�ivatelsk� rozhran� a barevn� v�stup
- **LINQ**: T��d�n�, filtrov�n� a pr�ce s kolekcemi
- **File I/O**: Trval� ukl�d�n� her, nastaven�, statistik a �eb���ku

### Program�torsk� postupy
- **Odd�len� logiky**: Hern� logika (Minefield) a UI (Program) jsou odd�len�
- **Siln� typovost**: Pou�it� enum�, t��d a vlastnost� pro p�ehlednost a bezpe�nost
- **V�cejazy�n� podpora**: Slovn�kov� syst�m pro snadnou lokalizaci
- **Ukl�d�n� nastaven�**: Jazyk a motiv se ukl�daj� v JSON pro pohodl� u�ivatele
- **Jednotkov� testy**: (viz ConsoleApp3.Tests) pro logiku minov�ho pole
- **O�et�en� chyb**: Kontrola existence soubor� a validn�ch dat
- **Modern� C# prvky**: Inicializ�tory objekt�, pattern matching, interpolovan� �et�zce
- **�itelnost k�du**: Konzistentn� form�tov�n�, smyslupln� n�zvy, koment��e

### Jak p�isp�vat
- Forkn�te repozit�� na GitHubu
- Pou��vejte pull requesty pro zm�ny
- Dodr�ujte best practices pro .NET a C#
- Pi�te jednotkov� testy pro nov� funkce

## Autor & Licence
Vytvo�il DevBrain � www.devbrain.cz
MIT Licence
