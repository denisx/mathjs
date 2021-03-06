<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->

# Function setCartesian

Create the cartesian product of two (multi)sets.
Multi-dimension arrays will be converted to single-dimension arrays before the operation.


## Syntax

```js
math.setCartesian(set1, set2)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`a1` | Array &#124; Matrix | A (multi)set
`a2` | Array &#124; Matrix | A (multi)set

### Returns

Type | Description
---- | -----------
Array &#124; Matrix | The cartesian product of two (multi)sets


## Examples

```js
math.setCartesian([1, 2], [3, 4]);        // returns [[1, 3], [1, 4], [2, 3], [2, 4]]
```


## See also

[setUnion](setUnion.md),
[setIntersect](setIntersect.md),
[setDifference](setDifference.md),
[setPowerset](setPowerset.md)
