**1.How Much is True?**

`#arrays #language_fundaments`

**Create a function which returns the number of true values there are in an array.**

**Examples**
```js
countTrue([true, false, false, true, false]) ➞ 2

countTrue([false, false, false, false]) ➞ 0

countTrue([]) ➞ 0
```

**Notes**

- Return 0 if given an empty array.
- All array items are of the type bool (true or false).

**Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/GLbuMfTtDWwDv2F73)
-----
**2.A Redundant Function**

`#clousers #functinonlal_programing #language_fundaments`

**Write a function redundant that takes in a string str and returns a function that returns str.**

**Examples**
```js
const f1 = redundant("apple")
f1() ➞ "apple"

const f2 = redundant("pear")
f2() ➞ "pear"

const f3 = redundant("")
f3() ➞ ""
```

**Notes**

- Your function should return a function, not a string.

**Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/hzxN9bAebBPNqdQto)

----

**3.RegEx Exercise: An empty string**

`#regax`

**If you've completed this RegEx series from I to XXII then you have been exposed to all of MDN's documentation on regular expressions special characters. You can check my Collections under Basic Reg Ex in my profile if you missed any. This next part of the series is to help solidify what you've learned. In order to save time I will be searching the web to find regular expression exercises to post here.**

**You can test for empty string like this:**

```js
"".length === 0 ➞ true
Use a regular expression to test for an empty string.

const REGEXP = /your solution/
REGEXP.test("") ➞ true
```

**Notes**
- You can find the solution in the Resources tab.
  
  **Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/bAqxpvYmDuuvz4LQz)

------

**4.Tile Teamwork Tactics**

`#conditions #language_fundaments #numbers #validation`

**In a board game, a piece may advance 1-6 tiles forward depending on the number rolled on a six-sided dice. If you advance your piece onto the same tile as another player's piece, both of you earn a bonus.**

**Can you reach your friend's tile number in the next roll? Create a function that takes your position a and your friend's position b and returns a boolean representation of whether it's possible to earn a bonus on any dice roll.**

**Examples**
```js
possibleBonus(3, 7) ➞ true

possibleBonus(1, 9) ➞ false

possibleBonus(5, 3) ➞ false
```

**Notes**

- You cannot move backward (which is why example #3 doesn't work).
- If you are already on the same tile, return false, as you would be advancing away.
- Expect only positive integer inputs.

**Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/NHfYRHg2tDtcZyykB)

-----
**5.Right Shift by Division**

**The right shift operation is similar to floor division by powers of two.**

**Sample calculation using the right shift operator ( >> ):**
```
80 >> 3 = floor(80/2^3) = floor(80/8) = 10
-24 >> 2 = floor(-24/2^2) = floor(-24/4) = -6
-5 >> 1 = floor(-5/2^1) = floor(-5/2) = -3
```
**Write a function that mimics (without the use of >>) the right shift operator and returns the result from the two given integers.**

**Examples**
```js
shiftToRight(80, 3) ➞ 10

shiftToRight(-24, 2) ➞ -6

shiftToRight(-5, 1) ➞ -3

shiftToRight(4666, 6) ➞ 72

shiftToRight(3777, 6) ➞ 59

shiftToRight(-512, 10) ➞ -1
```
**Notes**

- There will be no negative values for the second parameter y.
- This challenge is more like recreating of the right shift operation, thus,  - The use of the operator directly is prohibited.
- Alternatively, you can solve this challenge via recursion.
- A recursive version of this challenge can be found via this link.


**Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/ALGbgMWLuEdrh22fB)

----------

**6.Perimeters with a Catch**

`#condition #geometry  #logic #math #numbers`

**Write a function that takes a number and returns the perimeter of either a circle or a square. The input will be in the form (letter l, number num) where the letter will be either "s" for square, or "c" for circle, and the number will be the side of the square or the radius of the circle.**

