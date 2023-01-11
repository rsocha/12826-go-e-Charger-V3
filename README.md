# 12963-go-eCharger-V3
Baustein für den Gira Homeserver zur Kommunikation einer [go-e](https://go-e.com/) Wallbox. [API-v2](https://github.com/goecharger/go-eCharger-API-v2/blob/main/apikeys-en.md) basierend.

## Eingänge


| Nr. | Name | Init | Beschreibung |
|-----:|---------------| ---- | --- |
| 1 | E1 IP go-e Charger |  | IP Adresse der go-e Wallbox |
| 2 | E2 Port go-e Charger | 80 | Port der go-e Wallbox |
| 3 | E3 Intervall |   | Bei einem Wert <> 0 werden die Daten go-e Wallbox zyklisch mit dem angegebenen Intervall in Sekunden abgerufen. |
| 4 | E4 Trigger |   | Bei einem Wert <> 0 werden die Daten go-e Wallbox abgerufen. |
| 5 | E5 ff |   | Für die weiteren Parameter, s. go-eCharger API-2. Von der API-2 abweichende Einheiten sind am jew. Ein- Ausgang des Bausteins angegeben. |

