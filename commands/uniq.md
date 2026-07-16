# uniq

## Purpose

`uniq` removes or displays duplicate consecutive lines in a sorted file.

## Example

```bash
sort names.txt | uniq
```

Shows only unique lines.

## Common Options

| Option  |       Description         |
|---------|---------------------------|
|   `-c`  | Count occurrences         |
|   `-d`  | Show only duplicate lines |
|   `-u`  | Show only unique lines    |

## Use Cases

- Remove duplicates
- Count repeated values