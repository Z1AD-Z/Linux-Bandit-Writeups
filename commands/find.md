# find

## Purpose

`find` searches for files and directories based on different criteria.

## Syntax

```bash
find [path] [options]
```

## Examples

```bash
find .
```

Searches everything in the current directory.

```bash
find . -name secret.txt
```

Finds a file by name.

```bash
find . -size 1033c
```

Finds files that are exactly 1033 bytes.

## Common Options

|  Option   |    Description      |
|-----------|---------------------|
| `-name`   | Search by filename  |
| `-size`   | Search by file size |
| `-user`   | Search by owner     |
| `-group`  | Search by group     |
| `-type f` | Search only files   |

## Use Cases

- Locate files
- Search by permissions
- Search by owner