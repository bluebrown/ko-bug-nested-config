# Nested Config Bug

```bash
$ export KO_CONFIG_PATH="$PWD/nested/.ko.yaml"
$ docker run --rm "$(ko build -L -B ./cmd/app/)"
tag is not used
```
