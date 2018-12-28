## Use
`s.check_valid_email(email)`

## Description
Returns `TRUE` if the given email is a valid email address, `FALSE` otherwise.

## Example
```
v.foo = s.check_valid_email("notarealemail@codesimplescript.com")
s.echo(v.foo)
```
Returns `TRUE` because it is a valid email address despite the account not existing.