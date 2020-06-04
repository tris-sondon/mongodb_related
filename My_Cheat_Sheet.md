My Cheat Sheet
=================

```bash
mongo
```

```
show dbs
```

```
use pre
```

Show selected DB

```
db
```

Show collections in DB

```
show collections
```


Show all documents in collection

```
db.not_pii_pro.find().pretty()
```

Filter document

```


```

Delete collection

```
db.<collection>.drop()
```

Ingest multiple documents from a json file

```
mongoimport --db pre --collection  not_pii_pro --file test_ingest_db.json --jsonArray
```
