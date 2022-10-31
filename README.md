# Open Data

The full text of thousands of climate laws and policies from around the world.

Search through these using [our tool]("https://app.climatepolicyradar.org").

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
