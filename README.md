# EternityNum2
## Description
- Module that absolutely shatters Infinity
- New limit surpasses 1e1e100 (10^10^100)
- Total remake of EternityNum, no code is reused
  
## Features
- Mathematical computation
- Suffixes
- Advanced mathemtical functions
<p>More information under Usage</p>

  
## Usage
### Setup

```Lua
local ReplicatedStorage = game:GetService("ReplicatedStorage)
local xN = require(ReplicatedStorage.Modules.EternityNum) -- replace with your path
```
### Functions
```Lua
xN.add(x, y) -- adds x and y together
xN.sub(x, y) -- subtracts y from x
xN.mul(x, y) -- multiplies x and y
xN.div(x, y) -- divides x by y
xN.mod(x, y) -- calculates x modulo y
xN.recip(x) -- calculates the reciprocal of x (1 / x)
xN.pow(x, y) -- raises x to the power of y
xN.pow10(x) -- calculates 10 raised to the power of x
xN.root(x, y) -- finds the y-th root of x
xN.sqrt(x) -- calculates the square root of x
xN.cbrt(x) -- calculates the cube root of x
xN.exp(x) -- calculates e raised to the power of x
xN.log(x, base) -- calculates the logarithm of x with the given base
xN.ln(x) -- calculates the natural logarithm (base e) of x
xN.log10(x) -- calculates the base-10 logarithm of x
xN.rand(x, y) -- generates a random number between x and y
xN.randPrime(x, y) -- generates a random prime number between x and y
xN.floor(x) -- rounds x down to the nearest integer
xN.ceil(x) -- rounds x up to the nearest integer
xN.round(x, decimals) -- rounds x to the specified number of decimal places
xN.truncate(x, decimals) -- truncates x to the specified number of decimal places
xN.abs(x) -- calculates the absolute value of x
xN.neg(x) -- returns the negation of x
xN.isOdd(x) -- checks if x is an odd number
xN.isEven(x) -- checks if x is an even number
xN.hypot(x, y) -- calculates the hypotenuse of x and y (sqrt(x^2 + y^2))
xN.sum(values) -- calculates the sum of a list of numbers
xN.product(values) -- calculates the product of a list of numbers
xN.nCr(n, r) -- calculates combinations (n choose r)
xN.nPr(n, r) -- calculates permutations (n permute r)
xN.isSquare(x) -- checks if x is a perfect square
xN.mode(values) -- finds the most frequent value(s) in a dataset
xN.le(x, y) -- checks if x is less than y
xN.me(x, y) -- checks if x is more than y
xN.leeq(x, y) -- checks if x is less than or equal to y
xN.meeq(x, y) -- checks if x is more than or equal to y
xN.fact(x) -- calculates the factorial of x
xN.gamma(x) -- calculates the gamma function of x
xN.erf(x) -- calculates the error function of x
xN.beta(x, y) -- calculates the beta function for x and y
xN.digamma(x) -- calculates the digamma function of x
xN.zeta(x) -- calculates the Riemann zeta function of x
xN.gcd(x, y) -- calculates the greatest common divisor of x and y
xN.lcm(x, y) -- calculates the least common multiple of x and y
xN.factorise(x) -- performs prime factorization of x
xN.format(x) -- formats x for display with commas or scientific notation
xN.lambertW(x) -- calculates the Lambert W function of x
```
All functions will return their value in the form of `{x, y, z}`
<br>

**Stable release expected to come out July 2025**
