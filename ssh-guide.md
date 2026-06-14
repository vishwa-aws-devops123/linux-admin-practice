# SSH Guide

SSH stands for Secure Shell.

It is used to securely connect to remote Linux servers.

## Connect to a Server

```bash
ssh username@server-ip
```

## Connect Using a Key Pair

```bash
ssh -i mykey.pem ec2-user@server-ip
```

## Check SSH Service Status

```bash
systemctl status sshd
```

## Common SSH Troubleshooting

- Check network connectivity
- Verify SSH service is running
- Verify firewall rules
- Verify user permissions
