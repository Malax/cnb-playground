```
$ pack create-builder cnb-playground-builder -c builder.toml
```

```
$ pack -v build cnb-playground-test --path apps/ruby-app/ --builder cnb-playground-builder
```
