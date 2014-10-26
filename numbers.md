Numbers
=======

The **Number** JavaScript object is a wrapper object allowing you to work with numerical values.
A Number object is created using the Number() constructor.

---

#### Numbers
```javascript
1
1.2
0.2
-1
```

## Methods

#### Number.prototype.valueOf()

```javascript
/**
 * Returns the primitive value of a number object
 *
 * @return number
 */
Number.prototype.valueOf()

// Exemple
var number = new Number(2);

number.valueOf(); // 2
```

#### Number.isNaN(testValue) - Part of ES6 use global isNaN(testValue) or typeof testValue

```javascript
/**
 * Determine whether the passed value is NaN.
 *
 * @param testValue - value to test if its NaN
 *
 * @return boolean
 */
Number.isNaN(testValue);

// Exemple
Number.isNaN(NaN);    // true
Number.isNaN("a" - 2) // true
Number.isNaN(2);      // false
Number.isNaN("2");    // false
```

#### Number.prototype.toFixed(digits)
```javascript
/**
 * Formats a number using fixed-point notation.
 *
 * @param digits - Number of digits after point
 *
 * @return string - string representing the number
 */
Number.prototype.toFixed(digits);

// Exemple
var number = 0.1234;

number.toFixed(1); // "0.1"
number.toFixed(2); // "0.12"
number.toFixed(3); // "0.123"
```
