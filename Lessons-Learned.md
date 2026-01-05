# Lessons Learned

## Why least privilege matters
Least privilege limits the impact of mistakes and misuse. When users and technicians only have the access they need, a single error or compromised account cannot easily affect the entire system. This reduces risk and makes troubleshooting cleaner because actions are more controlled and predictable.

## Risks of shared admin accounts
Shared admin accounts remove accountability. There is no way to reliably tell who performed an action, which breaks auditing and incident response. If credentials are leaked or abused, every system using that account is immediately at risk, and containment becomes difficult.

## How this applies to Tier 1 help desk roles
Tier 1 technicians routinely reset passwords, unlock accounts, and assist users. Using standard accounts with elevation only when required enforces discipline and mirrors real enterprise environments. It protects systems while still allowing Tier 1 staff to do their jobs efficiently.

## One thing that surprised me
Even basic actions like logging in or failing a login generate useful security events. Seeing how much visibility is available with simple auditing enabled reinforced how important proper configuration is, even on a single workstation.

