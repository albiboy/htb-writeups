# [Machine Name] — HackTheBox Writeup

| Field | Detail |
|-------|--------|
| **Machine** | [Machine Name] |
| **OS** | [Linux / Windows] |
| **Difficulty** | [Easy / Medium / Hard] |
| **Release Date** | [YYYY-MM-DD] |
| **Retired Date** | [YYYY-MM-DD] |
| **Author** | Albion Rugovaj |

---

## Summary

> One paragraph describing the machine's attack path at a high level. What was the entry point, how was privilege escalation achieved, and what made this machine interesting or educational.

---

## 1. Reconnaissance

### Network Scan

```bash
nmap -sC -sV -oN nmap/initial [TARGET IP]
```

**Open Ports:**

| Port | Service | Version |
|------|---------|---------|
| | | |

### Additional Enumeration

*(Web directory busting, SMB enumeration, etc. as applicable)*

```bash
# commands used
```

---

## 2. Enumeration

### [Service / Port]

*(Detail what was found, what was interesting, and why it matters)*

**Key Finding:** [What you found]

---

## 3. Exploitation

### [Vulnerability / Technique Name]

**Description:** Brief explanation of the vulnerability exploited.

**Steps:**

```bash
# exploitation commands
```

**Result:** Initial shell as `[user]`

---

## 4. Post-Exploitation

### Local Enumeration

```bash
# commands used for local enum
```

**Findings:**
- [interesting finding]
- [interesting finding]

### Privilege Escalation

**Vector:** [e.g., SUID binary, sudo misconfiguration, kernel exploit, etc.]

```bash
# privesc commands
```

**Result:** Shell as `root` / `Administrator`

---

## 5. Flags

| Flag | Hash |
|------|------|
| user.txt | `[hash]` |
| root.txt | `[hash]` |

---

## 6. Remediation

| Finding | Risk | Recommendation |
|---------|------|----------------|
| [Finding 1] | High / Medium / Low | [Fix] |
| [Finding 2] | High / Medium / Low | [Fix] |

---

## 7. Lessons Learned

- [What you learned or found interesting]
- [Any new technique or tool encountered]
- [What you would do differently]

---

*Writeup by [Albion Rugovaj](https://github.com/albiboy) · [HTB Profile](https://app.hackthebox.com/users/1982095)*
