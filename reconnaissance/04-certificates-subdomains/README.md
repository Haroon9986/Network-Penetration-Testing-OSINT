# 04 – Certificates & Subdomains

## Objective

The objective of this stage was to identify publicly available certificate and subdomain information associated with the target domain.

## Methodology

Certificate Transparency records were reviewed using crt.sh to identify certificates and publicly listed hostnames associated with the target domain.

Additional searches were performed to check for publicly indexed portal and login-related pages.

No intrusive scanning, exploitation or interaction with internal systems was performed.

## Key Findings

The certificate search identified publicly listed hostnames associated with the domain, including:

- `www.cranberry.co.uk`
- `blog.cranberry.co.uk`
- `3cx.cranberry.co.uk`

The certificate records demonstrated how Certificate Transparency data can reveal externally visible hostnames.

Additional searches for portal and login-related pages did not identify matching publicly indexed results.

## Security Relevance

Certificate Transparency information can assist passive reconnaissance by revealing:

- Publicly listed hostnames
- Subdomain naming patterns
- External services
- Information useful for mapping an organisation's public-facing infrastructure

No direct vulnerability was identified from the certificate information alone.

## Evidence

![Certificate Transparency Results](figure-14-certificates.png)

## Assessment

The certificate analysis demonstrated how publicly available Certificate Transparency records can contribute to external reconnaissance without directly interacting with the organisation's internal systems.
