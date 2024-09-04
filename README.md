run ocaml's `Int64.of_string`

```bash
$ dune exec ocaml_int64
-481418970354774919
```

run jsoo's `Int64.of_string`

```bash
$ dune build ./bin/js_int64.bc.js && node ./_build/default/bin/js_int64.bc.js
Fatal error: exception Failure("int_of_string")
```
