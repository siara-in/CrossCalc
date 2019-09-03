# CrossCalc

CrossCalc is day to day Scientific Calculator that can be used on Android phones, tablets, iPhone, iPad, Mac, Windows and Linux and the browser.

It asks for no permissions and does not show any ads.

The User Interface is simple and intuitive with functions that are used in everyday life.  It also provides many advanced functions provided by modern Scientific calculators.

# Keyboard input

The mouse, keyboard and touch pad can all be used to operate the Calculator.

# Dual mode

The calculator can be used in two modes: Interactive mode and Direct expression input mode.

## Interactive mode

The interactive mode is same as any regular calculator that responds to pressing of buttons for calculations.

## Direct expression input

Alternatively, complex expressions can be composed with brackets, functions and operators, and evaluated.

# Responsive UI

The user interface automatically re-arranges the function pads according to space available on the screen, be it a mobile phone, tablet or desktop monitor.

# Functions

The functions supported by the calculator are described in the following sections:

## Basic

### Arithmetic

Basic arithmetic operators such as `+`, `-`, `×`, `÷` and `.` are available as in any regular calculator.

### Brackets

Brackets can be inserted where necessary to clarify the precedence of expression evaluation.  In the absense of brackets, expressions are evaluated according to the BODMAS rule.

### Percentage

Percentage function follows any regular calculator. It works in two modes:

1. Adding or subtracting a percentage of a number.  For example, `150+10%` gives `165` and `150-10%` gives `135` as result.
2. Converting a fraction to percent.  For example, `2÷5%` gives 40 (percent).

For all other cases, using `%` function simply divides by 100.

### Correction

The correction symbol (`◅`) removes the last entered symbol from the expression for correction.

If the expression is being directly entered, using the correction symbol removes the symbol just before the current cursor position.

### Equal symbol

The `=` symbol is used to produce the result of the expression.  On the keyboard, either `=` or `Enter` key may be used.

### Plus or minus

Using `±` symbol adds a minus at the beginning of the expression.  If there is already a minus present, it removes it.

### All cancel (ac)

The `ac` pad is used to clear any expression and reset it to `0` to start calculations afresh.  On the keyboard, `Esc` key may be pressed to clear all.

## Advanced

### Square

Pressing <em>x<sup>2</sup></em> applies `sqr()` function to the current expression, multiplying it with itself.

### Square Root

Pressing `√` applies `sqrt()` function to the current expression, to find the square root of it.

### Cube

Pressing <em>x<sup>3</sup></em> applies `cube()` function to the current expression, multiplying it with itself twice.

### Cube Root

Pressing `∛` applies `cbrt()` function to the current expression, to find the cube root of it.

### Inverse

Pressing `1/x` applies `inv()` function to the current expression, to find the reciprocal of it.

### Factorial

Pressing `x!` applies `fact()` function to the current expression, to find the factorial of it.

### Natural Logarithm

Pressing `ln` applies `loge()` function to the current expression, to find the logarithm of it using base `e`.

### Decimal logarithm

Pressing <em>log<sub>10</sub></em> applies `log10()` function to the current expression, to find the logarithm of it using base 10.

### Binary Logarithm

Pressing <em>log<sub>2</sub></em> applies `log2()` function to the current expression, to find the logarithm of it using base 2.

### Natural Exponent

Pressing <em>e<sup>x</sup></em> applies `powe()` function to the current expression, to find `e` (Euler's constant) raised to the power of it.

### Power of 10

Pressing <em>10<sup>x</sup></em> applies `pow(10, x)` function to the current expression, to find `10` raised to the power of it.

### To the power of any

Pressing <em>x<sup>y</sup></em> applies `pow(x, y)` function to the current expression, to have it multiplied with itself `y` times.

### Absolute value

Pressing `|x|` applies `abs()` function to the current expression, to remove the negativity, if present.

### Permutations

Pressing <em><sup>n</sup>P<sub>r</sub></em> applies `npr(n, r)` function to the current expression, to find the number of arrangements possible for `n` elements, taken `r` at a time.

### Combinations

Pressing <em><sup>n</sup>C<sub>r</sub></em> applies `npr(n, r)` function to the current expression, to find the number of selections possible for `n` elements, taken `r` at a time.

### Euler's constant (e)

Pressing `e` applies function `eul()`, which returns the Euler's constant.

### Random number

Pressing `rnd` applies function `rnd()`, which returns a random number less than 1.

### Modulo operation

Pressing `mod` appends the `%` (modulo) binary operator, which returns the remainder after the first number is divided by the second.

## Programmer

### Hexadecimal keypad

A keypad with keys `1` to `9` and `A` to `F` is provided to input hexadecimal numbers. Before keying in `hex` numbers, the prefix `0x` is to be used.  Press (<em>0<sub>x</sub></em>) on the function pad or the shortcut key `x` from keyboard to prefix `0x`.

### Hexadecimal Conversion

The function pad <em>▻<sub>16</sub></em> is used to convert the current expression to Hexadecimal notation.  For this the function `toHex()` is used.

### Octal Conversion

The function pad <em>▻<sub>8</sub></em> is used to convert the current expression to Octal notation.  For this the function `toOct()` is used.

### Binary Conversion

The function pad <em>▻<sub>2</sub></em> is used to convert the current expression to Binary notation.  For this the function `toBin()` is used.

### Decimal Conversion

If the current expression is in Hex, Octal or Binary notation, pressing `=` converts it to Decimal notation.

### Boolean (bitwise) operators

`and`, `or`, `not` and `xor` are the four bitwise operators supported on the function pad. Of these, `not` is a unary operator which inverts the bits against 0xFFFFFFFF and applies the function `not()`.  The others are binary operators.

### Bit Shift operators

Bit shift binary operators `<<` (left) and `>>` (right) are used to shift bits of a given expression, a given number of times.

### Radix indication

For the purpose of entry of numbers in other bases such as hexadecimal (16), octal (8) and binary (2), three prefixes are used, viz. `0x`, `0o` and `0b` respectively.

For instance, `0xAA55` represents the decimal number `43605` in decimal and the same can be entered as `0o125125` in octal and `0b1010101001010101` in binary.

This is useful for converting between the bases and also applying bitwise operators on them.

## Trigonometric functions

### Basic

The basic functions are evaluated using the functions `sin()`, `cos()`, `tan()`, `cosec()`, `sec()` and `cot()`.  The input is assumed to be in `degrees`.

### Inverse functions

The functions <em>sin<sup>-1</sup></em>, <em>cos<sup>-1</sup></em> and <em>tan<sup>-1</sup></em> are inverses of `sin()`, `cos()` and `tan()` and are represented by `asin()`, `acos()` and `atan()` respectively.

### Hyperbolic functions

The functions `sinh()`, `cosh()`, `tanh()`, `asinh()`, `acosh()` and `atanh()` represent the hyperbolic counterparts of the circular trigonometric equivalent.

### Degree to Radian conversion

The functions `▻deg` and `▻rad` convert from degrees to radians and vice versa respectively.

## Expression recall

When the result is shown, the corresponding expression that was evaluated is also shown above it.  It may be recalled for further modification and re-evaluation by tapping on it.

# Support

If you face any problems or issues, please create an issue here or write to `admin@siara.in`.

# Credits

The Application icon was designed by (Double J Design, UK)[http://www.doublejdesign.co.uk].

This software was developed by Arundale Ramanathan (arun@siara.cc).
