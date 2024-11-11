---
title: atomic-layout
categories: ['typescript', 'react', 'atomic-design']
---
## [atomic-layout](https://github.com/kettanaito/atomic-layout)

### Build declarative, responsive layouts in React using CSS Grid.


Modern layout development is about modularity and composition. Following the best practices of [Atomic design][atomic-design], we strive toward independent UI units that gradually compose into more meaningful pieces. While the attention paid to units implementation is thorough, we often overlook how to achieve layout composition that scales. It's as if we forget that _spacing defines composition_.

When it comes to distributing the spacing things get more difficult. First of all, true contextless spacing is hard. To make things worse, all present solutions couple spacing with UI elements, inevitably making small reusable pieces **contextful** and, thus, hard to maintain.

Atomic Layout helps you to compose your elements by introducing a dedicated spacing layer called _Composition_. It encourages you to separate concerns between UI elements' visual appearance and spacing between them. With the first-class responsive support at your disposal you can build gorgeous responsive permutations of your elements without leaving the dedicated spacing layer, keeping UI elements contextless and predictable. Embrace the era of a true layout composition!
