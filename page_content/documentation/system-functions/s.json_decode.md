## Use
`s.json_decode(jsonstring)`

## Description
Converts any given JSON string into a SimpleScript array.  Be sure to capture the array created from JSON string into a variable.

## Example
```
v.foo = s.array("animals", "cat", "dog", "duck", "fish")
v.foojson = s.json_encode(v.foo)
v.bar= s.json_decode(v.foojson)
```