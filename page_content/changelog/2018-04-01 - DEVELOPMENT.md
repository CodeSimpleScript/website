### Bugs fixed
* None...

### New system functions
* None...

### Other new features
* Mysql functions now have support for multiple databases built in. Just add the connection name to the last argument to each mysql system function. For example `s.mysql_connect("cats.com","foo","bar","theplace","connection_name")` if you dont supply a connection name it gets the name `default`. You can now make statements agains this specific connection for example `s.mysql_insert("INSERT INTO albums (TITLE, AUTHOR, TRACKS) VALUES ('Illusions', 'Thomas Bergersen', 19);","connection_name")`.
