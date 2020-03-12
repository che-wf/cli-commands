# Git

## Fetch

```powershell
git fetch
```

### **Fetch from remote:**

```powershell
git fetch [remote]
```

## **Merge with another branch:**

```powershell
git merge [branch]
```

**Options:**

- Merge with unrelated histories: `--allow-unrelated-histories`

## Remotes

### **Set remote:**

```powershell
git remote add [remote name] git@github.com:[account]/[repo].git
```

### **Verify remote:**

```powershell
git remote -v
```

## Tracking

### Ignore tracked files locally

```powershell
git update-index --assume-unchanged [<file>...]
```
