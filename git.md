# Git

## Fetch:

```
git fetch
```

### **Fetch from remote:**

```
git fetch [remote]
```

## **Merge with another branch:**

```
git merge [branch]
```

**Options:**

* Merge with unrelated histories: `--allow-unrelated-histories`

## Remotes

### **Set remote:**

```
git remote add [remote name] git@github.com:[account]/[repo].git
```

### **Verify remote:**

```
git remote -v
```

## Tracking

### Ignore tracked files locally

```
git update-index --assume-unchanged [<file>...]
```