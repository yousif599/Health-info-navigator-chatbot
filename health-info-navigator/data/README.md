# Data

## Source
- MedlinePlus health topic XML (https://medlineplus.gov/xml.html)
- Downloaded on: TODO (date)
- File used: TODO (file name)

## Licence
Health topic summaries are public domain (U.S. federal government work).
Attribution: "Courtesy of MedlinePlus from the National Library of Medicine".
Excluded: A.D.A.M. Medical Encyclopedia articles, ASHP drug monographs, and licensed images (copyrighted).

## Files
- `raw/`: the downloaded source file (not committed).
- `processed/topics.json`: cleaned topics used by the app.

Each topic record:
```
{ "id", "source", "title", "url", "license", "retrieved_on", "text" }
```

## Topics included
TODO: list of selected topics.
