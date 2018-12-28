## Use
`s.cookie_set(name, value, time, domain)`

## Description
Sets a cookie with the given name and value.  Time specifies how long the cookie is good for and is in seconds.  Domain is optional and will default to / for the current domain if not specified.

**Note:** cv.var will not retrieve the data set by a cookie until the next page load.

## Example
`s.cookie_set("Foo", "Bar", 60, "testsite.io")`