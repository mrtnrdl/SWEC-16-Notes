#Meteor.js

Presenter: Wok

## Allgemeines
- [Meteor Homepage](https://www.meteor.com/)
- Full stack javascript framework
- [graphql](http://graphql.org/learn/) als zwischenschicht wird eingezogen
- aktuell 'nur' mongodb
- db clientseitig als mini-mongo

## Ausgangslage
Was ist Meteor?
- one lanague for client and server
- full stack reactivity
- database everywhere
- data on the wire


4minitz
- [github repo](github.com/4minitz/4minitz)
- 3 Leute core team
- travis ci
- unit und end2end tests
- phantom.js bei den end2end tests als headless browser
- backlog in [waffle.io](https://waffle.io/)
- [demo server](4minitz.com)

## Fragen
- Welche Features/Vorteile bietet Meteor.js, was andere Frameworks nicht bieten. 
- Datenbanken?
- Framework Features?
- Template Engine? 

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
	- [blaze](https://guide.meteor.com/blaze.html)
	- observer pattern an variablen
	- Aenderungen werden minimalinvasiv ins DOM gepackt
- Meteor bring zusaetzlich zum Framework eine Build Umgebung mit
	- kein extra tooling fuer build/deploy noetig!
- Atmosphere: NPM-Pendant von [Meteor.js](https://atmospherejs.com)
	- install example: meteor add twbs:bootstrap
	- client/server-teile der pakete sauber getrennt
