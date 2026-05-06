# Linux File Permissions

Linux permissions help control access to files and directories.

## Permission Types

- Read (`r`)
- Write (`w`)
- Execute (`x`)

Permissions are assigned to:
- Owner
- Group
- Others

---

## `ls -l`

Displays file permissions and ownership information.

```bash
ls -l
```

Example output:

```bash
-rwxr-xr-- 1 user group file.txt
```

---

## `chmod`

Changes file permissions.

```bash
chmod 755 script.sh
```

Permission breakdown:
- Owner: read, write, execute
- Group: read, execute
- Others: read, execute

---

## `chmod +x`

Adds executable permission to a file.

```bash
chmod +x script.sh
```

---

## `chmod -w`

Removes write permission from a file.

```bash
chmod -w notes.txt
```

---

## `chown`

Changes file ownership.

```bash
chown user:file notes.txt
```

---

## `chgrp`

Changes group ownership.

```bash
chgrp developers notes.txt
```
