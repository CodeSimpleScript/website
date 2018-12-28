## Use
`s.mysql_insert('query')`

## Description
Will run a command against the current open MySQL database.  While it can be used for any query, it will only return the ID of the last affected row; otherwise, `FALSE` will be returned if it failed.

## Example
```
s.mysql_connect('cats.com','foo','bar','somecoolname')
s.mysql_insert("INSERT INTO albums (TITLE, AUTHOR, TRACKS) VALUES ('Illusions', 'Thomas Bergersen', 19);")
```
