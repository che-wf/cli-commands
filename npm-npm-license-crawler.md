---
description: >-
  Commands used by npm-license-crawler
  (https://www.npmjs.com/package/npm-license-crawler)
---

# npm - npm-license-crawler

### Save as CSV

```bash
npm-license-crawler --csv [file location/name]
```

Example:

```bash
npm-license-crawler --csv license.csv
```

### Options

* `--csv /path/to/save.csv` Saves to CSV
* `--start directory-path`: Starting path
* `--exclude directory-path`: directories \(and subdirectories\) that should be excluded
* `--unknown`: show only licenses that can't be determined or have been guessed.
* `--dependencies`: show only third-party licenses, i.e., only list the dependencies defined in package.json.
* `--production`: show only production dependencies
* `--development`: show only development dependencies
* `--onlyDirectDependencies`: show only direct dependencies licenses, i.e., don't list dependencies of dependencies.
* `--omitVersion`: omit version numbers in result \(e.g. "npm-license-crawler@0.1.5" becomes "npm-license-crawler"\)
* `--no-color`: \(or `--no-color`\) don't show colors in the console output
* `--relativeLicensePath`: output the relative file path for license files.
* `--json /path/to/save.json`: export data as JSON to the given file. The path will be created if it does not exist.

