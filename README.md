# Setup-greeting javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `name`

**Required** The name of the person to greet. Default `"Nikhil"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/setup-greeting@v1.0
with:
  name: 'Myname'
```
