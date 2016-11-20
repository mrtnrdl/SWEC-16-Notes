#Meteor.js

Presenter: Wok

## Allgemeines
- (Meteor Homepage)[https://www.meteor.com/]
- Full stack javascript framework
- (graphql)[http://graphql.org/learn/] als zwischenschicht wird eingezogen
- aktuell 'nur' mongodb
- db clientseitig als mini-mongo

## Ausgangslage
Was ist Meteor?


## Fragen
- Welche Features/Vorteile bietet Meteor.js, was andere Frameworks nicht bieten. 
- Datenbanken?
- Framework Features?
- Template Engine

## Ideen 
- 


## Technik
- Installer ueber curl. Shell skript
	- alle dependencies enthalten
	- mongodb, node, npm, etc
	- alles drin fuer 'blanke' rechner
- CRUD operationen im UI werden eigentlich 2x ausgefuehrt
	- Clientseitig MiniMongo
	- Serverseitig in die Mongo-Instanz
	- 'optimistic rendering'
- data on the wire
	- JSON vom server zum client
	- keine fertig gerenderten htmls
- reactive rendering
	- (blaze)[https://guide.meteor.com/blaze.html]
	- observer pattern an variablen
	- Aenderungen werden minimalinvasiv ins DOM gepackt
	-
