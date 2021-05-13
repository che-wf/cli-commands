# npm - npm-check-updates \(ncu\)

## Check for updates locally

```sh
ncu
```

## Check for minor releases

```sh
ncu --target minor
```

## Check for specific packages

```sh
ncu '/^(react-).*$/'
```

or

```sh
ncu react
```

## Checking for minor releases of specific packages

```sh
ncu --target minor '/^(react-).*$/'
```

## Checking for all packages except specific ones

```sh
ncu \!react-*
ncu '/^(?!react-).*$/' # mac/linux
ncu "/^(?!react-).*$/" # windows
```

**Options:**

Note: See all options here (<https://www.npmjs.com/package/npm-check-updates#user-content-options>)

- globally: `-g`
- update outdated: `-u`
