## Description
When used on a string, it will repeat the string a set amount of times.

## Parameters

### string
String of content that will be repeated.
  - Regular strings such as "Hello, world" should be in quotes.
  - SimpleScript code is run without quotes.
  - Variables can also be included by adding them to the text.

### number
Number of times the string will be repeated.

## Changelog
* Added in version 0.2.

## Examples

### Normal
	v.string=s.string_repeat("-",5)
Will return `-----`.