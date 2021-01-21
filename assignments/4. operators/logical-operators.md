# Logical Operator

1. 🥇What's the output of the following, write the output next to the code as comment.

* [ ] Logical AND operation

```js
true  && true; //output
true  && false;
false && true;
false && false;
"foo" && "bar";
"bar" && "foo";
"foo" && "";
""    && "foo";
" "   && "John" && "" && false
false && "Hey" && undefined
"undefined" && false && 42
```

* [ ] Logical OR operation
```js
true  || true;
true  || false;
false || true;
false || false;
"foo" || "bar";
"bar" || "foo";
"foo" || "";
""    || "foo";
" "   || "John" || "" || false
false || "Hey" || undefined
"undefined" || false || 42
```

2. 🥈You have two variables i.e `isGuestOneVeg` and  `isGuestTwoVeg` according to the value using logical && and || opeartor do the following.

* [ ] If both are veg "Only offer up vegan dishes."
* [ ] At least one veg  "Make sure to offer up some vegan options."
* [ ] Else, "Offer up anything on the menu"
```js
let isGuestOneVeg = false;
let isGuestTwoVeg = false;
// Your code goes here
```


3. 🎖Using the variable `temperature` and logical operators do the following
* [ ] If temperature is less then 32 alert "It is freezing outside"
* [ ] If the temperature is greater then 110 alert "It is hot outside"
* [ ] else 'Go for it. It is pretty nice out'
```js
let temperature = 4;
// Your code goes here
```

4. 🎖 Output of this
```js
alert( alert(1) || 2 || alert(3) );
```