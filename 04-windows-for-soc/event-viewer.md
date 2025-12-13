# Windows Event Viewer Basics

Windows logs are essential for SOC work.

## Key Log Categories

- **System** → Services, drivers, system errors
- **Application** → App-level events
- **Security** → Authentication & authorization
- **Microsoft-Windows-Sysmon** → Detailed process logging (if enabled)

## Important Event IDs

- **4624** → Successful login
- **4625** → Failed login
- **4672** → Admin privileges assigned
- **4688** → New process creation
- **4720** → New user account created
