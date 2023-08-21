# Spray n' Pray
An SMB password spraying script built using basic Unix utilities, with basic evasion/stealth.

## Usage
```
[USAGE]  /opt/smb-spray.sh <USER_LIST> <SMB_SERVERS> <PASSWORD> <DOMAIN>
[USAGE]  /opt/smb-spray.sh <USER_LIST> <SMB_SERVERS> <PASSWORD> <DOMAIN> <JITTER>

[USAGE]  USER_LIST   - Line-separated file list of users (e.g., jsmith, jdoe_adm)
[USAGE]  SMB_SERVERS - Line-separated file list of SMB servers (e.g., FILESRV1.TARGET.ORG)
[USAGE]  PASSWORD    - The password to spray (e.g., P@ssw0rd!)
[USAGE]  DOMAIN      - The target domain (e.g., TARGET.ORG)
[USAGE]  JITTER      - OPTIONAL: Jitter delay in seconds (e.g., 5)
```

## To Do
- Auto-detect for NT hashes for PtH instead of cleartext
- Test connection to target system before attempting to log in (sometimes client laptops may be offline and then the check fails automatically)
