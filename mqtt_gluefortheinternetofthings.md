#MQTT - Glue for the internet of things
(Jens Deters)[https;//www.twitter.com/jerady]

## Basis und Konzepte

(MQTT)[http://mqtt.org]: MQ Telemetrie Transport
- kein echtes Message Queue Protokoll
- kommt von IBM 
- Observer Pattern

### Broker/Topic
- Broker in der Mitte
- Topics sind Strings zur Gruppierung von Nachrichten
- Man subscribed auf ein topic. Diese topics muessen vorher nicht bekannt sein. Ab diesem Moment bekommt man alle Messages unter diesem topic.
- Topics koennen ueber eine seperator (/) aufgeteilt/gruppiert werden.
- + und # koennen nicht verwendet werden. Diese sind als wildcards blockiert. 
- Bridging Support: Kommunikation kann zwischen Brokern geforwarded werden.
### Wildcards
#### +
- Single level wildcard.
- Auf der Ebene, auf der das eingefuegt wird, werden alle subscriber addressiert. 

#### #
- Multi level
- Ab der Ebene, auf der das eingefuegt wird, geht's an alle.
### QoS
- 0/1/2 : at most one/at least once/exactly once
- je hoeher das qos-level desto mehr bandbreite
- broker kuemmert sich um das qos-management
- Es gibt keine Sicherheit, dass alle Subscriber die Nachricht bekommen
- 

### Security
- TCP mit TSL/SSL
- Basic-Auth
- Payload encryption

### Last Will and Testament
Notifications um clients die verbindung verlieren zu erfassen.

### $SYS
Spezial-Topics fuer interne statistiken.


## MQTT.fx
Desktop Anwendung fuer macOS/Linux/Windows.
- publish
- subscribe
- scripting support
- broker status
- log

## Weitere Clients
- Auch JavaFX
- Gluon: JavaFX kompiliert fuer Desktop/Android/iOS

## Data Visualization
- Raspberry Pi 3
- Elastic Search und Kibana
- Alternativ: Grafana und InfluxDB

## Misc
(Commodore plus 4)[https://en.wikipedia.org/wiki/Commodore_Plus/4]
(ESP8266)[https://www.sparkfun.com/products/13678]: Arduino-kompatibel mit Wifi Stacki
(Mosquitto)[https://mosquitto.org/]: Open Source MQTT Broker

jensd.de
