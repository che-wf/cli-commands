# Ubuntu

## Version

### Get version number

```powershell
lsb_release -a
```

## Packages

### **Check for outdated packages:**

```powershell
sudo apt update
```

### **Upgrade all outdated packages:**

```powershell
sudo apt upgrade
```

Options:

- Accept all without prompt: `-y`

### **Upgrade to new release:**

```powershell
sudo do-release-upgrade
```

Note: Check `/etc/update-manager/release-upgrades` for release version

Note: Make sure `update-manager-core` is installed to upgrade

### Unzip a Compressed Directory

```powershell
unzip [/path/to/file].zip -d [temp_for_zip_extract]
```
