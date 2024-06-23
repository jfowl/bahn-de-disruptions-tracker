# Tracking changes to "Aktuelle Verkehrsmeldungen" of Deutsche Bahn

Every 20 minutes, a GitHub Actions runs and fetches the current disruptions as listed on 
the ["DB Aktuelle Verkehrsmeldungen" page](https://www.bahn.de/service/fahrplaene/aktuell)
and stores them in [aktuelle-verkehrsmeldungen.json](./aktuelle-verkehrsmeldungen.json).

Any changes are committed to this repository, allowing us to view the history of DB disruptions over the time.

## Acknowledgement

Code <del>stolen</del> adapted from https://github.com/simonw/ca-fires-history. Thanks Simon :)

