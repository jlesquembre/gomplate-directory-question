I'm running it with:

```
gomplate --verbose --input-dir in --output-dir out --datasource params=params/  -- cat out/a.txt
```

But I get this error:

```
template: in/a.txt:2:29: executing "in/a.txt" at <"vars.yaml">: can't evaluate field foo in type string
```
