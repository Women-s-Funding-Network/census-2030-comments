# 2030 Census Rule: Public Comment Explorer

A project of [Women's Funding Network](https://www.womensfundingnetwork.org).

A searchable database and trends dashboard of public comments on the Census Bureau's proposed rule
*Decennial Census of the Population of Americans; Proposed Residence Criteria and Proposed Regulations for Demographic Questions*
([docket USBC-2026-0628](https://www.regulations.gov/docket/USBC-2026-0628)). Comments are due November 2, 2026.

- **Search:** `docs/index.html` opens the comment database in [Datasette Lite](https://lite.datasette.io), a free data explorer that runs in the browser.
- **Trends:** `docs/trends.html` shows comment volume, positions, topics, states and organizations over time.

## Privacy

Individual commenters are not named. Names, signatures, addresses, ZIP codes, emails and phone numbers are removed
automatically, and individuals' attachments are not included. Organizations and public officials are named. Every comment
links to the original on Regulations.gov. Redaction is automated; if you spot a name that slipped through, please contact
Women's Funding Network.

## Method

Position (oppose, support, unclear) and topics are assigned by keyword rules and are approximate. State is inferred from the
comment text where a commenter names it. Form letters are identical or near-identical letters submitted three or more times.

Data: Regulations.gov (public comments), U.S. Census Bureau American Community Survey 2024 (state populations).
