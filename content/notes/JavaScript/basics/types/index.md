---
weight: 10
menu:
  notes:
    name: Types
    identifier: notes-js-basics-types
    parent: notes-js-basics
    weight: 10
---

<!-- Let keyword -->

{{< note >}}

### Let keyword

Used to declare variables in a specific scope.

- `var` keyword has only global and function scoping and no block scope
- `let` keyword solve this issue, providing **block scoping** !

{{< /note >}}

<!-- const keyword -->

{{< note  >}}

### Const keyword

Allow to declare a constant variable. So, it is not possible to change it's value again. (It will trigger a syntax error).

_Note: const has "block" scoping as the let keyword._\
_Note: it's possible to have several variable using the same name if they are declared in different blocks or levels._

{{< /note >}}

<!-- Dynamic type -->

{{< note >}}

### Dynamic type

JavaScript is a dynamic language with dynamic types. Variables in JavaScript are not directly associated with any particular value type, and any variable can be assigned (and re-assigned) values of all types

```js
let foo = 42; // foo is now a number
foo = "bar"; // foo is now a string
foo = true; // foo is now a boolean
```

{{< /note >}}

<!-- String Type -->

{{< note >}}

### String

```js
let color = "Yellow";
let lastName = "Johnson";
```

{{< /note >}}

<!-- Number Type -->

{{< note >}}

### Number

```js
const number = 16;
const decimalNumber = 7.5;
```

{{< /note >}}
