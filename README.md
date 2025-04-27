# Privilege Escalation on Windows 7 using BypassUAC after Initial Compromise

## Objective
Gain SYSTEM level access on a Windows 7 machine after initial compromise using msfadmin user and BypassUAC exploit technique.

## Tools Used
- Kali Linux
- Windows 7
- Metasploit Framework

## Steps
1. Initial Access: Obtained low privilege shell via msfadmin.
2. Verified privileges (`getuid`).
3. Ran BypassUAC exploit to elevate privileges.
4. Verified SYSTEM level access.

## Observations
- UAC blocked direct SYSTEM escalation.
- BypassUAC successfully elevated privileges to SYSTEM.
- Privilege escalation enabled full control over the machine.

## Learning
Understanding UAC and privilege escalation is crucial in post-exploitation stages and mimics real-world attack techniques.
