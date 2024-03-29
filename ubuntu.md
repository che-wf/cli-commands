# Ubuntu

## Version

### Get version number

```sh
lsb_release -a
```

## Packages

### **Check for outdated packages:**

```sh
sudo apt update
```

### **Upgrade all outdated packages:**

```sh
sudo apt upgrade
```

Options:

- Accept all without prompt: `-y`

### **Upgrade to new release:**

```sh
sudo do-release-upgrade
```

Note: Check `/etc/update-manager/release-upgrades` for release version

Note: Make sure `update-manager-core` is installed to upgrade

### Unzip a Compressed Directory

```sh
unzip [/path/to/file].zip -d [temp_for_zip_extract]
```

## File Utilities

### Remove duplicate lines from a file (and create a new file with the duplicates removed)

*Note: No need to use brackets*

```sh
sort [duplicatesFile.txt] | uniq > [removedDuplicatesFile.txt]
```
