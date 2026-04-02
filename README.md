# ARCHIVED: This issue is fixed by https://github.com/voidzero-dev/vite-plus/pull/1232

## Description

Type definitions for `vite-plus` are broken when `--moduleResolution NodeNext` is specified.

## Steps to reproduce

1. Run `vp install`
2. Run `code .` to open the project in VSCode
3. Open `vite.config.ts` and try triggering code completion in the `defineConfig({})`

## Expected behavior

Code completion should work correctly. For example, the `test` property appears in the suggestions.

## Actual behavior

Code completion does not work, and the `test` property does not appear in the suggestions.
