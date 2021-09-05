# NTT (Node TypeScript Template)

> Quickly bootstrap a modern Node TypeScript project

if you don't have pnpm installed
```
npm install pnpm -g
```

install dependencies
```
pnpm install
```

convenience scripts
```
pnpm run build
pnpm run watch:build

pnpm run start
pnpm run watch:start // (not implemented yet, tbd how it should work)

pnpm run build:start

```

### Features
- fast code compile with esbuild
- strict eslint type checking
- prettier formatting
- sym linked node modules using pnpm

### Philosiphies
- simple, no abstractions (wysiwyg)
- easy to customize
- simple output

### Todo
- watch:start (esbuild.mjs subprocess or concurrent task?)
