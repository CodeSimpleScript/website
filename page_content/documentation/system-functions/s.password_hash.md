## Use
`s.password_hash(string)`

## Description
Encrypts the given string use the CRYPT_BLOWFISH algorithm.

## Example
```
v.foo = s.password_hash("asdfasdfasdf")
s.echo(v.foo)
```