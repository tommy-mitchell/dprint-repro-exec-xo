# dprint-repro-exec-xo

`dprint-plugin-exec-` does not seem to be work with `xo`.

Running the test script (`npm run fmt`) gives the following auto-fixable error from `xo`:

```sh
test.js:2:2
✖  2:2  Expected longform method syntax for string literal keys.  object-shorthand

1 error
```
