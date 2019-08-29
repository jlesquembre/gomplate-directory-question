I'm running it with:

```
gomplate --verbose --input-dir in --output-dir out --datasource params  -- cat out/a.txt
```

The output is this:

```
server_name  foo: "bar"
 ;
```

looks like is inserting the complete `vars.yaml` file

I'd expect this output:

```
server_name  bar ;
```
