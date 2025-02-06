# TypeScript: Object is possibly 'undefined' with optional parameter

This example demonstrates a common TypeScript error: `Object is possibly 'undefined'` when dealing with optional parameters that might be `undefined`. The error arises because TypeScript's type system is strict, and it needs explicit handling of the possibility that `name` could be `undefined` before accessing its properties.