# 03 – DNS Analysis

## Objective

The objective of this stage was to identify publicly available DNS information associated with the target domain using passive DNS reconnaissance.

## Methodology

DNS records were queried using `dig` in Kali Linux.

The following record types were examined:

- A records
- MX records
- TXT records
- NS records

No intrusive scanning, exploitation or interaction with internal systems was performed.

## Key Findings

### A Record

The A record identified a publicly resolvable IPv4 address associated with the domain.

### MX Record

The MX record indicated that email services were hosted through Microsoft Outlook/Microsoft 365 infrastructure.

### TXT Record

TXT records contained publicly visible domain verification and email-security information.

No sensitive credentials or passwords were identified.

### NS Record

The NS lookup identified publicly available authoritative name server information for the domain.

## Security Relevance

Public DNS information can assist passive reconnaissance by revealing:

- Publicly resolvable infrastructure
- Email service providers
- Authoritative name servers
- Domain verification information
- Information useful for external infrastructure mapping

Individually, these records do not represent a vulnerability. However, DNS information can contribute to broader reconnaissance when combined with other publicly available OSINT.

## Evidence

### A Record

![A Record](figure-10-a-record.png)

### MX Record

![MX Record](figure-11-mx-record.png)

### NS Record

![NS Record](figure-13-ns-record.png)

## Assessment

The DNS analysis demonstrated how publicly accessible DNS records can provide useful information about an organisation's external infrastructure without requiring intrusive interaction with its systems.
