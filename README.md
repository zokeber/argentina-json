# Argentina-JSON

## Localities in the Argentina provinces in format JSON for MongoDB and RethinkDB.

### MongoDB:

To importing into MongoDB, use:

```bash
mongoimport --jsonArray --db database --collection collection --type json --file argentina.json
```

### RethinkDB:

To importing into RethinkDB, use:

```bash
rethinkdb import -f argentina.json --table argentina.provinces
```

### Reference:

1. Wikipedia: [Provincias de Argentina](http://es.wikipedia.org/wiki/Provincias_de_Argentina)
2. Wikipedia: [Divisiones territoriales de segundo orden de la Argentina](http://es.wikipedia.org/wiki/Anexo:Divisiones_territoriales_de_segundo_orden_de_la_Argentina)
3. Wikipedia: [List of cities in Argentina](http://en.wikipedia.org/wiki/List_of_cities_in_Argentina)

### Revisions:
* 04 April 2015

### License:

[MIT](http://rem.mit-license.org)