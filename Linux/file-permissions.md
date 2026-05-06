# Linux File Permissions

Linux uses permissions to control access to files and directories.

## Permission Types

- Read (`r`)
- Write (`w`)
- Execute (`x`)

---

## `chmod`

Change file permissions.

```bash
chmod 755 script.sh
```

Permission breakdown:
- Owner: read, write, execute
- Group: read, execute
- Others: read, execute

---

## `chmod +x`

Add executable permission to a file.

```bash
chmod +x script.sh
```

---

## `chown`

Change the owner of a file.

```bash
chown user:file notes.txt
```

---

## `chgrp`

Change the group ownership of a file.

```bash
chgrp developers notes.txt
```

---

## `ls -l`

Display detailed permissions information.

```bash
ls -l
```
