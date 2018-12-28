## Use
`s.string_clean(string)`

## Description
Cleans a string of all style tags, HTML tags, javascript, and multi-line comments.

## Example
```
v.testvar = s.string_clean("<html><body><p>Hello, world!</p></body></html>")
s.echo(v.testvar)
```

Outputs: `Hello, world!`