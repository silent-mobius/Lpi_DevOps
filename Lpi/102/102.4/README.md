# 102

## Essential System Services

### 108.1 Maintain system time

Weight: 3
Description: Candidates should be able to properly maintain the system time and synchronize the clock via NTP.
Key Knowledge Areas:
    • Set the system date and time.
    • Set the hardware clock to the correct time in UTC.
    • Configure the correct timezone.
    • Basic NTP configuration using ntpd and chrony.
    • Knowledge of using the pool.ntp.org service.
    • Awareness of the ntpq command.

### 108.2 System logging

Weight: 4
Description: Candidates should be able to configure rsyslog. This objective also includes configuring the logging daemon to send log output to a central log server or accept log output as a central log server. Use of the systemd journal subsystem is covered. Also, awareness of syslog and syslog-ng as alternative logging systems is included.
Key Knowledge Areas:
    • Basic configuration of rsyslog.
    • Understanding of standard facilities, priorities and actions.
    • Query the systemd journal.
    • Filter systemd journal data by criteria such as date, service or priority.
    • Configure persistent systemd journal storage and journal size.
    • Delete old systemd journal data.
    • Retrieve systemd journal data from a rescue system or file system copy.
    • Understand interaction of rsyslog with systemd-journald.
    • Configuration of logrotate.
    • Awareness of syslog and syslog-ng.

### 108.3 Mail Transfer Agent (MTA) basics

Weight: 3
Description: Candidates should be aware of the commonly available MTA programs and be able to perform basic forward and alias configuration on a client host. Other configuration files are not covered.
Key Knowledge Areas:
    • Create e-mail aliases.
Configure e-mail forwarding.
Knowledge of commonly available MTA programs (postfix, sendmail, exim) (no configuration).

### 108.4 Manage printers and printing

Weight: 2
Description: Candidates should be able to manage print queues and user print jobs using CUPS and the LPD compatibility interface.
Key Knowledge Areas:
    • Basic CUPS configuration (for local and remote printers).
    • Manage user print queues.
    • Troubleshoot general printing problems.
    • Add and remove jobs from configured printer queues.