---
title: Ambient
---

## Ambient

Certain nodes in TypeScript can be ambient. For example, all nodes within a declaration file are ambient.

### Testing if ambient

Use `isAmbient()`:

```ts
classDeclaration.isAmbient(); // returns: boolean
```

This will do several checks to see if it's an ambient declaration.

### `declare` keyword

Check for the `declare` keyword:

```ts
classDeclaration.hasDeclareKeyword(); // returns: boolean
```

Or get the `declare` keyword if it exists:

```ts
classDeclaration.getDeclareKeyword();
```

Or set if it has a `declare` keyword:

```ts
classDeclaration.setHasDeclareKeyword(true);
classDeclaration.setHasDeclareKeyword(false);
```
