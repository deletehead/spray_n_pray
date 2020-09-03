# Spray 'n Pray
Offensive password spraying toolkit for internal penetration tests

Features:
* None atm :)

Desired Features:
* Password spray toolkit that can log in to a single target, or distribute the attack across a list of targets, for the following protocols:
  - SMB
  - LDAP
  - Kerberos
  - RDP?
  - MSSQL
  - ...
* Spray according to a lockout policy. Intelligently cease firing when reaching a lockout threshold, and sense when the spraying activities may have triggered a mass lockout (although hopefully the tool should prevent this!).
