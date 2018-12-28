## Use
`s.mysql_lastid()`

## Description
Returns the ID created by the previous MySQL code.  Will return the ID from the affected table in the last INSERT and UPDATE command.

## Example
```
s.mysql_connect('cats.com','foo','bar','somecoolname')
s.mysql_insert("INSERT INTO albums (TITLE, AUTHOR, TRACKS) VALUES ('Illusions', 'Thomas Bergersen', 19)")
v.previousID = s.mysql_lastid()
```