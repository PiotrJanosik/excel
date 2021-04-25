# excelCzy ktos miał z tym do czynienia i porafi to dziwne zjawisko wytłumaczyć? .
zamieściłem pliki excela do mojego wpisu.Jeden to plik excel drugi to sheet.xml pochodzący z niego po rozpakowaniu..https://github.com/PiotrJanosik/excel
Jak wiecie excel to paczka spkowanych plikow.
Rozpakujcie sobie myCellEx.xlsx  i zobaczcie wpisy w pliku sheet.xml
Kolumna o nazwie B@Z1 ma wartość : 1378.
Takie kolumny nie ma przecież !!!!!!!. Tam powinna być kolumna o nazwie : AZZ1 
Chyba wykryłem wadę programu excel.
Powinien zasygnalizować w takim przypadku bład bo nie ma adresu komorki B@Z1 a zobaczcie że wygenerowałem bedny plik sheet.xml w którym zapisany jest nie prawidłowy format adresu komorki.
Celowo to zrobiłem..
Ktoś cos wie dlaczego program excel na to pozwala ?
Na dole zamieściłęm dla ułatwienia kopię kilku komórek z pliku sheet.xml
</x:c>

-<x:c t="n" r="AZX1">

<x:v>1376</x:v>

</x:c>

-<x:c t="n" r="AZY1">

<x:v>1377</x:v>

</x:c>

-<x:c t="n" r="B@Z1">

<x:v>1378</x:v>

</x:c>

-<x:c t="n" r="BAA1">

<x:v>1379</x:v>

</x:c>

-<x:c t="n" r="BAB1">

<x:v>1380</x:v>

</x:c>

-<x:c t="n" r="BAC1">

<x:v>1381</x:v>

</x:c>

-<x:c t="n" r="BAD1">

<x:v>1382</x:v
