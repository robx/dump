---
date: 2019-06-08
tags: postgrest
---

### Running tests

```
$ export POSTGREST_TEST_CONNECTION=`./test/create_test_db postgres://rob@localhost/rob postgrest_test`
$ stack test
```
