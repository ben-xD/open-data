# Climate Policy Radar Open Data

The full text of thousands of climate laws and policies from around the world.

Search through these using [our tool]("https://app.climatepolicyradar.org").

## Contents

At the moment this is the data used to power the alpha version of our search tool:

* all the metadata of over 3,000 laws and policies, and
* the full text and metadata of just over 1,000 laws and policies.

We're missing the full text of some of these documents as we've so far only parsed text out of English language PDFs. We'll keep this repository up to date as we add more documents to our tool.

> **NOTE:** there are no guarantees that we'll keep the data structure backwards compatible with previous versions, as we're still in alpha. We recommend that you pin to a specific commit if you want to use this data.

## Data Structure

The data in the `data` folder is organised into subfolders by country. 

Each document is stored as a JSON file with the following structure:

```json
{
    "document_instrument_name": [
        "Subnational and citizen participation|Governance",
        "Processes, plans and strategies|Governance"
    ],
    "document_framework_name": [],
    "document_region_code": "East Asia & Pacific",
    "document_country_english_shortname": "Samoa",
    "document_category": "Policy",
    "document_sector_name": [
        "Social development",
        "Agriculture"
    ],
    "document_date": "25/12/2016",
    "document_language": "English",
    "document_name": "Agriculture Sector Plan 2016 – 2020",
    "document_country_code": "WSM",
    "document_hazard_name": [],
    "document_keyword": [
        "Food Security",
        "Fisheries"
    ],
    "document_response_name": [
        "Mitigation",
        "Disaster Risk Management",
        "Adaptation"
    ],
    "document_url": "https://cdn.climatepolicyradar.org/WSM/2016/WSM-2016-12-25-Agriculture Sector Plan 2016 – 2020_6d14dc614858c1408f43a6964f024f40.pdf",
    "document_type": "Plan",
    "text_blocks": [
        {"text_block_id": "p12_b122", "text": "sample text"},
        {"text_block_id": "p12_b123", "text": "more text"},
    ],
    "document_description": "This plan sets the government's vision to increase food, nutrition and income security in Samoa. It notably seeks to&nbsp;ensure an environmentally sustainable, climate and disaster resilient agricultural sector.<br><br><br>"
}
```

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License (CC-BY)](LICENSE).
