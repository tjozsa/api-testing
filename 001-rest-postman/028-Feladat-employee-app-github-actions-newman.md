# 028-Feladat-employee-app-github-actions-newman.md

## Előfeltételek
A feladat elvégzéséhez az alábbi előfeltételekkel élünk
* a Postman legújabb verizója telepítve van a gépeden
* telepítve van a gépeden a Docker Desktop és működik
* leforkoltad az emloyee app github repoját és saját gépedre kiklónoztad a repót
* az applikáció fut a saját gépeden docker segítségével és eléred a web böngésződből.
* elkészítetted az elployee collection-t és már van egy teszt kérésed benne
* az employee objektumra elkészítetted a CRUD műveleteket
* készült egy environment amiben több adatot beállíthatóvá tettél a környezetből
* készítettél egy külön collection-ben a jobdescription objektumra is egy CRUD tesztcsomagot.

## Feladatod
a videók alapján integráld CI folyamatba a newman futtatást a github actions workflow és a newman futtató segítségével.