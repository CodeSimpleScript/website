If statements is how most languages handle rules. If statements allow you to check variables, or functions and decide from that what to do. You have many IF statement rules you can pick from, we will list and show them below. You can also use `if not v.var == 4` for example to do a reverse check.

## Basic checks

#### if v.var == 4
This kind of statement is a equal to statement, where it checks the value on the left side and the right side of == to see if they match.

#### if v.var >= 4
This will compare checking if `v.var` is MORE or EQUAL to 4.

#### if v.var <= 4
This will compare checking if `v.var` is LESS or EQUAL to 4.

#### if v.var > 4
With this you can check if a value is MORE then 4, but will NOT match if EQUAL to 4.

#### if v.var < 4
With this you can check if a value is LESS then 4, but will NOT match if EQUAL to 4.

#### if v.var true
This will compare checking if `v.var` is set to a value of TRUE and will also match if text set "true" not just function returns.

#### if v.var false
This will compare checking if `v.var` is set to a value of FALSE and will also match if text set "false" not just function returns.

## Reverse check
When you run a check it is a IF true call, not great for matching things like `if v.var == "hello"`. To run code if this is NOT true you can use the NOT rule. For this you would use it just after all IF calls for example `if not v.var == "hello"`.

## Special rules
Special rules allow you to check things like if a variable is real, or if a variable is actually an array. Here are all the special rules you can use.

#### if array v.var
Will run if the variable is an array storing more then one piece of data at a time.

#### if notarray v.var
Will run if the variable is NOT an array.

#### if set v.var
Will run if the variable has any information stored.

#### if notset v.var
Will run if the variable has NO information stored.
