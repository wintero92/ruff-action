# ruff-action

## How to use

```
jobs:
  codelint:
    runs-on: ubuntu-latest

    steps:
      - name: Check-out
        uses: actions/checkout@v3
        with:
          fetch-depth: 1

      - name: Ruff
        uses: wintero92/ruff-action@v1
```

## Inputs

See `action.yaml` for possible inputs.