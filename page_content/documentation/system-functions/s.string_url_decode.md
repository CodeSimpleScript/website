## Use
`s.string_url_decode(string)`

## Description
Returns a regular version of a URL-safe string.

## Example
```
v.standardstring = s.string_url_decode("I+love+to+test+things+sometimes%21")
s.echo(v.standardstring)
```
Output: "I love to test things sometimes!"