**Use the following formulas:**
```
Perimeter of a square: 4 * side.
Perimeter of a circle: 6.28 * radius.
The catch is you can only use arithmetic or comparison operators, which means:
```

- No if... else statements.
- No objects.
- No arrays.
- No formatting methods, etc.
- The goal is to write a short, branch-free piece of code.

**Examples**

```js
perimeter("s", 7) ➞ 28

perimeter("c", 4) ➞ 25.12

perimeter("c", 9) ➞ 56.52
```

**Notes**

- No rounding is needed.


**Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/WEvqZTFcHeYzFn74c)

--------

**7.Find Number of Digits in Number**

`#matematika #chisla #regex`

**Create a function that will return an integer number corresponding to the amount of digits in the given integer num.**

**Examples**
```js
num_of_digits(1000) ➞ 4

num_of_digits(12) ➞ 2

num_of_digits(1305981031) ➞ 10

num_of_digits(0) ➞ 1
```

**Notes**

- Try to solve this challenge without using strings!

**Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/yFJzLfYghz7ZtsyAN)

-----
**8.Burglary Series (04): Add its Name**

`#language_fundaments #objects`

**Given three arguments ⁠— an object obj of the stolen items, the pets name and a value ⁠— return an object with that name and value in it (as key-value pairs).**

**Examples**
```js
addName({}, "Brutus", 300) ➞ { Brutus: 300 }

addName({ piano: 500 }, "Brutus", 400) ➞ { piano: 500, Brutus: 400 }

addName({ piano: 500, stereo: 300 }, "Caligula", 440) ➞ { piano: 500, stereo: 300, Caligula: 440 }
```

**Notes**

- The value argument will be a number.

**Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/9KEKJG5PZTFmG3Zau)

---------------

**9.Derivative of a Function**

`#math #numbers`

**Create a function that takes numbers b and m as arguments and returns the derivative of the function f(x)=x^b with respect to x evaluated at x=m, where b and m are constants.**

***Examples**
```js
derivative(1, 4) ➞ 1

derivative(3, -2) ➞ 12

derivative(4, -3) ➞ -108
```
**Notes**

- ^ in the context of this challenge means "to the power of", also known as the "exponent" operator.

**Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/Bxp6uGjgmf8TuG8Fe)
---------------
**10юWhich Generation Are You?**

`#conditions #logic #objects #string`

**Try finding your ancestors and offspring with code.**

**Create a function that takes a number x and a character y ("m" for male, "f" for female), and returns the name of an ancestor (m/f) or descendant (m/f).**

- If the number is negative, return the related ancestor.
- If positive, return the related descendant.
- You are generation 0. In the case of 0 (male or female), return "me!".

**Examples**
```js
generation(2, "f") ➞ "granddaughter"

generation(-3, "m") ➞ "great grandfather"

generation(1, "f") ➞ "daughter"
```
**Notes**

**Check the Resources tab for helpful hints.**

<table>
  <tr>
    <th>Generation</th>
    <th>Male</th>
    <th>Female</th>
  </tr>
  <tr>
    <td>-3</td>
    <td>great grandfather</td>
    <td>great grandmother</td>
  </tr>
  <tr>
    <td>-2</td>
    <td>grandfather</td>
    <td>	grandmother</td>
  </tr>
  <tr>
    <td>-1</td>
    <td>father</td>
    <td>mother</td>
  </tr>
  <tr>
    <td>0</td>
    <td>me!</td>
    <td>me!</td>
  </tr>
  <tr>
    <td>1</td>
    <td>son</td>
    <td>daugther</td>
  </tr>
    <tr>
    <td>2</td>
    <td>grandson</td>
    <td>granddaugther</td>
  </tr>
  <tr>
    <td>3</td>
    <td>great grandson</td>
    <td>great granddaugther</td>
  </tr>
</table>

**Resources**
- [something](https://link.com)
- [source link](https://edabit.com/challenge/48EJWLhF224na8po3)