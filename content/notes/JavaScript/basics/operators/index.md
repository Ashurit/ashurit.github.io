---
weight: 20
menu:
  notes:
    name: Operators
    identifier: notes-js-basics-operators
    parent: notes-js-basics
    weight: 20
---

<!-- Array destructuring -->

{{< note >}}

### Array destructuring

You can extract array values by destructuring it:

```js
const [, a, b, c] = [1, 2, 3];

expect(a).toEqual(2);
expect(b).toEqual(3);
expect(c).toEqual(undefined);
```

{{< /note >}}

<!-- Default parameter value -->

{{< note >}}

### Default parameter value

It's possible to use a default value for a function parameter, in case no any (or not enough) are passed.

```js
const getName = function (name = "Scott") {
  return name;
};

const firstGuyName = getName("John");
const secondGuyName = getName();

expect(firstGuyName).toEqual("John");
expect(secondGuyName).toEqual("Scott");
```

{{< /note >}}

<!-- Spread operator -->

{{< note >}}

### Spread operator

This operator perform a copy of array/object variables. It can be used to pass array values to a function or to populate another array:

```js
const arrayA = [4, 5, 6];
const arrayB = [1, 2, 3, ...arrayA, 7, 8, 9];

expect(arrayB).toEqual([1, 2, 3, 4, 5, 6, 7, 8, 9]);
```

{{< /note >}}
