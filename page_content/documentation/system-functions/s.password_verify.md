## Use
`s.password_verify(string, password)`

## Description
Compares a given string to an encrypted string.  If the string is the unencrypted password, `TRUE` is returned, otherwise `false` is returned.

## Example
```
v.foo = s.password_hash("asdfasdfasdf")
v.bar = s.password_verify("asdfasdfasdf", v.foo)
s.echo(v.bar)
```