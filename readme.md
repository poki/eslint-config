# @poki/eslint-config

This config rely on the fact that it's dependencies will be flatly installed [in your project's node_module](https://github.com/eslint/eslint/issues/3458).
For ESLint to work, this needs to be the case as ESLint doesn't resolve in nested directories.
Thus if for some reason you dependencies are not flatly installed, for example if you are using a really old version of NPM, well too bad.

```sh
yarn add --dev @poki/eslint-config
```
