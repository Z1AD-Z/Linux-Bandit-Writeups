# Level 0 → 1

## Objective

Retrieve the password for **Bandit Level 1** by locating and reading the file containing it.

---

## Understanding the Challenge

After successfully logging into **Bandit Level 0**, the next step is to find the password required to access **Bandit Level 1**.

> 💡 **Tip:** Create a local file to keep track of every password you discover throughout the Bandit wargame. This makes it easy to log back into previous levels whenever needed.

For example, I created a file named:

```text
theoverthewiredata.txt
```

I use this file to securely store each password as I progress through the challenges.

---

## Listing the Files

To view the contents of the current directory, I used the `ls` command.

```bash
ls
```

The output showed a file named:

```text
readme
```

---

## Reading the File

To display the contents of the `readme` file, I used the `cat` command.

```bash
cat readme
```

The command displayed the password required to access **Bandit Level 1**.

---

## Command Breakdown

### `ls`

Lists the files and directories in the current working directory.

```bash
ls
```

### `cat`

Displays the contents of a text file in the terminal.

```bash
cat readme
```

---

## Screenshots

### Listing the files and reading the password

![Level 0 - Listing files and reading the password](../screenshots/level01-ls-cat.png)

### Local password notes

![Local password notes](../screenshots/theoverthewiredata.png)

---

## What I Learned

- How to list files using the `ls` command.
- How to display the contents of a file using the `cat` command.
- The importance of keeping organized notes while working through cybersecurity labs.
- Basic Linux file navigation and file reading.

---

## Key Takeaway

Enumeration is one of the most important skills in Linux and cybersecurity. Before attempting anything complex, always inspect your environment, identify available files, and read any relevant information they contain.

---

## Password

The password for the next level is intentionally omitted to respect the learning experience and the spirit of the OverTheWire Bandit challenge.