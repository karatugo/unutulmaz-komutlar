Create DB
=========

```
python3
from app import db
db.create_all()
```

Start python3 console:

```
python3
```

and then:

```
import sqlalchemy as db
```

OR

```
import app as db
```

and then:

```
engine = db.create_engine('sqlite:///test.db', {})
connection = engine.connect()
metadata = db.MetaData()
census = db.Table('census', metadata, autoload=True, autoload_with=engine)
query = db.select([census])
ResultProxy = connection.execute(query)
ResultSet = ResultProxy.fetchall()
ResultSet[:3]
```

https://towardsdatascience.com/sqlalchemy-python-tutorial-79a577141a91
