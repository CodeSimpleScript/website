## Use
`s.ping(hostname, port)`

## Description
Returns the amount of time in milliseconds it takes for your site to contact the given hostname and get a response.  If it fails or takes too long, `FALSE` is returned.  Supplying a port is optional and it defaults to 80 if none is given.

**NOTE:** Keep in mind it takes hostnames and not URLs.  Having `http://www.` will fail.

## Example
```
v.foo = s.ping("codesimplescript.com")
v.bar = s.ping("sbih.co.cc", "8080")
```