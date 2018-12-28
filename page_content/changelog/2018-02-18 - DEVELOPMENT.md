### Bugs fixed
* None...

### New system functions
* `s.system_maxtime(seconds)` - Sets the max amount of time the page/scripts will run before closing. Default is 20 seconds.
* `s.system_sleep_second(seconds)` - Pauses the script from running for so many seconds.
* `s.system_sleep_ms(millisecond)` - Pauses the script from running for so many milliseconds, so a value of `2000` would be 2 seconds.

### Other new features
* You can give seconds to advanced the timestamp when calling `s.timestamp()`. So running `s.timestamp(5)` will give you what the timestamp will be in 5 seconds.
