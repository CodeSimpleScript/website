Global variables are stored outside of the current function, but can be used across functions or even between the main code and a function. It works the same way as a regular variable.

## Description
Global variables are stored in the global scope of code.  They can be accessed across functions and even between the main code and functions.

## Example
`gv.cats = 5` will create a global variable called “cats” with a value of 5.

## Outside scope limits
Becase we are accessing a outside scope, when setting or loading info using a global variable any sub set variables you are loading must also be from within the same global scope. So for example you cant use this `gv.users_loggedin[v.user_id]=true` will not save, it would need `v.user_id` in the same scope as global, so setting a global on `user_id` first will allow it to work in the following case.
```
gv.justforthis_user_id=v.user_id
gv.users_loggedin[gv.justforthis_user_id]=true
```
