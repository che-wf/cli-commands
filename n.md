# npm - n

Note: use `sudo` on Linux or WSL

## To install

```powershell
npm i -g n
```

### To install versions of node

```powershell
n latest
```

#### Options

- `latest`
- `stable`
- `lts`
- version number

## Remove a version

```powershell
n rm 8.9.0
```

or

```powershell
n - 8.9.0
```

## Prune all packages but current

```powershell
n prune
```
