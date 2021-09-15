# Security Onion Integration
## Using Sysmon to create better Windows Logging
Follow the Sysmon setup for Windows. [SysmonWalkthrough][1]
#### Meterial
[Sysmon Config & GPO Config][2]
## Use WinlogBeat to send logs to Security Onion
Follwo setup from guid [Winlogbeat Setup][3]
#### Setup for Security Onion
Since security onion uses Elastic search as the DB, it makes things simple

Use this config as a template [WinlogBeat Config][4]
#### Resources
[SO Sysmon][5]
[SO Beats][6]


[1]: https://github.com/carmichaeldylan-cdpro/APT06202001/blob/master/Courseware/C0310%20-%20Sysmon%20Optics.pdf
[2]: https://github.com/carmichaeldylan-cdpro/APT06202001/tree/master/Lab-Sysmon
[3]: https://github.com/carmichaeldylan-cdpro/APT06202001/blob/master/Courseware/C0330%20-%20Log%20Shipping%20and%20Ingestors.pdf
[4]: https://github.com/carmichaeldylan-cdpro/APT06202001/blob/master/SecurityOnion/winlogbeat.yml
[5]: https://docs.securityonion.net/en/2.3/sysmon.html
[6]: https://docs.securityonion.net/en/2.3/beats.html
