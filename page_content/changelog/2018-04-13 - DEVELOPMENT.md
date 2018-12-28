### Bugs fixed
* None...

### New system functions
* `s.run_sandbox_file(file)` - Runs a file in sandbox mode.
* `s.run_sandbox_code(code)` - Runs code given in sandbox mode. To keep the code from parsing it will only accept base64 encoded input text.


### Other new features
* New sandbox system in all functions to keep access to base v.var only and so on.
* Any code run in sandbox mode will get its response in JSON encoded string that contains the response in the var `response` and the cpu time in `cputime`.
