# Chocolatey

## Installing Chocolatey

Install with cmd.exe

```text
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

Install with PowerShell

```text
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

Source: [https://chocolatey.org/docs/installation](https://chocolatey.org/docs/installation)

## Install / Upgrade Packages

Note: Remember to run as administrator

**To install:**

```text
choco install [package name]
```

```text
cinst [package name]
```

**List outdated packages:**

```text
choco outdated
```

**Upgrade all outdated packages that aren't pinned:**

```text
choco upgrade all
```

```text
cup all
```

**Options:**

* Install/upgrade in a specific directory: `--params="'/installLocation:""C:\tools""'"`

Install source: [https://chocolatey.org/docs/commandsinstall](https://chocolatey.org/docs/commandsinstall)  
Upgrade source: [https://chocolatey.org/docs/commandsupgrade](https://chocolatey.org/docs/commandsupgrade)

## Pin

### Usage

```text
choco pin [list]|add|remove [<options/switches>]
```

### Examples

```text
choco pin   
choco pin list  
choco pin add -n=git
choco pin add -n=git --version 1.2.3
choco pin remove --name git
```

Source: [https://chocolatey.org/docs/commandspin](https://chocolatey.org/docs/commandspin)

## List

### Usage

```text
  choco search <filter> [<options/switches>]
```

```text
  choco list <filter> [<options/switches>]
```

```text
  clist <filter> [<options/switches>]
```

### Options

* Only local: `-l`, `--lo`, `--localonly`, `--local-only`
* Exact name: `-e`, `--exact`

Source: [https://chocolatey.org/docs/commandslist](https://chocolatey.org/docs/commandslist)



