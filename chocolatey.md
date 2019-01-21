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

## Install / Upgrade Packages

Note: Remember to run as administrator

**To install:**

```text
choco install [package name]
```

**Check updates:**

```text
choco outdated
```

**Upgrade all outdated packages that aren't pinned:**

```text
choco upgrade all
```

**Options:**

* Install/upgrade in a specific directory: `--params="'/installLocation:""C:\tools""'"`

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

