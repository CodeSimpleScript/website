## Description
URL variables contain any information passed in the URL scope and this type of variable works just like a global variable.  They can be set by adding a “?” to the end of the URL and then giving the variable information.

## Example
`page.ssc?cats=4` will create a URL variable for that page with the name “cats”.  It can be accessed in the code with `uv.cats` and will contain a value of 4.

Multiple values can be set using the “&” symbol.
`page.ssc?cats=4&dogs=2&fish=7` will create three separate URL variables that can be accessed using `uv.cats uv.dogs uv.fish`.
