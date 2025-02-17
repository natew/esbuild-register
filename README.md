# esbuild-register

## Install

```bash
npm i esbuild-register -D
# Or Yarn
yarn add esbuild-register --dev
```

## Usage

```bash
node -r esbuild-register file.ts
```

It will use `jsxFactory`, `jsxFragmentFactory` and `target` options from your `tsconfig.json`

When using Yarn, you can add an npm script:

```json
"ts": "node -r esbuild-register"
```

to shorten the command, now just run `yarn ts file.ts` instead.

## Programmatic Usage

```ts
const { register } = require('esbuild-register/dist/node')

register({
  // ...options
})
```

## License

MIT &copy; [EGOIST](https://egoist.sh)
w
