# File Permissions

## Check Permissions

```bash
ls -l
```

## Change Permissions

```bash
chmod 755 filename
```

## Change Ownership

```bash
chown user:group filename
```

## Change Group Ownership

```bash
chgrp groupname filename
```

## Permission Meaning

755 = rwxr-xr-x

- Owner = Read, Write, Execute
- Group = Read, Execute
- Others = Read, Execute
