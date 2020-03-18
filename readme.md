This is a forked esm, flatbundled version of https://github.com/schteppe/cannon.js for easier handling in module environments and tree shaking. Visit the original project for documentations and examples.

    yarn add cannon-es

```jsx
import { World } from 'cannon-es'

// ...
```

#### TO DO:

- Finish TS conversion
- Only import types where possible (don't impot unused class as value)
- Revisit math/Transform.ts types
- Revisit material/ContactMaterial.ts constructor assertions
- Remove use of defined assertion (!) where possible
- Find and refactor regex: `options:.*Options = \{\}`
- Correct & standardize JSDoc comments
- Test possible performance improvements by converting matrices to Maps (instead of Arrays)
