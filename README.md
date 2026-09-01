# 05 – Technology Stack

## Objective

The objective of this stage was to identify publicly observable technologies and web infrastructure associated with the target website.

## Methodology

Passive technology-stack reconnaissance was performed using Netcraft and HTTP response header analysis from Kali Linux.

The `curl` command was used to inspect publicly returned HTTP headers.

No intrusive scanning, exploitation or interaction with internal systems was performed.

## Key Findings

The analysis identified publicly observable information including:

- nginx web server information
- HTTP/2 support
- HTTP response headers
- Publicly observable website infrastructure information

Netcraft was also reviewed to gather additional publicly available information about the website and its technology history.

## Security Relevance

Technology fingerprinting can provide useful information for passive reconnaissance by helping identify:

- Web server technologies
- Supported protocols
- Public-facing infrastructure
- Technology patterns that could assist further reconnaissance

The information identified does not by itself represent a vulnerability.



## Assessment

The technology-stack analysis demonstrated how publicly observable web technologies and HTTP headers can be identified without intrusive interaction with the target infrastructure.
