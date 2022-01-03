---
title: Valinor
categories: ['php']
---
## [Valinor](https://github.com/CuyZ/Valinor)

### PHP library that helps to map any input into a strongly-typed value object structure.


There are many benefits of using value objects instead of plain arrays and
scalar values in a modern codebase, among which:

1. **Data and behaviour encapsulation** — locks an object's behaviour inside its
   class, preventing it from being scattered across the codebase.
2. **Data validation** — guarantees the valid state of an object.
3. **Immutability** — ensures the state of an object cannot be changed during
   runtime.

When mapping any source to an object structure, this library will ensure that
all input values are properly converted to match the types of the nodes — class
properties or method parameters. Any value that cannot be converted to the
correct type will trigger an error and prevent the mapping from completing.

These checks guarantee that if the mapping succeeds, the object structure is
perfectly valid, hence there is no need for further validation nor type
conversion: the objects are ready to be used.
