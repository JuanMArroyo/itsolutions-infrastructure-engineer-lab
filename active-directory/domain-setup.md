# Active Directory Domain Setup

This guide documents the deployment of the IT Solutions Active Directory domain.

## Steps

1. Install Windows Server 2022  
2. Assign static IP: 192.168.10.10  
3. Rename server: DC01  
4. Install AD DS role  
5. Promote server to Domain Controller  
6. Create domain: itsolutions.local  

## Verification

- `dcdiag` passes  
- SYSVOL and NETLOGON replicated  
- DNS resolving internal hosts  
