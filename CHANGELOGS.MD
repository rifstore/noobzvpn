# CHANGELOGS
This page is changelogs info. remember all major protocol version is not compatible for each other (ex: x.x.1a vs x.x.1b are not compatible each other).

### Version 2.1.1b
* New Protocols 1b implementation, replace the old protocol 1a (version: x.x.1a).
* New Features:
    * New aarch64 binary architecture for ARM 64-bit CPU.
    * Detect and block Device Multi-login per-user accounts.
    * Calculate and limit the Bandwidth per-user accounts (per Giga Bytes).
    * commandline ***--json*** api.
    * new customable identifier for make it harder from ISP Packet inspection
    * Server banner info for send to client.
    * Support Auth & Ping protocols for user before they are connected.
* Fixed:
    * User Database race condition (new seamless database account management system).
    * Using single service to serve all service type (no-forking service).
    * Precisely expired day.
    * Memory optimization.
    * etc...


### Version 1.3.1a [DISCONTIUNED]
* Initial release
* Now is discontiuned because is limited to support the new features. sorry..
