# 06 – Google Dorking

## Objective

The objective of this stage was to identify publicly indexed information associated with the target domain using search-engine-based OSINT techniques.

## Methodology

Google search operators were used to identify publicly accessible information indexed by search engines.

The searches included checks for:

- Publicly indexed PDF documents
- Password-related references
- Directory listings
- Configuration files

The activity was limited to publicly indexed search results. No restricted systems were accessed and no intrusive activity was performed.

## Key Findings

The `filetype:pdf` search identified publicly accessible PDF documents associated with the organisation.

The password-related search identified publicly indexed pages containing password-related references.

Searches for directory listings and configuration files did not return relevant results.

No credentials or restricted files were accessed.

## Security Relevance

Google Dorking can assist passive reconnaissance by identifying information that an organisation may have unintentionally made publicly searchable.

Public documents and exposed information can potentially assist further reconnaissance or social-engineering attempts.

## Evidence

![Google Dorking PDF Search](figure-21-filetype-pdf.png)

## Assessment

The Google Dorking exercise demonstrated how search-engine operators can be used to identify publicly indexed information without directly interacting with the organisation's internal systems.
