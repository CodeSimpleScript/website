## Description
The template system allows you to include a template file with tags of where the content will be placed. To see how to link the template file, look at the system function [s.template()](/documentation?page=system-functions%2Fs.template.md).

## Parameters

### place
This is the opening code that sets where the content will be placed.

### string
The content to be added to this location in the template when it's returned to the browser. To reset the value call with a empty string.

## Parameters For Template File

### {{location}}
You place a line of text with brackets `{{header}}` to say where the content will go. This will be replaced with the content from the call in your SimpleScript code. The supported characters are a-z, 0-9, dashes and underscores.

## Examples

### Basic "header" text
	t.header("Welcome")

### Reset "header"
	t.header()

## Template File Examples

### Placement for header tag as with example before
	{{header}}
