# Hello World JavaScript Action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `name-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@v1.1
with:
  name-to-greet: 'groot'
```