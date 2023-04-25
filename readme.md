```shell

git clone https://github.com/trim21/vuex-ts-bug

cd vuex-ts-bug

yarn

npx tsc --noEmit

```


```text
main.ts:1:29 - error TS7016: Could not find a declaration file for module 'vuex'. 'C:/Users/Trim21/proj/vue-i18n-next-but/node_modules/vuex/dist/vuex.mjs' implicitly has an 'any' type.
  There are types at 'C:/Users/Trim21/proj/vue-i18n-next-but/node_modules/vuex/types/index.d.ts', but this result could not be resolved when respecting package.json "exports". The 'vuex' library may need to update its package.json or typings.

1 import { createStore } from 'vuex'
                              ~~~~~~

main.ts:11:19 - error TS7006: Parameter 'state' implicitly has an 'any' type.

11         increment(state) {
                     ~~~~~


Found 2 errors in the same file, starting at: main.ts:1
```
