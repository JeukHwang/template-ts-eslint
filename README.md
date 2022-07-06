# template-ts-eslint
Template for TypeScript + ESLint

## How to use
- Caution
    - Write in `src` and compile to `dist`
- Command
    - `npm run clean` to erase compiled one
    - `npm run build` to compile new one
    - `npm run reset` to erase previous one and compile new one
- Essential config
    - Change `template-ts-eslint` to `<repo-name>`
    - Change description in `package.json`
    - Remove the content of `README.md`
- Optional config
    - Remove `dist` in `.gitignore` if you want to upload compiled one
    - Change `target`, `libs` in `dist.tsconfig.json/compilerOptions` as you want
    - Add `<lib-name>` to `dist.tsconfig.json/compilerOptions/types` after installing `@types/<lib-name>`