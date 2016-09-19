
# emptyFunction v1.0.0

Stripped from [facebook/fbjs](http://github.com/facebook/fbjs).

Compatible with both NodeJS and React Native.

```coffee
emptyFunction = require "emptyFunction"

emptyFunction()                        # undefined

emptyFunctionThatReturnsOne = emptyFunction.thatReturns 1

emptyFunctionThatReturnsOne()          # 1

emptyFunction.thatReturnsTrue()        # true

emptyFunction.thatReturnsFalse()       # false

emptyFunction.thatReturnsThis.call 1   # 1

emptyFunction.thatReturnsArg 1         # 1
```
