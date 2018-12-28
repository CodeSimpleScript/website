## Use
`s.mysql_select('query')`

## Description
Runs a command against the current open MySQL database.  The results are returned in an array even if only on object is present.  If it fails, `false` will be returned.

## Example
```
s.mysql_connect('cats.com','foo','bar','somecoolname')
v.results = s.mysql_select("SELECT * FROM thecooltable WHERE id=5")
```