# Day 01 – Create User with Non-Interactive Shell

## Task
Created a user named `james` with a non-interactive shell on App Server 3.

## Commands Used

```bash
ssh banner@stapp03
```

```bash
sudo useradd -s /sbin/nologin james
```

## Verification

```bash
grep james /etc/passwd
```

## What I Learned
- Linux user creation
- Non-interactive shell
- `/sbin/nologin`
- User verification
