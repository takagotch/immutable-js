### immutable-js
---
https://github.com/facebook/immutable-js

```js
// src/methods/mergeDeep.js
import { mergeDeepWithSources } from '../functional/merge';

export function mergeDeep(...iters) {
  return mergeDeepWithSources(this, iters);
}

export function mergeDeepWith(merger, ...iters) {
  return mergeDeepWithSources(this, iters, merger);
}
```

```
```

```
```

