## Use
`s.json_encode(array)`

## Description
Concerts an array stored in SimpleScript into a JSON string.  The content is what will be returned, so be sure to store the contents in a new variable.

## Example
```
v.foo = s.array("animals", "cat", "dog", "snake", "bunny")
v.jsonfoo = s.json_encode(v.foo)
```