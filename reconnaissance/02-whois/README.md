# 02 – WHOIS Analysis

## Objective

The objective of this stage was to gather publicly available domain registration information using passive WHOIS reconnaissance.

## Methodology

WHOIS information was reviewed using Kali Linux to identify publicly available domain registration and infrastructure information.

No intrusive scanning, exploitation or interaction with internal systems was performed.

## Key Findings

The WHOIS lookup identified:

- Domain: `cranberry.co.uk`
- Registrar: FastHosts Internet Ltd
- Registration date: 17 April 2003
- Expiry date: 17 April 2027
- Last updated: 18 March 2025
- Publicly listed name server information
- No personal registrant information was identified in the retrieved results

## Security Relevance

WHOIS information can assist with passive reconnaissance by providing information about:

- Domain ownership and registration history
- Registrar information
- Domain lifecycle dates
- Publicly listed name servers
- External infrastructure

Although no direct vulnerability was identified, publicly available registration information can contribute to wider reconnaissance and social-engineering risk when combined with other OSINT sources.

## Evidence

![WHOIS Analysis](whois-analysis.png)

## Assessment

The WHOIS lookup demonstrated how publicly available domain registration information can be collected without directly interacting with the organisation's internal systems.

The findings were used as part of the wider passive reconnaissance assessment.
