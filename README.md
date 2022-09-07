# IntelignentnaAnaliza

Jest to projekt implementujący analizę metodą KNN na zbiorze tekstów.

## Uruchomienie projektu

Projekt wymaga następujące narzędzia:

- Visual Studio 2022
- .NET 6.0
- 7z
- PowerShell 7
- Pobranego archiwum z tekstami, oto jest [link](http://archive.ics.uci.edu/ml/datasets/Reuters-21578+Text+Categorization+Collection)

1. Pobierz [archiwum z tekstami](http://archive.ics.uci.edu/ml/datasets/Reuters-21578+Text+Categorization+Collection) (plik `reuters21578.tar.gz`).
2. Umieść go w folderze `Datasets`.
3. Uruchom `pwsh` i przedź do `Datasets`.
4. Uruchom skrypt `extract.ps1` poleceniem:

    ```PowerShell
    .\extract.ps1
    ```

5. Uruchom Visual Studio 2022 i otwórz projekt w nim.
6. Zmień ustawienie kompilacji na **Release**, wtedy program będzie działał szybciej.
7. Uruchom program.

Program również zapisuje to co widzisz w konsoli do pliku `Datasets/log-#czasuruchomienia#.txt`
