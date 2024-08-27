Forked from: https://github.com/Patashu/break_infinity.js

My version of break_infinity.js
I mostly doing random changes to fit with my game's code!

- Removed `Decimal.toString()` and `Decimal.toJson()`, since it doesn't allow you to use `JSON.Stringify()` (at least i remember it being so, probably need to recheck that one. but anyway main reason i did it, Decimal object wasn't able to correctly be saved/loaded with json because of it. now it works like a charm)
- Added `doPlus`, `doMinus`, `doTimes`, `doDivide` functions, to change a Decimal object in-place, without creating a new one
