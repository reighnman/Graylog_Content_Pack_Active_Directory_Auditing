# Active Directory Auditing

This content pack provides several useful dashboards for auditing Active Directory events:
* DNS Object Summary - DNS Creations, Deletions
* Group Object Summary - Group Creations, Modifications, Deletions, Membership Changes
* User Object Summary - Account Creations, Deletions, Modifications, Lockouts, Unlocks
* Computer Object Summary - (in progress)
* Logon Summary - Failed Authentication Attempts, Interactive Logins

## Includes

* Input (GELF udp 5414)
* Failed Logon Stream (unconfigured)
* Dashboards 

## Requirements

* A GELF supported log exporter/collector such as nxlog or Graylog Collector outputting the system logs on each Domain Controller (or any handling logon events)
* Domain Controller secuirty policy with the following enabled:
** Audit Account Logon Events
** Audit Account Managmenet
** Audit Logon Events
** Audit Object Access
** Audit Policy Change
** Audit System Events

## Screenshots

![Dashboard](http://www.ohjeah.net/wp-content/uploads/2015/09/ad_audit.png)