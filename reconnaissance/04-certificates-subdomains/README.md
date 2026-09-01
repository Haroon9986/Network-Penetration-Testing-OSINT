# Certificate and Subdomain Checks

Passive reconnaissance of publicly available certificate and subdomain information.

## Objective

Identify publicly accessible certificates, subdomains and hosts associated with the target organisation.

## Method

Public certificate information was reviewed using crt.sh and browser-based searches.

Searches were performed for the organisation's website, portals and login-related subdomains.

No intrusive scanning or interaction with internal systems was performed.

## Areas Reviewed

- Public certificate records
- Certificate-associated hostnames
- Website subdomains
- Portal-related hosts
- Login-related hosts

## Findings

Public certificate information revealed organisation-related URLs and hostnames.

Searches for portal and login-related hosts did not return additional results.

The assessment did not identify a directly exploitable vulnerability through the certificate and subdomain checks.

## Security Considerations

Public certificate and subdomain information can assist threat actors in mapping an organisation's external infrastructure.

Regular monitoring of certificates and externally visible subdomains can help identify unexpected or outdated infrastructure.
