<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->

# Function floor

Round a value towards minus infinity.
For matrices, the function is evaluated element wise.


## Syntax

```js
floor(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | number &#124; BigNumber &#124; Fraction &#124; Complex &#124; Array &#124; Matrix | Number to be rounded

### Returns

Type | Description
---- | -----------
number &#124; BigNumber &#124; Fraction &#124; Complex &#124; Array &#124; Matrix | Rounded value


## Examples

```js
floor(3.2);              // returns number 3
floor(3.8);              // returns number 3
floor(-4.2);             // returns number -5
floor(-4.7);             // returns number -5

var c = complex(3.2, -2.7);
floor(c);                // returns Complex 3 - 3i

floor([3.2, 3.8, -4.7]); // returns Array [3, 3, -5]
```


## See also

[ceil](ceil.md),
[fix](fix.md),
[round](round.md)
