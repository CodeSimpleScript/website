## Description
A “session variable” is a variable type that is stored in a scope outside all others.  This is used for storing and getting data even when users switch pages.  A session variable will store all information given it until the session expires; the user leaving for a long time or closing the browser for example.  Usage is similar to a regular variable, but it can be called inside and outside of functions without using the global variable type.

**IMPORTANT**: Information stored in this type of variable will remain in memory on every page visit even when it is not used.  So this type is NOT recommended for storage of large data.

## Example
`sv.cats = 5` will create a session variable with a value of 5.