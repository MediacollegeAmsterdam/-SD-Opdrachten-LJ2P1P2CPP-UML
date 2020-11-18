# De abstracte RPG
Dit project bestaat uit 4 classes en hoeft geen echte data te bevatten of speelbaar te zijn.
-	Core.h en Core.cpp
-	Game.h en Game.cpp
-	Level.h en Level.cpp
-	Player.h en Player.cpp

**Alle variabelen zijn private** 

## Core
**De Core mag; (voorwaarden)**
-	Alleen geïnstantieerd worden met minimaal een naam en een telefoonnummer (Argumenten in de constructor).

**De Core houdt bij; (variabelen)** 
-	Welke Games op de Core zitten en de naam van de Core. De Core heeft een vast telefoonnummer, een adres en postcode.

**Aan de Core kan je; (functies)**
-	Games toevoegen en opvragen.
-	Je kan aan de Core vragen hoeveel Players er op de Core zitten.
-	Je kan de naam, het telefoonnummer, het adres en de postcode van de Core opvragen en aanpassen.

## Game
**De Game mag; (voorwaarden)**  
-	Alleen geïnstantieerd worden met minimaal een naam (Argumenten in de constructor).

**De Game houdt bij; (variabelen)**  
-	Welke Levels er mee doen aan de Game en de naam van de Level.
-	de naam van de Game

**Aan de Game kan je; (functies)**  
-	Levels opvragen, toevoegen en verwijderen.
-	De naam opvragen en aanpassen.

## Level
**De Level mag; (voorwaarden)**
-	Alleen geïnstantieerd worden met minimaal een naam (Argumenten in de constructor).

**De Level houdt bij; (variabelen)**
-	Welke Players er in de Level zitten
-	de naam van de Level

**Aan de Level kan je; (functies)**
-	Players opvragen, toevoegen en verwijderen.
-	De naam van de van de Level opvragen en aanpassen

## Player
**De Player mag; (voorwaarden)**  
-	Alleen geïnstantieerd worden met minimaal een naam (Argumenten in de constructor).

**De Player houdt bij; (variabelen)**  
-	de naam van de Player
-	de leeftijd van de Player
-	Gemiddelde score

**Aan de Player kan je; (functies)**  
-	De naam opvragen en aanpassen
-	De leeftijd van de Player opvragen en aanpassen
-	De gemiddelde score opvragen en aanpassen

