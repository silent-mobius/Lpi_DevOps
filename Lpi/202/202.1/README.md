# 202

## Domain Name Server

### 207.1 Basic DNS server configuration

Weight: 3
Description: Candidates should be able to configure BIND to function as a caching-only DNS server. This objective includes the ability to manage a running server and configuring logging.
Key Knowledge Areas:
    • BIND 9.x configuration files, terms and utilities
    • Defining the location of the BIND zone files in BIND configuration files
    • Reloading modified configuration and zone files
    • Awareness of dnsmasq, djbdns and PowerDNS as alternate name servers

### 207.2 Create and maintain DNS zones

Weight: 3
Description: Candidates should be able to create a zone file for a forward or reverse zone and hints for root level servers. This objective includes setting appropriate values for records, adding hosts in zones and adding zones to the DNS. A candidate should also be able to delegate zones to another DNS server.
Key Knowledge Areas:
    • BIND 9 configuration files, terms and utilities
    • Utilities to request information from the DNS server
    • Layout, content and file location of the BIND zone files
    • Various methods to add a new host in the zone files, including reverse zones

### 207.3 Securing a DNS server

Weight: 2
Description: Candidates should be able to configure a DNS server to run as a non-root user and run in a chroot jail. This objective includes secure exchange of data between DNS servers.
Key Knowledge Areas:
    • BIND 9 configuration files
    • Configuring BIND to run in a chroot jail
    • Split configuration of BIND using the forwarders statement
    • Configuring and using transaction signatures (TSIG)
    • Awareness of DNSSEC and basic tools
    • Awareness of DANE and related records