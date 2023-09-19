# dprint-repro-exec-xo

Reproduction for dprint/dprint-plugin-exec#30.

`dprint-plugin-exec` does not seem to be work with `xo`.

Running the test script (`npm run fmt`) gives the following auto-fixable error from `xo`:

```
test.js:2:2
✖  2:2  Expected longform method syntax for string literal keys.  object-shorthand

1 error
```
