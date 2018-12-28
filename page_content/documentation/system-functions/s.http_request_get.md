## Use
`s.http_request_get(url)`

## Description
Sends a web request for the content of the given url with the useragent: `CodeSimpleScript SSC Script HTTP_REQUEST`.

## Example

```
//Fetch page content and echo the results
v.content=s.http_request_get("https://www.codesimplescript.com")
s.echo(v.content)
```
