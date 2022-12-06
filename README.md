# Async for each

Async for each is an async loop method to allow you to loop and await for async tasks.

## Installation

``` npm install async-for-each ```

## Usages

```
import { asyncForEach } from 'async-for-each';

await asyncForEach(myArray, async (arrayItem) => {
  await doSomethingToTheItem(arrayItem);
});

```
