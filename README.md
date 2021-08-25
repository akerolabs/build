# Action

This action will handle an npm install, npm run build and push the branch with the built files

## Inputs

## `userName`

**Required** The git username to use in the commits. Default `"Barry Mittens"`.

## `userEmail`

**Required** The branch to be built.
## `target`


## Outputs
No outputs

## Example usage

```
uses: akerolabs/build@v1
with:
  target: ${GITHUB_REF#refs/heads/}
  userEmail: 'nigel@smith.com'
  userName: 'Action Hero'
```