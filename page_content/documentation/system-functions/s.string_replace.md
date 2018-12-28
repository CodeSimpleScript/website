## Description
Allows you to replace all instances of a string inside of a string with a new string (say that ten times fast).

## Parameters

### old
String of content to find in the string to be replaced.
  - Regular strings such as "Hello, world" should be in quotes.
  - SimpleScript code is run without quotes.
  - Variables can also be included by adding them to the text.

### new
String that will replace the first parameter when found in the content
  - Regular strings such as "Hello, world" should be in quotes.
  - SimpleScript code is run without quotes.
  - Variables can also be included by adding them to the text.

### string
String of content to check against.
  - Regular strings such as "Hello, world" should be in quotes.
  - SimpleScript code is run without quotes.
  - Variables can also be included by adding them to the text.

## Changelog
* Added in version 0.2.

## Examples

### Normal
	v.string=s.string_replace("dogs","cats","I have 2 dogs.")
Will return:  I have 2 cats.