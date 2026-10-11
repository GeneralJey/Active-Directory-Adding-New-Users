# Windows Server 2022 — Active Directory Infrastructure & Identity Management Lab

**Focus:** Identity administration and supporting Windows infrastructure  
**Tools:** Windows Server 2022, Active Directory DS, PowerShell, DNS, DHCP, File Services, Remote Access / Routing, Windows 10  
**Status:** Completed; lab decommissioned  
**Lab domain:** `HQ-JobSkill.org`

## Objective

Practice Active Directory user administration and PowerShell-based account provisioning in a Windows Server lab, alongside supporting domain services and file access configuration.

## Environment

| Component | Details |
| --- | --- |
| Server | Windows Server 2022 domain controller |
| Directory | Active Directory Domain Services; `HQ-JobSkill.org` |
| Client | Windows 10 |
| Identity administration | Active Directory Users and Computers and PowerShell |
| Supporting services | DNS, DHCP, file shares, NTFS permissions, quotas, and NAT/PAT |
| Status | Original lab decommissioned |

## Implementation

- Created and managed domain user accounts through Active Directory Users and Computers.
- Practiced PowerShell-based account provisioning, maintenance, and deprovisioning.
- Configured and explored DNS and DHCP services.
- Worked with file shares, NTFS permissions, and storage quotas.
- Configured Remote Access routing and NAT/PAT features.
- Used a Windows 10 client for domain administration exercises.

The original lab is no longer running. The README describes the documented lab scope; retained original screenshots focus on the user-creation workflow.

## Evidence

### Original screenshots

Six retained screenshots from the original lab document the Active Directory user-creation workflow:

1. [Open Active Directory Users and Computers](https://imgur.com/rmDERnc.png)
2. [Navigate the domain](https://imgur.com/Lj00R2M.png)
3. [Start the New User wizard](https://imgur.com/y19kuL8.png)
4. [Enter user information](https://imgur.com/zQBzxAf.png)
5. [Configure account options](https://imgur.com/wHdoRwJ.png)
6. [Complete user provisioning](https://imgur.com/yRh8mEy.png)

### Recreated illustrations

These repository images were reconstructed after the original lab was decommissioned. They are educational illustrations, not original screenshots or independent proof of historical configuration:

- [Lab architecture](01-lab-architecture.png) — illustrative topology.
- [Active Directory users](02-active-directory-users.png) — users, groups, and organizational units.
- [PowerShell provisioning](03-powershell-provisioning.png) — conceptual account management example; visible commands should be independently tested.
- [DNS Manager](04-dns-manager.png) — DNS administration illustration.
- [DHCP Manager](05-dhcp-manager.png) — scopes and address allocation illustration.
- [NTFS permissions](06-ntfs-permissions.png) — shared-folder access illustration.
- [Windows domain join](08-windows-domain-join.png) — client domain administration illustration.

The repository notes that a separate recreated NAT/PAT illustration has not been added. The retained originals should not be interpreted as evidence for every additional service described in the project.

## Lessons Learned

- Account lifecycle work includes provisioning, maintenance, and deprovisioning.
- Group-based permissions and appropriate NTFS access controls support least privilege.
- DNS and DHCP are core services for domain-connected clients.
- Configuration changes should be tested and access should be verified.
- Evidence provenance matters: recreated visuals communicate concepts but do not prove the original lab state.

## Next Steps

- Add a sanitized, runnable PowerShell example with prerequisites and validation steps if the script can be recovered or recreated and tested.
- Add original or clearly labeled recreated evidence for the supporting DNS, DHCP, file-services, and NAT/PAT activities.
- Add a separate NAT/PAT illustration if that part of the lab remains in scope.
