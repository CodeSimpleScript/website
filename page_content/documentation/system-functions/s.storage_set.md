## Use
`s.storage_set(name, data)`

## Description
Allows the storage of data that can be called any time in any session.  It used for things such as programs/installers needing to save settings such as database connection information.

## Example
```
s.storage_set("database_server", "somesite.com")
s.storage_set("database_name", "some_database")
s.storage_set("database_username", "foo")
s.storage_set("database_password", "bar")
```