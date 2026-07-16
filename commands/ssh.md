# SSH

## Purpose

`ssh` (Secure Shell) is used to securely connect to a remote Linux machine through the command line.

## Syntax

```bash
ssh username@hostname
```

## Example

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

## Explanation

- `ssh` → Starts a secure connection.
- `bandit0` → Username.
- `bandit.labs.overthewire.org` → Remote server.
- `-p 2220` → Specifies the port number.

## Common Options

| Option  |       Description         |
|---------|---------------------------|
|   `-p`  | Specify the SSH port      |
|   `-i`  | Use a private key         |
|   `-v`  | Display debug information |

## Use Cases

- Connect to a remote server
- Manage Linux machines remotely
- Complete OverTheWire challenges
