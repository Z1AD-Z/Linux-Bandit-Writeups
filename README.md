<div align="center">

<img src="https://raw.githubusercontent.com/gilbarbara/logos/main/logos/linux-tux.svg" width="90" alt="Linux Logo"/>

# Linux Bandit Writeups

**Learning Linux Through Hands-On Security Challenges**

*OverTheWire Bandit • Linux • Bash • SSH • CLI • System Administration*

<br>

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![SSH](https://img.shields.io/badge/OpenSSH-000000?style=for-the-badge&logo=openssh&logoColor=white)](https://www.openssh.com/)
[![OverTheWire](https://img.shields.io/badge/OverTheWire-Bandit-1a1a2e?style=for-the-badge)](https://overthewire.org/wargames/bandit/)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://www.markdownguide.org/)

</div>

<br>

> ⚠️ **Spoiler Warning**
> This repository contains solutions and methodologies for OverTheWire Bandit levels. If you're currently playing Bandit, attempt each level yourself before reading the corresponding writeup. **Passwords are intentionally omitted** to respect the spirit of the project and encourage genuine learning.

<br>

---

##  Table of Contents

- [About the Project](#-about-the-project)
- [Learning Objectives](#-learning-objectives)
- [What You'll Find](#-what-youll-find)
- [Learning Methodology](#-learning-methodology)
- [Topics Covered](#-topics-covered)
- [Progress](#-progress)
- [Repository Structure](#-repository-structure)
- [Command Reference](#-command-reference)
- [Skills Developed](#️-skills-developed)
- [Technologies & Tools](#️-technologies--tools)
- [Ethical Use](#-ethical-use)
- [Resources](#-resources)
- [Roadmap](#️-roadmap)
- [Acknowledgments](#-acknowledgments)
- [Author](#-author)

---

##  About the Project

This repository documents my personal journey through **[OverTheWire Bandit](https://overthewire.org/wargames/bandit/)**, a wargame built to teach the fundamentals of Linux from the command line.

I'm using this repository to:

- Improve my Linux command-line proficiency
- Document each level with clear explanations and practical examples
- Build a habit of writing structured, reproducible technical notes
- Help other beginners understand the reasoning behind each challenge — not just the commands that solve it

Every writeup here reflects genuine, in-progress learning. The focus is on **understanding the concepts**, not on collecting passwords as quickly as possible.

---

##  Learning Objectives

### Linux Fundamentals
- Command-line proficiency
- Filesystem navigation
- File manipulation
- File permissions
- Ownership

### Shell & Automation
- Bash
- Pipes
- Redirection
- Command chaining
- Text processing

### Security Foundations
- Authentication
- Permissions
- SUID
- Service interaction
- Enumeration

### Problem Solving
- Logical thinking
- Troubleshooting
- Investigation
- Experimentation

This repository represents **learning and practice** — not professional-level expertise.

---

##  What You'll Find

For each Bandit level, writeups can include:

- Challenge overview
- Objective
- Initial analysis
- Commands used
- Explanation of each command
- Reasoning behind the solution
- Linux concepts involved
- Practical examples
- Lessons learned
- Key takeaways

> **The goal is understanding, not command memorization.**

---

##  Learning Methodology

```text
Challenge
    ↓
Understand the Objective
    ↓
Inspect the Environment
    ↓
Research / Experiment
    ↓
Test Linux Commands
    ↓
Understand the Result
    ↓
Document the Solution
    ↓
Record Lessons Learned
```

The focus is on **methodology and reasoning**, not just the final command that happens to work.

---

##  Topics Covered

### Linux Fundamentals
- Linux filesystem
- Directories
- Absolute and relative paths
- Hidden files
- File manipulation
- File types
- Standard input/output

### Shell & Bash
- Bash
- Pipes
- Redirection
- Command chaining
- Environment variables
- Shell behavior
- Command substitution

### File Analysis
`file` · `find` · `grep` · `strings` · `head` · `tail` · `sort` · `uniq` · `cut` · `tr` · `wc`

### Permissions & Ownership
- Read / Write / Execute
- Users
- Groups
- Ownership
- `chmod`
- SUID
- Permission analysis

### Data & Encoding
- Base64
- Hexadecimal
- Hexdumps
- Compression
- Archives
- File formats

### Networking
- SSH
- Ports
- Services
- Localhost
- Network communication
- Netcat

---

##  Progress

| Level   | Status |
|---------|:------:|
| 0 → 1   |   ✅   |
| 1 → 2   |   ✅   |
| 2 → 3   |   ⬜   |
| 3 → 4   |   ⬜   |
| 4 → 5   |   ⬜   |
| 5 → 6   |   ⬜   |
| 6 → 7   |   ⬜   |
| 7 → 8   |   ⬜   |
| 8 → 9   |   ⬜   |
| 9 → 10  |   ⬜   |
| 11 → 12 |   ⬜   |

*Legend: ✅ Completed · ⬜ Not yet documented*

*Note: level `10 → 11` is not yet tracked in this table — it will be added once documented.*

This table is updated as writeups are added to the repository.

---

##  Repository Structure

```text
Linux-Bandit-Writeups/
│
├── README.md
├── levels/         → Bandit level writeups
├── commands/        → Useful Linux command references
├── screenshots/      → Supporting visual material
└── resources/        → Additional learning resources
```

*This reflects the intended organization of the repository and may be adjusted as content is added.*

---

##  Command Reference

| Command   | Purpose                   |
|-----------|----------------------------|
| `ls`      | List directory contents   |
| `cd`      | Navigate directories      |
| `pwd`     | Display current directory |
| `cat`     | Display file contents     |
| `file`    | Identify file type        |
| `find`    | Search for files          |
| `grep`    | Search text patterns      |
| `strings` | Extract readable strings  |
| `chmod`   | Modify permissions        |
| `ssh`     | Connect to remote systems |

---

##  Skills Developed

| Area            | Skills                                         |
|------------------|-------------------------------------------------|
| Linux            | CLI, filesystem, permissions                   |
| Bash             | Shell commands, pipelines, automation          |
| Networking       | SSH, ports, services                           |
| Security         | Enumeration, authentication, permissions       |
| Problem Solving  | Analysis, experimentation, troubleshooting     |
| Documentation    | Technical writing and reproducible methodology |

*These are skills being developed through hands-on practice, not claims of professional-level expertise.*

---

##  Technologies & Tools

<div align="left">

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.linux.org/)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![SSH](https://img.shields.io/badge/OpenSSH-000000?style=flat-square&logo=openssh&logoColor=white)](https://www.openssh.com/)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/)
[![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)](https://www.markdownguide.org/)

</div>

---

##  Ethical Use

This repository is for **educational purposes only**. All writeups document work performed within **OverTheWire Bandit**, an environment explicitly provided for authorized, legal practice.

Security techniques and reasoning documented here should only ever be applied to systems where you have explicit authorization.

---

##  Resources

- [OverTheWire — Official Site](https://overthewire.org/)
- [OverTheWire — Bandit Wargame](https://overthewire.org/wargames/bandit/)
- [GNU/Linux Documentation Project](https://tldp.org/)
- [GNU Bash Reference Manual](https://www.gnu.org/software/bash/manual/)
- [OpenSSH Documentation](https://www.openssh.com/manual.html)

---

##  Roadmap

- [x] Start documenting Bandit
- [x] Complete initial levels
- [ ] Continue progressing through Bandit
- [ ] Expand Linux command references
- [ ] Improve writeup quality
- [ ] Add useful diagrams
- [ ] Document lessons learned
- [ ] Refine repository organization

---

##  Acknowledgments

Thanks to the **OverTheWire** team for building one of the best platforms to learn Linux and cybersecurity fundamentals through hands-on, practical challenges.

---

##  Author

**Z1AD-Z**
GitHub: [github.com/Z1AD-Z](https://github.com/Z1AD-Z)

---

<div align="center">

<strong> Learn Linux. Solve Problems. Build Security Skills.</strong>

<br><br>

Built through hands-on learning with OverTheWire Bandit.

</div>