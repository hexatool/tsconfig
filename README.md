<h1 align="center">
  Hexatool's TypeScript configuration
</h1>

<p align="center">
   TSConfig for working with Node 20 + ESM + Strictest.
</p>

## Installation

```bash
npm install --save-dev @hexatool/tsconfig
```

**Using yarn**

```bash
yarn add @hexatool/tsconfig --dev
```

## How to use

Add it to your `tsconfig.json` file:

   ```json
   {
     "extends": "@hexatool/tsconfig"
   }
   ```

## Hexatool Code Quality Standards

Publishing this package we are committing ourselves to the following code quality standards:

- Respect **Semantic Versioning**: No breaking changes in patch or minor versions
- No surprises in transitive dependencies: Use the **bare minimum dependencies** needed to meet the purpose
- **One specific purpose** to meet without having to carry a bunch of unnecessary other utilities
- **Tests** as documentation and usage examples
- **Well documented ReadMe** showing how to install and use
- **License favoring Open Source** and collaboration
