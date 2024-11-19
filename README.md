# pnpm monorepo issue

We have a monorepo and a module-a, the module-a dependencies `rimraf` at first.

1. `pnpm install`
2. remove `rimraf` from module-a
3. add dependency `rimraf` to workspace
4. run `pnpm run -C packages/module-a clean`

and the error shows:
