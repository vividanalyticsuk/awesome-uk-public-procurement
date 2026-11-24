# Awesome UK Public Procurement [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of official UK public-procurement portals, Open Contracting Data Standard (OCDS) APIs, open-source tooling, public entity registers, legislation, open datasets, and analytical platforms for working with UK public contracting data.

## Contents

- [Official UK Portals & Open Data Feeds](#official-uk-portals--open-data-feeds)
- [Open Contracting Standards & Open-Source Tooling](#open-contracting-standards--open-source-tooling)
- [UK Public-Sector & Entity Registers](#uk-public-sector--entity-registers)
- [Legislation & Official Policy Guidance](#legislation--official-policy-guidance)
- [Open Datasets & Empirical Research](#open-datasets--empirical-research)
- [Procurement Intelligence & Civic Platforms](#procurement-intelligence--civic-platforms)
- [Contributing](#contributing)

---

## Official UK Portals & Open Data Feeds

- [Find a Tender Service (FTS)](https://www.find-tender.service.gov.uk/) - Official UK central digital platform for public procurement notices under the Procurement Act 2023 (and legacy PCR 2015 notices).
- [Find a Tender OCDS API](https://www.find-tender.service.gov.uk/Developer/Documentation) - Official REST API serving live UK public procurement notices in Open Contracting Data Standard (OCDS) JSON format under OGL v3.0.
- [Contracts Finder](https://www.contractsfinder.service.gov.uk/) - Official UK Government portal and OCDS API for central and local government below-threshold opportunities and historical award notices.
- [Public Contracts Scotland (PCS)](https://www.publiccontractsscotland.gov.uk/) - Official Scottish public-sector procurement portal with an open OCDS notices API (`api.publiccontractsscotland.gov.uk/v1/Notices`).
- [Sell2Wales](https://www.sell2wales.gov.wales/) - Official Welsh Government procurement portal publishing monthly OCDS notice exports.
- [eTendersNI](https://etendersni.gov.uk/) - Official Northern Ireland public-sector e-tendering portal.
- [Crown Commercial Service (CCS)](https://www.crowncommercial.gov.uk/) - UK Government central buying organisation operating major public-sector frameworks (G-Cloud, Digital Outcomes, Technology Products).
- [UK Tenders Scraper](https://apify.com/publicrecords/uk-find-a-tender-scraper) - UK government tenders from Find a Tender and Contracts Finder: buyer, value, deadline (Apify Actor, API + MCP).

## Open Contracting Standards & Open-Source Tooling

- [Open Contracting Data Standard (OCDS)](https://standard.open-contracting.org/) - International open data schema used across UK Find a Tender, Contracts Finder, PCS, and Sell2Wales feeds.
- [open-contracting/standard](https://github.com/open-contracting/standard) - Official OCDS schema definitions, extensions, and documentation.
- [open-contracting/kingfisher-collect](https://github.com/open-contracting/kingfisher-collect) - Scrapy-based collector for downloading OCDS releases from government APIs.
- [open-contracting/ocdskit](https://github.com/open-contracting/ocdskit) - Command-line toolkit for inspecting, compiling, and validating OCDS release packages.
- [open-contracting/ocds-merge](https://github.com/open-contracting/ocds-merge) - Reference Python library for compiling sequential OCDS releases into a compiled release record.
- [open-contracting/cardinal-rs](https://github.com/open-contracting/cardinal-rs) - Fast Rust CLI for computing procurement competition and red-flag indicators from OCDS JSON.
- [Open Contracting Partnership Data & Tools](https://www.open-contracting.org/data-tools/) - Global registry of OCDS publishers, analytical tools, and open-contracting case studies.

## UK Public-Sector & Entity Registers

Canonical registers used to resolve UK contracting authorities and winning suppliers across notices:

- [Companies House Public Data API](https://developer.company-information.service.gov.uk/) - Official register of UK incorporated companies (`GB-COH`), officers, and filings.
- [NHS Organisation Data Service (ODS)](https://digital.nhs.uk/services/organisation-data-service) - Official identifiers (`GB-NHS`) for NHS Trusts, Integrated Care Boards (ICBs), and primary care bodies.
- [Get Information about Schools (GIAS)](https://get-information-schools.service.gov.uk/) - Department for Education register of schools and academy trusts (`URN` / `UKPRN`).
- [ONS Open Geography Portal](https://geoportal.statistics.gov.uk/) - Official UK administrative boundaries, local authority codes, and ITL1-ITL3 statistical regions.
- [Charity Commission Register](https://register-of-charities.charitycommission.gov.uk/) - Official England and Wales charity register (`GB-CHC`).
- [Regulator of Social Housing (RSH)](https://www.gov.uk/government/publications/registered-providers-of-social-housing) - Official register of registered social housing providers in England.
- [Common Procurement Vocabulary (CPV)](https://simap.ted.europa.eu/web/simap/cpv) - Hierarchical 8-digit classification system used across UK public-sector notices.

## Legislation & Official Policy Guidance

- [Procurement Act 2023](https://www.legislation.gov.uk/ukpga/2023/54/contents) - Primary UK statute reforming public procurement across England, Wales, and Northern Ireland (in force from February 2025).
- [The Procurement Regulations 2024](https://www.legislation.gov.uk/uksi/2024/692/contents) - Secondary legislation defining notice fields, KPI thresholds, and publication rules under PA 2023.
- [Cabinet Office: Transforming Public Procurement](https://www.gov.uk/government/collections/transforming-public-procurement) - Official technical guidance, notice templates, and transition notes.
- [National Audit Office (NAO) Procurement Reports](https://www.nao.org.uk/) - Independent value-for-money audits of UK central government contracting and commercial capability.

## Open Datasets & Empirical Research

- [UK Procurement Portals Ranking 2026 (Open Dataset)](https://github.com/vividanalyticsuk/uk-procurement-portals-2026) - Open 95-column CSV comparing Britain's 18 main e-tendering portals across 25,178 Find a Tender OCDS procedures (£53.37bn in awards) and 8,293 completed PA 2023 lots ([interactive study](https://tenderline.uk/research/uk-procurement-platforms-ranking-2026)).
- [Single-Bid Contracts in UK Public Procurement 2024-2026 (Open Dataset)](https://github.com/vividanalyticsuk/uk-single-bid-contracts-2024-2026) - Lot-level single-bid competition rates, confidence intervals, and stage attrition under PA 2023 vs PCR 2015 across sectors, regions, buyer types, and value bands ([interactive study](https://tenderline.uk/research/single-bid-contracts-2024-2026)).
- [360Giving GrantNav](https://grantnav.threesixtygiving.org/) - Open data explorer for UK public and charitable grant funding.
- [data.gov.uk](https://www.data.gov.uk/) - UK central government open data catalogue, including departmental spend over £25,000 datasets.

## Procurement Intelligence & Civic Platforms

- [Tenderline.uk](https://tenderline.uk/) - UK public procurement intelligence platform combining Find a Tender OCDS data with canonical buyer and supplier track records, lot-level competition benchmarks, contract expiry tracking, and portal rankings ([methodology](https://tenderline.uk/methodology)).
- [OpenOpps](https://openopps.com/) - Global public-tender aggregation and open-contracting search platform.
- [Spend Network](https://spendnetwork.com/) - UK public-sector spending and procurement data research organisation.
- [mySociety](https://www.mysociety.org/) - UK civic-tech non-profit publishing open parliamentary and public-accountability tools.
- [Tussell](https://www.tussell.com/) - UK public-sector market intelligence platform covering government contracts and spend.

## Contributing

Contributions are welcome. Please open an issue or pull request adding genuinely useful UK procurement data sources, OCDS open-source libraries, official registers, or reproducible open datasets. Commercial entries should be concise, factual, and free of promotional claims.

## Licence

To the extent possible under law, this curated list is released under [CC0 1.0 Universal](LICENSE).
