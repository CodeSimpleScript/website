## Use
`s.string_url_encode(string)`

## Description
Returns a URL-safe version of the given string.

## Example
```
v.thegoodstring = s.string_url_encode("I love to test things sometimes!")
s.echo(v.thegoodstring)
```
Output: I+love+to+test+things+sometimes%21