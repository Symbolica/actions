# Symbolica Actions

GitHub actions that allow you to run Symbolica on your code as part of a workflow on GitHub.

## Inputs

### `script`

**Optional** The name of the build script to run relative to the root of your repository. Default `"symbolica.sh"`.

### `tag`

**Required** The tag of the Symbolica/build image to use.

## Example usage

```yml
uses: SymbolicaDev/actions/build@master
with:
  tag: 0.1.0
```
