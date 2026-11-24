Day 03 – Disable SSH Root Login

Objective

Disable direct SSH root login on all application servers in the Stratos Datacenter.

Servers

- stapp01
- stapp02
- stapp03

Configuration

File: "/etc/ssh/sshd_config"

Updated setting:

PermitRootLogin no

Steps Performed

1. Connected to each application server using SSH.
2. Opened the SSH configuration file.
3. Changed "PermitRootLogin" to "no".
4. Validated the configuration.
5. Restarted the SSH service.
6. Verified the effective SSH setting.

Commands Used

sudo vi /etc/ssh/sshd_config
sudo sshd -t
sudo systemctl restart sshd
sudo sshd -T | grep permitrootlogin

Troubleshooting

- Identified an active "PermitRootLogin yes" setting.
- Corrected the active configuration.
- Learned that commented settings do not apply.
- Used "sshd -T" to verify the effective configuration.

What I Learned

- SSH server configuration.
- Root login security.
- Linux service management.
- Configuration validation and troubleshooting.
