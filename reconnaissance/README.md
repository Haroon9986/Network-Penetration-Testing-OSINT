# Network Penetration Testing – Passive OSINT Assessment

A passive reconnaissance and Open-Source Intelligence (OSINT) security assessment conducted as part of my Network Penetration Testing studies.

The project demonstrates how publicly available information can be collected and analysed to understand an organisation's external digital footprint without performing intrusive scanning or exploitation.

## Project Overview

The assessment focused on six passive reconnaissance activities:

1. [Public Website OSINT](reconnaissance/01-public-website-osint/README.md)
2. [WHOIS Analysis](reconnaissance/02-whois/README.md)
3. [DNS Analysis](reconnaissance/03-dns-analysis/README.md)
4. [Certificate & Subdomain Analysis](reconnaissance/04-certificates-subdomains/README.md)
5. [Technology Stack Analysis](reconnaissance/05-technology-stack/README.md)
6. [Google Dorking](reconnaissance/06-google-dorking/README.md)

## Methodology

The assessment used publicly available information and passive reconnaissance techniques.

Tools and techniques included:

- Kali Linux
- WHOIS
- DNS analysis using `dig`
- Certificate Transparency / crt.sh
- Netcraft
- HTTP header analysis using `curl`
- Google search operators

No exploitation, vulnerability scanning or unauthorised access was performed.

## Key Findings

The assessment identified publicly observable information relating to:

- Public website and business information
- Domain registration information
- DNS records
- Certificate-associated hostnames
- Web server and protocol information
- Publicly indexed documents

No direct vulnerability was identified during the passive reconnaissance activities.

The findings demonstrate how publicly available information can contribute to external reconnaissance and potential social-engineering risk when combined.

## Security Considerations

The project highlights the importance of regularly reviewing an organisation's publicly available digital footprint.

Organisations can reduce unnecessary exposure by:

- Reviewing publicly indexed documents
- Monitoring certificate and subdomain exposure
- Limiting unnecessary infrastructure information
- Reviewing DNS configuration
- Regularly assessing publicly available information

## Technologies & Tools

| Category | Tools |
|---|---|
| Operating System | Kali Linux |
| Reconnaissance | WHOIS, `dig`, crt.sh |
| OSINT | Netcraft, Google Search |
| Web Analysis | `curl`, HTTP headers |
| Documentation | Markdown, Git, GitHub |

## Repository Structure

```text
reconnaissance/
├── 01-public-website-osint/
│   └── README.md
├── 02-whois/
│   └── README.md
├── 03-dns-analysis/
│   └── README.md
├── 04-certificates-subdomains/
│   └── README.md
├── 05-technology-stack/
│   └── README.md
└── 06-google-dorking/
    └── README.md
