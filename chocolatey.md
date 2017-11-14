# Chocolatey

Note: Remember to run as administrator

## Install / Upgrade

**To install:**

```
choco install [package name]
```

**Check updates:**

```
choco outdated
```

**Upgrade all outdated packages that aren't pinned:**

```
choco upgrade all
```

## Pin[^1]

### Usage

```
choco pin [list]|add|remove [<options/switches>]
```

### Examples

```
choco pin   
choco pin list  
choco pin add -n=git
choco pin add -n=git --version 1.2.3
choco pin remove --name git
```

[^1]: [Chocolatey Documentation - Pinning](https://github.com/chocolatey/choco/wiki/CommandsPin)

