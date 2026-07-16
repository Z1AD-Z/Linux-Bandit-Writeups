# Level 0 → 1

## Objective

Connect to the Bandit game server using SSH and retrieve the password for the next level.

---

## Given Credentials

The OverTheWire website provides the following information to connect:

- **Username:** `bandit0`
- **Password:** `bandit0`
- **Host:** `bandit.labs.overthewire.org`
- **Port:** `2220`

> 📷 **Screenshot:** `screenshots/given-credentials.png`

---

## Resolving the Hostname

Before connecting, I wanted to identify the IP address associated with the hostname.

I used the `nslookup` command:

```bash
nslookup bandit.labs.overthewire.org
```

The command resolved the hostname to the following IP address:

```text
51.20.162.29
```

> **Note:** Although SSH can connect directly using the hostname, I chose to use the IP address as a networking exercise to better understand how DNS resolves domain names.

---

## Connecting with SSH

Using the resolved IP address, I connected to the Bandit server with the following command:

```bash
ssh bandit0@51.20.162.29 -p 2220
```

When prompted, I entered the password:

```text
bandit0
```

After successful authentication, I was logged into the Bandit Level 0 Linux environment.

> 📷 **Screenshot:** `screenshots/firstlogin.png`

---

## Command Breakdown

### `nslookup`

Resolves a domain name (hostname) into its corresponding IP address.

```bash
nslookup bandit.labs.overthewire.org
```

### `ssh`

Establishes a secure, encrypted connection to a remote Linux server.

```bash
ssh bandit0@51.20.162.29 -p 2220
```

- `ssh` → Starts an SSH connection.
- `bandit0` → Username used to authenticate.
- `51.20.162.29` → Server IP address.
- `-p 2220` → Specifies the SSH port.

---

## What I Learned

- How to connect to a remote Linux server using SSH.
- The difference between a hostname and an IP address.
- How DNS resolves a hostname into an IP address.
- How to specify a custom SSH port using the `-p` option.
- The importance of SSH for secure remote administration.

---

## Key Takeaway

SSH is one of the most important tools in Linux and cybersecurity. It enables administrators and security professionals to securely access and manage remote systems. Understanding both hostname resolution and SSH connectivity is a fundamental networking skill.

---

## Password

The password for the next level is intentionally omitted to respect the learning experience and the spirit of the OverTheWire Bandit challenge.