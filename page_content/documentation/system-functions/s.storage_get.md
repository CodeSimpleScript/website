## Use
`s.storage_get(name)`

## Description
Retrives data with a given name set by `s.storage_set()`.

## Example
```
v.db_server = s.storage_get("database_server")
v.db_name = s.storage_get("database_name")
v.db_user = s.storage_get("database_username")
v.db_pass = s.storage_get("database_password")
```