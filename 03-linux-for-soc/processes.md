# Linux Processes for SOC

## Red Flags
- Processes running from /tmp
- Python/Node/Java processes by unknown users
- Long-running reverse shells
- Cron jobs launching unknown scripts
- Unusual process parent-child relationships

## Key Commands
- ps aux
- top / htop
- pstree
- lsof -p PID
- systemctl status
