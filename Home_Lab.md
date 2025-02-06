Home Lab:
•	Hypervisor & Virtualization: Running Proxmox on a Dell OptiPlex 7050 Micro with 32GB SODIMM RAM for hosting and managing virtual machines and LXC containers.

•	Self-Hosted Services:

•	LXCs: Running Filebrowser, VS Code Server, Wallos for remote access and management.

•	VMs: Hosting Ubuntu (2FA Authentication), Windows (Audiobookshelf, IDM, HandBrake automation).

•	Media & Notifications: Plex, Homarr (dashboard), NTFY (push notifications) accessible via Cloudflare Tunnel with Zero Trust for secure remote access.

•	Automation & Security:

•	Created a Proxmox LXC template for rapid deployment.

•	Configured Crontab & Unattended Upgrades to automate system updates, modifying visudo for permissions.

•	Set up NTFY alerts for upgrade availability and SSH login notifications, displaying username, hostname, and IP of login attempts.

•	Developed scripts for IDM and HandBrake to send completion notifications via NTFY.
