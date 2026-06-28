# 🌟 Wildcards and Globbing in Linux — Complete Guide with Examples (2026)

![Linux](https://img.shields.io/badge/Linux-Guide-blue)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-green)
![Updated](https://img.shields.io/badge/Updated-2026-orange)
![Focus](https://img.shields.io/badge/Focus-Wildcards%20%26%20Globbing-important)

> Want to manage hundreds of files with a single command?  
> Learn how Linux wildcards and globbing patterns help you search, copy, move, delete, and process files efficiently without typing every filename manually.

📖 **[Full Guide (wildcards + globbing + practical examples → linuxteck.com)](https://www.linuxteck.com/wildcards-and-globbing-in-linux/?utm_source=github&utm_medium=repo&utm_campaign=wildcards-globbing)**

---

## ⚡ 1-Minute Overview

Master these four wildcard patterns:

- `*` → Match zero or more characters
- `?` → Match exactly one character
- `[abc]` → Match specific characters
- `[a-z]` → Match a range of characters

💡 Wildcards are one of the biggest productivity boosters in the Linux command line.

---

## 🖼️ Preview

> Use wildcards and globbing patterns to manage files efficiently in Linux

![Preview](https://www.linuxteck.com/wp-content/uploads/2026/06/Wildcards-and-globbing-in-Linux.png)

---

## 🧠 Why This Guide Exists

Imagine deleting 500 log files one by one.

Instead, you can simply run:

```bash
rm *.log
```

Wildcards let you:

- Manage hundreds of files
- Simplify shell scripts
- Automate repetitive tasks
- Save significant time

Every Linux administrator and developer uses globbing every day.

---

## 🔄 Common Wildcards

| Pattern | Matches |
|----------|----------|
| `*` | Zero or more characters |
| `?` | Exactly one character |
| `[abc]` | Any one listed character |
| `[a-z]` | Character range |
| `[0-9]` | Numeric range |
| `[!abc]` | Any character except listed ones |

---

## 👉 Want all wildcard patterns, advanced globbing, and real-world examples?

Read here:

https://www.linuxteck.com/wildcards-and-globbing-in-linux/?utm_source=github&utm_medium=repo

---

## 🚀 Quick Practice (Copy-Paste Ready)

### List All Text Files

```bash
ls *.txt
```

---

### Copy All Log Files

```bash
cp *.log backup/
```

---

### Delete Temporary Files

```bash
rm *.tmp
```

---

### Match One Character

```bash
ls file?.txt
```

Matches:

```text
file1.txt
fileA.txt
fileX.txt
```

---

### Match a Character Range

```bash
ls report[1-5].txt
```

---

### Match Multiple Extensions

```bash
ls *.{jpg,png,gif}
```

*(Requires Bash brace expansion support.)*

---

## 🧪 Real-World Examples

### Move All Backup Files

```bash
mv *.bak archive/
```

---

### Compress All Log Files

```bash
tar -czf logs.tar.gz *.log
```

---

### Search All Shell Scripts

```bash
grep "sudo" *.sh
```

---

### Change Permissions

```bash
chmod +x *.sh
```

---

## 🔄 Real-World Use Cases

```text
✔ Bulk File Management
✔ Log Cleanup
✔ Shell Script Automation
✔ Backup Operations
✔ Batch Renaming
✔ Source Code Management
✔ System Administration
✔ Deployment Automation
```

---

## ⚠️ Common Mistakes

| Mistake | Impact |
|----------|---------|
| Running `rm *` carelessly | Massive file deletion |
| Confusing wildcards with regex | Unexpected results |
| Forgetting quotes in scripts | Unwanted expansion |
| Assuming hidden files match `*` | Hidden files are excluded by default |

---

## 🔄 Wildcards vs Regular Expressions

| Wildcards | Regular Expressions |
|------------|--------------------|
| Used by the shell | Used by tools like `grep`, `sed`, and `awk` |
| Match filenames | Match text patterns |
| Simpler syntax | More powerful pattern matching |
| Great for file operations | Great for searching and parsing text |

💡 Wildcards operate on filenames, while regular expressions operate on text.

---

## 🎯 Who Gets the Most Value

| You Are | Benefit |
|---------|--------|
| 🟢 Beginner | Learn efficient file management |
| 🔵 Sysadmin | Automate repetitive admin tasks |
| 🔴 DevOps Engineer | Build smarter deployment scripts |
| 🟡 Developer | Manage project files quickly |
| ⚫ Linux Power User | Master advanced shell usage |

---

## 🔗 More LinuxTeck Guides You'll Want

> 📂 *Part of the **LinuxTeck Master Series** — practical Linux guides*

- 📁 https://www.linuxteck.com/linux-file-system-comparison-ext4-xfs-btrfs/
- 📂 https://www.linuxteck.com/tree-command-in-linux-with-examples/
- 📋 https://www.linuxteck.com/cp-command-in-linux/
- 🚚 https://www.linuxteck.com/mv-command-in-linux/
- 🔍 https://github.com/linuxteck?tab=repositories

---

## ✍️ About LinuxTeck

**https://www.linuxteck.com** publishes practical, hands-on Linux guides for developers, system administrators, and DevOps engineers. Whether you're learning Linux fundamentals or mastering advanced shell techniques, these guides help you become more productive at the command line.

⭐ Found this useful? Star this repo—it helps more Linux users discover LinuxTeck.  
🔁 Share it with your team—especially if they're still typing every filename manually. 😄  
👤 https://github.com/linuxteck

---

**Topics:** linux • wildcards • globbing • bash • shell-scripting • linux-commands • sysadmin • devops • terminal • file-management
