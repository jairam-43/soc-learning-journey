# Windows Registry Basics

Registry stores system configurations and startup entries.

## Suspicious Areas

- `HKCU\Software\Microsoft\Windows\CurrentVersion\Run`
- `HKLM\...\Run`
- `HKLM\System\CurrentControlSet\Services`

## Signs of Threats

- Unknown startup items
- Modified services
- New scheduled tasks created by attackers
