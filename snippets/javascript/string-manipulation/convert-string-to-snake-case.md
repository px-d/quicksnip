---
title: Convert String to Snake Case
description: Converts a given string into snake_case.
author: axorax
tags: string,case,snake_case
---

```js
function toSnakeCase(str) {
  return str.replace(/([a-z])([A-Z])/g, '$1_$2')
            .replace(/\s+/g, '_')
            .toLowerCase();
}

// Example usage:
console.log(toSnakeCase('Hello World Test')); // Output: 'hello_world_test'
```
