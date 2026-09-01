# DNS Analysis

Passive analysis of publicly available DNS records associated with the target organisation.

## Objective

Review publicly accessible DNS information to identify infrastructure and email-related information that could contribute to reconnaissance.

## Method

DNS information was collected using the `dig` command in Kali Linux.

The assessment reviewed publicly available DNS records without interacting with internal systems.

## Records Reviewed

- A records
- MX records
- TXT records
- NS records

## Findings

The DNS analysis identified publicly available information relating to:

- The organisation's public IP address
- Mail exchange infrastructure
- Name servers
- TXT records containing verification information

The MX records indicated the use of Outlook mail protection.

No sensitive information was identified during the DNS queries.

## Security Considerations

Public DNS information can assist threat actors in understanding an organisation's infrastructure.

Information such as public IP addresses, mail servers and name servers may contribute to reconnaissance and could be used when planning future attacks.

Regular review of externally visible DNS records can help organisations identify unnecessary or unexpected information.
