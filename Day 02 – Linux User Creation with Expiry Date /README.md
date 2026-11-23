# Day 02 – Linux User Creation with Expiry Date 👤

**Environment:** App Server 3  
**Tool:** Linux Terminal

## Implementation Steps
1. Connect to App Server 3 using SSH.
2. Create a new user using the `useradd` command.
3. Set an account expiry date using `-e`.
4. Verify the user details using `chage -l`.

## Commands Used

```bash
sudo useradd -e YYYY-MM-DD username

sudo chage -l username
```

## What I Learned
- Linux user management.
- Creating users with `useradd`.
- Setting account expiry dates.
- Verifying account expiry using `chage`.

**100 Days of DevOps | Day 02** 🚀
