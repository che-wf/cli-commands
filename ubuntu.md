# Ubuntu

## Version

### Get version number

```text
lsb_release -a
```

## Packages

### **Check for outdated packages:**

```text
sudo apt update
```

### **Upgrade all outdated packages:**

```text
sudo apt upgrade
```

Options:

* Accept all without prompt: `-y`

### **Upgrade to new release:**

```text
sudo do-release-upgrade
```

Note: Check `/etc/update-manager/release-upgrades` for release version

Note: Make sure `update-manager-core` is installed to upgrade

### Unzip a Compressed Directory

```text
unzip [/path/to/file].zip -d [temp_for_zip_extract]
```

