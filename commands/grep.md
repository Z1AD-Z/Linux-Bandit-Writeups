# grep

## Purpose

`grep` searches for specific words or patterns inside a file.

## Syntax

```bash
grep "text" filename
```

## Example

```bash
grep password data.txt
```

Displays every line containing the word `password`.

## Common Options

| Option  |      Description           |
|---------|----------------------------|
|  `-i`   | Ignore uppercase/lowercase |
|  `-r`   | Search recursively         |
|  `-n`   | Show line numbers          |

## Use Cases

- Find keywords
- Search configuration files
- Filter command output