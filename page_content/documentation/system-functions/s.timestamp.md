## Use
`s.timestamp()`

## Description
Returns the current full timestamp. You can give seconds to advanced the timestamp when calling. So running `s.timestamp(5)` will give you what the timestamp will be in 5 seconds.

## Example
```
v.testvar = s.timestamp()
s.echo(v.testvar)
```
