### Bugs fixed
* If you use a function like `s.string_replace()` with a space replace like in the example `v.name=s.string_replace("-"," ",v.newname)` it was removing the space, but now will keep it if the value is ONLY a space.

### New system functions
* `s.random_string_phrase(number)` - Will generate a random dash separated phrase like `crape-myrtle-pigeon`. The number supplied will be the number of words used. It will default to 50/50 chance of 2 or 3 words.
* `s.string_first_word_uppercase(string)` - Will only make the first word have a upper case starting character, making a string like `crape myrtle pigeon` become `Crape myrtle pigeon`.

### Other new features
* None...
