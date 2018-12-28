## Description
Outputs text to the page when used.

## Parameters

### string
String of content to run.
  - Regular strings such as "Hello, world" should be in quotes.
  - SimpleScript code is run without quotes.
  - Variables can also be included by adding them to the text.  (Example shown last)

## Changelog
* Added in version 0.1.

## Examples

### Basic Text
	s.echo("I am making a echo")

### Return variable
	v.hello="Hello World"
	s.echo(v.hello)
	
### Both options
	s.echo("I can also echo direcly like this v.hello")
	