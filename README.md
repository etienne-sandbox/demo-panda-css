# Panda CSS Demo

## Install

```bash
pnpm install -D @pandacss/dev
pnpm panda init --postcss
```

-> Update `index.css`
-> Add `"prepare": "panda codegen",` to `package.json` scripts
-> Add `"styled-system"` to `tsconfig.app.json` `include` array
-> Run `pnpm prepare` to generate the initial CSS
-> Use it !

### Fonctionnalités

- `strictTokens` & `strictPropertyValues`
- React support: `jsxFramework: "react"`
- Shorthand properties (`&:hover`, `& span`)
- Nested properties
- Pseudo Props (`_hover`, `_disabled`)
- Merge de styles
- Patterns
- Recipes (Class Variance Authority)
- Hashing des classes
- Virtual Color
