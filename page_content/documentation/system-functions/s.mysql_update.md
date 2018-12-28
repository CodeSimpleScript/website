## Use
`s.mysql_update('query')`

## Description
Will run a command against the current open MySQL database.  While it can be used for any query, it will only return the ID of the last affected row.  Otherwise `false` will be returned if it fails.

## Example
```
s.mysql_connect('cats.com','foo','bar','somecoolname')
s.mysql_update("UPDATE amazingtable SET name='John', username='mew' WHERE id=42")
```