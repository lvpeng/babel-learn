How preset-env works ?
===================================

- use
 [compat-table](https://kangax.github.io/compat-table/es6/)
  - how compat-table collect all features supported in different envrioments
- is plugins collections

maintain a mapping between js features and babel plugins

es2016+ vs es next vs es7


[compat-table: issue1003](https://github.com/kangax/compat-table/issues/1003) : Decorator proposal has been changed in Stage 2, but the current test of class & property decorator is still based on the proposal in stage 1
1. what is decorator ?
  - ES next Draft(stage 2) class decorators http://kangax.github.io/compat-table/esnext
  - [javascript-decorators](https://github.com/wycats/javascript-decorators)
  - learn decorators pattern
2. this needs Babylon parser support first and this work was started by @DrewML recently

3. [babel/babylon#236](https://github.com/babel/babylon/pull/236)
