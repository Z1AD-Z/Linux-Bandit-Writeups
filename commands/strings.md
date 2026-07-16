# strings

## Purpose

`strings` extracts readable text from binary files.

## Example

```bash
strings data.bin
```

Displays all printable strings found in the binary file.

## Common Use

```bash
strings data.bin | grep password
```

Searches for the word `password` inside a binary file.

## Use Cases

- Analyze binaries
- Extract hidden text
- Reverse engineering basics