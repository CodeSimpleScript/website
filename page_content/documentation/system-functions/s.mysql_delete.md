## Use
`s.mysql_delete('query')`

## Description
Runs a command to the current open MySQL connection.  Returns `true` if the query succeeds, `fail` if it does not.

## Example
```
s.mysql_connect('cats.com','foo','bar','somecoolname')
s.mysql_delete('DELETE FROM thatOneTable WHERE table_id=74')
```