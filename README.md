# CI-Tests
Example for the usage of 
 [x] appveyor
 [ ] GithubActions


## Vorgehensweise Appveyor
* appveyor.yml erstellt
* image fuer *Visual Studio 2017*
* eigenes Build Skript erstellt

## TODO

- [x] installation - *cmake --build . --target INSTALL*
- [x] Installationspaket zur Verfügung stellen - Heureka
- [x] test erstellen
- [x] test auf basis von gtest
- [x] conan muss vor dem bauen der Tests im appveyor über conan installiert werden
    - [x] conan muss zuvor installiert werden (über *pip*)
    - [x] conan muss gtest herunterladen
- [x] Linux und Windows bauen

### Status
Branch|status
----|----
master | [![Build status](https://ci.appveyor.com/api/projects/status/960mgtdgpo14mdj3/branch/master?svg=true)](https://ci.appveyor.com/project/PinkySan/appveyorexample/branch/master)

### Download

Master|Link
----|----
Debug| [Download](https://ci.appveyor.com/api/projects/PinkySan/appveyorExample/artifacts/pkgHello.zip?job=Configuration%3A+Debug)
Release| [Download](https://ci.appveyor.com/api/projects/PinkySan/appveyorExample/artifacts/pkgHello.zip?job=Configuration%3A+Release)

Test for Wolfgang   
