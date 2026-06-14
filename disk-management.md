# Disk Management

## Check Disk Usage

```bash
df -h
```

Shows filesystem usage in human-readable format.

## Check Directory Size

```bash
du -sh *
```

Displays size of files and directories.

## Find Large Files

```bash
find / -type f -size +100M
```

Find files larger than 100 MB.

## Check Mounted Filesystems

```bash
mount
```

Displays mounted filesystems.

## Check Block Devices

```bash
lsblk
```

Lists disks and partitions.

## Common Disk Full Troubleshooting

1. Check disk usage using `df -h`
2. Identify large directories using `du -sh`
3. Review log files
4. Remove unnecessary files if approved
5. Escalate for storage expansion if required
